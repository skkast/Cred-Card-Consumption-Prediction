# 📊 Predicting Credit Card Consumption – Capstone ML Project  

This project aims to **predict the average credit card consumption for the next three months** for customers of a leading bank, using historical customer demographic and behavioral data. The model is built as part of a **capstone project from AnalytixLabs**.  

---

## 📌 Table of Contents  
- [Problem Statement](#-problem-statement)  
- [Data Overview](#-data-overview)  
- [Objective](#-objective)  
- [Approach](#-approach)  
- [Model Performance](#-model-performance)  
- [Results & Deliverables](#-results--deliverables)  
- [How to Run](#-how-to-run)  
- [Author](#-author)  

---

## 🧠 Problem Statement  
The banking sector leverages customer behavior data to **customize services and improve marketing strategies**.  
In this project, the goal is to **predict credit card spending behavior of customers** based on their past transactions and demographic data.  

---

## 📂 Data Overview  
The data consists of three datasets:  
- **CustomerDemographics.csv** → Personal and demographic information like gender, age, income, tenure, region, etc.  
- **CustomerBehaviorData.csv** → Past credit/debit card usage, loan status, transaction details, and investment behavior.  
- **CreditConsumptionData.csv** → Target variable `cc_cons` for training (some missing, needs to be predicted for others).  

---

## 🎯 Objective  
- Predict the **average credit card consumption (`cc_cons`)** for the next three months.  
- Use **demographic and behavioral variables**.  
- Handle **missing target values**.  
- Evaluate models using **RMSPE (Root Mean Square Percentage Error)**.  

---

## 🛠️ Approach  
- Exploratory Data Analysis (EDA)  
- Data Cleaning & Missing Value Imputation  
- Feature Engineering  
- Train-test split with cross-validation  
- Model Training (tested multiple models):  
  - Linear Regression  
  - Decision Tree Regressor  
  - Random Forest  
  - Ridge Regression  
  - XGBoost  
  - Random Forest (with Grid Search)  
- Model Evaluation using RMSPE  
- Final predictions on missing `cc_cons`  

---

## 📈 Model Performance  

| Model                      | RMSPE (Test Set) |
|----------------------------|------------------|
| Linear Regression          | 36.12            |
| Decision Tree              | 76.75            |
| Random Forest              | 37.92            |
| Random Forest (GridSearch) | 35.98            |
| Ridge Regression           | 36.08            |
| **XGBoost**                | **34.32 ✅**     |

👉 **XGBoost** performed the best with the lowest RMSPE.  

---

## 📦 Results & Deliverables  
- Exploratory analysis and visualizations  
- Model training and evaluation  
- Final model predictions on unseen data  
- Cleaned, well-documented code  
- Project report (PDF)  

---

## 🚀 How to Run  

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/credit-consumption-prediction.git
   cd credit-consumption-prediction
   Install dependencies  
2.pip install -r requirements.txt  
3.Open the Jupyter Notebook  
jupyter notebook Credit_Consumption.ipynb  

## 👤 Author
**Pranjal Kastwar**  
📧 Email: pranjalkastwar12@gmail.com  
🔗 LinkedIn: [linkedin.com/in/pranjal-kastwar-82b846177](https://www.linkedin.com/in/pranjal-kastwar-82b846177)  
🌐 GitHub: [github.com/skkast](https://github.com/skkast)  
🎓 Certified Data Analyst – AnalytixLabs



