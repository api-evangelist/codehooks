# Codehooks (codehooks)

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

Codehooks is a JavaScript-native serverless backend platform that bundles a NoSQL document database, key-value store, persistent queues with workers, CRON jobs, blob storage, frontend hosting, and an automatic CRUD REST API in a single CLI-deployable runtime. Developers write small Node.js handler files and Codehooks generates a secure REST API, OpenAPI documentation, and event hooks (onBefore/onAfter Create/Read/Update/Delete) without managing servers. The platform targets agent-native and AI backend use cases where simple, fast, MongoDB-style data access and event-driven automation matter.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Backend
- Database
- Events
- Hooks
- JavaScript
- NoSQL
- Queues
- Serverless
- Webhooks
- Workers
- Workflows

## Timestamps

- **Created:** 2025-02-08
- **Modified:** 2026-05-19

## APIs

### Codehooks Database REST API

Auto-generated, secure REST API for Codehooks NoSQL collections, the built-in key-value store, and queue topics. Supports MongoDB-style query operators ($gt, $lt, $in, $nin, $exists, $regex, $or, $and), pagination, sorting, field selection, bulk update/delete by query, counts, and increment/decrement on key-value entries. Authenticated via API key.

- **Human URL:** [https://codehooks.io/docs/](https://codehooks.io/docs/)
- **Base URL:** `https://{projectId}.api.codehooks.io/{space}`

#### Tags

- CRUD
- Database
- Documents
- Key-Value
- NoSQL
- Queues
- REST

#### Properties

- [Documentation](https://codehooks.io/docs/)
- [API Reference](https://codehooks.io/docs/restapi)
- [OpenAPI](openapi/codehooks-database-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/codehooks-database-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codehooks-database-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Codehooks Events (AsyncAPI)

Asynchronous CRUD lifecycle hooks (onBeforeCreate, onAfterCreate, onBeforeRead, onAfterRead, onBeforeUpdate, onAfterUpdate, onBeforeDelete, onAfterDelete) and queue worker processing (onQueueJob) for serverless backend operations. AsyncAPI describes these as event-driven channels backed by an internal pub/sub and persistent queue runtime.

- **Human URL:** [https://codehooks.io/docs/hooks-and-workers](https://codehooks.io/docs/hooks-and-workers)

#### Tags

- Async
- Events
- Hooks
- Lifecycle
- Queues
- Workers

#### Properties

- [Documentation](https://codehooks.io/docs/hooks-and-workers)
- [AsyncAPI](asyncapi/codehooks-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/codehooks-database-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codehooks-database-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/codehooks-io)
- [Website](https://codehooks.io/)
- [Documentation](https://codehooks.io/docs/)
- [Getting Started](https://codehooks.io/docs/quickstart-cli)
- [Blog](https://codehooks.io/blog)
- [Pricing](https://codehooks.io/#pricing)
- [Git Hub](https://github.com/RestDB)
- [N P M Package](https://www.npmjs.com/package/codehooks-js)
- [Terms of Service](https://codehooks.io/terms)
- [Privacy Policy](https://codehooks.io/privacy)
- [JSON-LD](json-ld/codehooks-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/codehooks-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/codehooks-key-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/codehooks-queue-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](rules/codehooks-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [L L Ms Txt](https://codehooks.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
