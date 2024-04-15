# Credit Score Prediction Project
This project aims to predict credit scores based on various features such as annual income, age, payment behavior, and credit history age. The prediction task is approached as a classification problem, where the credit score is divided into discrete classes.

# Introduction
Predicting credit scores is crucial for financial institutions to assess the creditworthiness of individuals. This project explores the use of machine learning techniques to predict credit scores based on various demographic and financial features.

# Dataset
The dataset used in this project consists of both training and testing data"https://www.kaggle.com/datasets/parisrohan/credit-score-classification". It includes the following columns:
- ID: Unique identifier for each record.
- Customer_ID: Unique identifier for each customer.
- Month: Month of the record.
- SSN: Social Security Number of the customer.
- Amount_invested_monthly: Amount invested monthly.
- Other features including demographic information, payment behavior, credit history, etc.

# Preprocessing
The preprocessing steps include:
- Handling missing values using mean imputation.
- Encoding categorical variables using Label Encoding.
- Dropping irrelevant columns.
- Feature engineering: Mean encoding for certain numerical features.

# Modeling
Three classification models are trained and evaluated:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Linear Support Vector Classifier (LinearSVC)

# Evaluation
The performance of each model is evaluated using accuracy score on both training and testing data. Additionally, further evaluation metrics such as precision, recall, and F1-score can be considered.

