# Codehooks (codehooks)

Codehooks is a JavaScript-native serverless backend platform that bundles a NoSQL document database, key-value store, persistent queues with workers, CRON jobs, blob storage, frontend hosting, and an automatic CRUD REST API in a single CLI-deployable runtime. Developers write small Node.js handler files and Codehooks generates a secure REST API, OpenAPI documentation, and event hooks (onBefore/onAfter Create/Read/Update/Delete) without managing servers. The platform targets agent-native and AI backend use cases where simple, fast, MongoDB-style data access and event-driven automation matter.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/codehooks/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
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
- **Modified:** 2026-04-26

## APIs

### Codehooks Database REST API
Auto-generated secure REST API for Codehooks NoSQL collections, the built-in key-value store, and queue topics. Supports MongoDB-style query operators, pagination, sorting, field selection, bulk update/delete by query, counts, and increment/decrement on key-value entries.

**Human URL:** [https://codehooks.io/docs/](https://codehooks.io/docs/)

#### Tags

- CRUD, Database, Documents, Key-Value, NoSQL, Queues, REST

#### Properties

- [Documentation](https://codehooks.io/docs/)
- [API Reference](https://codehooks.io/docs/restapi)
- [OpenAPI](openapi/codehooks-database-rest-api-openapi.yml)

### Codehooks Events (AsyncAPI)
Asynchronous CRUD lifecycle hooks (`onBeforeCreate`, `onAfterCreate`, `onBeforeRead`, `onAfterRead`, `onBeforeUpdate`, `onAfterUpdate`, `onBeforeDelete`, `onAfterDelete`) and queue worker processing (`onQueueJob`) for serverless backend operations.

**Human URL:** [https://codehooks.io/docs/hooks-and-workers](https://codehooks.io/docs/hooks-and-workers)

#### Tags

- Async, Events, Hooks, Lifecycle, Queues, Workers

#### Properties

- [Documentation](https://codehooks.io/docs/hooks-and-workers)
- [AsyncAPI](asyncapi/codehooks-events-asyncapi.yml)

## Common Properties

- [Website](https://codehooks.io/)
- [Documentation](https://codehooks.io/docs/)
- [Getting Started](https://codehooks.io/docs/quickstart-cli)
- [Blog](https://codehooks.io/blog)
- [Pricing](https://codehooks.io/#pricing)
- [GitHub](https://github.com/RestDB)
- [NPM Package](https://www.npmjs.com/package/codehooks-js)
- [Terms of Service](https://codehooks.io/terms)
- [Privacy Policy](https://codehooks.io/privacy)
- [JSON-LD Context](json-ld/codehooks-context.jsonld)
- [Document JSON Schema](json-schema/codehooks-document-schema.json)
- [Key-Value JSON Schema](json-schema/codehooks-key-value-schema.json)
- [Queue Job JSON Schema](json-schema/codehooks-queue-job-schema.json)
- [Spectral Ruleset](rules/codehooks-rules.yml)
- [Naftiko Capabilities](capabilities/codehooks-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
