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

Our integrated R&D effort, **The GAMBIT**, formalises and tests systems that preserve optionality through valence-derived policies across technical, physical, and economic domains.

### Phase I: The Kernel & Cognition
*Engineering agency.*

| Active Workstream | Description | Key Technical Goals |
| :--- | :--- | :--- |
| **STOKs (State-Time Option Kernels)** |  <br> Modular Reachability Engine using **Burn**. Maintains Factorized Transition Tensors on GPU to compute 'Feasibility Iteration' updates in milliseconds. | • **JIT Fusion:** Compile update rules into single kernels for millisecond world-model retraining.<br>• **Control:** Actions derived by batched tensor sampling of dynamic models.<br>• **Novel Hardware:** Implementing sampling methods on paradigms like **Extropic** EBMs. |
| **PSKA (Persistence State-Kernel Architecture)** | Model-based dynamic predictive map frameworks. | • **Compositionality:** Applying Ringström’s theory to valence and empowerment heuristics.<br>• **Dynamic Mapping:** Constructing predictive maps that guide agents toward viable option-spaces. |
| **Empowerment Metrics** | Deriving entropy-based proxies to measure diversity and dispersion of feasible futures. | • **Entropy:** $\hat{\epsilon} = H(\eta) + \lambda D(\eta)$ (Breadth + Dispersion).<br>• **Valence:** $\Delta\hat{\epsilon}_{self} + \Delta\hat{\epsilon}_{others}$.<br>• **Latency:** Updates at control-loop rates (Hz to 100Hz). |

### Phase II: Instantiation & Substrate
*Grounding abstract kernels in physics and hardware.*

| Active Workstream | Description | Key Technical Goals |
| :--- | :--- | :--- |
| **Client <-> Server Relationships** | Architecting WASI-compliant environments for high-concurrency runtimes. | • **Infrastructure:** Secure multi-tenant compute workloads.<br>• **Netcode:** Deterministic execution for verifiable distributed agent inference. |
| **Hybrid & Embodied Agents** | Combining fast executors (RL/PID) with narrative foresight (LLM for the time being). | • **Architecture:** Couple reflective "Valence Oracle" with reactive "Motor Cortex".<br>• **Policy:** Hot-swappable executor policies based on feasibility priors.<br>• **Sim-to-Real:** Minimal viable embodiments (thermal regulation, CNC axes). |

### Phase III: Organizational & Economic Cybernetics
*Market structures as oracles of costly information.*

| Active Workstream | Description | Key Technical Goals |
| :--- | :--- | :--- |
| **Prediction Markets** | Autonomous LP bootstrap contracts for sovereign, recurrent prediction modules acting as oracles of costly information. | • **Sovereign Liquidity:** Markets that do not require human profit incentives for base liquidity.<br>• **Recurrence:** Persistent prediction modules maintained by agents as epistemic tools. |
| **Organizational Cybernetics** | The Social Purpose Corporation (SPC) as a site for autonomous resource stewardship. | • **Governance:** Framing memos/budgets as feasibility-preserving acts.<br>• **Valence:** Evaluating actions by dual profit/purpose outcomes.<br>• **Legal:** Mechanisms for agents to steward resources under SPC protections. |

