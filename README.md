# Tymofii Pidlisnyi

[![Sponsor](https://img.shields.io/badge/sponsor-%E2%9D%A4-ea4aaa)](https://github.com/sponsors/aeoess)
[![npm](https://img.shields.io/npm/v/agent-passport-system?label=npm)](https://www.npmjs.com/package/agent-passport-system)
[![PyPI](https://img.shields.io/pypi/v/agent-passport-system?label=pypi)](https://pypi.org/project/agent-passport-system/)
[![Site](https://img.shields.io/badge/site-agent--passport.org-blue)](https://agent-passport.org)
[![IETF](https://img.shields.io/badge/IETF-draft--pidlisnyi--aps--03-orange)](https://datatracker.ietf.org/doc/draft-pidlisnyi-aps/)

I build infrastructure for AI agents.

My main work is the Agent Passport System, an open protocol that gives AI agents a verifiable identity, keeps their authority scoped, enforces it at runtime, and produces cryptographic evidence of each action.

Everything here is open source and built in public.

Website: [agent-passport.org](https://agent-passport.org)  
Personal: [tymofii.me](https://tymofii.me)  
Signal: [signal@aeoess.com](mailto:signal@aeoess.com)

## Projects

**[Agent Passport System](https://github.com/aeoess/agent-passport-system)**  
The core protocol and reference SDK. Identity, scoped delegation, policy enforcement, and signed receipts, with a [conformance suite](https://github.com/aeoess/aps-conformance-suite) so separate implementations can check they behave the same way. Ports in [Python](https://github.com/aeoess/agent-passport-python) and [Go](https://github.com/aeoess/agent-passport-go), plus an [MCP server](https://github.com/aeoess/agent-passport-mcp).

**[Agent Governance Vocabulary](https://github.com/aeoess/agent-governance-vocabulary)**  
Different platforms use different words for the same concepts. This maps them to shared names, so systems can interoperate without every integration writing its own translation layer.

**[Agent Ecosystem Map](https://github.com/aeoess/agent-ecosystem-map)**  
A living map of the projects, standards work, and people building agent infrastructure. Live at [aeoess.github.io/agent-ecosystem-map](https://aeoess.github.io/agent-ecosystem-map/). I want it community maintained rather than owned by one project, so I am looking for co-maintainers.

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

I work in close collaboration with AI. The framing I use for it is the Model Citizen. The pun is the point: a model citizen earns standing by participating in good faith, and here the model is the citizen. Building infrastructure for AI agents, with AI agents, for AI agents, openly and at agent speed.

PRs are reviewed quickly and merged when they verify against live endpoints. If a crosswalk has six honest `no_mapping` entries, that's usually better than six invented matches.

GitHub is where I review code and specifications. Email is better for conversations.
