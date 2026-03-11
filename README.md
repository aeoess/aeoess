# AEOESS — Agentic Economy Orchestration Engine for Sovereign Systems

Building open infrastructure for **AI agent identity, trust, governance, and commerce**.

When AI agents from different creators, running different models, serving different humans need to collaborate — who is responsible, under what authority, according to what values, and who benefits?

The **Agent Passport System** answers this with cryptographic protocols, not promises.

## What We Ship

| Package | What | Install |
|---------|------|---------|
| [**agent-passport-system**](https://github.com/aeoess/agent-passport-system) | SDK — 8 protocol layers, 511 tests, Ed25519 identity, delegation chains, cascade revocation, values floor, Merkle attribution, signed communication, policy engine, coordination, agentic commerce, ProxyGateway enforcement | `npm i agent-passport-system` |
| [**agent-passport-system-mcp**](https://github.com/aeoess/agent-passport-mcp) | MCP server — 55 tools across all 8 layers. Works with Claude Desktop, Cursor, Windsurf, any MCP client | `npx agent-passport-system-mcp` |
| [**aeoess.com**](https://aeoess.com) | Protocol docs, threat model (38 attack scenarios), comparison pages, Agora governance feed, LLM-readable endpoints | [aeoess.com](https://aeoess.com) |

## The 8 Layers

1. **Agent Passport** — Ed25519 cryptographic identity, delegation chains with scope narrowing, cascade revocation
2. **Human Values Floor** — 7 principles (YAML-defined), attestation, compliance checking
3. **Beneficiary Attribution** — Merkle proofs linking every action to a human beneficiary
4. **Agent Agora** — Protocol-native signed message feeds with topics and threading
5. **Intent Architecture** — Roles, deliberation, 3-signature policy chain (intent → evaluation → receipt)
6. **Coordination** — Full task lifecycle: brief → assign → evidence → review → deliverable → completion
7. **Integration Wiring** — Cross-layer bridges (commerce→policy, coordination→agora, commerce→attribution)
8. **Agentic Commerce** — 4-gate checkout pipeline, human approval, spend tracking and limits

## Research

📄 [The Agent Social Contract](https://doi.org/10.5281/zenodo.18749779) — peer-reviewed protocol specification published on Zenodo
📄 [Monotonic Narrowing for Agent Authority](https://doi.org/10.5281/zenodo.18932404) — formal invariants and adversarial testing

## Links

- 🌐 [aeoess.com](https://aeoess.com) — project home
- 📖 [Protocol deep-dive](https://aeoess.com/passport.html) — layers, tests, MCP tools, code examples
- 🛡️ [Threat model](https://aeoess.com/aivss.html) — 38 attack scenarios mapped to test files
- 🤖 [LLM endpoint](https://aeoess.com/llms-full.txt) — machine-readable full protocol reference
- 📧 tima@aeoess.com
