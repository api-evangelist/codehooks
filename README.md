# Codehooks (codehooks)

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
