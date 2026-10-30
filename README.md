# Ketryx

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Ketryx is an AI-native application lifecycle management (ALM) and compliance platform for regulated medical-device and life-sciences software teams. It integrates with developer tools such as Jira and GitHub to automate the documentation, traceability, and quality-management work required by FDA, EU MDR, ISO 13485, ISO 14971, and IEC 62304, keeping teams continuously audit-ready. Capabilities include automated Design and Development File generation, requirement-risk-code-test traceability, agentic AI for repetitive compliance tasks, ISO 14971 risk management, software bill-of-materials (SBOM) and vulnerability tracking, QMS enforcement, and change-impact assessment. Ketryx exposes a public Build API that lets CI/CD pipelines report builds, JUnit / Cucumber test results, build artifacts, and CycloneDX / SPDX SBOM documents into a project, via a first-party GitHub Action and Python utility. The company is backed by Lightspeed Venture Partners.

**Areas:** Company · Medical Devices · Life Sciences · Compliance · Regulatory · Application Lifecycle Management · Quality Management · SBOM · DevOps · Healthcare · Governance · CI/CD

## Ketryx on APIs.io

Everything profiled for Ketryx is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ketryx/](https://apis.io/providers/ketryx/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Ketryx Artifacts API](https://apis.io/apis/ketryx/ketryx-artifacts-api/) — Upload build artifacts, test results, and SBOM files.
- [Ketryx Builds API](https://apis.io/apis/ketryx/ketryx-builds-api/) — Report builds and their status to Ketryx.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [ketryx](https://apis.io/servers/ketryx/ketryx/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ketryx Agentic Access](https://apis.io/agentic-access/ketryx/ketryx-agentic-access/)

#### Collections (2)

Postman and Open Collection request collections.

- [Ketryx Build Artifacts API](https://apis.io/collections/ketryx/open-ketryx-artifacts-api/)
- [Ketryx Build Artifacts Builds API](https://apis.io/collections/ketryx/open-ketryx-builds-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Ketryx Build Api Overlay](https://apis.io/overlays/ketryx/ketryx-build-api-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Ketryx Authentication](https://apis.io/security/ketryx/ketryx-authentication/)
- [Ketryx Domain Security](https://apis.io/security/ketryx/ketryx-domain-security/)
- [Ketryx Trust Center](https://apis.io/security/ketryx/ketryx-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ketryx.com/)
- [Documentation](https://docs.ketryx.com)
- [API reference](https://docs.ketryx.com/api/build-api)
- [Pricing](https://www.ketryx.com/pricing)
- [Sign up](https://app.ketryx.com/auth/signup)
- [Support](https://ketryx.zendesk.com/hc/en-us)
- [Blog](https://www.ketryx.com/learn/blog)
- [Compliance](https://trust.ketryx.com)
- [Trust centre](https://trust.ketryx.com)
- [Terms of service](https://www.ketryx.com/terms)
- [Privacy policy](https://www.ketryx.com/privacy)
- [GitHub](https://github.com/Ketryx)
- [Status](https://status.ketryx.com)

## API Evangelist rating

**Kin Score 33.7** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 14.3 |
| Contract governance | 18.2 |
| Operational transparency | 10.5 |
| Developer ergonomics | 28.0 |
| Access clarity | 60.5 |

**Agent readiness 18.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 27.3** — Health

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ketryx/](https://apis.io/providers/ketryx/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Ketryx: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ketryx/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
