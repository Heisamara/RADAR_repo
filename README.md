# RADAR: Risk-Aware Ambiguity Detection and Decision Modeling for Regulatory Requirements

RADAR (Risk-Aware Decision Framework for Ambiguity in Requirements) is a hybrid ambiguity detection and decision-support framework designed for safety-critical and regulatory requirements engineering environments.

The framework combines:
- Rule-based linguistic ambiguity indicators
- Transformer-based semantic representations
- Probabilistic fusion and calibration
- Bayesian risk-sensitive threshold adaptation
- Lightweight regulatory semantic grounding
- LLM-assisted recommendation support

RADAR treats ambiguity analysis as a **risk-sensitive decision problem** rather than a conventional fixed-threshold classification task.

---

## Overview

Ambiguity in natural-language requirements remains a major challenge in safety-critical systems, where unclear specifications may propagate into:
- Verification failures
- Certification delays
- Redesign effort
- Compliance violations
- Downstream safety risks

Traditional ambiguity detection systems primarily optimize predictive performance under fixed thresholds and symmetric assumptions. RADAR instead introduces adaptive threshold behavior grounded in Bayesian decision theory, enabling configurable operating modes aligned with regulatory and operational risk priorities.

---

# Repository Structure

```text
RADAR_repo/
│
├── Con_Paper/
│   ├── FINAL RADAR.drawio.png
│   ├── FNR rate across Models.png
│   └── Adaptive Threshold Under Asymetric risk.png
│
├── data/
│   ├── phase3_features/
│   ├── phase4_outputs/
│   ├── phase5_outputs/
│   ├── strict_splits/
│   └── radar_results.csv
│
├── Notebook/
│   ├── Phase 2/
│   ├── Phase 3/
│   ├── Phase 4/
│   └── Phase 5/
│       ├── Ablation_code.ipynb
│       └── Evaluation.ipynb
│
├── Results/
│
└── src/
    └── regulqa_ambig_pool.csv
```

---

## Dataset

The complete dataset repository is available separately:

https://github.com/Heisamara/Ambiguity-Detection-Framework-RegulQA-Comprehensive-Dataset

The dataset includes:
- Regulatory requirements
- Safety-critical specifications
- PURE dataset integration
- NASA TRICK SRS samples
- Synthetic ambiguity augmentation
- Multi-domain ambiguity annotations

---

## Included Research Artifacts

This repository contains:
- Experimental notebooks
- Evaluation scripts
- Ablation experiments
- Calibration analysis
- Adaptive threshold evaluation
- Research figures and outputs

---

## Technologies

Experiments were implemented using:
- Python
- Scikit-learn
- Sentence-Transformers
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Running the Project

## Clone Repository

```bash
git clone https://github.com/Heisamara/RADAR_repo.git
cd RADAR_repo
```

## Run Notebooks

Execute notebooks sequentially:
1. Phase 2
2. Phase 3
3. Phase 4
4. Phase 5

---

# Research Motivation

RADAR investigates the following problem:

> How should ambiguity detection behave when the cost of missed ambiguities substantially exceeds the cost of additional review effort?

The framework therefore shifts ambiguity analysis:
- from static classification
- toward adaptive risk-aware decision support.

---

# Data Availability

Implementation artifacts, notebooks, evaluation resources, and experimental outputs are available in this repository. The associated dataset repository is publicly available at:

https://github.com/Heisamara/Ambiguity-Detection-Framework-RegulQA-Comprehensive-Dataset

Some third-party regulatory documents remain subject to external licensing restrictions.

---

# Authors

## Amarachi Nwosu
Department of Electrical, Computer and Software Engineering  
Ontario Tech University  
Oshawa, Canada  

## Sanaa Alwidian
Department of Electrical, Computer and Software Engineering  
Ontario Tech University  
Oshawa, Canada  

---

# License

This repository is provided for academic and research purposes.
