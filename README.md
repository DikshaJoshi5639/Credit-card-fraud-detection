Credit Card Fraud Detection
📌 Project Overview
This project aims to build a machine learning model to detect fraudulent credit card transactions. The dataset contains anonymized features obtained through PCA transformation, along with the transaction time, amount, and a binary class indicating whether a transaction is fraudulent.

The data represents transactions made by European cardholders in September 2013, capturing two days' worth of activity. It is highly imbalanced, with fraudulent transactions constituting only 0.172% of the dataset.

📊 Dataset Description
Total Transactions: 284,807

Fraudulent Transactions: 492

Non-Fraudulent Transactions: 284,315

Imbalance Ratio: ~0.172%

Features:
Time: Seconds elapsed between the transaction and the first transaction in the dataset

Amount: Transaction amount

V1 to V28: Principal Components obtained via PCA

Class: Target variable (1 = Fraud, 0 = Not Fraud)

ℹ️ Due to confidentiality, original features and more background details are not provided.

🎯 Objective
Build a classification model to accurately detect fraudulent transactions.

Address the class imbalance problem.

Evaluate using Area Under the Precision-Recall Curve (AUPRC) rather than traditional accuracy metrics.

📈 Evaluation Metrics
Because of the extreme class imbalance, we use:

AUPRC (Area Under Precision-Recall Curve)

F1-Score

Precision and Recall

Confusion Matrix (only for reference, not primary metric)

⚙️ Technologies Used
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook

🧠 Approaches to Consider
Resampling Techniques: SMOTE, Undersampling

Anomaly Detection Models

Cost-sensitive learning

Ensemble methods (Random Forest, XGBoost)
