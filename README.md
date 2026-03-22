# Titanic EDA Analysis

Exploratory Data Analysis on the Titanic dataset using 
Python, Pandas, and Seaborn.

## Project Overview
Full EDA pipeline on 891 Titanic passengers — missing value 
analysis, survival distributions, correlations, and 5 
actionable business insights.

## Key Findings
- Female survival rate 74% vs male 19% — 55pp gap
- First class survival (63%) was 2.6x higher than third class (24%)
- Passenger class strongest numerical predictor (r = -0.34)
- Survivors paid 2.2x higher fares ($48.40 vs $22.12)
- 20% of age data missing — imputation required for modeling

## 📊 Visualizations

### Chart 1 — Survival Rate by Sex
> Females survived at 74% vs males at 19%



### Chart 2 — Survival Rate by Age
> Children aged 0-9 had highest survival (~61%)

### Chart 3 — Age vs Fare
> Higher fare passengers survived more







## Tools Used
Python · Pandas · NumPy · Seaborn · Matplotlib

## Files
- `titanic_eda.ipynb` — full analysis notebook with charts

📊 Results Summary:
AnalysisFindingOverall survival38.4% survived (342 out of 891)Female survival74.2% ✅Male survival18.9%1st Class survival63.0% ✅2nd Class survival47.3%3rd Class survival24.2%Avg fare (survived)$48.40Avg fare (died)$22.12

🔥 Strongest Correlations with Survival:

Pclass: -0.34 → Higher class = more survival
Fare: +0.26 → Higher fare = more survival
Age: -0.08 → Slight negative (older = less survival)

## Author
Laxmi Rushaali Kuravi
M.S. Business Analytics — Harrisburg University
SQL · Python · Power BI · scikit-learn · SHAP · XGBoost
