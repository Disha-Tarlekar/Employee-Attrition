# 🧠 Employee Attrition Prediction Using Machine Learning

This project predicts whether an employee will leave the company (Attrition) based on HR features such as age, job role, salary, overtime, work environment, and performance metrics.  
The goal of this project is to help organizations identify employees who are at risk of exiting and take action to reduce turnover.

---

## 🚀 Project Overview
Employee attrition is one of the major challenges faced by companies.  
High attrition results in:
- Hiring and training costs
- Productivity loss
- Lack of project continuity

This project builds a **Machine Learning classification model** to detect whether an employee is likely to leave the company.

---

## 📂 Dataset Information
Dataset: **IBM HR Analytics Employee Attrition Dataset**

| Details | Information |
|--------|-------------|
| Rows | ~1470 |
| Target Variable | `Attrition` (Yes / No) |
| Type | Structured HR data |

The dataset includes:
- Demographics (Age, Gender, Education)
- Job Factors (JobRole, JobLevel, Department)
- Compensation (MonthlyIncome, StockOptionLevel)
- Work Environment (WorkLifeBalance, JobSatisfaction)
- Employment History (YearsAtCompany, Promotions, Training)

---

## 🔍 Methodology
| Step | Description |
|------|-------------|
| 1. Data Understanding | Dataset loading, structure & stats |
| 2. EDA | Visualizations & correlations |
| 3. Pre-processing | Encoding, missing values handling |
| 4. Train-Test Split | 80% training, 20% testing |
| 5. Model Building | **RandomForestClassifier** |
| 6. Evaluation | Accuracy + Classification Report + Feature Importance |
| 7. Business Insights | Factors leading to attrition |

---

## 📊 Key Visualizations
- Attrition distribution
- Age & Income histograms
- Correlation heatmap
- Top 10 feature importances

---

## 🤖 Model Results
| Metric | Result |
|--------|--------|
| Model Used | Random Forest Classifier |
| Performance | High accuracy & balanced precision/recall |
| Most Important Factors | MonthlyIncome, OverTime, JobLevel, YearsAtCompany, WorkLifeBalance |

---

## 💼 Business Conclusion
The prediction model can help HR take proactive actions to retain employees.  
Major attrition drivers observed:
- Overtime
- Work–life balance
- Job satisfaction
- Salary levels
- Career growth

📌 Improving these areas can significantly reduce attrition.

---

## 🚀 Future Enhancements
- Use XGBoost / CatBoost for higher accuracy
- Optimize hyperparameters extensively
- Deploy via Streamlit / Flask
- Integrate with HR dashboards (Power BI/Tableau)
- Build real-time monitoring system



---

## 🏷 Author
👤 **Disha Tarlekar**  


⭐ *If you like this project, don’t forget to give the repository a star!*
