# Social Media Addiction Classification 🧠📱

## Problem Statement
Predict whether a student is addicted to social media based on
demographic, academic, and behavioral features.

## Dataset
- Source: Kaggle
- Features: Age, Gender, Academic Level, Daily Usage, Sleep Hours, etc.
- Target: Addicted_Score

## Approach
- Data preprocessing using `ColumnTransformer`
- Encoding:
  - One-Hot Encoding (categorical features)
- Scaling using Quantile Transformer
- Model:
  - Stacking Classifier
  - Base models: KNN, XGBoost
  - Meta model: SVM

## Results
- Achieved stable classification performance
- Stacking improved results compared to individual models

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost

## How to Run
```bash
pip install -r requirements.txt
