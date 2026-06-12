# ElectricSQL (electric-sql)

ElectricSQL (Electric) is a local-first sync engine for Postgres that streams live database changes to browsers, apps, and AI agents via an HTTP-based Shape sync protocol. It provides a managed Electric Cloud service as well as a self-hosted Docker image, along with TypeScript and Elixir client SDKs. The platform also encompasses PGlite (an embeddable Postgres under 3 MB) and Durable Streams for agent messaging.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/electric-sql/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/electric-sql/refs/heads/main/apis.yml)

Run with Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=electric-sql-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=electric-sql-api-evangelist&utm_content=repo)

## Tags

Developer Tools, Database, Sync, Local-First, Postgres, Real-Time, Open Source

## APIs

- [Electric HTTP Sync API](https://electric.ax/docs/api/http) — Core `GET /v1/shape` endpoint that streams Postgres shape log entries to clients via long-polling or Server-Sent Events.
- [Electric TypeScript Client](https://electric.ax/docs/api/clients/typescript) — `@electric-sql/client` NPM package with `ShapeStream` and `Shape` primitives for browser and Node.js environments.
- [Electric Sync Service Configuration API](https://electric.ax/docs/api/config) — Environment-variable interface for self-hosted Electric sync service deployments.

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/electric-sql-plans-pricing.yml](plans/electric-sql-plans-pricing.yml) |
| Rate Limits | [rate-limits/electric-sql-rate-limits.yml](rate-limits/electric-sql-rate-limits.yml) |
| FinOps | [finops/electric-sql-finops.yml](finops/electric-sql-finops.yml) |

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://electric.ax |
| Documentation | https://electric.ax/docs/sync/ |
| GitHub Organization | https://github.com/electric-sql |
| LinkedIn | https://www.linkedin.com/company/electric-sql |
| Blog | https://electric.ax/blog |
| Changelog | https://electric.ax/changelog |
| Pricing | https://electric.ax/pricing |
| X (Twitter) | https://x.com/ElectricSQL |
| Discord | https://discord.electric-sql.com |

## Maintainers

- Kin Lane / kin@apievangelist.com
