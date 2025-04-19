# Module 20 Report Template

## Overview of the Analysis

The goal of this analysis was to predict whether a loan is high-risk (1) or healthy (0) using financial data from borrowers.
 
The dataset included information such as annual income, debt-to-income ratio, and loan amount. The target variable was loan_status.

To understand the balance of the data, we used value_counts():
----print(y.value_counts())----

This revealed that the dataset contains more healthy loans than high-risk ones, showing some class imbalance.

The machine learning process included:

* Loading and exploring the data
* Separating features (X) and target (y)
* Splitting into training and testing sets
* Training a Logistic Regression model
* Making predictions and evaluating performance

## Results

* Machine Learning Model 1: Logistic Regression
   * Accuracy: 0.99
   * Precision
      * Class 0 (healthy loan): 1.00
      * Class 1 (high-risk loan): 0.84
   * Recall
      * Class 0: 0.99
      * Class 1: 0.94
   * F1-Score
      * Class 0: 1.00
      * Class 1: 0.89

## Summary

The logistic regression model performs very well overall, achieving 99% accuracy. It identifies healthy loans with perfect precision and recall, and also performs strongly on high-risk loans, with a recall of 94% and an F1-score of 0.89.

Since predicting high-risk loans is important, the high recall for class 1 is encouraging. Based on these results, logistic regression is a reliable model for this task and can be recommended for use.
