# Loan Default Risk Prediction

A machine learning project focused on predicting whether a borrower would default on a loan using borrower, credit, and loan characteristics.

## Project Overview

The project compared multiple classification approaches for identifying loan defaults, including:

- Regularized Logistic Regression
- Decision Trees
- XGBoost
- Neural Networks

Because loan defaults were the minority class, model evaluation focused on **recall, precision, F1 score, balanced accuracy, detection rate, and AUC** rather than accuracy alone.

## Results

The final model selected for prediction was **XGBoost**, using class weighting, cross-validation, and probability threshold optimization. 

The selected XGBoost model achieved an **F1 score of approximately 0.57** and correctly identified roughly two-thirds of loan defaults. 

Neural network models were also competitive, with the strongest reaching an **AUC of 0.825** and **recall of 0.665**.

## Tools

**R • XGBoost • caret • Keras • tidyverse**
