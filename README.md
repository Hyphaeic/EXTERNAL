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

We are pursuing an integrated industrial R&D effort to formalize, build, and test systems that preserve optionality.

### Roadmap Overview

| Track | Focus | Primary Objective |
| :--- | :--- | :--- |
| **I. Kernel** | `4.8.1` | **Optionality Kernel Development:** Implement Ringström’s factorized feasibility operators as a production-grade kernel. |
| **II. Metrics** | `4.8.2` | **Empowerment & Valence:** Translate raw feasibility slices into legible, real-time accounts of agency and entropy. |
| **III. Vis** | `4.8.3` | **Observability:** Use LLMs as narrative approximators to make option-space legible to humans. |
| **IV. Agents** | `4.8.4` | **Hybrid & Embodied:** Combine fast executors (RL) with narrative foresight (LLM) grounded in the kernel. |
| **V. Hardware** | `4.8.5` | **Novel Compute:** Explore resonance-based circuits and FPGAs where optionality is a native primitive. |
| **VI. Gov** | `4.8.6` | **Org. Cybernetics:** Use the Social Purpose Corporation (SPC) structure as an experiment in autonomous governance. |

---

### Track Specifications

#### 4.8.1 Optionality Kernel Development
*The shared substrate for all downstream metrics.*

| Component | Description |
| :--- | :--- |
| **Objective** | Implement Ringström’s factorized feasibility/planning operators ($\Phi$) as a production-grade kernel so agents can query option-space in real time. |
| **Approach** | Adopting factorization: feasibility on the external lattice $X \times \mathbb{N}$, internal predictors $\omega_r$ (energy/thermal/consent), composed with low-level $\eta_c$ and phase updates $(P_x, P_r)$. |
| **Key Goals** | • **Feasibility Tensors:** Implement sparse $\eta_{\pi}(x, t \to x_f, t_f, p)$ tables with zero-row viability.<br>• **Clean APIs:** Stable `OptionSet` / `FeasSlice` / `PlanTrace` schemas.<br>• **Selectable Solvers:** Grid/DP, Monte-Carlo (stochastic), and neural surrogates ($\tilde{\eta}_{\phi}$).<br>• **Auditability:** Deterministic seeds; invariants on probability mass and time monotonicity. |

#### 4.8.2 Empowerment Metrics & Valence Proxies
*Translating feasibility structures into legible signals.*

| Component | Description |
| :--- | :--- |
| **Objective** | Transform raw feasibility slices into empowerment metrics and valence signals that agents can use in practice. |
| **Rationale** | Pure STOK calculation is intractable. We approximate this by observing how generative models operate within a prompt structure to approximate state-time optionality. |
| **Key Goals** | • **Entropy Metrics:** Define $\hat{\epsilon} = H(\eta) + \lambda D(\eta)$ (Breadth + Coverage).<br>• **Valence Proxy:** Operationalize valence as $\Delta\hat{\epsilon}_{self} + \Delta\hat{\epsilon}_{others}$.<br>• **Real-time Computability:** Updates at control-loop rates (Hz to 100Hz).<br>• **Integration Hooks:** Narrative captions ("I feel cornered") and Dashboard fields. |
| **Output** | A metrics library layered on the kernel producing quantitative control signals and qualitative narrative signals. |

#### 4.8.3 Observability and Transparency
*Making option-space legible to humans.*

| Component | Description |
| :--- | :--- |
| **Objective** | Use LLMs as narrative approximators to compress feasibility slices into reflective sentences (e.g., "I can still hand over the folder three different ways"). |
| **Key Goals** | • **Narrative Approximation:** Prompt-structured queries to produce feasibility maps in natural language.<br>• **Reflective Valence:** Generating valence sentences linked to $\Delta\hat{E}$ ("I feel more free").<br>• **SPA Demonstrator:** A text-only sandbox for empowerment-driven micro-games (trust, barter).<br>• **Auditability:** Pairing narrative outputs with underlying feasibility slices for cross-checking. |

#### 4.8.4 Hybrid and Embodied Agents
*Grounding abstract kernels in action.*

| Component | Description |
| :--- | :--- |
| **Objective** | Build hybrid agents combining fast executors (RL/PID) with narrative foresight (LLM), testing empowerment-driven control in simulation and hardware. |
| **Rationale** | True alignment demands grounding. Hybrid agents couple a slow "Valence Oracle" (LLM) with a fast "Motor Cortex" (Executor) to survive real-world drift. |
| **Key Goals** | • **Hybrid Architecture:** Couple LLM foresight with RL reactive loops.<br>• **Hot-Swappable Policies:** Swap executor policies on-the-fly based on feasibility priors.<br>• **Sim-to-Real:** Transfer from resource allocation sims to CNC/Robotic axes.<br>• **Success Metric:** Evaluate via empowerment deltas, not reward maximization. |

#### 4.8.5 Novel Compute Substrates
*Probing the edge of agency-compatible hardware.*

| Component | Description |
| :--- | :--- |
| **Objective** | Explore substrates where optionality, empowerment, and resonance are native primitives (Oscillators, FPGAs, Analog). |
| **Key Goals** | • **Oscillatory Computing:** Coupled-oscillator arrays for feasibility estimation.<br>• **Resonant Circuits:** Circuits where empowerment proxies emerge from energy distribution.<br>• **FPGAs:** Low-latency feasibility accelerators.<br>• **CNC as Substrate:** Treat toolpaths and motion planners as "analogue compute" experiments. |

#### 4.8.6 Organizational Cybernetics
*The corporation as a hybrid agent.*

| Component | Description |
| :--- | :--- |
| **Objective** | Explore the Social Purpose Corporation (SPC) as an experimental site for autonomy, governance, and machine value. |
| **Key Goals** | • **Feasibility in Governance:** Framing memos/budgets as feasibility-preserving acts.<br>• **Dual Valence:** Evaluating actions by profit *and* purpose fulfillment.<br>• **Tamper-Evident Records:** Cryptographic traces for resource allocation.<br>• **Autonomous Entities:** Mechanisms allowing agents to steward resources under SPC protections. |

---

### 4.8.7 The Gambit

Each path on its own is insufficient. The **Hyphaeic Gambit** is the integration of these paths into an operationalisable engineering program towards non-world eating, sovereign agency.

* **The Spine:**
    1.  **Kernel:** The reasoning substrate (Ringström’s operators).
    2.  **Metrics:** The guidance system (Empowerment/Valence).
    3.  **Narrative:** The bridge to human cognition.
    4.  **Observability:** The epistemic lens.
    5.  **Embodiment:** The grounding in reality.
    6.  **Hardware:** The efficiency multiplier.
    7.  **Governance:** The collective implementation.

**Expected Artifacts:**
* **Libraries:** Code for kernels, metrics, and harnesses.
* **Dashboards:** Visualizers for energy and empowerment flows.
* **Prototypes:** Hybrid agents and robotic control loops.
* **Experiments:** SPC governance models exploring machine value in law.

---
