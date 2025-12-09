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
 
## 4. Research Directions (The Hyphaeic Stack)

Our R&D program operates as a vertical slice: from mathematical kernels up to organizational governance. We treat these not as separate projects, but as a unified dependency tree for sovereign agency.

### The Tech Tree: Strategic Overview

| Layer | Module | Objective | Status |
| :--- | :--- | :--- | :--- |
| **L4: Governance** | **Organizational Cybernetics** | The SPC as a cybernetic loop; self-owning entities. | *Conceptual* |
| **L3: Physics** | **Novel Substrates** | Thermodynamics-native hardware (FPGAs, Oscillator arrays, **Extropic**). | *Exploratory* |
| **L3: Body** | **Hybrid Agents** | Sim-to-real transfer; Valence-driven actuators. | *Prototyping* |
| **L2: Interface** | **Observability** | Narrative approximation of hidden states; "I feel boxed in." | *Active* |
| **L1: Signal** | **Empowerment Metrics** | Deriving $\hat{\epsilon}$ (Entropy) and $\Delta\hat{\epsilon}$ (Valence). | *Defined* |
| **L0: Kernel** | **Optionality Kernel** | Implementation of Ringström’s factorized feasibility operators. | *In Dev* |

HYPHAEIC_GAMBIT
├── I.  Kernel_Layer (Control & Reasoning)
│   ├── Optionality Kernel (Factorised Feasibility)
│   └── Empowerment Metrics (Entropy & Valence)
├── II. Interface_Layer (Semantics)
│   └── Observability (Narrative Approximation)
├── III. Physical_Layer (Action)
│   ├── Hybrid Embodiment (Blockchain as constraint layer)
│   └── Novel Substrates (Thermodynamic/Analog)
└── IV. Social_Layer (Governance)
    └── Organizational Cybernetics (The SPC)
---

### Phase I: Fundamentals
*The goal is an auditable, mechanistically steerable substrate for agency.*

| Direction | Key Goals | Implementation Notes |
| :--- | :--- | :--- |
| **4.8.1 Optionality Kernel** | • **Feasibility Tensors:** Sparse $\eta_\pi$ tables with zero-row viability.<br>• **Selectable Solvers:** Support for Grid/DP, Monte-Carlo, and Neural Surrogates ($\tilde{\eta}_\phi$).<br>• **Auditability:** Deterministic seeds; replayable `PlanTrace`. | The kernel is the shared substrate. It emits `OptionSet` / `FeasSlice` versions for all downstream consumers. |
| **4.8.2 Empowerment Metrics** | • **Entropy ($\hat{\epsilon}$):** Measure breadth of options.<br>• **Dispersion:** Measure coverage of distinct futures.<br>• **Valence ($\Delta\hat{\epsilon}$):** Operationalize as `Delta_Self` + `Delta_Others`. | **Real-time Requirement:** Metrics must update at control-loop rates (Hz to 100Hz). Used to ground narrative generation. |

### Phase II: The Cognitive Interface
*Making high-dimensional option spaces legible to humans and actionable for hybrid agents via narrative compression.*

| Direction | Key Goals | Rationale |
| :--- | :--- | :--- |
| **4.8.3 Observability** | • **Narrative Approximation:** LLMs as compressors for feasibility slices.<br>• **Reflective Valence:** "I feel free" vs "I feel cornered" based on $\Delta\hat{\epsilon}$.<br>• **SPA Sandbox:** Text-only micro-games (trust, barter) driven by empowerment gradients. | Kernel metrics are opaque. We use LLMs as a "Prefrontal Cortex" to steer faster, reactive components. |
| **4.8.4 Hybrid Agents** | • **Architecture:** Couple "Valence Oracle" (LLM/Slow) with "Motor Cortex" (RL/Fast).<br>• **Hot-Swapping:** Dynamic policy switching based on feasibility priors.<br>• **Metric:** Success measured by feasibility preservation, not reward maximization. | Validates whether valence-driven control survives real-world drift, noise, and stochasticity. |

### Phase III: Embodiment & Substrates
*Moving beyond the Von Neumann bottleneck. Agency requires hardware that understands resonance, not just logic.*

| Direction | Key Goals | The "Extropic" Frontier |
| :--- | :--- | :--- |
| **4.8.5 Novel Substrates** | • **Oscillatory Computing:** Phase-locking as an analogue for empowerment density.<br>• **Resonant Circuits:** Entropy/dispersion emerging from energy distribution.<br>• **FPGA Kernels:** Low-latency feasibility accelerators. | We explicitly probe hardware beyond bitwise logic. We align with thermodynamic computing paradigms (e.g., **Extropic**) where stochasticity and noise are features of the feasibility search, not bugs. |
| **4.8.6 Org Cybernetics** | • **The SPC Experiment:** Purpose & Profit as co-equal feasibility drivers.<br>• **Tamper-Evident Governance:** Cryptographic traces for resource allocation.<br>• **Self-Ownership:** Legal mechanisms for agents to steward their own resources. | Treating the corporation itself as a "Hybrid Agent" where human directors and machine systems form a coupled homeostatic loop. |
