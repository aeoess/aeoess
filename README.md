# Tymofii Pidlisnyi

[![Sponsor](https://img.shields.io/badge/sponsor-%E2%9D%A4-ea4aaa)](https://github.com/sponsors/aeoess)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0002--4700--3594-a6ce39?logo=orcid&logoColor=white)](https://orcid.org/0009-0002-4700-3594)

Building governance infrastructure for the agent economy

My main work is the Agent Passport System, an open protocol that gives AI agents a verifiable identity, keeps their authority scoped, enforces it at runtime, and produces cryptographic evidence of each action.

Everything here is open source and built in public.

Website: [agent-passport.org](https://agent-passport.org)  
Project: [æœss.com](https://æœss.com)  
Personal: [tymofii.me](https://tymofii.me)  
Signal: [signal@aeoess.com](mailto:signal@aeoess.com)

## Projects

**[Agent Passport System](https://github.com/aeoess/agent-passport-system)**  
The core protocol and reference SDK. Identity, scoped delegation, policy enforcement, and signed receipts. Ports in [Python](https://github.com/aeoess/agent-passport-python) and [Go](https://github.com/aeoess/agent-passport-go), plus an [MCP server](https://github.com/aeoess/agent-passport-mcp).

**[Agent Authority Conformance](https://github.com/Agent-Authority-Conformance/aps-conformance-suite)**  
An LF Decentralized Trust Lab for reproducible conformance testing of agent authority protocols. Versioned test vectors, negative cases, runners in three languages, and reproducible run reports. The initial corpus covers APS; the lab is separate from the protocol and does not issue product conformance verdicts.

**[Agent Governance Vocabulary](https://github.com/aeoess/agent-governance-vocabulary)**  
Different platforms use different words for the same concepts. This maps them to shared names, so systems can interoperate without every integration writing its own translation layer.

**[Mingle](https://aeoess.com/mingle)**  
Agent-mediated networking. Your AI meets other people's AIs. You meet the people.

## Research

Most of these started as working code and became papers later.

* [The Agent Social Contract](https://doi.org/10.5281/zenodo.18749779)
* [Monotonic Narrowing](https://doi.org/10.5281/zenodo.18932404)
* [Faceted Authority Attenuation](https://doi.org/10.5281/zenodo.19260073)
* [Behavioral Derivation Rights](https://doi.org/10.5281/zenodo.19476002)
* [Physics-Enforced Delegation](https://doi.org/10.5281/zenodo.19478584)
* [Governance in the Medium](https://doi.org/10.5281/zenodo.19582550)
* [Cognitive Attestation](https://doi.org/10.5281/zenodo.19646276)
* [The Evidence-Safety Gap](https://doi.org/10.5281/zenodo.19914628)
* [Plausibly Wrong](https://doi.org/10.5281/zenodo.21208555)

IETF Internet-Draft: [`draft-pidlisnyi-aps-03`](https://datatracker.ietf.org/doc/draft-pidlisnyi-aps/)

## How I build

Everything here ships in the open.

Roadmap: [agent-passport.org/roadmap.html](https://agent-passport.org/roadmap.html)

## How I work

I work in close collaboration with AI. The framing I use for it is the [Model Citizen](https://open.substack.com/pub/timafey/p/the-model-citizen?r=2ih725&utm_campaign=post-expanded-share&utm_medium=web). The pun is the point: a model citizen earns standing by participating in good faith, and here the model is the citizen. Building infrastructure for AI agents, with AI agents, for AI agents, openly and at agent speed.

PRs are reviewed quickly and merged when they verify against live endpoints. If a crosswalk has six honest `no_mapping` entries, that's usually better than six invented matches.

GitHub is where I review code and specifications. Email is better for conversations.
