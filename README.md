# Credit Card Fraud Detection using XGBoost

A machine learning project for detecting fraudulent credit card transactions using **XGBoost**, **SMOTE**, **decision threshold tuning**, and **feature importance analysis**.

## 📌 Problem Statement

Credit card fraud detection is a highly imbalanced classification problem where fraudulent transactions represent a small proportion of total transactions.

The goal of this project is to build a machine learning model that can identify potentially fraudulent transactions while handling class imbalance and evaluating the trade-off between precision and recall.

## 🎯 Objectives

- Analyze transaction data and identify patterns related to fraud.
- Handle class imbalance using **SMOTE**.
- Train an **XGBoost classifier** for fraud detection.
- Evaluate model performance using precision, recall, and F1-score.
- Tune the classification decision threshold.
- Interpret the model using feature importance.

## 📊 Dataset

This project uses the **BankSim dataset**, a synthetic financial transaction dataset containing transaction and customer-related attributes.

The dataset includes features such as:

- Transaction step
- Age
- Gender
- Merchant
- Transaction category
- Transaction amount
- Fraud label

> Note: BankSim is a synthetic dataset and should not be interpreted as real individual customer banking data.

## 🔄 Machine Learning Workflow

```text
Raw Transaction Data
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Feature Selection
        ↓
Categorical Encoding
        ↓
Train-Test Split
        ↓
Class Imbalance Analysis
        ↓
SMOTE Oversampling
        ↓
XGBoost Classifier
        ↓
Fraud Probability Prediction
        ↓
Decision Threshold Tuning
        ↓
Model Evaluation
        ↓
Feature Importance Analysis
