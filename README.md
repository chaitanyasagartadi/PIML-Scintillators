# Physics-Informed Machine Learning for Scintillator Light Yield Prediction

This repository provides the supporting information, datasets, and codebase for the manuscript: **"Predicting Scintillator Light Yield Using Physics-Informed Machine Learning."**

## 📖 Overview

Scintillators are critical materials in radiation detection. Predicting their light yield (LY) involves complex interactions between material properties and physical constraints. This project implements a **Physics-Informed Machine Learning (PIML)** approach using Gradient Boosting to predict LY with high accuracy while maintaining physical consistency.

### Key Features
- **Reproducible Workflow**: Full end-to-end pipeline from raw data to final analysis.
- **Physics-Informed Features**: Inclusion of density, electronegativity mismatch, size mismatch, and bandgap_doping_ratio.
- **Explainable AI**: Integrated SHAP analysis for feature importance and physical interpretability.
- **Visualization**: Automated generation of parity plots and error distributions.

---

## 📂 Repository Structure

```text
PIML-Scintillators/
├── data/
│   ├── raw/                # Original datasets as collected
│   └── processed/          # Cleaned and feature-engineered datasets
├── notebooks/
│   └── Scintillator_f   # Main notebook for ML training and evaluation
├── requirements.txt        # Python dependency list
├── LICENSE                 # MIT License
└── README.md               # Project documentation
```

