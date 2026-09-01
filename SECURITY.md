# ActiveLane Security Policy

Security is especially important to ActiveLane because the platform is intended to distribute and execute third-party software.

## Reporting a vulnerability

Do not report suspected vulnerabilities through public issues, pull requests, discussions, or social media.

Use **GitHub private vulnerability reporting** in the affected repository when it is available:

1. Open the repository’s **Security** tab.
2. Select **Report a vulnerability**.
3. Provide the affected component and version, reproduction steps, impact, and any suggested mitigation.

If private vulnerability reporting is not enabled, contact an ActiveLane organisation owner through a private GitHub contact channel without including exploit details in a public message. A dedicated security address will be published before ActiveLane offers production marketplace services.

Please report one vulnerability per submission unless several findings are inseparable.

## Helpful report contents

Include, where possible:

- affected repository, component, version, and host;
- required permissions or configuration;
- reproducible steps or a minimal proof of concept;
- expected and observed behavior;
- practical impact;
- whether the issue is already being exploited;
- suggested remediation;
- and whether you want public attribution.

Do not access data that does not belong to you, degrade services, persist after demonstrating the issue, or use social engineering.

## Response process

The project will aim to:

1. acknowledge a complete report;
2. reproduce and assess the issue;
3. coordinate a fix and affected releases;
4. determine whether packages, signing identities, or releases must be revoked;
5. notify affected users when appropriate;
6. publish an advisory after a safe remediation window;
7. and credit the reporter if requested and appropriate.

As an early solo-maintained project, ActiveLane cannot currently promise contractual response times. Critical reports involving code execution, package integrity, signing, authentication, entitlements, or sensitive data will receive priority.

## Supported versions

ActiveLane is currently pre-stable. Until a repository publishes a specific support table:

- only the most recent release or development version may receive fixes;
- breaking changes may occur;
- and prototypes should not be treated as production security boundaries.

Repositories will publish explicit supported-version policies before stable releases.

## Security-sensitive areas

Reports are particularly valuable when they involve:

- `.alx` archive validation, traversal, or extraction;
- package signatures, hashes, signing keys, or revocation;
- extension isolation and MessagePort bridges;
- capability or permission enforcement;
- registry substitution and update integrity;
- filesystem or process access;
- Wails bindings;
- authentication, sessions, Library data, or entitlements;
- private registry or air-gapped operation;
- and ownership or publisher verification.

## Safe-harbour intent

ActiveLane supports good-faith security research that avoids privacy violations, service disruption, extortion, and unnecessary access to data. A formal safe-harbour policy may be adopted with professional review before public production services launch.

