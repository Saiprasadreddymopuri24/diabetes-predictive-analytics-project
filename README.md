# Diabetes Predictive Analytics Project

AI-Enhanced Predictive Analytics System for Diabetes Risk Detection using Machine Learning.

## Project Overview
This project focuses on predicting diabetes risk using machine learning techniques. Health indicators such as age, BMI, HbA1c level, blood glucose level, hypertension, and smoking history are used to build predictive models.

The goal is to identify individuals who may be at risk of diabetes and understand the factors contributing to the prediction.

## Dataset
The dataset includes health-related variables such as:
- Age
- BMI
- HbA1c level
- Blood glucose level
- Hypertension
- Smoking history
- Diabetes outcome

## Methods Used
The following steps were performed in the project:

1. Data exploration and preprocessing
2. Train-test split with stratification
3. Logistic Regression model (baseline)
4. Random Forest model
5. Threshold optimization
6. SHAP explainability analysis
7. Risk probability prediction
8. Risk categorization (Low, Medium, High)

## Key Insights
- Random Forest performed better than Logistic Regression.
- HbA1c level and blood glucose level were the strongest predictors.
- SHAP helped explain the influence of different health indicators on diabetes prediction.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- SHAP

## Repository Contents
- `diabetes-predictive-analytics-project.ipynb` → main notebook
- `diabetes_prediction_dataset.csv` → dataset used for modeling
- `diabetes_risk_predictions.csv` → predicted risk results
