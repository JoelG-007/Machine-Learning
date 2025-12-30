# Adult Income Dataset Analysis

## Overview
This project presents a structured study of the Adult Income (Census Income) dataset using machine learning techniques. The objective is to predict whether an individual's annual income exceeds $50K based on demographic and employment-related features.

## Dataset
- Source: UCI Adult Income Dataset (via Kaggle)
- Type: Supervised binary classification
- Target Variable: Income (<=50K, >50K)

## Methodology
- Data cleaning and preprocessing
- One-Hot Encoding of categorical features
- Feature scaling for numerical variables
- Logistic Regression as a baseline model
- Model evaluation using accuracy, confusion matrix, and ROC-AUC

## Bias & Fairness Analysis
- Income distribution analysis by gender and race
- Prediction disparity analysis
- False Negative Rate comparison across demographic groups
- Discussion of ethical implications and fairness concerns

## Key Findings
- The dataset exhibits significant gender and racial imbalance
- Logistic Regression achieves reasonable baseline performance
- Model predictions reflect existing societal biases present in the data
## Disclaimer
This project is for educational purposes only and highlights the ethical risks of deploying machine learning models on socio-economic data without bias mitigation.
