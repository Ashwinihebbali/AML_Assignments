# Applied Machine Learning - Assignment Series
This repository contains a collection of academic assignments focused on Symbolic Machine Learning, Concept Learning, and Ensemble Methodologies. The projects explore real-world applications in Cybersecurity and Astrobiology, highlighting the strengths and limitations of classical ML algorithms.

## 📂 Repository Structure

* **Cybersecurity Intrusion Detection (NIDS)**
    * `cybersecurity_intrusion_report.tex`: Comprehensive 8-page analysis of Decision Tree variants and Version Space constraints.
    * `decision_tree_variants.py`: Python implementation of 7 tree models (ID3, C4.5, CART, CHAID, MARS, Random Forest, GBDT).
* **Astrobiology: Exoplanet Habitability**
    * `limitations_version_spaces.tex`: Detailed report on five specific scenarios where Version Space algorithms (Find-S/Candidate Elimination) fail.
    * `precision_agriculture_vs.py`: Simulation of agricultural soil suitability classification.

## 🚀 Key Implementations

### 1. Multi-Model Decision Tree Analysis
We evaluate seven distinct decision tree architectures on a custom 15-instance Network Intrusion Detection dataset.
* **Information Theory Models:** ID3 and C4.5 focus on Entropy and Gain Ratio.
* **Statistical Models:** CHAID and CART prioritize Gini Impurity and Chi-Square interactions.
* **Ensemble Methods:** Random Forest and Gradient Boosted Trees (GBDT) are implemented to showcase resilience against adversarial label noise.

### 2. Version Space Failure Analysis
A deep dive into the **Candidate Elimination** algorithm, identifying five critical failure points:
1.  **Observational Uncertainty:** Contradictory labels in identical instances.
2.  **Disjunctive Concepts:** The inability of conjunctive hypotheses to represent "OR" logic.
3.  **Data Scarcity:** Absence of positive or negative instances (Zero-Day scenarios).
4.  **Continuous Domains:** Challenges with high-dimensional real-valued attributes.
5.  **Concept Drift:** Non-stationary data in live network environments.

##  Installation & Usage

### Prerequisites
* Python 3.8+
* Pandas
* Scikit-learn
* NumPy

### Running the Simulations
To execute the decision tree comparison:
```bash
python decision_tree_variants.py
```

To simulate a Version Space collapse:
```bash
python precision_agriculture_vs.py
```
