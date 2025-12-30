# Adult Income Dataset – Machine Learning & Fairness Analysis

## Overview
This project presents a structured study of the Adult Income (Census Income) dataset using machine learning techniques. The objective is to predict whether an individual's annual income exceeds $50K based on demographic and employment-related features.

## Dataset
- This project uses the **Adult Income Dataset** from Kaggle:
- https://www.kaggle.com/datasets/wenruliu/adult-income-dataset
- The dataset contains census data used to predict whether an individual makes over \$50K per year.

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
