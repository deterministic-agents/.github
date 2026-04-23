# Deterministic Agents

**Open frameworks and reference implementations for governed agentic AI.**

Agentic AI systems  -  software that plans, retrieves context, and executes
actions with minimal human intervention  -  introduce a risk profile that
existing enterprise security and governance frameworks were not designed for.

We build open, implementable frameworks that let enterprises deploy AI agents
that are secure, auditable, and compliant by design.

---

## GATE  -  Governed Agent Trust Environment

GATE is a control-plane framework that defines 16 controls for trustworthy
agentic AI. It wraps the probabilistic agent in a deterministic shell of
governance: enforceable tool and memory boundaries, verifiable evidence,
deterministic replay, and human oversight primitives.

**[deterministicagents.ai](https://deterministicagents.ai)**  -  spec, controls, quickstarts

| Repo | What it is |
|---|---|
| [gate](https://github.com/deterministic-agents/gate) | Framework paper (PDF) and release home |
| [gate-contracts](https://github.com/deterministic-agents/gate-contracts) | JSON Schema contracts for all control plane events |
| [gate-python](https://github.com/deterministic-agents/gate-python) | Python reference library |
| [gate-policies](https://github.com/deterministic-agents/gate-policies) | OPA/Rego baseline policy and invariant bundles |
| [gate-conformance](https://github.com/deterministic-agents/gate-conformance) | Conformance checks, self-assessment, and runbooks |

---

## License

All content CC BY 4.0  -  Andrew Stevens
