# Early Dementia-Related Classification Using Machine Learning Models
A Comparative Analysis of Feature Accessibility, Model Complexity, and Ethical Trade-Offs

MSc Information Studies (Data Science) — University of Amsterdam, 2026
Author: Merle van Hellemondt

## Overview
This study compares Logistic Regression, Random Forest, and XGBoost trained on three feature sets of increasing clinical cost for dementia-related classification, evaluating predictive performance, interpretability, and fairness. Models are trained on OASIS-1 and externally validated on OASIS-2.

## Repository Structure
Thesis-DS/
├── notebooks/
│   └── Pipeline.ipynb    # Full analysis pipeline (run top to bottom)
├── data/                 # Not included — see Data section below
└── results/              # Model outputs, CSVs, and figures

## Data
Not included due to access restrictions. Download from https://www.oasis-brains.org:
- OASIS-1 (cross-sectional) → save as data/OASIS1.csv
- OASIS-2 (longitudinal) → save as data/OASIS2.csv

## Requirements
Python 3.9+

pip install pandas numpy scikit-learn xgboost shap matplotlib

## How to Run
Open notebooks/Pipeline.ipynb and run all cells top to bottom. The notebook covers data preprocessing, feature engineering, hyperparameter tuning, model evaluation, SHAP analysis, fairness analysis, and external validation on OASIS-2.
