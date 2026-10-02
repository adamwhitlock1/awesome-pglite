# Awesome PGlite [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of PGlite integrations, browser apps, testing tools, and guides for embedded PostgreSQL.

[![License: CC0 1.0](https://img.shields.io/badge/license-CC0_1.0-blue.svg)](LICENSE)

[PGlite](https://pglite.dev/) packages PostgreSQL as WebAssembly for JavaScript runtimes. This list covers practical ways to query it, build reactive UIs, persist data, and use it in tests.

An independent community list. **Official** identifies resources maintained by the project team; **Integration** identifies documentation or examples maintained by an integrating project; **Community** identifies third-party work.

## Contents

- [Start here](#start-here)
- [ORMs and query builders](#orms-and-query-builders)
- [Reactive UIs and persistence](#reactive-uis-and-persistence)
- [Browser apps to study](#browser-apps-to-study)
- [Testing](#testing)
- [Extensions and developer tools](#extensions-and-developer-tools)
- [Compatibility](#compatibility)
- [Contributing](#contributing)
- [License](#license)

## Start here

- [PGlite source](https://github.com/electric-sql/pglite) - Embedded PostgreSQL engine, TypeScript client, and companion packages. **Official.**
- [Getting started](https://pglite.dev/docs/) - Create a database in memory, on disk, or in browser storage. **Official.**

## ORMs and query builders

- [Drizzle PGlite driver](https://orm.drizzle.team/docs/connect-pglite) - Use Drizzle queries and migrations with a PGlite instance. **Integration.**
- [Kysely PGlite dialect](https://kysely.dev/docs/getting-started?dialect=pglite) - Built-in PGliteDialect, available in Kysely 0.29 and later. **Integration.**
- [Prisma local development](https://www.prisma.io/docs/local-development/postgres) - Run a local Prisma Postgres database backed by PGlite. **Integration.**
- [knex-pglite](https://github.com/czeidler/knex-pglite) - Knex dialect with a single-connection pool for PGlite. **Community.**
- [typeorm-pglite](https://github.com/muraliprajapati/typeorm-pglite) - Connect TypeORM through a PGlite-backed PostgreSQL driver. **Community.**

## Reactive UIs and persistence

- [Live queries](https://pglite.dev/docs/live-queries) - Subscribe to changing SQL query results. **Official.**
- [React hooks](https://pglite.dev/docs/framework-hooks/react) - Bind a PGlite instance and live queries to React. **Official.**
- [Vue hooks](https://pglite.dev/docs/framework-hooks/vue) - Use PGlite in Vue components. **Official.**
- [Multi-tab worker](https://pglite.dev/docs/multi-tab-worker) - Share a database across browser tabs through a worker. **Official.**
- [Filesystems](https://pglite.dev/docs/filesystems) - Choose persistence and understand the available storage backends. **Official.**

## Browser apps to study

- [PostgreSQL playground](https://github.com/datawan-labs/pg) - Browser SQL playground with query history and schema visualization. **Community.**
- [Browser vector search](https://github.com/thorwebdev/browser-vector-search) - In-browser semantic search using Transformers.js and PGlite with pgvector. **Community.**
- [Calories tracker](https://github.com/typeonce-dev/calories-tracker-local-only-app) - Local-only app using TanStack Router, Drizzle, Effect, and PGlite. **Community.**

## Testing

- [Drizzle and Vitest demo](https://github.com/rphlmr/drizzle-vitest-pg) - Example of testing Drizzle queries with a real PGlite instance in Vitest. **Community.**
- [py-pglite](https://github.com/wey-gu/py-pglite) - Python testing interface backed by the JavaScript PGlite runtime. **Community.**

## Extensions and developer tools

- [Extension catalog](https://pglite.dev/extensions/) - Check which PostgreSQL extensions are packaged for PGlite. **Official.**
- [REPL component](https://pglite.dev/docs/repl) - Embed a SQL console in an application. **Official.**
- [PGlite Socket](https://pglite.dev/docs/pglite-socket) - Connect PostgreSQL clients through a socket bridge. **Official.**

## Compatibility

PGlite runs PostgreSQL in a single-user environment. A passing PGlite test does not establish server concurrency or extension parity. Community demos may pin older dependencies; check versions and licenses before reusing their code.

Links and source descriptions were reviewed on October 2, 2026. [Verification notes](VERIFICATION.md) record the checks and exclusions. Linked applications were not installed or run as part of this review.

## Contributing

We include resources that actually use electric-sql/PGlite. Unrelated projects with the same name, server-only PostgreSQL tools, and speculative adapters are excluded.

Read the [contribution guide](CONTRIBUTING.md), then open a pull request with one resource and a short explanation of what it adds. Corrections, broken-link reports, and removal requests are welcome. Participation follows the [code of conduct](CODE_OF_CONDUCT.md).

## License

This list and its original descriptions are dedicated to the public domain under [CC0 1.0](LICENSE). Linked projects, documentation, and trademarks retain their own licenses and ownership.
