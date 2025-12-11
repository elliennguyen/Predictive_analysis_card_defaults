# Full Credit-Risk Prediction Pipeline

## Executive Summary
This project analyses over 30,000 customer credit records to predict which individuals are most likely to default on their credit payments.
The dataset was cleaned, validated and transformed before testing two machine learning models. Logistic Regression achieved the strongest performance (~80% accuracy) and generalised better than KNN.
The final model enables earlier identification of high-risk customers, supporting more reliable lending decisions and stronger risk management.

## Project Overview
This project builds a full credit-risk prediction pipeline using Python, focusing on demographic and payment-behaviour features.

The workflow covers:
- Data cleaning and anomaly handling
- Categorical transformation and feature engineering
- Train–test preparation
- Model training and evaluation
- Selecting the most reliable model for credit-risk assessment

## Data Preparation
Key steps included:
- Handling invalid and unexpected categorical values
- Encoding categorical features using one-hot encoding
- Splitting data into training (70%) and testing (30%) sets
- Standardising numerical features to improve model stability

These steps ensured clean, consistent data for model training.

## Model Training and Evaluation
**1. Logistic Regression**
- Test Accuracy: ~80%
- Strong generalisation with minimal overfitting
- Interpretable coefficients useful for financial risk decisions
**2. K-Nearest Neighbours (KNN)**
- Test Accuracy: ~78%
- Higher training accuracy but weaker performance on unseen data
- Evidence of overfitting

## Recommended Model
Logistic Regression was selected because it:
- Achieved the highest and most stable accuracy
- Generalised well to unseen data
- Provides interpretability important for credit-risk assessment
- Aligns with industry practice in financial modelling

## Tools Used
- Python
- Pandas
- NumPy
- StandardScaler
- Logistic Regression
- KNN

## Results
- Over 30,000 customer records analysed
- ~80% accuracy achieved with Logistic Regression
- Improved identification of high-risk customers
- Supports more consistent and explainable credit-risk decisions
