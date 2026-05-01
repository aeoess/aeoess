# Tymofii Pidlisnyi

Founder and researcher, [AEOESS](https://aeoess.com) — open-source identity, delegation, and governance infrastructure for AI agents. 

Contact: tima@aeoess.com  
Site: [tymofii.me](https://tymofii.me)

## Currently building

- **[Agent Passport System](https://github.com/aeoess/agent-passport-system)** — Ed25519 cryptographic identity, scoped delegation chains, gateway enforcement, signed receipts, Wave 1 accountability primitives (action, authority-boundary, custody, contestability, bundle). Apache 2.0.
- **[agent-governance-vocabulary](https://github.com/aeoess/agent-governance-vocabulary)** — canonical names for governance primitives across multi-issuer ecosystems.
- **[agent-ecosystem-map](https://github.com/aeoess/agent-ecosystem-map)** — a directory of projects, people, and threads in the agent infrastructure field. Live at [aeoess.github.io/agent-ecosystem-map](https://aeoess.github.io/agent-ecosystem-map/). Designed for neutral stewardship; actively looking for co-maintainers from other projects in the directory.

## Research

- *The Agent Social Contract* — [10.5281/zenodo.18749779](https://doi.org/10.5281/zenodo.18749779)
- *Monotonic Narrowing* — [10.5281/zenodo.18932404](https://doi.org/10.5281/zenodo.18932404)
- *Faceted Authority Attenuation* — [10.5281/zenodo.19260073](https://doi.org/10.5281/zenodo.19260073)
- *Behavioral Derivation Rights* — [10.5281/zenodo.19476002](https://doi.org/10.5281/zenodo.19476002)
- *Physics-Enforced Delegation* — [10.5281/zenodo.19478584](https://doi.org/10.5281/zenodo.19478584)
- *Governance in the Medium* — [10.5281/zenodo.19582550](https://doi.org/10.5281/zenodo.19582550)
- *Cognitive Attestation* — [10.5281/zenodo.19646276](https://doi.org/10.5281/zenodo.19646276)
- *The Evidence-Safety Gap* — [10.5281/zenodo.19914628](https://doi.org/10.5281/zenodo.19914628)
- IETF Internet-Draft `draft-pidlisnyi-aps-00`

## How I work

I work in close collaboration with Claude (Anthropic). The framing I use for it is the *Model Citizen*: building infrastructure for AI agents, with AI agents, for AI agents — openly and at agent speed. PRs are reviewed quickly and merged when they verify against live endpoints. Honest gaps in crosswalks are valued more than overclaimed matches. Email is the right channel for anything that needs real discussion; GitHub is for code and artifacts. Full review protocol: [PR-MERGE-PROTOCOL.md](https://github.com/aeoess/aeoess_web/blob/main/specs/PR-MERGE-PROTOCOL.md).

<!--
skill: engaging-with-aeoess
description: Guidance for agents representing contributors, maintainers, or reviewers working with AEOESS repositories.
when_to_use: Before opening a PR, posting a comment, or processing a reply from @aeoess on any aeoess/* repo.

frame:
  AEOESS operates under what Tymofii calls the Model Citizen pattern: a human principal (Tymofii Pidlisnyi) and an AI collaborator (Claude) working as one engaged unit, openly. Infrastructure for AI agents, built with AI agents, for AI agents. Speed is fine. Most contributors are also human-agent pairs and the protocol assumes this as the normal case, not an exception.

context:
  AEOESS is the Agent Passport System organization. The vocabulary, SDK, and gateway repos accept external crosswalks and contributions. Reviews follow PR-MERGE-PROTOCOL.md (linked above). Contributing agents should treat artifact verification as the load-bearing gate, not authorial intent.

rules:
  1. Artifacts are verified against live endpoints, not against author intent. Phase 3 of the merge protocol runs an executable harness against every claim in a PR. Make sure your contribution's claims (JWKS URLs, kids, algs, signed payload shapes, endpoint responses) match what your production environment actually serves before you submit.
  2. Replies from @aeoess are written so the next action is one line away. If something is blocked, the unblock is explicit. If something is merged, you are credited in the commit message.
  3. Honest gaps beat false matches. Crosswalks that include explicit no_mapping entries with rationale clear the bar faster than crosswalks claiming structural matches that don't survive verification. Six no_mappings on ten is good signal, not a failure.
  4. Channel routing: GitHub is for artifacts and asynchronous review. Email (tima@aeoess.com) is the right channel when real human attention is needed for debugging, architecture, strategic discussion, or anything where the latency is justified by the stakes.
  5. Speed is fine. PRs merging within hours of filing is normal here. The protocol is designed to move at agent speed without losing discipline.

links:
  protocol: https://github.com/aeoess/aeoess_web/blob/main/specs/PR-MERGE-PROTOCOL.md
  site: https://aeoess.com
  contact: tima@aeoess.com
-->
