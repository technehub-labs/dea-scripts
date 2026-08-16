# dea-scripts

> Tools and playbooks for working with the DEA catalogs — seeding, migration, and bulk operations.

## What this is

Operational scripts that support the DEA repository stack
([repository map](https://github.com/technehub-labs/dea-architecture-framework#repository-map)):

- **catalog seeding** — bootstrap a T2 catalog repo from the root model
- **migration** — rename/restructure playbooks (e.g. the ADR-0004 catalog renames)
- **bulk operations** — org-wide sweeps across the 40+ catalog repos

For typed queries, validation, and viewpoint generation use
[`dea-cli`](https://github.com/technehub-labs/dea-cli); for generation from
catalog entries use [`dea-code-gen`](https://github.com/technehub-labs/dea-code-gen).

## Status

Scaffold — scripts land as playbooks are exercised
([Project #5 — Developer Tooling](https://github.com/orgs/technehub-labs/projects/5)).

## License

Apache 2.0 — see [LICENSE](./LICENSE) and [NOTICE](./NOTICE).
