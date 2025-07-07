# 🎓 Machine Learning-Based Student Loan Default Prediction

This project presents a machine learning-based system to predict student loan defaulters using real-world data and comparative model evaluation. It applies both traditional (Gaussian Naive Bayes) and advanced (CatBoost Classifier) algorithms to classify applicants as defaulters or non-defaulters based on financial, academic, and demographic features.

---

## 📊 Problem Statement

Student loan defaults are a major concern for financial institutions. Traditional credit scoring systems fail to capture complex patterns in borrower behavior. This project aims to:

- Predict loan default risk using supervised ML techniques.
- Enhance early warning systems for financial institutions.
- Compare baseline models with modern algorithms.

---

## 🚀 Project Objectives

- Preprocess and clean real-world student loan data.
- Perform Exploratory Data Analysis (EDA).
- Train and evaluate:
  - Gaussian Naive Bayes (baseline)
  - CatBoost Classifier (proposed)
- Visualize model performance using confusion matrices and feature importances.

---

## 🛠️ Tech Stack

- **Language**: Python 3.7.6
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`
  - `CatBoost`
  - `StandardScaler`
  - `SMOTE` (for imbalance correction if needed)

---

## 📁 Dataset Features

| Feature              | Description                            |
|----------------------|----------------------------------------|
| `credit_score`       | Numerical credit rating                |
| `income_monthly`     | Monthly income                         |
| `debt_to_income`     | Debt-to-income ratio                   |
| `loan_amount`        | Amount of loan requested               |
| `payment_history`    | Past repayment behavior                |
| `employment_years`   | Number of years employed               |
| `previous_defaults`  | Number of past loan defaults           |
| `default_risk`       | Target: 1 (defaulter), 0 (non-defaulter) |

---

## 📈 EDA Highlights

- Correlation analysis via heatmaps.
---

## 🧠 Models Trained

### 1. Gaussian Naive Bayes (GNB)
- Simple probabilistic model.
- Assumes feature independence.
- Accuracy: ~89%

### 2. CatBoost Classifier (Proposed)
- Handles categorical features natively.
- Reduces overfitting via Ordered Boosting.
- Accuracy: **93.5%**
- Feature importance included.

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **Confusion Matrix** (with seaborn heatmaps)

---
