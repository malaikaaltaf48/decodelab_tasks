# Project 2 — Fraud Detection Pipeline

**Dataset:** creditcard.csv (284,807 transactions)

## Overview
This project builds an end-to-end fraud detection pipeline using classification models on a highly imbalanced dataset.

## Key Steps
- Stratified train/test split
- Two `imblearn.pipeline.Pipeline` objects (Logistic Regression and Random Forest)
- SMOTE applied to handle class imbalance
- Hyperparameter tuning via GridSearchCV with StratifiedKFold
- Evaluation using Precision, Recall, F1-score, and ROC-AUC (accuracy was intentionally excluded due to class imbalance)

## Files
- Notebook (`.ipynb`) to be uploaded in this folder
- Dataset not included due to file size; loaded via external source in the notebook
