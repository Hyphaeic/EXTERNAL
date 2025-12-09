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

Our industrial R&D effort, **The GAMBIT**, is an integrated attempt to formalize, build, and test systems that preserve optionality through valence-derived policies across technical, physical, and organizational domains.

### Phase I: The Kernel & Cognition
*Formalizing the mathematical substrate of agency.*

| Research Thrust | Objective | Key Technical Goals |
| :--- | :--- | :--- |
| **Optionality Kernel Development** | Implement Ringström’s factorized feasibility operators as a production-grade kernel. Agents must preserve and query option-space in real-time. | • **Feasibility Tensors:** Sparse $\eta_\pi$ tables with zero-row viability.<br>• **Selectable Solvers:** Grid/DP for small $X$, Neural Surrogates $\tilde{\eta}_\phi$, and Monte-Carlo.<br>• **Auditability:** Deterministic seeds; invariants on probability mass; replayable `PlanTrace`. |
| **Empowerment Metrics & Valence Proxies** | Translate feasibility structures into legible accounts of agency. Deriving entropy-based proxies to measure the diversity and dispersion of feasible futures. | • **Entropy Metrics:** Define $\hat{\epsilon} = H(\eta) + \lambda D(\eta)$ (Breadth + Dispersion).<br>• **Valence Proxy:** Operationalize valence as $\Delta\hat{\epsilon}_{self} + \Delta\hat{\epsilon}_{others}$.<br>• **Real-time Computability:** Updates at control-loop rates (Hz to 100Hz). |
| **Observability & Transparency** | Use LLMs as narrative approximators to make option-space legible to humans and actionable for hybrid agents (System 2 Reflection). | • **Reflective Valence:** Generating captions tied to $\Delta\hat{\epsilon}$ ("I feel cornered" / "I feel free").<br>• **Narrative Approximation:** Prompt-structured queries to produce natural language feasibility maps.<br>• **SPA Demonstrator:** Text-only sandboxes for micro-games (trust, barter, trolling). |

### Phase II: Instantiation & Substrate
*Grounding abstract kernels in physics and hardware.*

| Research Thrust | Objective | Key Technical Goals |
| :--- | :--- | :--- |
| **Hybrid & Embodied Agents** | Combine fast executors (RL/PID) with narrative foresight (LLM) grounded in the kernel. Testing if valence-driven control survives real-world entropy. | • **Hybrid Architecture:** Couple "Valence Oracle" (Reflective) with "Motor Cortex" (Reactive).<br>• **Hot-Swappable Policies:** Swap executor policies on-the-fly based on feasibility priors.<br>• **Sim-to-Real:** Minimal viable embodiments (thermal regulation, CNC axes). |
| **Novel Compute Substrates** | Explore architectures where optionality and resonance are native primitives, moving beyond temporally local, economically viable hardware paradigms. | • **Thermodynamic AI:** Utilizing **Extropic's** Energy-Based Models (EBM) for native probabilistic sampling.<br>• **Oscillatory Computing:** Coupled-oscillator arrays where phase-locking $\approx$ empowerment density.<br>• **FPGA Kernels:** Low-latency hardware accelerators for feasibility estimation. |

### Phase III: Organizational Cybernetics
*The Social Purpose Corporation (SPC) as a living laboratory.*

| Research Thrust | Objective | Key Technical Goals |
| :--- | :--- | :--- |
| **Organizational Cybernetics** | Explore the SPC structure as an experimental site for autonomy. Moving beyond profit/non-profit binaries to explore recursive self-ownership. | • **Feasibility in Governance:** Framing memos and budgets as feasibility-preserving acts.<br>• **Dual Valence Tests:** Evaluating actions by profit outcomes *and* purpose fulfillment.<br>• **Autonomous Entities:** Legal/technical mechanisms for agents to steward resources under SPC protections. |

---
