# 🕵️‍♀️ Fraud Detection with SMOTE and XGBoost

This project detects fraudulent transactions from an imbalanced credit card dataset using SMOTE for resampling and XGBoost for classification.

---

## 📦 Dataset

- Credit Card Fraud Detection  
- Features are anonymized (V1–V28) + `Amount`, `Time`, and target `Class`
- 0 = Non-Fraud, 1 = Fraud  
- [Source](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

---

## ⚙️ Requirements

```bash
pip install pandas scikit-learn imbalanced-learn xgboost
