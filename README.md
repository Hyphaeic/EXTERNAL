# Hyphaeic

> "To live, it must be able to die."

## 0. Abstract
Welcome to our public showcase! This repo lists our open-source projects and research papers. Hyphaeic is a system physics & cognition R&D lab creating self-sovereign living systems as aligned, autonomous & persistent economic agents.

## 1. Primary Research
We are moving alignment from a pedagogical problem (teaching values) to a mechanism design problem (constructing consequence).

| Document | Type | Description |
| :--- | :--- | :--- |
| **[Research Prospectus 2 Pager](./research_prospectus/2Pager_Research.pdf)** | Executive Primer | *A 2-page overview of the experimental framework.* Introduces the core thesis: providing agents with a "synthetic metabolism" built on cryptocurrency where depletion results in permanent cessation of function. |
| **[Sovereign AI Alignment](./research_prospectus/positionPaper.pdf)** | Position Paper | *10,000ft view of why proxies & heuristics are dead.* <br> Argues that proxy-based rewards fail due to the Symbol Grounding Problem. Proposes "Viability" as the grounding mechanism, using Blockchain as a substrate for thermodynamic irreversibility. |
| **[Research Programme Proposal](./research_prospectus/alignmentResearchProposal.pdf)** | Research Programme Proposal | *Technical Specification.* <br> Details the Semantic Empowerment Approximation (SEA), the mathematics of the PILE model, and the specific experimental regimes (Renewable vs. Lump-Sum) used to test our hypotheses. |

## 2. Experimental Hypotheses
As detailed in our [Proposal](./research_prospectus/2Pager_Research.pdf), we are testing four primary signals:

1.  **Rhythmic Stability:** Renewable agents should exhibit expenditure variance synchronised with yield cadence.
2.  **Scarcity-Induced Volatility:** Lump-sum agents will likely exhibit higher action volatility as reserves decline.
3.  **Calibration:** Constrained agents will show superior world-model calibration versus unbounded controls.
4.  **Efficiency:** Agents driven by Empowerment & Valence (under constraint) will achieve higher optionality gained per unit energy spent.

## 3. Active Repositories
Our research is implemented across the following codebases:

* **[agent-metric-dashboard](https://github.com/Hdpbilly/agent-metric-dashboard)**
    * *A Toy example This is an early exploration of our app's Agent TUI.* All data, metrics, and mock values are for demonstration purposes only. This screencast helps us visualize the interface and refine initial ideas about state calculations and system    dynamics.
* **[radix-runtime](https://github.com/Hyphaeic/radix-runtime)**
    * *Browser WASM clock system* A WebAssembly-based mixed-radix clock implementation using SharedArrayBuffer for shared memory between the main thread and Web Workers.
 
## 4. Research Directions
We are actively pursuing the following R&D thrusts to formalize and implement the "Gambit"—our integrated attempt to build systems that preserve optionality through valence-derived policies.

| Thrust | Objective | Technical Implementation |
| :--- | :--- | :--- |
| **1. Optionality Kernel** | **Production-grade Feasibility.** Implement Ringström’s factorized feasibility operators ($X \times \mathbb{N}$) as a stable kernel so agents can query option-space in real time. | • **Feasibility Tensors:** Sparse $\eta_\pi$ tables with zero-row viability.<br>• **Selectable Solvers:** Grid/DP for small $X$, Monte-Carlo for stochastic crowds, and Neural Surrogates ($\tilde{\eta}_\phi$).<br>• **Auditability:** Deterministic seeds and replayable `PlanTrace` structs. |
| **2. Empowerment Metrics** | **Legible Agency.** Translate raw feasibility slices into entropy-based proxies ($\hat{\epsilon}$) for empowerment and valence. | • **Entropy & Dispersion:** Define $\hat{\epsilon} = H(\eta) + \lambda D(\eta)$ to capture option breadth.<br>• **Valence Proxy:** Operationalize valence as $\Delta \hat{\epsilon}_{self} + \Delta \hat{\epsilon}_{others}$.<br>• **Real-time:** Compute proxies at control-loop rates (Hz to 100Hz). |
| **3. Observability** | **Narrative Approximation.** Use LLMs to compress opaque feasibility slices into reflective natural language ("I feel cornered"). | • **Reflective Valence:** Generating captions tied to $\Delta \hat{\epsilon}$ ("I feel free").<br>• **SPA Demonstrator:** A text-only sandbox for micro-games (trust, barter) measured by empowerment gradients, not task reward. |
| **4. Hybrid Agents** | **Grounded Foresight.** Coupling "slow" LLM valence oracles with "fast" RL executors to survive real-world drift. | • **Architecture:** LLM (Prefrontal Cortex) steering RL (Motor Cortex).<br>• **Hot-Swapping:** Executor policies swapped on-the-fly based on feasibility priors.<br>• **Metric:** Success measured by feasibility preservation, not score maximization. |
| **5. Novel Substrates** | **Hardware-Native Agency.** Exploring architectures where resonance and optionality are native primitives (beyond bitwise logic). | • **Oscillatory Computing:** Phase-locking and coherence as analogues for empowerment density.<br>• **FPGAs:** Hardware feasibility accelerators for low-latency control.<br>• **Analog:** Using CNC toolpaths as "analog compute" for agency metrics. |
| **6. Org Cybernetics** | **The SPC as Agent.** Using the Social Purpose Corporation (SPC) structure to test autonomous governance and machine value. | • **Feasibility Governance:** Framing board memos/budgets as feasibility-preserving acts.<br>• **Dual Valence:** Evaluating actions by profit *and* purpose fulfillment.<br>• **Autonomy:** Legal/technical mechanisms for agents to steward resources. |

### The Technical Spine
Each thrust above contributes to a unified design language for agency.
1.  **Kernel:** Implements the factorized operators.
2.  **Metrics:** Derives measurable guidance ($\hat{\epsilon}$) from the Kernel.
3.  **Narrative:** Compresses Metrics into human-legible reflection.
4.  **Observability:** Instruments the flow of energy and feasibility.
5.  **Embodiment:** Grounds the abstract Kernel in physical action.
6.  **Substrates:** Accelerates the calculation via native hardware.
7.  **Cybernetics:** Extends the principles into legal and financial governance.
```

---
