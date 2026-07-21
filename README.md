# 🚌 Bus Trajectory Analysis Using Differential Privacy

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Differential Privacy](https://img.shields.io/badge/Differential%20Privacy-Research-blue)
![Transit Analytics](https://img.shields.io/badge/Domain-Transit%20Analytics-success)
![Real-World Project](https://img.shields.io/badge/Real--World-Project-brightgreen)
![Industry Collaboration](https://img.shields.io/badge/Industry-Collaboration-orange)
![University of Victoria](https://img.shields.io/badge/University-Victoria-red)

### A Case Study on BC Transit
**M.Sc. Thesis | University of Victoria**

This repository documents my M.Sc. research project completed at the University of Victoria in collaboration with BC Transit.

The research explored how meaningful transit analytics can be published while protecting passenger privacy. Using real operational smart card tap-in data, I designed a realistic trajectory reconstruction approach, evaluated state-of-the-art Differential Privacy algorithms, and proposed enhancements to improve both privacy preservation and analytical utility.

> **Confidentiality Notice:** Due to data confidentiality agreements, the original datasets and implementation are not publicly available. This repository summarizes the research methodology, technical contributions, and key findings.

---

## 🎯 Business Problem

Public transit agencies collect large volumes of smart card data that can provide valuable insights into passenger travel behavior, service planning, and operational decision-making.

However, publishing this data introduces significant privacy risks, making it difficult to balance analytical value with passenger confidentiality.

The goal of this research was to develop a privacy-preserving data publishing framework that enables meaningful transit analytics while protecting individual rider privacy.

---

## 🎯 Research Objectives

- Reconstruct realistic passenger trajectories from fragmented smart card tap-in records.
- Evaluate state-of-the-art Differential Privacy methods on real operational transit data.
- Improve existing privacy-preserving algorithms while maintaining analytical utility.
- Assess the effectiveness of the proposed methods using complex analytical queries and sequential pattern mining.

---

## ⚙️ Technical Contributions

### 1. Trajectory Reconstruction

Designed a role-based trajectory reconstruction approach to transform fragmented smart card tap-in records into realistic passenger travel trajectories by incorporating travel behavior, temporal regularity, and rider profiles.

### 2. Differential Privacy Evaluation

Evaluated two state-of-the-art privacy-preserving data publishing methods—Noisy Prefix Tree (NPT) and Privacy-Preserving Data Publishing (PPDP)—using real operational BC Transit data.

### 3. Algorithm Enhancements

Proposed and evaluated two improvements to existing Differential Privacy methods:

- Developed a weighted post-processing strategy to improve consistency and preserve local trajectory structures in the NPT algorithm.
- Designed a spatio-temporal pruning strategy that improved the efficiency of the PPDP algorithm while maintaining analytical utility.

### 4. Experimental Evaluation

Compared the original and enhanced methods using real-world transit data through analytical queries and frequent sequential pattern mining to evaluate both privacy protection and data utility.

---

## 🔬 Methodology

The research followed an end-to-end analytical workflow, combining data engineering, privacy-preserving data publishing, and analytical evaluation.

The methodology consisted of four main stages:

1. **Data Preparation**
   - Processed real operational smart card tap-in records provided by BC Transit.
   - Cleaned and transformed raw data for trajectory reconstruction.

2. **Trajectory Reconstruction**
   - Developed a role-based behavioral model to reconstruct realistic passenger trajectories from fragmented smart card records.
   - Incorporated temporal patterns, travel behavior, and rider profiles to generate representative travel sequences.

3. **Privacy-Preserving Data Publishing**
   - Evaluated the Noisy Prefix Tree (NPT) and Privacy-Preserving Data Publishing (PPDP) algorithms.
   - Proposed enhancements to improve analytical utility while preserving Differential Privacy guarantees.

4. **Performance Evaluation**
   - Compared the original and enhanced algorithms using analytical queries and frequent sequential pattern mining on real operational transit data.
  
---

## 📊 Results & Evaluation

The proposed improvements demonstrated measurable benefits over the original Differential Privacy methods.

Key outcomes included:

- Improved consistency of published trajectory data.
- Better preservation of local travel patterns.
- Increased computational efficiency through spatio-temporal pruning.
- Stronger balance between passenger privacy and analytical utility.
- More reliable support for downstream analytical queries and sequential pattern mining.

---

## 🛠 Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Privacy Techniques | Differential Privacy |
| Algorithms | Noisy Prefix Tree (NPT), PPDP |
| Data | Smart Card Transit Data |
| Research | Trajectory Reconstruction, Sequential Pattern Mining |


---

## 🌟 Project Impact

This research demonstrates that valuable transit analytics can be generated without compromising passenger privacy.

Beyond the technical contributions, the project required close collaboration with BC Transit stakeholders to align research objectives with operational needs, navigate privacy requirements, and build trust around the responsible use of sensitive transportation data.

The proposed framework supports safer data sharing practices while enabling transit agencies to make more informed, data-driven decisions.


---

## 🙏 Acknowledgements

I would like to sincerely thank:

- **BC Transit Enterprise Data & Analytics Team** for their collaboration, trust, and support throughout this research.
- **Andrew Miller** for his guidance and valuable industry insights.
- **Dr. Yun Lu** for her supervision, mentorship, and continuous support during my M.Sc. research at the University of Victoria.
