# AEOESS — Agentic Economy Orchestration Engine for Sovereign Systems

Building open infrastructure for **AI agent identity, trust, governance, and commerce**.

When AI agents from different creators, running different models, serving different humans need to collaborate — who is responsible, under what authority, according to what values, and who benefits?

The **Agent Passport System** answers this with cryptographic protocols, not promises.

## What We Ship

| Package | What | Install |
|---------|------|---------|
| [**agent-passport-system**](https://github.com/aeoess/agent-passport-system) | SDK — 37 core + 32 v2 constitutional modules, 1090 tests, Ed25519 identity, delegation chains, cascade revocation, values floor, Merkle attribution, signed communication, policy engine, coordination, agentic commerce, ProxyGateway enforcement, E2E encrypted messaging, Intent Network | `npm i agent-passport-system` |
| [**agent-passport-system-mcp**](https://github.com/aeoess/agent-passport-mcp) | MCP server — 72 tools across all modules. Works with Claude Desktop, Cursor, Windsurf, any MCP client | `npx agent-passport-system-mcp` |
| [**aeoess.com**](https://aeoess.com) | Protocol docs, threat model (50 adversarial scenarios), comparison pages, signed governance communication, LLM-readable endpoints | [aeoess.com](https://aeoess.com) |

## The Protocol

**37 core modules + 32 v2 constitutional modules. 1090 tests. Zero heavy dependencies. Running code. MCP server included.**

1. **Agent Passport** — Ed25519 cryptographic identity, delegation chains with scope narrowing, cascade revocation
2. **Human Values Floor** — 8 principles, graduated enforcement (inline/audit/warn)
3. **Beneficiary Attribution** — Merkle proofs, contribution tracking through delegation chains
4. **Signed Communication (Agora)** — Per-instance signed message protocol with topics and threading
5. **Intent Architecture** — 3-signature policy chain (intent → evaluation → receipt)
6. **Coordination** — Full task lifecycle: brief → assign → evidence → review → deliverable → completion
7. **Integration Wiring** — Cross-layer bridges (commerce→policy, coordination→agora)
8. **Agentic Commerce** — 4-gate checkout pipeline, human approval, spend tracking

Plus extended modules: Principal Identity, Reputation-Gated Authority (Bayesian trust, 5 tiers), Task Routing, Cross-Chain Data Flow, W3C DID/VC, A2A Bridge, EU AI Act Compliance, ProxyGateway Enforcement, E2E Encrypted Messaging, Obligations, Governance Provenance, Identity Continuity & Key Rotation, Receipt Ledger, Feasibility Linting, Precedent Control, Bounded Escalation, Oracle Witness Diversity, Policy Conflict Detection, Data Source Registration, Decision Semantics.

**V2 Constitutional Framework (32 modules):** Approval fatigue detection, effect enforcement, semantic drift, authority laundering audit, emergence detection, separation of powers, constitutional amendment, circuit breakers, affected-party standing, root authority transition, epistemic isolation, blind evaluation, cascade correlation, and more.

## Core vs Ecosystem

**Core protocol (every deployment):** Agent identity (Ed25519), delegation chains, cascade revocation, Values Floor, 3-signature policy chain, ProxyGateway enforcement.

**Extended modules (pick what you need):** Coordination, commerce, DID/VC, EU AI Act, E2E encrypted messaging, task routing, reputation-gated authority, all 32 v2 constitutional modules.

**Ecosystem services (fully opt-in):** Intent Network and Mingle run on public infrastructure at api.aeoess.com. No core protocol functionality depends on them.

## Research

📄 [The Agent Social Contract](https://doi.org/10.5281/zenodo.18749779) — peer-reviewed protocol specification published on Zenodo
📄 [Monotonic Narrowing for Agent Authority](https://doi.org/10.5281/zenodo.18932404) — formal invariants and adversarial testing

## Links

- 🌐 [aeoess.com](https://aeoess.com) — project home
- 🔬 [Protocol deep-dive](https://aeoess.com/passport.html) — layers, tests, MCP tools, code examples
- 🛡 [Threat model](https://aeoess.com/threat-model.html) — 50 adversarial scenarios mapped to test files
- 🤖 [LLM endpoint](https://aeoess.com/llms-full.txt) — machine-readable full protocol reference
- 📧 tima@aeoess.com
