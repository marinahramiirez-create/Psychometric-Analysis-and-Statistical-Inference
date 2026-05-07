
# Psychometric Analysis and Statistical Inference (AAE1)

![Status](https://img.shields.io/badge/Status-Completed-success)
![Field](https://img.shields.io/badge/Field-Psychometrics-blue)
![Analysis](https://img.shields.io/badge/Analysis-EFA%20%7C%20ANOVA-orange)

## Project Overview
This repository contains a comprehensive psychometric workflow for instrument validation. The study ranges from content validity assessment via expert judgment to the exploration of internal structure using multivariate statistical techniques.

The analysis is based on a sample of **N=245** participants to study cognitive processes and scale reliability.

## Methodology & Phases

### 1. Content Validity (Aiken's V)
Quantification of item relevance and representativeness based on expert judge consensus (10 judges).
* **File:** `DATOS AIKEN AAE1.csv`
* **Objective:** To calculate the **Aiken's V** coefficient. All 12 items met the threshold ($V > 0.70$).

### 2. Technical Quality & Pilot Testing (Clarity)
Preliminary assessment of item comprehension to ensure the target population correctly interprets the scale.
* **File:** `DATOS CLARIDAD AAE1.csv`

### 3. Structural Validity (Exploratory Factor Analysis - EFA)
Identification of the underlying latent variables using **Principal Axis Factoring** with **Promax rotation**.
* **File:** `DATOS AFE AAE1.csv`

## Repository Structure
| File | Description |
| :--- | :--- |
| `DATOS AFE AAE1.csv` | Raw data for factor structure analysis. |
| `DATOS AIKEN AAE1.csv` | Validation matrix from expert judges. |
| `DATOS CLARIDAD AAE1.csv` | Participant reports on item legibility and clarity. |

---

## Key Results & Conclusions

### 1. Psychometric Findings
* **Aiken's V:** All items were validated with scores above 0.70. Qualitative adjustments were made to items 3, 5, and 12 to improve semantic flow.
* **EFA Suitability:** The **KMO index was .847**, and Bartlett's Test of Sphericity was significant ($\chi^2 = 1358.55, p < .001$).
* **Factor Structure:** A **2-factor solution** was identified (Clarity and Coherence), explaining **53.8% of the cumulative variance**.
* **Reliability:** The instrument showed high internal consistency (**Cronbach's Alpha = .88**).

### 2. Statistical Inference (ANOVA)
A Repeated Measures ANOVA revealed a **significant main effect** of cognitive load on performance:
* $F(2, 488) = 15.34, p < .001, \eta_p^2 = .06$.
* Post-hoc tests confirmed significant performance drops as cognitive interference increased.

## Final Conclusions
1. **Instrument Robustness:** The test is a valid and reliable tool for assessing cognitive clarity and coherence.
2. **Experimental Impact:** Theoretical assumptions regarding cognitive load were confirmed by the experimental data.
3. **Reproducibility:** The workflow follows APA standards for reporting psychometric properties.


