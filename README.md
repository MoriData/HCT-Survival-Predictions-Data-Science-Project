# Survival Predictions - Simple CatBoost Model

![Kaggle Badge](https://img.shields.io/badge/Kaggle-Equity%20Post--HCT%20Survival%20Predictions-blue)

This repository contains a simple implementation of a **CatBoost model** for the **[Equity Post-HCT Survival Predictions](https://www.kaggle.com/competitions/equity-post-HCT-survival-predictions/overview)** Kaggle competition. The goal of the project is to predict survival rates post-hematopoietic cell transplantation (HCT) using patient data while respecting the nuances of clinical datasets.

---

## 🏆 Project Highlights
- **Competition**: [Equity Post-HCT Survival Predictions](https://www.kaggle.com/competitions/equity-post-HCT-survival-predictions/overview)
- **Model Used**: [CatBoost](https://catboost.ai/)
- **Score**: 0.681 (simple implementation)
- **Key Steps**:
  - Data preprocessing and feature engineering.
  - Training a CatBoost model with minimal hyperparameter tuning.
  - Generating predictions for the test dataset.

---

## 📁 Project Structure
```plaintext
.
├── data/
│   ├── train.csv               # Training dataset
│   ├── test.csv                # Test dataset
│   └── sample_submission.csv   # Sample submission file
├── notebooks/
│   └── survival_predictions.ipynb   # Jupyter Notebook for data processing and modeling
├── outputs/
│   └── submission.csv          # Model predictions
├── README.md                   # Project description and instructions
└── requirements.txt            # Python dependencies
