# Deterministic Agents

**Open frameworks and reference implementations for governed agentic AI.**

Agentic AI systems  -  software that plans, retrieves context, and executes
actions with minimal human intervention  -  introduce a risk profile that
existing enterprise security and governance frameworks were not designed for.

We build open, implementable frameworks that let enterprises deploy AI agents
that are secure, auditable, and compliant by design.

---

## GATE  -  Governed Agent Trust Environment

GATE is a control-plane framework that defines 20 controls for trustworthy
agentic AI. It wraps the probabilistic agent in a deterministic shell of
governance: enforceable tool and memory boundaries, verifiable evidence,
deterministic replay, and human oversight primitives.

**[deterministicagents.ai](https://deterministicagents.ai)**  -  spec, controls, quickstarts

| Repo | What it is |
|---|---|
| [gate](https://github.com/deterministic-agents/gate) | Framework releases: artifacts bundle, paper PDF and markdown export |
| [gate-framework-paper](https://github.com/deterministic-agents/gate-framework-paper) | Source of the framework paper (Quarto book, diagram sources, export builders) |
| [gate-contracts](https://github.com/deterministic-agents/gate-contracts) | JSON Schema contracts for all control plane events |
| [gate-python](https://github.com/deterministic-agents/gate-python) | Python reference library |
| [gate-policies](https://github.com/deterministic-agents/gate-policies) | OPA/Rego baseline policy and invariant bundles |
| [gate-conformance](https://github.com/deterministic-agents/gate-conformance) | Conformance runner, self-assessment, standards mappings, runbooks |
| [gate-rust](https://github.com/deterministic-agents/gate-rust) | Rust companion crate: canonical JSON, envelopes, ledger, ES256 signing |
| [gate-fuzz](https://github.com/deterministic-agents/gate-fuzz) | Cross-language differential property suite (gate-python vs gate-rust) |
| [gate-knowledge](https://github.com/deterministic-agents/gate-knowledge) | The GATE conceptual layer as an Open Knowledge Format bundle |

---

## License

All content CC BY 4.0  -  Andrew Stevens
