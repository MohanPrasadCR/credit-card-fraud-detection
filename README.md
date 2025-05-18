# 💳 Credit Card Fraud Detection using Machine Learning

## 🧠 Project Overview

This project addresses the critical problem of detecting fraudulent credit card transactions using machine learning techniques. With the rise of online banking, credit card fraud has become increasingly common, leading to major financial losses for banks and customers. The goal of this project is to build a reliable classification model that can identify fraudulent transactions with high recall while minimizing false negatives.

---

## 🎯 Objective

To build a machine learning model that accurately identifies fraudulent credit card transactions in a highly imbalanced dataset, helping financial institutions reduce fraudulent activity and potential monetary losses.

---

## 🛠️ Technologies & Methods

- **Language**: Python
- **Libraries**: Scikit-learn, XGBoost, Pandas, NumPy, Seaborn, Matplotlib, Imbalanced-learn
- **Models Used**:
  - Random Forest
  - XGBoost
- **Techniques**:
  - Exploratory Data Analysis (EDA)
  - Feature Selection
  - Data balancing using **ADASYN (Adaptive Synthetic Sampling)**
  - Model Evaluation using **Recall**, **Precision**, **F1-score**, and **AUC-ROC**
  - **Hyperparameter Tuning** using GridSearchCV and Cross-validation
  - **Cost-Benefit Analysis**

---

## 🔬 Root Cause Analysis

- Sensitive customer data compromised through ATM skimming, stolen cards, or hacked systems.
- Fraudulent transactions typically occur during non-peak hours (when users are inactive).
- Banks incur losses as they reimburse fraudulent transactions and lose customer trust.

---

## 📊 Workflow

1. **Data Import & Cleaning**
2. **EDA** to understand fraud patterns by time, user demographics, and transaction type
3. **Class Imbalance Handling** using ADASYN
4. **Model Building** with Random Forest & XGBoost
5. **Evaluation** using confusion matrix, AUC, F1-score, Recall, Precision
6. **Threshold Optimization** to reduce false negatives
7. **Cost-Benefit Analysis** to quantify savings from model deployment

---

## 📈 Model Performance

- **Recall-focused evaluation** to prioritize identifying actual frauds
- **AUC-ROC** used for optimal threshold selection
- Final model shows strong performance in reducing undetected fraudulent transactions

---

## 💰 Cost Benefit Analysis

| Metric                                  | Value        |
|----------------------------------------|--------------|
| Avg. monthly fraud loss (before model) | $213,060     |
| Monthly fraud loss (after model)       | $107,632     |
| **Estimated monthly savings**          | **$105,428** |

---


---

## ✅ Key Takeaways

- ADASYN significantly improved fraud detection by balancing class distribution
- XGBoost and Random Forest gave robust performance with high recall
- Business-focused evaluation (cost savings) shows real-world impact

---




