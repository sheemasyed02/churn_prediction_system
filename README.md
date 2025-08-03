# Customer Churn Prediction System

This project presents a complete machine learning pipeline to predict customer churn using structured customer data. The system implements and compares three classification algorithms and selects the best-performing model for deployment-ready predictions.

---

## 1. Introduction

Customer churn directly impacts business profitability. Identifying customers at risk of leaving helps organizations design targeted retention strategies. This machine learning system uses customer demographic and behavioral data to classify whether a customer is likely to churn.

---

## 2. Key Highlights

- **Data Preprocessing**  
  - Cleansing, encoding, and feature engineering techniques applied  
  - Handling missing values and categorical variables

- **Class Imbalance Handling**  
  - Upsampling techniques used to correct imbalance in target distribution

- **Modeling Approaches**  
  - Logistic Regression (with hyperparameter tuning)  
  - Random Forest Classifier (with parameter optimization)  
  - XGBoost Classifier (gradient boosting-based)

- **Model Evaluation and Selection**  
  - Accuracy-based selection of the best performing model  
  - Evaluation via confusion matrix, classification report, and ROC curve  
  - Feature importance visualization for interpretability

- **Prediction Output**  
  - Predicts customer churn along with associated probability scores  
  - Supports business decision-making with interpretable results

---

## 3. Dataset Details

The system is built to process customer records with the following schema:

| Feature           | Description                                 |
|------------------|---------------------------------------------|
| CustomerID        | Unique identifier for each customer         |
| Gender            | Customer gender (Male/Female)               |
| Age               | Customer age                                |
| Tenure            | Years of association with the company       |
| Balance           | Account balance                             |
| NumOfProducts     | Number of products used by the customer     |
| HasCrCard         | Credit card status (0 = No, 1 = Yes)        |
| IsActiveMember    | Active member status (0 = No, 1 = Yes)      |
| EstimatedSalary   | Estimated salary of the customer            |
| Exited            | Target label (1 = Churned, 0 = Retained)    |

---

## 4. Installation Requirements

To run this project, install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib
