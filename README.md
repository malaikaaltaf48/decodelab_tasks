**DecodeLabs Data Science Industrial Training — Batch 2026**

 Malaika Altaf
Program: DecodeLabs Data Science Industrial Training (Batch 2026)
Institution: BS Software Engineering, University of Gujrat

**About This Repository**

This repository contains all the tasks completed as part of the DecodeLabs Data Science Industrial Training Program. Each project demonstrates a different stage of the data science workflow — from exploratory data analysis and feature engineering, to building classification pipelines for imbalanced data, to unsupervised learning for customer segmentation. All notebooks are built to be fully reproducible, with datasets loaded via public URLs wherever possible so they can be run by anyone without local file dependencies.


## Projects

# 1. Advanced EDA & Feature Engineering

Folder: project1_eda
Dataset: Kaggle House Prices

This project focuses on preparing a real-world housing dataset for modeling through structured exploratory data analysis and feature engineering. Key techniques include domain-aware missing value imputation, IQR-based Winsorization to handle outliers, creation of five new engineered features, One-Hot Encoding of categorical variables, and multicollinearity removal using a 0.80 correlation threshold.

 # 2. Fraud Detection Pipeline

Folder: project2_fraud_detection
Dataset: Credit Card Transactions (284,807 records)

This project builds an end-to-end machine learning pipeline to detect fraudulent transactions in a highly imbalanced dataset. It uses stratified train/test splitting, two complete imblearn pipelines (Logistic Regression and Random Forest), SMOTE for class balancing, and GridSearchCV with StratifiedKFold for hyperparameter tuning. Model performance is evaluated using Precision, Recall, F1-score, and ROC-AUC, since accuracy alone is not a reliable metric for imbalanced classification problems.

# 3. Customer Segmentation
Folder: project3_customer_segmentation
Dataset: Mall Customers Dataset

This project applies unsupervised learning to segment mall customers into meaningful groups based on spending behavior and demographics. The workflow includes feature scaling, dimensionality reduction using PCA, optimal cluster selection through the Elbow Method and KneeLocator, cluster validation via Silhouette Score, and translation of cluster centroids into actionable business personas.


## Tools & Technologies

Python, Pandas, NumPy, Scikit-learn, imbalanced-learn (imblearn), Matplotlib, Seaborn, Google Colab

 Note

This repository was created as part of the DecodeLabs Data Science Industrial Training Program (Batch 2026) submission requirements.
