## Credit_Card_Fraud_Detection
Credit Card Fraud Detection is a classic and critical application of machine learning and data analytics used in the banking and financial industry to identify and prevent unauthorized or fraudulent transactions. Here’s an overview, suitable for a project, report, or presentation.
## Overview
Credit card fraud occurs when someone uses your card or card details to make unauthorized purchases or withdrawals. Since fraudulent transactions are rare compared to legitimate ones, detecting them poses unique challenges.
## Goals of Fraud Detection
# Identify fraudulent transactions as early as possible.

# Minimize false positives (flagging legitimate transactions as fraud).

# Minimize false negatives (missing actual fraud).

Improve real-time detection.

## Steps in Fraud Detection Using Machine Learning
1. Data Collection
Transaction history (amount, time, location)

Customer data (account age, past transactions)

Device information

Labels: Fraudulent or not

2. Data Preprocessing
Handling class imbalance (fraud cases are rare)

Feature engineering (e.g., time since last transaction)

Normalization/Scaling

Encoding categorical variables

3. Exploratory Data Analysis (EDA)
Analyze patterns in fraud vs. non-fraud

Visualizations (e.g., histograms, time series)

Correlation heatmaps

4. Model Building
Common models include:

Logistic Regression

Decision Trees / Random Forests

Gradient Boosting (XGBoost, LightGBM)

Neural Networks

Isolation Forest / One-Class SVM (for anomaly detection)

5. Evaluation Metrics
Accuracy is misleading due to imbalance

Prefer:

Precision

Recall

F1 Score

ROC-AUC

6. Dealing with Class Imbalance
Oversampling (SMOTE)

Undersampling

Cost-sensitive learning

