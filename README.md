# Behavioral Digital Twins (BDT) for Tobacco Regulatory Science

## Proposed Roadmap at IHPS (UCSF)

This repository open-sources the strategic roadmap and conceptual framework for the **Behavioral Digital Twin (BDT)** approach, as proposed for the Institute for Health Policy Studies (IHPS) at UCSF.

[**🌐 Live Page**](https://yichao2022.github.io/Behavioral-Digital-Twin-Roadmap/) | [**📄 Quarto Source (.qmd)**](https://github.com/yichao2022/Behavioral-Digital-Twin-Roadmap/blob/main/index.qmd)

### 1. Vision: Generative Population Modeling
As a **Problem Solver** bridging economic theory and machine learning, this framework proposes the use of **Behavioral Digital Twins (BDT)** to address the complexity of modern tobacco use. 

Traditional models often fail to capture the granular, non-linear transitions between traditional cigarettes, E-cigarettes, and HTPs (like IQOS). The BDT approach creates individual-level generative agents that “experience” policy changes in a simulated environment before they manifest in the population.

### 2. Core Research Synergies: From Data to Policy Audit
The BDT logic flow moves from raw data (PATH, NHIS, Social Media) to an independent regulatory decision support layer.

#### A. Modeling Transitions & Poly-use Dynamics
Transitions are rarely binary. The BDT framework treats a user’s tobacco journey as a **stochastic state-space model**.
- **Product Attributes**: Modeling how flavor bans or nicotine caps alter the “utility surface,” driving users toward cessation or alternative product uptake.
- **Dynamic Poly-use**: Simulation of concurrent use patterns based on longitudinal survey data.

#### B. Precision Equity: Vulnerable Group Simulations
Aggregated data masks inequality. This framework specializes in **disaggregated agent modeling** for:
- **Low SES & Minority Groups**: Integrating constraints like financial burden and retail density.
- **Youth & Social Media Influence**: Utilizing ML to extract behavioral priors from platforms like TikTok/XHS to model the initiation phase.

#### C. The Independent Audit Tool
In response to industry-funded health impact models, the BDT advocates for **Independent, Transparent, and Robust Population Health Simulations**.

| Feature | Industry “Black-Box” Models | Behavioral Digital Twin (BDT) |
| :--- | :--- | :--- |
| **Transparency** | Proprietary / Hidden Causal Chains | **Open-Source / Peer-Audited** |
| **Granularity** | Aggregate cohorts | **Individual-level Agents** |
| **Bias Mitigation** | Optimized for commercial validation | **Optimized for Health Equity** |
| **Data Fusion** | Limited to historical trends | **Real-time Social Media + Survey Fusion** |

### 3. Technical Stack
- **Generative Agents**: Large-scale simulation of 100k+ independent tobacco-using agents.
- **ML & Social Media**: NLP pipelines for analyzing transition signals from unstandardized data.
- **Large Data Economics**: Expertise in longitudinal survey analysis (PATH, NHIS) integrated with structural modeling.

### 4. Proposed Roadmap at IHPS
1. **Phase 1**: Pilot a BDT model using California-specific tobacco purchase data to simulate the impact of recent flavor restrictions on Low SES households.
2. **Phase 2**: Integrate social media sentiment analysis into transition probability matrices for emerging products (HTPs/Cannabis).
3. **Goal**: Establish a **“Regulatory Sandbox”** for policy evaluation that prioritizes health equity and independent oversight.

---
**Author**: Yichao (Cary) Jin  
**Positioning**: Behavioral Architect
