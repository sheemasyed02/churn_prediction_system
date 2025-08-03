## Customer Churn Prediction System

A comprehensive machine learning system for predicting customer churn using multiple classification algorithms. This project implements and compares three different models to identify customers who are likely to leave a service, enabling proactive retention strategies.

---

## Project Overview

Customer churn prediction is a critical business application that helps organizations identify customers at risk of discontinuing their services. This system analyzes customer data including demographics, account information, and service usage patterns to predict churn probability.

---

## Features

- **Data Preprocessing**: Comprehensive data cleaning, handling missing values, and feature engineering  
- **Class Imbalance Handling**: Implements upsampling techniques to address dataset imbalance  
- **Multiple Model Implementation**:  
  - Logistic Regression with hyperparameter tuning  
  - Random Forest Classifier with optimized parameters  
  - XGBoost Classifier for gradient boosting  
- **Model Comparison**: Automatic selection of best performing model based on accuracy  
- **Comprehensive Evaluation**: Includes classification reports, confusion matrices, ROC curves, and feature importance analysis  
- **Prediction Output**: Generates predictions with probability scores for business decision making  

---

## Dataset Structure

The system works with customer data containing the following features:

- `CustomerID`: Unique identifier for each customer  
- `Gender`: Customer gender (Male/Female)  
- `Age`: Customer age  
- `Tenure`: Number of years with the company  
- `Balance`: Account balance  
- `NumOfProducts`: Number of products used  
- `HasCrCard`: Credit card status (0/1)  
- `IsActiveMember`: Active membership status (0/1)  
- `EstimatedSalary`: Customer's estimated salary  
- `Exited`: Target variable indicating churn (0/1)  

---

## Installation Requirements

To run this project, make sure the following Python libraries are installed:

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  
- `xgboost`  
- `joblib`  
