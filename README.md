# 💳 Credit Card Fraud Detection

## 📌 Project Overview

This project aims to develop a **machine learning model** capable of detecting **fraudulent credit card transactions**. 

The dataset contains transactions made by European cardholders over **two days in September 2013**, comprising **284,807 transactions**, of which **492 are fraudulent** (only **0.172%**).

---

## 📊 Dataset Description

| Feature     | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| `Time`      | Seconds elapsed between the current and first transaction                  |
| `Amount`    | Transaction amount                                                          |
| `V1`–`V28`  | Principal components obtained via **PCA** transformation                    |
| `Class`     | **Target variable** – `1` for fraud, `0` for non-fraud                      |

> ⚠️ The dataset is **highly imbalanced**. Traditional accuracy metrics are misleading.

---

## 🎯 Objective

- Detect fraudulent transactions with **high precision and recall**
- **Handle class imbalance** using resampling or cost-sensitive techniques
- **Evaluate using AUPRC** (Area Under the Precision-Recall Curve)

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**

---

## 🧪 Evaluation Metrics

Given the imbalance, we use:
- ✅ **AUPRC**
- ✅ **F1-Score**
- ✅ **Precision & Recall**
- ❌ **Accuracy** (not suitable)

---

