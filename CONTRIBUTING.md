# Contributing to ActiveLane

Thank you for considering a contribution to ActiveLane.

ActiveLane is early-stage software led by a solo maintainer. Contributions are most useful when they are focused, discussed before substantial implementation, and aligned with the active milestone of the target repository.

## Before you begin

Please:

1. Read the target repository’s README and development instructions.
2. Search existing issues and discussions for related work.
3. Open or join a proposal before beginning a substantial feature, architectural change, new dependency, or public API.
4. Wait for maintainer agreement before investing significant time.

Agreement to explore an idea is not necessarily agreement to merge a particular implementation.

## Good contributions

At the current stage, especially helpful contributions include:

- reproducible bug reports;
- failing tests that expose real behavior;
- small, well-scoped fixes;
- accessibility improvements;
- documentation corrections;
- compatibility and platform testing;
- security hardening coordinated through the security process;
- and design feedback grounded in a real user journey.

## Changes that require prior discussion

Please do not open a large implementation without prior agreement when it introduces or substantially changes:

- public extension or host APIs;
- manifest or `.alx` formats;
- persisted schemas or migrations;
- repository structure;
- runtime permissions or security boundaries;
- major dependencies;
- user identity, licensing, payments, or telemetry;
- deployment architecture;
- or product direction.

## Development expectations

A contribution should normally:

- solve one coherent problem;
- avoid unrelated refactoring;
- preserve offline and air-gapped behavior where applicable;
- use capability checks rather than hard-coded host assumptions;
- avoid importing internal modules across declared package boundaries;
- include tests appropriate to the risk of the change;
- update affected documentation and examples;
- provide actionable failure messages;
- and avoid compatibility shims unless an approved migration explicitly requires one.

Repository-specific instructions take precedence where they are more precise.

## Pull requests

Keep pull requests small enough to review meaningfully. The description should explain:

- the problem and user impact;
- the root cause or design reasoning;
- what changed;
- how it was verified;
- any compatibility, migration, security, or privacy impact;
- and any remaining risk.

Screenshots or recordings are useful for visible behavior, but they do not replace functional verification.

## Tests and verification

Run the checks documented by the repository. Where relevant, verify the complete user journey rather than only isolated units.

Examples include:

- clean build and type checking;
- unit and integration tests;
- web and Wails host behavior;
- offline startup;
- package validation and verification;
- install, enable, update, rollback, disable, and uninstall flows;
- keyboard and accessibility behavior;
- and persisted-state migration.

If you cannot run a required check, say so explicitly in the pull request.

## Generated code and AI assistance

AI-assisted contributions are welcome when the contributor understands and takes responsibility for the result.

Do not submit large generated changes without reviewing their behavior, security, licensing implications, tests, and fit with the project. The human contributor remains responsible for every submitted line.

## Licensing and provenance

Only submit work you have the right to contribute. Do not copy proprietary code, incompatible licensed material, credentials, personal information, or content whose provenance is unclear.

By submitting a contribution, you agree that it may be distributed under the licence of the target repository.

## Conduct

Participation is governed by the [Code of Conduct](CODE_OF_CONDUCT.md).

## Security

Do not disclose suspected vulnerabilities through public issues or discussions. Follow the [Security Policy](SECURITY.md).

## Maintainer capacity

Response times may vary. A delayed response does not indicate that a contribution is unimportant. The project will favour correctness, security, coherent architecture, and sustainable maintenance over merge volume.

