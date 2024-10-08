# Bank Customer Churn Prediction

## Project Overview

This project is part of my Midterm Exam for the Model Deployment Course. The goal is to develop a predictive model that accurately identifies customers who are likely to churn based on their attributes. By doing so, the bank can implement targeted strategies to retain customers, reduce churn rates, and improve overall customer satisfaction. After training and selecting the best model, we deployed it using Streamlit.

## Dataset
The dataset used in this project is derived from bank customer information, encompassing features related to customer demographics, account details, and transaction history. The target variable is `churn`, indicating whether a customer has churned.

## Modeling
Following the exam requirements, we compared two modeling techniques: Random Forest and XGBoost, to determine the best model for predicting customer churn. We also performed hyperparameter tuning for both models to optimize their performance and identify the most effective model for this task.

## Evaluation Metrics
Due to class imbalance in the dataset, accuracy alone is not a reliable measure of performance. Instead, we utilize precision, recall, and F1-score, particularly focusing on the minority class (churn customers), to evaluate model effectiveness.

## Result
![Model Evaluation Results](https://github.com/user-attachments/assets/0a69a171-4657-4f2d-a41f-d45ac0c72513)

Among the evaluated models, XGBoost 1 demonstrated the best performance in effectively identifying the churn class. With the highest F1-score, it provides valuable insights for developing strategies to retain at-risk customers.
