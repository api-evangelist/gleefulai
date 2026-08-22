# Gleeful AI (gleefulai)

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

Gleeful AI publishes Visibility, an AI-visibility and answer-engine-optimization audit API: it scores how visible and understandable a website is to AI assistants and agents, audits AI crawler access (GPTBot, ClaudeBot and others), generates a production-ready llms.txt and schema.org markup, checks brand citation across assistants, and runs competitor gap analysis. The access model is the notable part — there are no API keys. Every priced endpoint answers an unauthenticated request with HTTP 402 and an x402 v2 challenge in a Payment-Required header, settled in USDC on Base at prices from $0.06 to $0.55 a call, published machine-readably at /api/pricing alongside /api/capabilities and /api/catalog. Discovery, pricing and two preview endpoints are free. It is an agent-native API in both directions: built to be paid for and called by an agent, and built to measure whether agents can read you.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gleefulai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gleefulai/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Artificial Intelligence
- Agents
- x402
- Micropayments
- SEO
- Audit
- Website
- Content
- Crawlers
- Monetization

## Timestamps

- **Created:** 2026-08-03
- **Modified:** 2026-08-13

## APIs

### Gleeful AI Audit API

The Audit API from Gleeful AI — 3 operation(s) for audit.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Audit

#### Properties

- [OpenAPI](openapi/gleefulai-audit-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-audit-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-audit-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Bots API

The Bots API from Gleeful AI — 1 operation(s) for bots.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Bots

#### Properties

- [OpenAPI](openapi/gleefulai-bots-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-bots-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-bots-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Capabilities API

The Capabilities API from Gleeful AI — 1 operation(s) for capabilities.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Capabilities

#### Properties

- [OpenAPI](openapi/gleefulai-capabilities-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-capabilities-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-capabilities-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Catalog API

The Catalog API from Gleeful AI — 1 operation(s) for catalog.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Catalog

#### Properties

- [OpenAPI](openapi/gleefulai-catalog-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-catalog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-catalog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Cite API

The Cite API from Gleeful AI — 2 operation(s) for cite.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Cite

#### Properties

- [OpenAPI](openapi/gleefulai-cite-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-cite-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-cite-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Compare API

The Compare API from Gleeful AI — 2 operation(s) for compare.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Compare

#### Properties

- [OpenAPI](openapi/gleefulai-compare-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-compare-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-compare-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Content API

The Content API from Gleeful AI — 1 operation(s) for content.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Content

#### Properties

- [OpenAPI](openapi/gleefulai-content-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-content-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-content-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Examples API

The Examples API from Gleeful AI — 1 operation(s) for examples.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Examples

#### Properties

- [OpenAPI](openapi/gleefulai-examples-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-examples-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-examples-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Fixes API

The Fixes API from Gleeful AI — 1 operation(s) for fixes.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Fixes

#### Properties

- [OpenAPI](openapi/gleefulai-fixes-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-fixes-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-fixes-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Health API

The Health API from Gleeful AI — 1 operation(s) for health.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Health

#### Properties

- [OpenAPI](openapi/gleefulai-health-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-health-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-health-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Llms API

The Llms API from Gleeful AI — 1 operation(s) for llms.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Llms

#### Properties

- [OpenAPI](openapi/gleefulai-llms-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-llms-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-llms-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Meta API

The Meta API from Gleeful AI — 1 operation(s) for meta.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Meta

#### Properties

- [OpenAPI](openapi/gleefulai-meta-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-meta-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-meta-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Preview API

The Preview API from Gleeful AI — 2 operation(s) for preview.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Preview

#### Properties

- [OpenAPI](openapi/gleefulai-preview-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Pricing API

The Pricing API from Gleeful AI — 1 operation(s) for pricing.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Pricing

#### Properties

- [OpenAPI](openapi/gleefulai-pricing-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-pricing-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-pricing-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Probe API

The Probe API from Gleeful AI — 1 operation(s) for probe.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Probe

#### Properties

- [OpenAPI](openapi/gleefulai-probe-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-probe-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-probe-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Schema API

The Schema API from Gleeful AI — 1 operation(s) for schema.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Schema

#### Properties

- [OpenAPI](openapi/gleefulai-schema-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-schema-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-schema-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

### Gleeful AI Status API

The Status API from Gleeful AI — 1 operation(s) for status.

- **Human URL:** [https://visibility.gleefulai.com/docs](https://visibility.gleefulai.com/docs)
- **Base URL:** `https://visibility.gleefulai.com`

#### Tags

- Status

#### Properties

- [OpenAPI](openapi/gleefulai-status-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gleefulai-status-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gleefulai-status-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [X- Open A P I- Source](https://visibility.gleefulai.com/openapi.json)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [X- Capabilities](https://visibility.gleefulai.com/api/capabilities)
- [X- Catalog](https://visibility.gleefulai.com/api/catalog)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Llms Text](https://visibility.gleefulai.com/llms.txt)

## Common Properties

- [Domain Security](security/gleefulai-domain-security.yml)
- [Website](https://visibility.gleefulai.com)
- [Documentation](https://visibility.gleefulai.com/docs)
- [Pricing](https://visibility.gleefulai.com/api/pricing)
- [Llms Text](llms/gleefulai-llms.txt)
- [Authentication](authentication/gleefulai-authentication.yml)
- [Plans](plans/gleefulai-plans.yml)
- [Lifecycle](lifecycle/gleefulai-lifecycle.yml)
- [Error Catalog](errors/gleefulai-problem-types.yml)
- [Conventions](conventions/gleefulai-conventions.yml)
- [Conformance](conformance/gleefulai-conformance.yml)
- [Packages](packages/gleefulai-packages.yml)
- [Rate Limits](rate-limits/gleefulai-rate-limits.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
