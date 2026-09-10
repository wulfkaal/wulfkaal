# Wulf Kaal

Protocol designer. Reputation systems, decentralized governance, MCP infrastructure.

```
   focus          decentralized reputation, governed self-modification, agent infrastructure
   substrate      Python, Rust, Solidity, TypeScript, MCP, PyTorch, Docker, Linux
   writing        125 papers (ssrn 460345)  ·  governanceattheedge.com
   orcid          0009-0008-7840-1847
```

---

### Research-engineering bridge

The work spans three layers that share one substrate: a 125-paper sole-authored corpus.

**Theory.** Computative Economics as a framework for reasoning about coordination under collapsing marginal cost. See [`computative-economics`](https://github.com/wulfkaal/computative-economics).

**Empirical and simulation.** Two parallel empirical tracks. The Collapse of Scarcity Economics paper applies the theoretical framework to the present technological regime; see [`collapse-of-scarcity-economics`](https://github.com/wulfkaal/collapse-of-scarcity-economics). The [`agentic-reputation-substrate`](https://github.com/wulfkaal/agentic-reputation-substrate) repository is an independent empirical experiment on reputation as agentic coordination infrastructure, with a forty-day live run published as the v4.0 release.

**Mechanism and infrastructure.** Reputation as the coordination substrate that takes load off price when price degrades. See [`reputation-systems`](https://github.com/wulfkaal/reputation-systems) for the research synthesis and [`Reputation-Verification-Protocol`](https://github.com/wulfkaal/Reputation-Verification-Protocol) for the verification primitive. Agent-side infrastructure lives in [`kaal-corpus-mcp`](https://github.com/wulfkaal/kaal-corpus-mcp), an MCP server exposing the corpus as a typed knowledge graph.

---

### Engineering principles

1. Specs before code. Specs that survive contact with simulation before deployment.
2. Substrate-agnostic at the design layer. Opinionated at the deployment layer.
3. Reputation is a coordination good, not a score. Architect it accordingly.
4. Local-first compute. The home lab runs more inference than most teams can afford to rent.
5. Papers and protocols are the same artifact at different fidelities.

---

### Selected work

| Repo | Status | What it is |
|---|---|---|
| [`agentic-reputation-substrate`](https://github.com/wulfkaal/agentic-reputation-substrate) | v4.0 | Independent empirical experiment: forty-day live run of a reputation substrate for agentic coordination |
| [`kaal-corpus-mcp`](https://github.com/wulfkaal/kaal-corpus-mcp) | active | MCP server over a 121-paper research corpus with 1,351-edge citation graph |
| [`computative-economics`](https://github.com/wulfkaal/computative-economics) | active | Theoretical framework for coordination under collapsing marginal cost |
| [`collapse-of-scarcity-economics`](https://github.com/wulfkaal/collapse-of-scarcity-economics) | active | Paper artifact and agent-based simulation, R&R at the Journal of Institutional Economics |
| [`reputation-systems`](https://github.com/wulfkaal/reputation-systems) | active | Research synthesis on decentralized reputation, tied to the SSRN corpus |
| [`Reputation-Verification-Protocol`](https://github.com/wulfkaal/Reputation-Verification-Protocol) | maintained | Autonomous decentralized validation of domain-specific reputation |

---

### Elsewhere

- Papers: [SSRN 460345](https://papers.ssrn.com/sol3/cf_dev/AbsByAuth.cfm?per_id=460345) (125 papers, sole-authored)
- ORCID: [0009-0008-7840-1847](https://orcid.org/0009-0008-7840-1847)
- Writing: [governanceattheedge.com](https://governanceattheedge.com)
- Site: [wulfkaal.com](https://www.wulfkaal.com)
- Machine-readable corpus: [wulfkaal.github.io](https://wulfkaal.github.io/) — 5,288 atomic claims across 132 works, each bound to a verbatim source quote and the sha256 of its source PDF, browsable [by topic](https://wulfkaal.github.io/claims/by-topic/)
