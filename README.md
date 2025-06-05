# 📊 Predicting Credit Card Consumption – Capstone ML Project
This project aims to predict the average credit card consumption for the next three months for customers of a leading bank, using historical customer demographic and behavioral data. The model is built as part of a capstone project from AnalytixLabs.

## 📌 Table of Contents
Problem Statement

Data Overview

Objective

Approach

Model Performance

Tech Stack

Results & Deliverables

How to Run

Author

## 🧠 Problem Statement
The banking sector leverages customer behavior data to customize services and improve marketing strategies. In this project, the goal is to predict credit card spending behavior of customers based on their past transactions and demographic data.

## 📂 Data Overview
The data consists of three datasets:

CustomerDemographics.csv: Personal and demographic information like gender, age, income, tenure, region, etc.

CustomerBehaviorData.csv: Past credit/debit card usage, loan status, transaction details, and investment behavior.

CreditConsumptionData.csv: Target variable cc_cons for training (some missing, needs to be predicted for others).

## 🎯 Objective
Predict the average credit card consumption for the next three months (cc_cons) using:

Demographic and behavioral variables.

Handle missing target values.

Use RMSPE (Root Mean Square Percentage Error) as the evaluation metric.

## 🛠️ Approach
Exploratory Data Analysis (EDA)

Data Cleaning & Missing Value Imputation

Feature Engineering

Train-test split with cross-validation

Tried models like:

Linear Regression

Decision Tree Regressor

Random Forest

XGBoost

Model Evaluation using RMSPE

Final predictions on missing cc_cons

## 📈 Model Performance
### Model	                             RMSPE (Test Set)
### Linear Regression	                 36.11503392744342
### Decision Tree                      76.74600231115936
### XGBoost	                           34.32448082190799 
### Random Forest	                      37.91552084350399
### Random Forest with Grid Search      35.9763303129249
### Ridge Regression                    36.08174596130946

## 📦 Results & Deliverables
✔️ Exploratory analysis and visualizations

✔️ Model training and evaluation

✔️ Final model predictions on unseen data

✔️ Cleaned code with comments

✔️ Project report PDF

## 🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/credit-consumption-prediction.git
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Open the Jupyter notebook

bash
Copy
Edit
jupyter notebook Credit_Consumption.ipynb

## 👤 Author
Pranjal Kastwar
📧 pranjalkastwar12@gmail.com 
🎓 Certified Data Analyst, AnalytixLabs

