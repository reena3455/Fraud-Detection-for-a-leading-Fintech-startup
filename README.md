# Fraud-Detection-for-a-leading-Fintech-startup

## Overview

This project detects fraudulent transactions using machine learning on an imbalanced dataset. It applies advanced techniques like SMOTE, threshold tuning, and PR-AUC evaluation for better fraud detection.

## Objectives
- Detect fraudulent transactions
- Handle class imbalance effectively
- Compare multiple classification models
- Optimize decision threshold

## Tech Stack

Python, Pandas, NumPy, Scikit-learn, XGBoost, Imbalanced-learn

## Models Used
- Random Forest
- Logistic Regression
- XGBoost

## Best Model
XGBoost / Random Forest performed best based on PR-AUC, which is ideal for imbalanced datasets.

## Key Techniques
- SMOTE (oversampling minority class)
- Stratified K-Fold Cross Validation
- Threshold tuning using F1-score
- Evaluation using ROC-AUC & PR-AUC
  
## Metrics Used
- ROC-AUC
- PR-AUC(primary metric) 
- F1 Score
- Confusion Matrix
  
## Business Impact
- Detects high-risk transactions
- Reduces financial fraud losses
- Improves transaction security systems
