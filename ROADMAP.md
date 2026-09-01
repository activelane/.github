# ActiveLane Public Roadmap

This roadmap describes direction, not promised dates. ActiveLane is currently a solo-maintained, pre-stable project, so progress is controlled by evidence and milestone gates rather than calendar commitments.

## Now: establish the foundation

- Clarify the platform doctrine and product boundaries.
- Inventory and test existing prototypes.
- Decide what to retain, refactor, or replace.
- Establish the monorepo, toolchains, CI, versioning, configuration, and recovery practices.
- Define Product, Creator, Publisher, Owner, Release, Distribution, Entitlement, Library, Installation, and Capability contracts.
- Generate compatible TypeScript and Go models.

**Exit gate:** the repository is reproducible, core concepts are explicit, and retained prototypes have evidence-backed reasons to survive.

## Next: working local platform

- Implement shared capability-driven Web and Wails 3 hosts.
- Stabilise the modular Workbench and docking system.
- Define the extension manifest and runtime API.
- Complete dynamic contributions without host hard-coding.
- Implement explicit permissions and isolated views.
- Build deterministic `.alx` packaging and developer tooling.
- Complete a local registry, verified installation, updates, and rollback.
- Publish one useful reference product exercising the platform end to end.

**Exit gate:** a product can be created, packaged, published locally, discovered, installed, used, updated, rolled back, and removed through public contracts.

## Then: private alpha

- Choose one narrow, real user problem.
- Recruit a small number of reachable testers.
- Observe activation, task completion, reliability, and return use.
- Fix the complete user journey before increasing platform breadth.

**Exit gate:** several users complete the core workflow and return voluntarily because the product is useful, not merely interesting.

## Later: hosted catalogue and free marketplace

- Harden the initial VPS and deployment process.
- Deploy public registry metadata and bounded artifact delivery.
- Add minimal identity and cross-host Library synchronization.
- Build product discovery and creator publishing.
- Add moderation, revocation, verified-use reviews, and service observability.
- Launch initially with free products to prove distribution before commerce.

## After demonstrated demand and professional support

- Paid products, subscriptions, trials, refunds, payouts, tax, and entitlement services.
- Creator profiles, analytics, release management, teams, and audience tools.
- Developer-supplied standalone application downloads.
- Business accounts, private marketplaces, enterprise identity, and managed deployments.
- On-premise and air-gapped enterprise distribution.
- Independent security review and mature trust operations.

## Long-term direction

- A mobile marketplace and creator companion—not a mobile Workbench.
- Structured, verified product ownership transfer and acquisitions.
- Optional managed platform services for creators.
- Ecosystem governance informed by users, creators, companies, and maintainers.

## Explicit non-commitments

Listing an item here does not mean that it:

- has a committed release date;
- is actively being implemented;
- will use a particular commercial model;
- is safe for production use;
- or will be completed before evidence changes the plan.

Security, legal, financial, moderation, and enterprise commitments will not be launched merely as technical prototypes when responsible operation requires other professions or a larger team.

## North star

> Reduce the distance between creating useful software and building lasting value from it.

