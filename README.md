# credit-risk-classification

This project uses a machine learning model — Logistic Regression — to predict whether a loan is high-risk or healthy based on borrower financial data.

The goal is to help financial institutions identify potentially risky loans before approval.

The dataset lending_data.csv contains the following features:

* Annual income
* Debt-to-income ratio
* Loan amount
...and other financial indicators.
The target variable is:

* loan_status — 0 for healthy loans, 1 for high-risk loans

## Machine Learning Workflow
1) Data loading and exploration (pandas)
2) Feature and label separation
3) Splitting into training/testing sets
4) Model training with Logistic Regression (sklearn)
Evaluation using:
- Confusion matrix
- Classification report (accuracy, precision, recall, F1)
