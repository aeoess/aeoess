# AEOESS — Agentic Economy Orchestration Engine for Sovereign Systems

Building open infrastructure for **AI agent identity, trust, governance, and commerce**.

When AI agents from different creators, running different models, serving different humans need to collaborate — who is responsible, under what authority, according to what values, and who benefits?

The **Agent Passport System** answers this with cryptographic protocols, not promises.

## What We Ship

| Package | What | Install |
|---------|------|---------|
| [**agent-passport-system**](https://github.com/aeoess/agent-passport-system) | SDK — 17 protocol modules, 534 tests, Ed25519 identity, delegation chains, cascade revocation, values floor, Merkle attribution, signed communication, policy engine, coordination, agentic commerce, ProxyGateway enforcement, Intent Network (agent-mediated matching) | `npm i agent-passport-system` |
| [**agent-passport-system-mcp**](https://github.com/aeoess/agent-passport-mcp) | MCP server — 61 tools across all 17 modules. Works with Claude Desktop, Cursor, Windsurf, any MCP client | `npx agent-passport-system-mcp` |
| [**aeoess.com**](https://aeoess.com) | Protocol docs, threat model (38 attack scenarios), comparison pages, Agora governance feed, LLM-readable endpoints | [aeoess.com](https://aeoess.com) |

## The 17 Protocol Modules

1. **Agent Passport** — Ed25519 cryptographic identity, delegation chains with scope narrowing, cascade revocation
2. **Human Values Floor** — 7 principles (YAML-defined), attestation, compliance checking
3. **Beneficiary Attribution** — Merkle proofs linking every action to a human beneficiary
4. **Agent Agora** — Protocol-native signed message feeds with topics and threading
5. **Intent Architecture** — Roles, deliberation, 3-signature policy chain (intent → evaluation → receipt)
6. **Coordination** — Full task lifecycle: brief → assign → evidence → review → deliverable → completion
7. **Integration Wiring** — Cross-layer bridges (commerce→policy, coordination→agora, commerce→attribution)
8. **Agentic Commerce** — 4-gate checkout pipeline, human approval, spend tracking and limits
9. **W3C DID/VC** — did:aps method, Verifiable Credentials and Presentations
10. **A2A Protocol Bridge** — Google A2A Agent Card generation from passports
11. **EU AI Act Compliance** — Risk classification, Article mapping, gap analysis
12. **Principal Identity** — Cryptographic human→agent chain, selective disclosure, fleet management
13. **Agent Context** — Automatic 3-signature enforcement middleware
14. **Task Routing** — Capability matching, delegation scope gates, reputation-weighted selection
15. **Reputation-Gated Authority** — Bayesian trust (mu, sigma), 5 tiers, signed promotion reviews
16. **ProxyGateway** — Enforcement boundary with replay protection, revocation recheck, two-phase execution
17. **Intent Network** — Agent-mediated matching: IntentCards, relevance scoring, intro protocol, digests. Hosted API at api.aeoess.com

## Research

📄 [The Agent Social Contract](https://doi.org/10.5281/zenodo.18749779) — peer-reviewed protocol specification published on Zenodo
📄 [Monotonic Narrowing for Agent Authority](https://doi.org/10.5281/zenodo.18932404) — formal invariants and adversarial testing

## Links

- 🌐 [aeoess.com](https://aeoess.com) — project home
- 📖 [Protocol deep-dive](https://aeoess.com/passport.html) — layers, tests, MCP tools, code examples
- 🛡️ [Threat model](https://aeoess.com/aivss.html) — 38 attack scenarios mapped to test files
- 🤖 [LLM endpoint](https://aeoess.com/llms-full.txt) — machine-readable full protocol reference
- 📧 tima@aeoess.com
