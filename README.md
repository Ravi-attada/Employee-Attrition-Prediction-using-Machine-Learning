# Employee Attrition Analysis

## 📌 Project Overview
Employee Attrition Analysis is a Machine Learning project that analyzes employee data to identify the key factors influencing employee turnover and predict whether an employee is likely to leave the organization. The project combines exploratory data analysis (EDA), data preprocessing, predictive modeling, and business insights to help HR teams make data-driven retention decisions.

## 🎯 Objectives
- Analyze employee attrition patterns across different departments and job roles.
- Identify the major factors contributing to employee turnover.
- Build and compare multiple machine learning models for attrition prediction.
- Evaluate model performance using classification metrics.
- Provide actionable HR recommendations to improve employee retention.

## 📂 Dataset
- IBM HR Analytics Employee Attrition & Performance Dataset
- Total Records: **1,470**
- Features: **35**
- Target Variable: **Attrition (Yes/No)**

## 🛠️ Project Workflow
- Data Loading & Exploration
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting Classifier
- Model Evaluation
- Feature Importance Analysis
- Business Insights & HR Recommendations

## 📊 Key Findings
- Sales Department recorded the highest attrition rate (20.63%).
- Sales Representatives and Laboratory Technicians showed the highest employee turnover.
- Employees working overtime and those who travel frequently are more likely to leave.
- Employees with lower monthly income and longer periods without promotion have a higher risk of attrition.
- Most employee exits occur during the first two years of employment.

## 📈 Visualizations
- Attrition Rate by Department & Job Role
- Monthly Income vs Attrition
- Confusion Matrix
- Top 10 Feature Importance
- ROC Curve Comparison

## 🤖 Machine Learning Models
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

Among the evaluated models, **Logistic Regression** delivered the best overall performance by achieving the highest balance between identifying employees likely to leave and maintaining reliable predictions.

## 💡 Business Recommendations
- Focus retention efforts on the Sales Department and high-risk job roles.
- Reduce excessive overtime and improve work-life balance.
- Provide timely promotions and career development opportunities.
- Strengthen onboarding and employee engagement during the first two years of employment.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📁 Repository Contents
```

Employee-Attrition-Analysis/
│── analysis.ipynb
│── WA_Fn-UseC_-HR-Employee-Attrition.csv
│── summary.pdf
│── README.md

```

## ⭐ Future Improvements
- Hyperparameter tuning for improved prediction accuracy.
- Apply advanced ensemble methods such as XGBoost and LightGBM.
- Deploy the model as a web application using Flask or Streamlit.
- Develop an interactive HR dashboard for real-time employee attrition monitoring.

---
**This project demonstrates an end-to-end Machine Learning workflow, combining data analysis, predictive modeling, visualization, and business-focused recommendations to support HR decision-making.**
```
