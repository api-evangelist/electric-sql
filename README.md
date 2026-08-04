# ElectricSQL (electric-sql)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
