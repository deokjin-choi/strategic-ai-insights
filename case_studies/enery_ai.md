## **AI Consumes Electricity, but Also Designs the Grid**

***The Duality of AI and Energy Through the Lens of the IEA Report and an Execution Framework***


## **(0) Introduction – Why I Read This Report to the End**

When I read technical reports, I often pay more attention to the "structure" than to individual "sentences." The IEA's "Energy and AI" report was no exception. AI appears as a power-consuming entity, but also as a tool for optimizing the grid. A dual role. To me, this was not just a technical issue but a sign that **the system itself demands both collision and redesign**.

This article aims to:

1. Structurally summarize the core content of the report, and  
2. Lay out a step-by-step framework to translate it into an executable system.


## **(1) Key Summary of the Report – The Structure of Conflict and Coexistence Between AI and Energy**

### **1. AI Cannot Exist Without Electricity → Data Centers Consume Power at Industrial Scale**

- **As of 2024: Data centers consume 415 TWh (1.5% of global total)**  
- **By 2030: Expected to rise to 945 TWh** → Equivalent to Japan's total electricity usage  
- **AI-specific data centers consume more power than aluminum smelters**  
- Example: GPT-4 training requires **tens of thousands of NVIDIA A100/H100s running 24/7 for weeks** → **Several MW to tens of MW load**, equivalent to consumption by over 100,000 households

### **2. Structure of Power Consumption: Training + Inference + Cooling**

| Stage | Process | Reason for Energy Use |
|-------|---------|------------------------|
| **Training** | Optimize billions of parameters (loss minimization loop) | Repeated large matrix multiplications, parallel GPU operation |
| **Inference** | Generate output from input | Token processing, load accumulates with continuous input |
| **Cooling** | Fans/coolant/insulating oil to prevent server overheating | Accounts for 30~40% of energy use (need for PUE improvement) |

- Cooling evolution: Air → Water → **Immersion Cooling**  
  - With immersion cooling, **PUE < 1.1** is possible (used by Meta, Microsoft)

### **3. Big Tech Doesn’t Rely on National Power Grids – Building Proprietary Energy Systems**

| Company | Energy Strategy |
|---------|-----------------|
| **Google** | Operates solar + wind plants + ESS + 24/7 Carbon-Free Energy project |
| **Microsoft** | Invests in Small Modular Reactors (SMRs), partners with TerraPower |
| **AWS** | Global wind contracts via PPA + operates own wind farms in some regions |
| **Meta** | Installs dedicated solar near data centers + immersion cooling systems |

Key goals: **Energy independence + ESG (carbon neutrality) + supply chain risk mitigation**

### **4. AI Strengthens the Grid: 175 GW Capacity Without Additional Infrastructure**

- With AI-based grid control:
  - **Real-time renewable forecasting** → reduces surplus power
  - **Load shifting optimization** → relieves congestion
  - **Dynamic Line Rating** → adjusts transmission based on weather/wind conditions

Example: U.S. operator TenneT → AI-based load shifting **eased 15% congestion**

Summary: AI enables **smarter use of existing infrastructure** without new physical builds

### **5. AI Accelerates Energy Technology Innovation 10x**

| Tech Area | AI Use |
|-----------|--------|
| **CO₂ capture materials (MOFs, Zeolites)** | Predicts high-performance adsorbents using GNN, XGBoost |
| **Batteries** | Predicts chemistry combinations, optimizes charging/discharging pathways |
| **Synthetic fuel catalysts** | Analyzes papers + patents with LLMs to identify promising candidates |
| **Cement/Steel CO₂ reduction** | Models processes + optimizes control via reinforcement learning |

MIT: RL-based CO₂ process control → **20% energy savings**

### **6. AI Emits Carbon Too → Balance Is Needed**

- Report scenarios (Base Case):
  - Data center emissions: **180 Mt in 2024 → 300 Mt by 2035**
  - Worst-case (Lift-Off): **could rise to 500 Mt**

- Meanwhile, AI-driven optimization may reduce **5~7% of total energy emissions**

▶ **AI reduces GHGs but is also a significant emitter – a duality exists**

### **7. Explainable AI Is Essential in the Energy Sector**

- In grid control, CO₂ processes, and policy decisions:
  - Must **explain the rationale** behind decisions
  - Must present prediction + reasoning via **numbers/logics/visuals** for regulatory clarity

| Predictive Models | Explainable Models |
|------------------|---------------------|
| GPT, DNN, CNN | XGBoost + SHAP, Autoencoders, Rule-based |
| High performance but black-box | Slightly lower performance but more trustworthy |

### **8. Emerging Markets Have High Leapfrog Potential in AI+Energy**

- Many internet users, but limited data center infrastructure → **leap opportunities**
- Requirements: **Grid stability + renewable spread + digital talent pool**
- With AI: **Short-term scale-up of forecasting, efficient plant ops, local energy optimization**

Examples: India, Indonesia, Kenya → expanding AI-based microgrids, digital ESS

**Summary: AI is Both a Heavy Energy Consumer and the Strongest Catalyst for Energy Innovation.**
**The key to future energy strategy lies in who controls and utilizes this duality.**

---

## **(2) Execution Framework – Turning This Flow into a Structured System**

### **1. Define Preconditions – What Needs to Be in Place?**

- **Technical**: Interpretable, control-capable AI (not just predictive)
- **Infrastructure**: Sensor-connected AI with 2-way control (not passive calculators)
- **Institutional**: Human-centered AI design (not autonomous authority)

### **2. Assess Executability – Where and How to Start?**

| Priority | Area | Reason |
|---------|------|--------|
| 1st | Renewable energy forecasting | High demand, structured prediction, real-world decision linkage |
| 2nd | Grid load shifting | Sensor-based, semi-controllable, integrable |
| 3rd | CO₂ capture control | Technically complex, costly, regulation-sensitive |

Key bottlenecks include:  
- Unexplainable AI → operator distrust  
- Limited sensing + data access  
- Rigid regulatory structure

### **3. System Structuring – What Would an Actual Implementation Look Like?**

**Example 1: AI Grid Optimization Loop**

```
[1] Realtime sensing → [2] AI forecasting → [3] AI judgment → 
[4] Operator review → [5] Execution + feedback loop
```

**Example 2: Leapfrog Microgrid (e.g. Malaysia)**

```
[1] Local solar + ESS → [2] Edge AI demand prediction → 
[3] Autonomous scheduling + explainable logic → 
[4] One-click approval → [5] P2P grid exchange
```

**Design principles**:
1. Explainability first  
2. AI = Assistive logic  
3. Loop structure = Predict → Decide → Execute → Feedback → Retrain

---

## **(3) Conclusion – How Should We Understand the Clash Between AI and Energy?**

This report shows that **AI and energy are not just complementary – they also conflict**.  
The only way forward is **designing systems** where this duality becomes productive, not destructive.  
And that design must begin now.
