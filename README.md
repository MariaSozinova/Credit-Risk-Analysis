# Credit-Risk-Analysis

# Credit Risk Analysis — Onyx Data Challenge

This repository contains my submission for the **Onyx Data Challenge — Credit Risk Analysis**.  
The project focuses on understanding **which borrowers are most likely to default and why**, in order to support **safer and fairer lending decisions**.

Dataset not included — please download from [Onyx Data Challenge](https://datadna.onyxdata.co.uk/challenges/)

---

## Project Overview

Banks face a critical challenge: deciding who to lend to and at what terms while controlling default risk.  
Using a dataset of ~32,000 customers and their loan details, this analysis answers:

- Which groups of borrowers are more or less likely to default?
- What factors matter most for predicting loan outcomes?
- How do loan size, income, interest rates, and repayment terms affect risk?
- What early signals indicate financial trouble?

The analysis was done in **Python** (data cleaning & exploration) and visualized in **Tableau** through interactive dashboards.

---

## 📊 Dashboards

The project resulted in **three Tableau dashboards**:

1. **Loan Portfolio Snapshot**  
   - Portfolio composition by geography, loan purpose, grade, and term  
   - Interest rate & default rate overview  
   - KPIs summarizing the bank’s current loan book  

2. **Lending Risk Analysis**  
   - Deep dive into default drivers  
   - Past defaulters & repeat risk  
   - High-risk loan intents (debt consolidation, medical, home improvement)  
   - Relationship between loan size, income, interest, and default  

3. **Borrower Risk Profile**  
   - Demographic and financial risk factors  
   - Loan-to-Income (LTI) & Debt-to-Income (DTI) distributions  
   - Home ownership, employment, and utilization impact on default  
   - Heatmaps combining multiple risk drivers

   ![](https://github.com/MariaSozinova/Credit-Risk-Analysis/blob/main/assets/Portfolio%20Snapshot-2.png)

   ![](https://github.com/MariaSozinova/Credit-Risk-Analysis/blob/main/assets/Risk%20Analysis-2.png)

   ![](https://github.com/MariaSozinova/Credit-Risk-Analysis/blob/main/assets/Borrower%20Risk%20Profile-2.png)

🔗 **Interactive Tableau dashboards:**  
👉 [View on Tableau Public](https://public.tableau.com/views/CreditRiskAnalylsis/BorrowerRiskProfile)

---

## 🛠️ Tech Stack & Workflow

- **Python** (Jupyter Notebook)  
  - Data cleaning: missing values, outliers detection  
  - Exploratory data analysis (EDA): distributions, correlations, feature grouping
- **Tableau**  
  - Interactive visual analytics and storytelling dashboards
  - Custom navigation buttons and layout for executive readability

**Key Python libraries:**  
`pandas` · `numpy` · `matplotlib` · `seaborn`

---

## 🔑 Key Insights

- Borrowers with a **past default** are ~3× more likely to default again.
- Loans for **debt consolidation, medical expenses, and home improvement** show higher default rates despite similar interest rates.
- High **Loan-to-Income (LTI)** and **Debt-to-Income (DTI)** ratios, plus **unstable employment**, strongly increase risk.
- Interest rates do not fully reflect long-term loan risk — potential pricing opportunity.

---

