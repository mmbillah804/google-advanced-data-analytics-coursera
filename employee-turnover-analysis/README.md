# 📊 Predicting Employee Turnover Using Machine Learning  
*Capstone Project – Google Advanced Data Analytics Certificate*

## 🔍 Project Overview
This capstone project aims to support the HR department at **Salifort Motors** by identifying factors that lead to employee attrition and building a machine learning model to **predict whether an employee is likely to leave the company**. By using predictive analytics, we hope to help HR take proactive steps to improve **employee satisfaction** and **retention**, thereby reducing recruitment and training costs.

## 🎯 Business Problem
> “What’s likely to make the employee leave the company?”

Using employee survey data, we:
- Conducted detailed **exploratory data analysis (EDA)** to uncover trends and outliers.
- Engineered meaningful features.
- Trained multiple **machine learning models**, including Random Forest and XGBoost.
- Evaluated the model using **ROC-AUC**, **F1-score**, and **confusion matrices**.
- Interpreted **feature importance** to provide actionable insights.


## 🧠 Key Insights
- Overwork (monthly hours > 175) strongly correlates with attrition.
- Employees with **7 projects** all left the company.
- **Satisfaction level**, **number of projects**, **tenure**, and **evaluation score** are top predictors.
- Long-tenured employees (>6 years) rarely leave.
- Very few promotions despite high workloads contributed to dissatisfaction.
- Employees who left generally fall into two groups: **underperformers** and **high performers who are overworked**.


## 🛠️ Technologies Used
- **Languages**: Python  
- **Libraries**: pandas, NumPy, seaborn, matplotlib, scikit-learn, xgboost  
- **Modeling Techniques**:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest (GridSearchCV-tuned)  
  - Feature Engineering and Encoding  
  - Model Evaluation using multiple classification metrics  


## ✅ Modeling Highlights

- **Target Variable**: `left` (binary: 1 = employee left, 0 = stayed)
- **Top Features**: `last_evaluation`, `number_project`, `tenure`, `overworked`
- **Final Model**: Random Forest Classifier with hyperparameter tuning via GridSearchCV
- **Best AUC (Test Set)**: _High performing, with more false positives than false negatives (conservative strategy)_

Confusion Matrix and feature importance visualizations helped validate model behavior and interpretability.


## 📌 Next Steps
- Assess potential **data leakage**, especially from `last_evaluation` and `satisfaction_level`.
- Retrain the model without those fields and compare performance.
- Explore predicting **performance score** instead of attrition.
- Present findings to HR to inform policy changes and early retention strategies.


## 🙋‍♂️ About the Author
This project was completed as part of the **Google Advanced Data Analytics Certificate** program, where I developed skills in data analysis, statistics, and machine learning using Python.

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/mmbillah804/)   
📁 View my full portfolio: [GitHub](https://github.com/mmbillah804)

