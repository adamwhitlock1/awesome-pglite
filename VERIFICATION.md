# Verification notes

Initial review date: October 2, 2026.

The README contains 20 curated entries. Each entry's source was inspected for relevance and its URL checked. GitHub repositories and paths were checked through the authenticated GitHub REST API; other pages were fetched with HTTP GET. Repository checks also inspected archive status and the current default branch. Descriptions summarize the linked material in original wording.

These checks establish source availability and documented use. They do not prove installation, runtime behavior, deployment reliability, security, or compatibility with every current dependency version. A repository's latest push can include non-code changes. Dates below are review snapshots, not a maintenance commitment.

## Entries

| Resource | Source inspected | Availability on review date | Upstream latest push, UTC date |
| --- | --- | --- | --- |
| [PGlite source](https://github.com/electric-sql/pglite) | Repository readme | GitHub API, 200 | 2026-08-26 |
| [Getting started](https://pglite.dev/docs/) | Documentation page | HTTP GET, 200 | Not applicable |
| [Drizzle PGlite driver](https://orm.drizzle.team/docs/connect-pglite) | Documentation page | HTTP GET, 200 | Not applicable |
| [Kysely PGlite dialect](https://kysely.dev/docs/getting-started?dialect=pglite) | Documentation page | HTTP GET, 200 | Not applicable |
| [Prisma local development](https://www.prisma.io/docs/local-development/postgres) | Documentation page | HTTP GET, 200 | Not applicable |
| [knex-pglite](https://github.com/czeidler/knex-pglite) | Repository readme | GitHub API, 200 | 2026-04-02 |
| [typeorm-pglite](https://github.com/muraliprajapati/typeorm-pglite) | Repository readme | GitHub API, 200 | 2026-02-28 |
| [Live queries](https://pglite.dev/docs/live-queries) | Documentation page | HTTP GET, 200 | Not applicable |
| [React hooks](https://pglite.dev/docs/framework-hooks/react) | Documentation page | HTTP GET, 200 | Not applicable |
| [Vue hooks](https://pglite.dev/docs/framework-hooks/vue) | Documentation page | HTTP GET, 200 | Not applicable |
| [Multi-tab worker](https://pglite.dev/docs/multi-tab-worker) | Documentation page | HTTP GET, 200 | Not applicable |
| [Filesystems](https://pglite.dev/docs/filesystems) | Documentation page | HTTP GET, 200 | Not applicable |
| [PostgreSQL playground](https://github.com/datawan-labs/pg) | Repository readme | GitHub API, 200 | 2024-12-02 |
| [Browser vector search](https://github.com/thorwebdev/browser-vector-search) | Repository readme | GitHub API, 200 | 2024-08-15 |
| [Calories tracker](https://github.com/typeonce-dev/calories-tracker-local-only-app) | Repository readme | GitHub API, 200 | 2025-03-12 |
| [Drizzle and Vitest demo](https://github.com/rphlmr/drizzle-vitest-pg) | Repository readme | GitHub API, 200 | 2024-07-08 |
| [py-pglite](https://github.com/wey-gu/py-pglite) | Repository readme | GitHub API, 200 | 2025-09-17 |
| [Extension catalog](https://pglite.dev/extensions/) | Documentation page | HTTP GET, 200 | Not applicable |
| [REPL component](https://pglite.dev/docs/repl) | Documentation page | HTTP GET, 200 | Not applicable |
| [PGlite Socket](https://pglite.dev/docs/pglite-socket) | Documentation page | HTTP GET, 200 | Not applicable |

## Excluded or superseded candidates

- solidsnack/pglite and Oslandia/pglite: different PostgreSQL projects, not electric-sql/PGlite.
- Standalone Kysely adapters were omitted because Kysely now documents a built-in PGlite dialect.
- Server-only PostgreSQL extensions were not listed without evidence of PGlite support.

## Updating this record

For a later addition or correction, record the check date, source evidence, and result with the affected entry. Retain the original date for unchanged rows. Link-check failures need investigation: rate limits and access restrictions can occur even when a page exists. Prefer a verified canonical replacement to an unexamined redirect.
