# AI-Powered Alternate Credit Scoring System

## Overview
Built an XGBoost-based credit scoring model using alternative data signals 
to assess creditworthiness of borrowers who lack traditional credit history.

## Problem Statement
Traditional credit scoring excludes millions of borrowers. This model uses 
alternative data including utility payments, mobile usage, and social trust 
scores to build a fairer and more inclusive credit assessment system.

## Key Features
- Dataset: 10,000 synthetic borrower records
- Model: XGBoost with SMOTE for class imbalance handling
- AUC-ROC: 0.76
- SHAP explainability for model transparency
- Fairness audit using Disparate Impact Ratio

## Tools Used
- Python, XGBoost, Scikit-learn
- SHAP for explainability
- Imbalanced-learn for SMOTE
- Matplotlib, Seaborn for visualization

## Results
- AUC-ROC: 0.76
- Model passes Four-Fifths fairness rule
- Loan decision system: Approve, Manual Review, Reject
