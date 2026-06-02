# Credit-Card-Fraud-Detection
A machine learning pipeline using Random Forest to classify fraudulent transactions with high precision, leveraging PCA-transformed financial features.

# Project Overview

A visual pipeline showing the 5 stages from data ingestion through evaluation, with library badges and project description.

# Dataset Summary

Key stats (568,630 records, 30 features, balanced 50/50 classes), plus notes on data quality (zero nulls, zero duplicates) and the reasoning behind dropping the id column.

# Exploratory Data Analysis

Three tabbed views covering feature importance (V17, V14, V12, V10 are top discriminators), the correlation matrix interpretation (PCA features are orthogonal by design), and class distribution analysis with a note on how the balanced 2023 dataset differs from real-world fraud distributions.

# Model Training

Decision Tree baseline vs. Random Forest primary model, with a highlighted note that max_depth=4 may be limiting performance and should be tuned.

# Confusion Matrix

A color-coded matrix with full interpretation of all four quadrants (TP, TN, FP, FN) and their business costs in fraud detection, plus derived metrics (accuracy, precision, recall, F1).

# ROC & AUC

An illustrated ROC curve with explanation of what the curve shape means, why AUC beats accuracy for threshold-sensitive tasks, and how to use it to tune the decision boundary.
Recommendations added that you didn't mention: hyperparameter tuning with GridSearchCV, testing on imbalanced data with SMOTE, adding a Precision-Recall curve, and SHAP explainability for regulatory compliance.
