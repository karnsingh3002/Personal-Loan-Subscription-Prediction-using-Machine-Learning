# Personal Loan Subscription Prediction using Machine Learning

## Overview

This project develops a machine learning framework to predict whether a bank customer is likely to accept a personal loan offer. The objective is to help financial institutions identify potential customers and improve the effectiveness of marketing campaigns.

The project covers the complete machine learning workflow including data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and performance evaluation.

---

## Dataset

The dataset contains information about 5000 bank customers and includes demographic, financial, and account-related attributes.

### Features

- Age
- Income
- Family Size
- Average Credit Card Spending (CCAvg)
- Education
- Mortgage
- Securities Account
- CD Account
- Online Banking Usage
- Credit Card Ownership

### Target Variable

- Personal Loan
  - 1 = Customer accepted loan
  - 0 = Customer did not accept loan

---

## Project Workflow

### 1. Data Preprocessing

- Imported and inspected the dataset
- Checked data types and statistical summaries
- Verified missing values
- Removed irrelevant features (ID)
- Handled inconsistent values in Experience
- Removed highly correlated and redundant features
- Dropped ZIP Code due to high cardinality

### 2. Exploratory Data Analysis

- Distribution analysis
- Correlation analysis
- Feature importance investigation
- Identification of influential customer characteristics

### 3. Feature Engineering

- Feature selection
- Scaling and normalization
- Data transformation

### 4. Model Development

The following machine learning models were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gaussian Naive Bayes
- XGBoost Classifier

### 5. Hyperparameter Tuning

- GridSearchCV
- Stratified K-Fold Cross Validation

### 6. Model Evaluation

Performance metrics used:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Cross-Validation Score

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- StatsModels

---

## Results

The machine learning models successfully learned customer behavior patterns and demonstrated strong predictive capability for personal loan acceptance.

Key findings:

- Income and customer financial indicators were among the strongest predictors.
- Proper feature selection improved model performance.
- Cross-validation provided reliable model evaluation.
- Advanced ensemble methods achieved competitive classification performance.

---

## Applications

- Banking and financial services
- Customer targeting
- Marketing campaign optimization
- Loan recommendation systems
- Customer segmentation

---
