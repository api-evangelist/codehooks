# Codehooks

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

**Areas:** Backend · Database · Event · Hooks · JavaScript · NoSQL · Queues · Serverless · Webhook · Workers · Workflows

## Codehooks on APIs.io

Everything profiled for Codehooks is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/codehooks/](https://apis.io/providers/codehooks/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Codehooks Events (AsyncAPI)](https://apis.io/apis/codehooks/codehooks-events/) — Asynchronous CRUD lifecycle hooks (onBeforeCreate, onAfterCreate, onBeforeRead, onAfterRead, onBeforeUpdate, onAfterUpdate, onBeforeDelete, onAfterDelete)…
- [Codehooks Documents API](https://apis.io/apis/codehooks/codehooks-documents-api/) — CRUD operations on NoSQL collection documents
- [Codehooks Key-Value Store API](https://apis.io/apis/codehooks/codehooks-key-value-store-api/) — Fast key-value storage with optional TTL for caching and lookups
- [Codehooks Queue API](https://apis.io/apis/codehooks/codehooks-queue-api/) — Asynchronous job queue for worker processing

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Codehooks Events API](https://apis.io/asyncapis/codehooks/codehooks-events-asyncapi/)

#### Event channels (9)

Individual events and webhooks the provider emits.

- [collection/afterCreate](https://apis.io/channels/codehooks/collection-aftercreate/)
- [collection/afterDelete](https://apis.io/channels/codehooks/collection-afterdelete/)
- [collection/afterRead](https://apis.io/channels/codehooks/collection-afterread/)
- [collection/afterUpdate](https://apis.io/channels/codehooks/collection-afterupdate/)
- [collection/beforeCreate](https://apis.io/channels/codehooks/collection-beforecreate/)
- [collection/beforeDelete](https://apis.io/channels/codehooks/collection-beforedelete/)
- [collection/beforeRead](https://apis.io/channels/codehooks/collection-beforeread/)
- [collection/beforeUpdate](https://apis.io/channels/codehooks/collection-beforeupdate/)
- [queue/{topic}](https://apis.io/channels/codehooks/queue-topic/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Codehooks Agentic Access](https://apis.io/agentic-access/codehooks/codehooks-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Codehooks Document](https://apis.io/schemas/codehooks/codehooks-document/)
- [Codehooks Key-Value Entry](https://apis.io/schemas/codehooks/codehooks-key-value/)
- [Codehooks Queue Job](https://apis.io/schemas/codehooks/codehooks-queue-job/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Codehooks Context](https://apis.io/jsonld/codehooks/codehooks-context/)

#### Collections (4)

Postman and Open Collection request collections.

- [Codehooks Database REST API](https://apis.io/collections/codehooks/open-codehooks-database-rest-api/)
- [Codehooks Database REST Documents API](https://apis.io/collections/codehooks/open-codehooks-documents-api/)
- [Codehooks Database REST Documents Key-Value Store API](https://apis.io/collections/codehooks/open-codehooks-key-value-store-api/)
- [Codehooks Database REST Documents Queue API](https://apis.io/collections/codehooks/open-codehooks-queue-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Codehooks — asyncapi rules](https://apis.io/rules/codehooks/codehooks-asyncapi-spectral-rules/)
- [Codehooks — jsonschema rules](https://apis.io/rules/codehooks/codehooks-jsonschema-spectral-rules/)
- [Codehooks API Rules](https://apis.io/rules/codehooks/codehooks-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Codehooks Authentication](https://apis.io/security/codehooks/codehooks-authentication/)
- [Codehooks Domain Security](https://apis.io/security/codehooks/codehooks-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Codehooks Plans Pricing](https://apis.io/plans/codehooks/codehooks-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Codehooks Rate Limits](https://apis.io/rate-limits/codehooks/codehooks-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Codehooks Finops](https://apis.io/finops/codehooks/codehooks-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://codehooks.io/)
- [Documentation](https://codehooks.io/docs/)
- [Getting started](https://codehooks.io/docs/quickstart-cli)
- [Pricing](https://codehooks.io/#pricing)
- [Blog](https://codehooks.io/blog)
- [Terms of service](https://codehooks.io/terms)
- [Privacy policy](https://codehooks.io/privacy)

## API Evangelist rating

**Kin Score 40.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 64.3 |
| Contract quality | 62.3 |
| Contract governance | 13.6 |
| Operational transparency | 13.2 |
| Developer ergonomics | 36.9 |
| Access clarity | 34.2 |

**Agent readiness 23.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 24.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/codehooks/](https://apis.io/providers/codehooks/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Codehooks: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/codehooks/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
