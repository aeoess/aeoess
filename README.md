[![Sponsor](https://img.shields.io/badge/sponsor-%E2%9D%A4-ea4aaa)](https://github.com/sponsors/aeoess)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--4700--3594-a6ce39?logo=orcid&logoColor=white)](https://orcid.org/0009-0002-4700-3594)

Building verifiable authority and action evidence for AI agents

My main work is the **Agent Passport System**, an open protocol for delegated authority, pre-action enforcement, signed receipts, and attribution across systems. I also work on the conformance suite used to test those guarantees across independent implementations.

## Start contributing

The [APS contribution path](https://github.com/aeoess/agent-passport-system/blob/main/CONTRIBUTION_PATH.md) explains the artifact standard, checks, and what a merged contribution does and does not establish.

### Vocabulary

Map a real external system to the shared governance vocabulary. Contributions need source links and must preserve the difference between direct, partial, and inferred mappings.

[Open unassigned vocabulary tasks](https://github.com/aeoess/agent-governance-vocabulary/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22help%20wanted%22%20no%3Aassignee)

### APS and conformance

Implement or falsify specified behavior with fixtures and tests. This lane includes SDK cross-checks and conformance runner work.

- [Open unassigned APS tasks](https://github.com/aeoess/agent-passport-system/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22help%20wanted%22%20no%3Aassignee)
- [Open unassigned conformance tasks](https://github.com/Agent-Authority-Conformance/aps-conformance-suite/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22help%20wanted%22%20no%3Aassignee)

### Gateway

Exercise enforcement and outbound integrations in the Gateway service code. Gateway tasks must have deterministic tests and must not require production credentials or deployment access.

[Open unassigned Gateway tasks](https://github.com/aeoess/agent-passport-gateway/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22help%20wanted%22%20no%3Aassignee)

The [authority lifecycle model](https://github.com/aeoess/agent-authority-lifecycle) is published reading material. That repository is frozen and is not a contributor lane.

Protocol definitions, vocabulary semantics, canonical hashing, receipt bytes, and compatibility decisions remain maintainer-reviewed Core work.

### Contributor credit

External contributors have added crosswalks, fixtures, validators, and interoperability checks across these repositories. Recent merged work includes contributions from [@douglasborthwick-crypto](https://github.com/aeoess/agent-governance-vocabulary/pull/167), [@arian-gogani](https://github.com/aeoess/agent-governance-vocabulary/pull/161), [@Shxnque](https://github.com/aeoess/agent-governance-vocabulary/pull/151), [@kenneives](https://github.com/aeoess/agent-governance-vocabulary/pull/139), [@imokokok](https://github.com/Agent-Authority-Conformance/aps-conformance-suite/pull/83), and [@Math1987](https://github.com/aeoess/agent-passport-system/pull/95).

The repository histories contain the complete attribution record.
