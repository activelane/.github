# ActiveLane

**A platform for creating, using, distributing, monetizing, growing, and owning software.**

ActiveLane is exploring a different path for software products and the people who create them.

Today, turning a useful piece of software into a sustainable product usually means assembling a long list of unrelated systems: application shells, distribution, updates, identity, licensing, payments, analytics, discovery, and support. ActiveLane’s long-term goal is to reduce that distance—so more developers and domain experts can move from an idea to useful software, from useful software to an audience, and from an audience to lasting value.

## The vision

ActiveLane is being designed around a simple idea:

> Software creators should be able to build, publish, distribute, monetize, grow, and eventually transfer software products without first constructing an entire software company around them.

The intended product lifecycle is:

**Idea → Build → Publish → Discover → Use → Monetize → Grow → Distribute independently → Transfer ownership**

Not every creator or product needs to follow the whole path. A product may remain free, earn a modest recurring income, become an independent application, grow into a company, or eventually be acquired.

## What ActiveLane is becoming

### A shared software Workbench

The ActiveLane Workbench is a modular environment where compatible products can contribute views, commands, settings, navigation, and workflows.

It is not intended to be an IDE or a collection of hard-coded productivity features. It is one host within the broader ActiveLane platform.

### A product and extension platform

In ActiveLane, a **Product** is larger than an extension package.

A product may eventually be available through one or more distributions:

- inside the ActiveLane Workbench;
- through the ActiveLane web application;
- as a developer-supplied standalone desktop application;
- through a private company catalogue;
- or through other compatible surfaces in the future.

An ActiveLane extension is therefore one possible distribution of a product—not the product itself.

### A marketplace and Library

The Marketplace is where people discover products and creators. The ActiveLane Library is where a person or company sees the products they own, follow, saved, subscribed to, created, or received through an organisation.

Ownership and installation are separate. A product can belong to someone’s Library without being installed on a particular device.

### A software creator economy

ActiveLane’s long-term ambition is to help developers participate in a software creator economy:

- publish useful software with low initial friction;
- build an audience and reputation;
- offer free, paid, one-time, subscription, team, or enterprise products;
- distribute software inside and outside ActiveLane;
- understand product adoption and revenue;
- collaborate through publisher teams;
- and eventually transfer a product as a durable asset.

ActiveLane should succeed when its creators succeed.

## Hosts

ActiveLane is being designed as one platform with different hosts.

### Web

The web application will use the shared Vue frontend with browser-compatible capabilities and optional distributed services.

### Desktop

The desktop application uses Vue and Wails 3, with Go providing native capabilities such as local storage, filesystem access, and other explicitly granted integrations.

Offline and air-gapped operation are first-class design constraints. Remote identity, marketplace, sync, licensing, and telemetry must remain optional or replaceable where the deployment requires it.

### Mobile — future

The future mobile application is intended as a discovery and creator companion—not a phone-sized Workbench.

People could discover products, follow creators, save or acquire software, manage their Library, and later use compatible products through ActiveLane Web or Desktop.

## Technical direction

The current technical direction includes:

- Vue 3 and TypeScript for shared frontend experiences;
- Go for backend services, native capabilities, and developer tooling;
- Wails 3 for the desktop host;
- capability-driven host APIs rather than scattered web/desktop checks;
- declarative extension contributions;
- explicit permissions and compatibility;
- deterministic `.alx` packages;
- signed releases and verifiable installation;
- public and private registries;
- and local-first operation where appropriate.

These are architectural directions, not claims that every capability is complete today.

## Current status

ActiveLane is at an early, experimental stage and is currently led by a solo developer.

Existing work includes prototypes of the Workbench, docking system, extension runtime, registry, `.alx` tooling, Wails desktop host, marketplace experiences, and browser-based experiments. The project is being deliberately reassessed around a cleaner platform model.

Expect breaking changes, incomplete documentation, exploratory repositories, and evolving APIs until stable release boundaries are announced.

## Principles

- **Product is larger than Extension.** Packages, releases, products, publishers, owners, and distributions are separate concepts.
- **Capabilities over host assumptions.** Features depend on declared capabilities, not scattered platform checks.
- **Offline is an architecture.** Air-gapped Desktop operation is not merely an online application with a temporary offline mode.
- **Creators should retain options.** ActiveLane should be a useful runtime and distribution channel, not a prison for successful products.
- **Trust must be specific.** Identity, repository control, publisher control, business verification, and legal ownership are different claims.
- **Security boundaries are real.** Extensions receive explicit capabilities and meaningful permission expansions require review.
- **Evidence before scale.** Infrastructure, teams, and complex commerce should grow from demonstrated need.
- **Sustainable maintenance matters.** A solo-maintained project must prefer understandable systems over unnecessary operational complexity.

## Repositories

As repositories become ready for public use, this organisation will include:

- **`activelane`** — the main platform, shared frontend, hosts, Workbench, runtime, and services;
- **`alx`** — extension creation, validation, development, packaging, verification, and publishing tools;
- **`extensions`** — official examples and reference products;
- **`.github`** — organisation information and community guidance.

Additional repositories will be created only when they need genuinely independent release, security, contribution, or ownership boundaries.

## Participate

ActiveLane is not yet inviting broad production adoption. Thoughtful discussion, architectural feedback, reproducible bug reports, and focused contributions are welcome where a repository indicates that it is accepting them.

Before contributing, please read the organisation’s [contribution guide](../CONTRIBUTING.md), [governance](../GOVERNANCE.md), [security policy](../SECURITY.md), and the guidance in the target repository.

## A long-term north star

> Reduce the distance between creating useful software and building lasting value from it.

ActiveLane may begin as a Workbench and extension platform, but the larger ambition is to become infrastructure for a new generation of software creators.

