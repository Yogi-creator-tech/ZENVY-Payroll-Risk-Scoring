# Payroll Absenteeism Risk Prediction — Machine Learning Project

This project builds a supervised Machine Learning model to predict employees who are likely to fall under the **High Absentee** category using workforce, commute and lifestyle attributes from an absenteeism dataset.

The objective is to support HR and payroll teams by identifying employees with a higher probability of frequent absentee behaviour, enabling better workforce planning and attendance risk monitoring.

---

## 🏗 Project Workflow

1) Data Cleaning & Handling Missing Values  
2) Exploratory Data Analysis (EDA) with visualisations  
3) Target Creation — High vs Low Absentee Employees  
4) Feature Selection (no target leakage)  
5) Train–Test Split & Standardisation  
6) Machine Learning Model Training  
7) Model Performance Comparison  
8) Feature Importance Interpretation & Insights  

---

## 🎯 Target Definition

Employees are labelled as:

- **1 = High Absentee**
- **0 = Low Absentee**

based on whether their total absenteeism hours are **greater than the median value** in the dataset.

This creates a realistic and balanced binary classification problem.

---

## 🤖 Machine Learning Models Evaluated

- Logistic Regression  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)

Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC Score  

**Random Forest** achieved the best overall performance and was selected as the final model due to its stronger generalisation capability and ability to capture non-linear behaviour patterns.

---

## 📊 Feature Importance — Key Insights

Important predictors influencing absentee risk include:

- Transportation Expense  
- Body Mass Index (BMI)  
- Service Time  
- Age  
- Distance from Residence to Work  

**Interpretation**

- Higher commute cost / distance is associated with increased absentee likelihood  
- BMI and health-related indicators contribute to absence behaviour  
- Employees with longer tenure generally show more stable attendance patterns  

These insights provide practical value for:

- commute support or flexibility initiatives  
- employee wellness and health monitoring  
- attendance guidance for early-tenure employees  

---

## 🚀 Skills Demonstrated

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Selection & Scaling  
- Supervised ML Model Training  
- Performance Evaluation & Comparison  
- Feature Importance Interpretation  
- Business Insight Reporting  

---

