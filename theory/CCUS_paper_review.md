# Comprehensive Dissection of TFSC CCUS Patent Analysis Paper

## Paper Information

* **Title**: Observing technology reserves of carbon capture and storage via patent data: Paving the way for carbon neutral
* **Journal**: Technological Forecasting & Social Change (TFSC), 2021
* **Authors**: Jia-Ning Kang, Yi-Ming Wei, Lan-cui Liu, Jin-Wei Wang

---

## Overall Structure

```text
Introduction → Literature Review → Methods → Results & Discussions → Conclusions & Policy Implications
```

---

## 1. Introduction (Section 1)

### Key Sentences & Meaning

* **"The Paris Agreement proposed an ambitious goal of limiting the global temperature increase..."**
  → CCUS is crucial for meeting climate goals.
* **"There are heavy responsibilities on the way to a carbon-free future."**
  → CCUS plays a central role in achieving carbon neutrality.
* **"CCUS is developed with the focus of removing carbon dioxide from the atmosphere."**
  → CCUS focuses on capture, utilization, and storage of CO2.

### Research Questions

1. What progress is being made with CCUS, especially in different economies?
2. What are the technology reserves and their spatial distribution characteristics of CCUS?
3. What are the key paths of CCUS technology development?
4. What are the potential breakthrough technologies? Which technology clusters lack research?

---

## 2. Literature Review (Section 2)

### Key Points

* Describing the **status quo** of technology helps forecast future trends.
* Existing methods used:

  * Bibliometrics
  * Expert-based Delphi surveys
  * S-curve models
  * Technology forecasting based on expert opinions
* Limitations:

  * Narrow coverage
  * Lack of automation
  * Expert bias
  * Insufficient dynamic monitoring

### Contribution of This Study

* Introduces a **data-driven integrated approach**.
* Combines **patent data**, **LDA topic modeling**, and **FCFP (Forward Citation Full Path)** to extract technology paths and gaps.

---

## 3. Methods (Section 3)

### 3.1 Data Collection

* **Database**: Derwent Innovation (DWPI)
* **Timeframe**: 1963 - 2019
* **Sample**: 36,854 patent records (12,906 patent families)
* **Search Strategy**: Combination of keywords and IPC codes

### 3.2 Topic Modeling with LDA

* Use Latent Dirichlet Allocation to extract 20 technology topics from patent abstracts.
* Each patent assigned to a technology cluster.

### 3.3 Forward Citation Full Path (FCFP)

* Builds development paths from patent citation networks.
* Applies dynamic programming to identify main paths.

#### Weight Calculation:

$$
W(e_{ij}) = (d^+(i) + 1) \times (d^+(j) + 1)
$$

#### Path Weight Sum:

$$
FCPW(s \rightarrow t) = \sum W(e_{ij})
$$

#### Dynamic Programming Maximum Path:

$$
MFCPW(s \rightarrow c_i) = \max \left( \sum W(e_{c_{i-1},c_i}) + MFCPW(s \rightarrow c_{i-1}) \right)
$$

### 3.4 Technology Gap Calculation

* Based on development distance in citation network:

$$
\text{Technology Gap} = 1 - \left( \frac{\text{Current Development Distance}}{\text{Maximum Development Distance}} \right)
$$

* A higher gap indicates a less developed and less connected cluster.

---

## 4. Results and Discussion (Section 4)

### 4.1 CO2 Capture Market Status

* Rapid growth from 2005 to 2011; now matured.
* China, US, and EU hold majority of patents.

### 4.2 CO2 Storage and Utilization Market Status

* Storage and utilization started later (1972+), still in growth phase.
* Significant technological gaps remain.

### 4.3 Technology Reserves by Country

* US: Balanced and diversified technology layout.
* China: Rapid growth but focused on specific processes (chemical absorption, equipment upgrade).
* Japan/Developing countries: Narrower technology spectrum.

### 4.4 Technology Evolution Paths

* 27 key technology development paths identified using FCFP.
* Multiple paths allowed per start-end pair if weights equal.

### 4.5 Breakthrough Technologies

* 57 potential breakthrough technologies identified:

  * CO2 Capture: 35 breakthroughs (adsorbents, membranes, DAC, regeneration processes, etc.)
  * Storage & Utilization: 22 breakthroughs (EOR, mineralization, CO2 utilization pathways)

### 4.6 Technology Gaps Visualization (LDA-based)

* Topic density map reveals valleys (under-researched topics).
* Densely populated areas = mature topics; valleys = future development potential.
* Developing countries should target valley clusters for R\&D catch-up.

---

## 5. Conclusions and Policy Implications (Section 5)

### 5.1 Key Conclusions

* CO2 capture matured; storage and utilization still emerging.
* Major gaps exist in storage/utilization sectors.
* Technology gaps quantified using citation paths and LDA topic models.

### 5.2 Policy Implications

* Developing countries should:

  * Focus on low-energy, low-cost materials initially.
  * Close technology gaps in core clusters.
  * Prioritize identified breakthrough clusters (monitoring, storage, microalgae separation, direct air capture, etc.)

---

## 6. Full Analytical Flow Summary

```text
Patent Data → IPC & Keyword Filtering → LDA Topic Modeling → Citation Network → FCFP Path Extraction → Development Distance → Technology Gap → Breakthrough Detection → Policy Recommendations
```

---

*This markdown is fully GitHub-ready and captures the entire TFSC CCUS paper dissection.*
