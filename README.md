# Credit Risk Analysis & Insights

Credit risk analysis is essential for financial institutions to understand the likelihood of default and make informed lending decisions.  
This project uses the **American Express dataset** to explore borrower characteristics, identify key risk factors, and build **data-driven dashboards and reports** that highlight patterns in credit card defaults.  

Instead of focusing only on machine learning models, the project emphasizes:
- **Data cleaning & preprocessing**  
- **Exploratory Data Analysis (EDA)**  
- **Visualization of borrower behavior and risk factors**  
- **Business insights for financial decision-making**  

---

## Dataset Overview

- **Rows**: 45,528 (subset of 30,000 used)  
- **Columns**: 19 (6 categorical, 13 numerical)  
- **Target Variable**: `credit_card_default` (0 = no default, 1 = default)  

### Key Fields
- `credit_score` – Borrower’s creditworthiness  
- `credit_limit_utilization` – How much of the credit limit is used  
- `days_employed` – Length of employment  
- `income_category`, `education_level`, `marital_status`  

---

## Analysis & Insights

1. **Data Cleaning**
   - Handled missing values and outliers  
   - Encoded categorical features  
   - Standardized numerical fields  

2. **Exploratory Data Analysis**
   - Distribution of defaults across age, income, education  
   - Correlation heatmaps for numeric variables  
   - Credit utilization vs. default likelihood  

3. **Key Insights**
   - **High credit limit utilization** strongly correlates with defaults  
   - **Employment stability** is an important predictor  
   - **Borrower’s age** is **not significant** for default risk  
   - Default rates vary significantly by **income and education levels**  

---

## Visualizations

The analysis includes:
- Default distribution across borrower demographics  
- Correlation heatmaps of financial indicators  
- Boxplots & bar charts showing risk drivers  
- Dashboard-style summary of KPIs for credit risk monitoring  

---

## Predictive Modeling

While the main focus is on **data analysis & visualization**, machine learning models were also tested:  
- Logistic Regression, Random Forest, Decision Tree, LightGBM, CatBoost, XGBoost  
- **XGBoost achieved the highest accuracy: 97.3%**  

This step demonstrates how advanced analytics can complement data analysis by predicting future borrower defaults.  

---

## Business Impact

- Helps banks & lenders **identify high-risk borrowers early**  
- Supports **data-driven credit policy decisions**  
- Reduces potential **financial losses from defaults**  
- Provides a **dashboard/reporting framework** for ongoing monitoring  

---

## Tools & Tech

- **Languages**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, XGBoost, LightGBM, CatBoost  
- **Visualization**: Matplotlib, Seaborn (with potential Power BI/Tableau extensions)  
- **Environment**: Jupyter Notebook  

---

## Repository Structure
