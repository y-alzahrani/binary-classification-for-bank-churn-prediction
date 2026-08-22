# Churn Prediction for Bank Customers Using Binary Classification Models

## Project Overview

This project aims to predict **bank customer churn** using three supervised machine learning algorithms:

- **Logistic Regression**  
- **K-Nearest Neighbors**  
- **Support Vector Machine**  

The dataset contains simulated records for 10,000 customers, with **11 variables** such as credit score, age, tenure, balance, and activity status. The target variable is `churn`, where:
- `1` indicates the customer has churned
- `0` indicates the customer remains with the bank

## Objectives

- Train and evaluate **binary classification models** to predict customer churn
- Identify which features have the **strongest influence** on the likelihood of churn

For the analysis, explanation, and discussion of the results, please refer to the [report](report.pdf).

**Note:** The **Logistic Regression** and **KNN** algorithms were implemented manually from scratch **without using the scikit-learn library**, to strengthen understanding of how the algorithms work internally.