# Payroll Risk Scoring System (ZENVY)

This project develops a Payroll Risk Scoring model using engineered behavioural
features derived from employee absenteeism patterns and salary change indicators.

The objective of the system is to identify **high-risk payroll records** that may
indicate anomalies such as excessive absenteeism, irregular salary revisions or
manual payroll adjustments.

---

## 🏗 Project Workflow

1️⃣ Exploratory Data Analysis & Cleaning  
2️⃣ Feature Engineering (attendance & salary based features)  
3️⃣ Risk Label Creation (rule-based classification)  
4️⃣ Correlation & Behavioural Pattern Analysis  
5️⃣ Model Training with Hyperparameter Tuning  
6️⃣ Model Comparison & Mathematical Justification  
7️⃣ Feature Importance Interpretation

---

## 🧠 Engineered Features

| Feature | Meaning |
|--------|--------|
| absence_ratio | Absenteeism hours relative to service time |
| high_absence_flag | Frequent / long-duration absenteeism indicator |
| salary_change_pct | Salary revision percentage behaviour |

These features capture behavioural risk signals not visible in raw payroll data.

---

## 🤖 Machine Learning Models Evaluated

• SVM (RBF Kernel)  
• Random Forest (Tuned)  
• Gradient Boosting (Tuned)

Gradient Boosting was selected as the **final model** because:

✔ Strong ROC-AUC performance  
✔ Lower variance vs Random Forest  
✔ Better generalisation on behavioural risk patterns  
✔ Suitable for risk scoring systems

---

## 📊 Key Insights

✔ Absence ratio is the strongest risk indicator  
✔ Unusual salary change % contributes to payroll anomalies  
✔ Frequent absenteeism increases risk probability  
✔ Risk behaviour is driven by **attendance + salary behaviour together**

---

## 📂 Repository Contents

• Jupyter Notebook — Payroll Risk Scoring System  
• Dataset used for modelling  
• Model comparison & feature importance analysis

---

### 🚀 This project demonstrates:

✔ Feature engineering  
✔ Risk modelling  
✔ Hyperparameter tuning  
✔ Model justification  
✔ Data-driven payroll analytics
