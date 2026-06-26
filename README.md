# Employee Attrition Prediction

Internship Project — Week 2

## What this project does

Predicts whether an employee is likely to leave the company using HR data.
Analyzes factors like salary, overtime, job satisfaction, and work-life balance
to help HR teams identify at-risk employees before they resign.

## Dataset

`WA_Fn-UseC_-HR-Employee-Attrition.csv` — 1,470 employees, 35 features
(Age, Department, JobRole, MonthlyIncome, OverTime, WorkLifeBalance, YearsAtCompany, Attrition, and more)

## What's in this repo

- `analysis.ipynb` — full notebook with all 7 tasks (EDA, model training, charts, insights)
- `WA_Fn-UseC_-HR-Employee-Attrition.csv` — dataset used
- `summary.pdf` — 1-page write-up of findings for HR Director
- `charts/` — all saved chart images

## Steps done

1. Loaded and explored the data (attrition rate, shape, column types)
2. Cleaned it (dropped irrelevant columns, encoded categories, scaled features)
3. Performed EDA (attrition by department, job role, income, work-life balance)
4. Trained 3 models — Logistic Regression, Random Forest, Gradient Boosting
5. Evaluated using Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix
6. Extracted top 10 features driving employee exit
7. Written HR recommendations in non-technical language

## Key Findings

- Sales Representatives have the highest attrition rate (~40%)
- Overtime is the strongest predictor of employee exit
- Most employees leave within the first 1-3 years
- Gradient Boosting gave the best ROC-AUC score