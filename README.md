# 💳 Santander Customer Transaction Prediction (Kaggle Competition)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn-orange)
![Kaggle](https://img.shields.io/badge/Kaggle-Competition-20BEFF)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🏆 Kaggle Competition

This project is based on the Kaggle competition:

👉 **Santander Customer Transaction Prediction**  
🔗 https://www.kaggle.com/competitions/santander-customer-transaction-prediction

---

## 📌 Overview

The goal of this competition is to predict whether a customer will make a specific transaction based on **anonymized numerical features**.

Unlike traditional datasets, feature meanings are hidden — making this a **pure machine learning problem focused on pattern recognition**.

---

## 🎯 Objective

- Predict the probability of a customer making a transaction  
- Build a high-performing classification model  
- Optimize performance based on **ROC-AUC score**

---

## 📊 Dataset Information

- 200+ anonymized features (`var_0` to `var_199`)
- Binary target variable (`target`)
- No missing values
- Highly balanced dataset

## ⚙️ Workflow

![Workflow](outputs/workflow.png)

---

## 🔍 Approach

### 📌 Data Processing
- Removed irrelevant identifiers
- Standardized features
- Created row-level statistical features:
  - Mean, Std, Median
  - Min, Max, Sum
  - Positive/Negative counts

---

### 📊 Feature Engineering Insight

Instead of relying on domain knowledge (not available), we extracted **statistical signals across rows**, which significantly improved model learning.

---

### 🤖 Models Used

- Logistic Regression  
- Random Forest  
- XGBoost  

---

## 📈 Results

![Model Performance](outputs/model_performance.png)

| Model               | ROC-AUC |
|--------------------|--------|
| Logistic Regression| 0.84   |
| Random Forest      | 0.86   |

---

## 📉 ROC Curve

![ROC Curve](outputs/roc_curve.png)

---

## 🔬 Feature Importance

![Feature Importance](outputs/feature_importance.png)

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib  
- Seaborn  

---

## 📂 Project Structure
Santander-Customer-Transaction-Prediction/

│

├── data/

├── notebooks/

├── src/

├── outputs/

│ └── visuals/

│ ├── workflow.png

│ ├── model_performance.png

│ ├── roc_curve.png

│ └── feature_importance.png

├── README.md

└── requirements.txt

---

## 💡 What Makes This Project Strong?

👉 Works on **fully anonymized data**  
👉 Focuses on **feature engineering over domain knowledge**  
👉 Demonstrates **real-world ML problem-solving**  

---

## 🚀 Future Improvements

- Hyperparameter tuning (GridSearchCV)  
- SHAP explainability  
- Ensemble stacking  
- Neural networks  

---

## 🤝 Let's Connect

If you found this interesting, feel free to connect or contribute!

---

