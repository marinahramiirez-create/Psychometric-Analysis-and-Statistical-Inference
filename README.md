# Psychometric-Analysis-and-Statistical-Inference AAE1
Structural validity analysis using EFA (N=245) and experimental study of cognitive processes using repeated measures ANOVA

## Methodology & Phases

# Psychometric Analysis and Statistical Inference (AAE1)

![Status](https://img.shields.io/badge/Status-Completed-success)
![Field](https://img.shields.io/badge/Field-Psychometrics-blue)
![Analysis](https://img.shields.io/badge/Analysis-EFA%20%7C%20ANOVA-orange)

## Project Overview
This repository contains a comprehensive psychometric workflow for instrument validation. The study ranges from content validity assessment via expert judgment to the exploration of internal structure using multivariate statistical techniques.

The analysis is based on a sample of **N=245** participants to study cognitive processes and scale reliability.

## Methodology & Phases

### 1. Content Validity (Aiken's V)
Quantification of item relevance and representativeness based on expert judge consensus.
* **File:** `DATOS AIKEN AAE1.csv`
* **Objective:** To calculate the **Aiken's V** coefficient and filter items that do not meet the minimum validity threshold (e.g., V > 0.70).

### 2. Technical Quality & Pilot Testing (Clarity)
Preliminary assessment of item comprehension to ensure the target population correctly interprets the scale.
* **File:** `DATOS CLARIDAD AAE1.csv`
* **Metrics:** Frequency analysis of item clarity and readability scores.

### 3. Structural Validity (Exploratory Factor Analysis - EFA)
Identification of the underlying latent variables (dimensions) of the instrument.
* **File:** `DATOS AFE AAE1.csv`
* **Methodology:** - Correlation matrix assessment.
    - Sampling adequacy tests (**KMO** and **Bartlett's Test of Sphericity**).
    - Factor extraction and rotation (e.g., Promax/Varimax) for factor loading interpretation.

### 4. Statistical Inference (Repeated Measures ANOVA)
Experimental study of cognitive processes by comparing means across different conditions or time points.

## Repository Structure
| File | Description |
| :--- | :--- |
| `DATOS AFE AAE1.csv` | Raw data for factor structure analysis. |
| `DATOS AIKEN AAE1.csv` | Validation matrix from expert judges. |
| `DATOS CLARIDAD AAE1.csv` | Participant reports on item legibility and clarity. |

##  Technical Requirements
To replicate these analyses, the following tools are recommended:
* **R / RStudio** (Suggested libraries: `psych`, `GPArotation`, `lavaan`)
* **Python** (Suggested libraries: `factor_analyzer`, `pandas`, `statsmodels`)
* **JASP / SPSS**

---
**Contributor:** [Your Name / GitHub Username]  
**Institution:** [Your University/Organization]

