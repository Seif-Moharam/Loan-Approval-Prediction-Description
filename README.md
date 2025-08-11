# Loan-Approval-Prediction-Description

## Overview
This project predicts whether a loan application will be approved or rejected using Logistic Regression and Decision Tree classifiers. It handles class imbalance with SMOTE and includes comprehensive performance evaluation.

## Dataset
[Loan Approval Prediction Dataset](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset)

## Key Steps
1. Data cleaning
2. Feature encoding
3. Data splitting
4. Feature standardization
5. Class imbalance handling (SMOTE oversampling)

## Training
Models: Logistic Regression & Decision Tree  
Metrics: Accuracy, Confusion Matrix  

## Data Distribution
<img width="1621" height="1239" alt="Data Distribution" src="https://github.com/user-attachments/assets/6104a9a2-9955-4a39-94b9-3bc2303195b2" />


## Results:
### Logistic Regression
Without SMOTE:

<img width="539" height="455" alt="lr" src="https://github.com/user-attachments/assets/2c8bf098-a484-456f-943f-7dd12b3b8cfe" />

With SMOTE:

<img width="539" height="455" alt="lr smote" src="https://github.com/user-attachments/assets/9e02a6b7-e5f7-4fd6-bba0-f86d33ce97dd" />

### Decision Tree
Without SMOTE:

<img width="539" height="455" alt="dt" src="https://github.com/user-attachments/assets/a0103c54-7224-4a3a-9be3-b953340b75cb" />

With SMOTE:

<img width="539" height="455" alt="dt smote" src="https://github.com/user-attachments/assets/8afec279-a9fd-41dc-8082-7e103aa31835" />

## Requirements:

Python 3.12

pandas

scikit-learn

imbalanced-learn

matplotlib

seaborn
