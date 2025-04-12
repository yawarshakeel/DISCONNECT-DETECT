# DISCONNECT-DETECT
## CHURN INTELLIGENCE FOR TELECOM

## Overview

This Power BI project analyzes customer retention and churn behavior for a telecom company. The goal is to help business stakeholders understand customer loss patterns, identify high-risk segments, and suggest effective retention strategies.

The entire project was completed using Power BI, from data cleaning and modeling to creating a professional 5-page interactive report.

---

## Tools Used

- *Power BI* – For data cleaning, modeling, DAX calculations, and building the report

---

## Objectives

- Identify factors contributing to customer churn
- Analyze retention and churn trends over time
- Segment customers based on churn behavior
- Build a visually engaging, insight-driven Power BI report
- Support data-driven decisions for improving customer retention

---

## Power BI Report Pages

### *1. Executive Summary Dashboard*
- Key KPIs: Total Customers, Churned Customers, Churn Rate, Revenue
- Monthly trends of churn and retention
- Customer distribution by state and segment

### *2. Customer Demographics*
- Distribution by gender, distribution by age groups, contract type, Cities with highest customers (Top 10)

### *3. Revenue Spending And Behaviour Analysis*
- Distribution of customers by monthly charges
- Average monthly charges by contract type
- Total revenue by internet type
- Distribution of customers by monthly charges and churn status

### *4. Churn Breakdow Analysis*
- City wise churn rate with average monthly charges
- Churn rate by age group, payment method, contract type and internet type

### *5. Recommendations*
- Strategic insights based on data
- Suggested actions to reduce churn and improve retention
- Summary cards highlighting key takeaways

---

## Dataset

- Sample telecom customer data
- Columns: Customer ID, Gender, Senior Citizen, Partner, Dependents, Tenure, Contract, Internet Service, Monthly Charges, Total Charges, Churn

---

## Key DAX Measures

- *Churn Rate* = DIVIDE([Churned Customers], [Total Customers])
- *Retention Rate* = 1 - [Churn Rate]
- *Average Tenure* = AVERAGE(Customer[Tenure])
- *Monthly Churn Count* = COUNTROWS(FILTER(Customer, Customer[Churn] = "Yes"))

---

## Outcome

This Power BI report delivers a complete analysis of customer churn behavior and highlights retention opportunities. It showcases key Power BI skills including data modeling, DAX, and dashboard design, making it a strong portfolio project for data analyst roles.

---

## Author

*Yawar Shakeel*  
Aspiring Data Analyst | Skilled in Power BI, Excel, SQL, and Python
