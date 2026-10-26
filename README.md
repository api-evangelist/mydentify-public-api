# Mydentify Public API (mydentify-public-api)

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

Public, keyless REST API for Mydentify — a permanent product directory with weekly community-signaled product leaderboards. The OpenAPI 3.1 contract covers intent-based product discovery, the curated startup/SaaS/AI directory catalog with Directory Score and link-type metadata, a portable product-category taxonomy mapped to G2/Capterra/Product Hunt, and a diagnostic-first product submission workflow: a non-destructive dry run, an idempotency-keyed durable import with a resumable SSE event stream, an AI-readiness rubric report, duplicate resolution, editorial manual review and backlink-verified publication. Mydentify also ships an unusually complete agent-native discovery surface — an APIs.json index, an RFC 9727 API Catalog, site-wide and per-resource llms.txt, an ai.txt usage policy, robots.txt Content Signals, and three published agentskills.io skills.

**APIs.json:** [https://mydentify-public-api.apievangelist.com/apis.yml](https://mydentify-public-api.apievangelist.com/apis.yml)

## Tags

- product discovery
- startup directories
- leaderboards
- research
- SaaS
- developer tools
- agent-native
- llms.txt
- agent skills
- directories

## Timestamps

- **Created:** 2026-07-27
- **Modified:** 2026-08-09

## APIs

### Mydentify Public API Directories API

The Directories API from Mydentify Public API — 2 operation(s) for directories.

- **Human URL:** [https://mydentify.com/developers](https://mydentify.com/developers)
- **Base URL:** `https://mydentify.com`

#### Tags

- Directories

#### Properties

- [OpenAPI](openapi/mydentify-public-api-directories-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mydentify-public-api-directories-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mydentify-public-api-directories-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Examples](examples/_index.yml)
- [Documentation](https://mydentify.com/submit.md)
- [Getting Started](https://mydentify.com/submit.md)
- [Developer Portal](https://mydentify.com/developers)
- [L L Ms Txt](llms/mydentify-public-api-llms.txt)
- [Tool Crosswalk](mcp/mydentify-public-api-tool-crosswalk.yml)
- [Authentication](authentication/mydentify-public-api-authentication.yml)
- [Conventions](conventions/mydentify-public-api-conventions.yml)
- [Idempotency](conventions/mydentify-public-api-conventions.yml)
- [Error Catalog](errors/mydentify-public-api-problem-types.yml)
- [Data Model](data-model/mydentify-public-api-data-model.yml)
- [Lifecycle](lifecycle/mydentify-public-api-lifecycle.yml)
- [Sandbox](sandbox/mydentify-public-api-sandbox.yml)
- [Conformance](conformance/mydentify-public-api-conformance.yml)

### Mydentify Public API Directories.json API

The Directories.json API from Mydentify Public API — 1 operation(s) for directories.json.

- **Human URL:** [https://mydentify.com/developers](https://mydentify.com/developers)
- **Base URL:** `https://mydentify.com`

#### Tags

- Directories.json

#### Properties

- [OpenAPI](openapi/mydentify-public-api-directories-json-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mydentify-public-api-directories-json-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mydentify-public-api-directories-json-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Examples](examples/_index.yml)
- [Documentation](https://mydentify.com/submit.md)
- [Getting Started](https://mydentify.com/submit.md)
- [Developer Portal](https://mydentify.com/developers)
- [L L Ms Txt](llms/mydentify-public-api-llms.txt)
- [Tool Crosswalk](mcp/mydentify-public-api-tool-crosswalk.yml)
- [Authentication](authentication/mydentify-public-api-authentication.yml)
- [Conventions](conventions/mydentify-public-api-conventions.yml)
- [Idempotency](conventions/mydentify-public-api-conventions.yml)
- [Error Catalog](errors/mydentify-public-api-problem-types.yml)
- [Data Model](data-model/mydentify-public-api-data-model.yml)
- [Lifecycle](lifecycle/mydentify-public-api-lifecycle.yml)
- [Sandbox](sandbox/mydentify-public-api-sandbox.yml)
- [Conformance](conformance/mydentify-public-api-conformance.yml)

### Mydentify Public API Imports API

The Imports API from Mydentify Public API — 8 operation(s) for imports.

- **Human URL:** [https://mydentify.com/developers](https://mydentify.com/developers)
- **Base URL:** `https://mydentify.com`

#### Tags

- Imports

#### Properties

- [OpenAPI](openapi/mydentify-public-api-imports-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mydentify-public-api-imports-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mydentify-public-api-imports-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Examples](examples/_index.yml)
- [Documentation](https://mydentify.com/submit.md)
- [Getting Started](https://mydentify.com/submit.md)
- [Developer Portal](https://mydentify.com/developers)
- [L L Ms Txt](llms/mydentify-public-api-llms.txt)
- [Tool Crosswalk](mcp/mydentify-public-api-tool-crosswalk.yml)
- [Authentication](authentication/mydentify-public-api-authentication.yml)
- [Conventions](conventions/mydentify-public-api-conventions.yml)
- [Idempotency](conventions/mydentify-public-api-conventions.yml)
- [Error Catalog](errors/mydentify-public-api-problem-types.yml)
- [Data Model](data-model/mydentify-public-api-data-model.yml)
- [Lifecycle](lifecycle/mydentify-public-api-lifecycle.yml)
- [Sandbox](sandbox/mydentify-public-api-sandbox.yml)
- [Conformance](conformance/mydentify-public-api-conformance.yml)

### Mydentify Public API Leaderboards API

The Leaderboards API from Mydentify Public API — 1 operation(s) for leaderboards.

- **Human URL:** [https://mydentify.com/developers](https://mydentify.com/developers)
- **Base URL:** `https://mydentify.com`

#### Tags

- Leaderboards

#### Properties

- [OpenAPI](openapi/mydentify-public-api-leaderboards-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mydentify-public-api-leaderboards-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mydentify-public-api-leaderboards-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Examples](examples/_index.yml)
- [Documentation](https://mydentify.com/submit.md)
- [Getting Started](https://mydentify.com/submit.md)
- [Developer Portal](https://mydentify.com/developers)
- [L L Ms Txt](llms/mydentify-public-api-llms.txt)
- [Tool Crosswalk](mcp/mydentify-public-api-tool-crosswalk.yml)
- [Authentication](authentication/mydentify-public-api-authentication.yml)
- [Conventions](conventions/mydentify-public-api-conventions.yml)
- [Idempotency](conventions/mydentify-public-api-conventions.yml)
- [Error Catalog](errors/mydentify-public-api-problem-types.yml)
- [Data Model](data-model/mydentify-public-api-data-model.yml)
- [Lifecycle](lifecycle/mydentify-public-api-lifecycle.yml)
- [Sandbox](sandbox/mydentify-public-api-sandbox.yml)
- [Conformance](conformance/mydentify-public-api-conformance.yml)

### Mydentify Public API Leaderboards.json API

The Leaderboards.json API from Mydentify Public API — 1 operation(s) for leaderboards.json.

- **Human URL:** [https://mydentify.com/developers](https://mydentify.com/developers)
- **Base URL:** `https://mydentify.com`

#### Tags

- Leaderboards.json

#### Properties

- [OpenAPI](openapi/mydentify-public-api-leaderboards-json-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mydentify-public-api-leaderboards-json-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mydentify-public-api-leaderboards-json-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Examples](examples/_index.yml)
- [Documentation](https://mydentify.com/submit.md)
- [Getting Started](https://mydentify.com/submit.md)
- [Developer Portal](https://mydentify.com/developers)
- [L L Ms Txt](llms/mydentify-public-api-llms.txt)
- [Tool Crosswalk](mcp/mydentify-public-api-tool-crosswalk.yml)
- [Authentication](authentication/mydentify-public-api-authentication.yml)
- [Conventions](conventions/mydentify-public-api-conventions.yml)
- [Idempotency](conventions/mydentify-public-api-conventions.yml)
- [Error Catalog](errors/mydentify-public-api-problem-types.yml)
- [Data Model](data-model/mydentify-public-api-data-model.yml)
- [Lifecycle](lifecycle/mydentify-public-api-lifecycle.yml)
- [Sandbox](sandbox/mydentify-public-api-sandbox.yml)
- [Conformance](conformance/mydentify-public-api-conformance.yml)

### Mydentify Public API Product Categories.json API

The Product Categories.json API from Mydentify Public API — 1 operation(s) for product categories.json.

- **Human URL:** [https://mydentify.com/developers](https://mydentify.com/developers)
- **Base URL:** `https://mydentify.com`

#### Tags

- Product Categories.json

#### Properties

- [OpenAPI](openapi/mydentify-public-api-product-categories-json-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mydentify-public-api-product-categories-json-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mydentify-public-api-product-categories-json-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Examples](examples/_index.yml)
- [Documentation](https://mydentify.com/submit.md)
- [Getting Started](https://mydentify.com/submit.md)
- [Developer Portal](https://mydentify.com/developers)
- [L L Ms Txt](llms/mydentify-public-api-llms.txt)
- [Tool Crosswalk](mcp/mydentify-public-api-tool-crosswalk.yml)
- [Authentication](authentication/mydentify-public-api-authentication.yml)
- [Conventions](conventions/mydentify-public-api-conventions.yml)
- [Idempotency](conventions/mydentify-public-api-conventions.yml)
- [Error Catalog](errors/mydentify-public-api-problem-types.yml)
- [Data Model](data-model/mydentify-public-api-data-model.yml)
- [Lifecycle](lifecycle/mydentify-public-api-lifecycle.yml)
- [Sandbox](sandbox/mydentify-public-api-sandbox.yml)
- [Conformance](conformance/mydentify-public-api-conformance.yml)

## Common Properties

- [M C P Server](mcp/mydentify-public-api-mcp.yml)
- [Overlay](overlays/mydentify-public-api-overlay.yaml)
- [Agentic Access](agentic-access/mydentify-public-api-agentic-access.yml)
- [Domain Security](security/mydentify-public-api-domain-security.yml)
- [Website](https://mydentify.com)
- [Developer Portal](https://mydentify.com/developers)
- [Documentation](https://mydentify.com/submit.md)
- [Getting Started](https://mydentify.com/submit.md)
- [Status Page](https://mydentify.com/api/health)
- [Pricing](https://mydentify.com/pricing)
- [Sign Up](https://mydentify.com/join)
- [Terms of Service](https://mydentify.com/terms)
- [Privacy Policy](https://mydentify.com/privacy)
- [Support](mailto:hello@mydentify.com)
- [Blog](https://mydentify.com/articles)
- [Blog Feeds](https://mydentify.com/articles/feed.xml)
- [GitHub Organization](https://github.com/mitdralla)
- [Well Known](well-known/mydentify-public-api-well-known.yml)
- [A P I Catalog](well-known/mydentify-public-api-api-catalog.json)
- [Content Signal](https://mydentify.com/robots.txt)
- [Acceptable Use Policy](well-known/mydentify-public-api-ai.txt)
- [A P Is Json](https://mydentify.com/apis.json)
- [Agent Skill](skills/_index.yml)
- [Lifecycle](lifecycle/mydentify-public-api-lifecycle.yml)
- [Conformance](conformance/mydentify-public-api-conformance.yml)

## Maintainers

**FN:** Mydentify
**Email:** hello@mydentify.com
**URL:** https://mydentify.com/about
