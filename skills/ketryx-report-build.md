---
name: Report a build to Ketryx
description: >-
  Upload test results and SBOM documents, then report a build to a Ketryx
  project so CI/CD results feed the platform's traceability and compliance
  records.
api: openapi/ketryx-build-api-openapi.yml
operations:
  - uploadBuildArtifact
  - reportBuild
generated: '2026-07-19'
method: generated
---

# Report a build to Ketryx

Use this skill to push CI/CD build results — test reports, build artifacts, and
SBOM documents — into a Ketryx project via the Build API.

## Prerequisites
- A Ketryx **project ID** and a per-project **API key**.
- Base URL `https://app.ketryx.com` (or your self-hosted `KETRYX_URL`).
- Auth: send the API key as an HTTP Bearer token —
  `Authorization: Bearer <api-key>` — on every request.

## Steps

1. **Upload each artifact** with `uploadBuildArtifact`
   (`POST /api/v1/build-artifacts?project=<projectId>`).
   Send the file as `multipart/form-data` under the `file` field. Supported
   inputs include JUnit XML and Cucumber JSON test reports, CycloneDX and SPDX
   JSON SBOM files, and build output files. Capture the returned artifact `id`.

2. **Report the build** with `reportBuild` (`POST /api/v1/builds`, JSON body):
   - `project`: the project ID (required).
   - `artifacts`: the list of artifact `id`s from step 1.
   - `version` **or** `commitSha`: set `version` to bind to a specific Ketryx
     version; otherwise `commitSha` resolves the version from the commit.
   - Optional: `buildName` (to disambiguate parallel builds), `sourceUrl`,
     `repositoryUrls`, `log`.

3. **Read the result.** A `200` returns the build with its `id`/`buildId` and
   `ok` flag. Any non-200 status is a failure — surface the response body text.

## Rules
- There is **no idempotency key**; do not blindly retry `reportBuild` on an
  ambiguous failure — check whether the build was recorded first.
- API keys are project-scoped; never reuse a key across projects.
- See `conventions/ketryx-conventions.yml` and `errors/ketryx-problem-types.yml`
  for the request/response and error semantics.
