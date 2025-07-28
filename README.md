# Customer Churn Prediction (Machine Learning)

Predict customer churn using classification models to help businesses retain customers and improve revenue.

## Project Overview
This project builds **Machine Learning models** to predict whether a customer will churn, based on demographic and service data.

## Dataset
- **Source:** [Telco Customer Churn – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Size:** 7,043 customers
- **Fields:** Gender, SeniorCitizen, Tenure, Contract, Charges, etc.

## Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature encoding & scaling
- Model building: Logistic Regression & Random Forest
- Hyperparameter tuning with GridSearchCV
- Cross-validation & ROC-AUC analysis

## Tech Stack
- Python (Pandas, Scikit-learn)
- Data Visualization (Matplotlib, Seaborn)

## Usage
Open the Jupyter Notebook:
jupyter notebook Customer_Churn_Prediction.ipynb

## Results
- Random Forest model achieved ~85% accuracy
- Key features influencing churn: Contract type, Tenure, Monthly Charges
