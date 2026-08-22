Customer Churn Analysis – Power BI

Project Overview
Customer Churn Analysis is an interactive Power BI dashboard built using a telecom customer churn dataset obtained from Kaggle.
The project analyzes customer churn patterns and identifies key factors associated with customer attrition, with the goal of generating actionable insights for customer retention.

Objectives
- Analyze overall customer churn and churn rate
- Identify customer segments with higher churn
- Analyze churn across contract types
- Analyze churn by payment method
- Analyze churn by internet service
- Study the relationship between customer tenure and churn
- Analyze churn based on the number of services used
- Compare churn across demographic segments

Tools & Technologies
- Power BI
- Power Query
- DAX
- Microsoft Excel
- Kaggle Dataset

Data Preparation
The telecom customer churn dataset was imported into Power BI.
Using Power Query, categorical Yes/No service indicators were transformed into binary 1/0 values where appropriate.
A calculated column was created to determine the total number of services used by each customer.
A `Churn Flag` was also created to represent whether a customer had churned:
- 1 = Churned
- 0 = Not Churned

DAX measures were then used to calculate key KPIs including total customers, churned customers, average monthly charges, and churn rate.

Dashboard
The Power BI dashboard consists of two pages.

Page 1 – Customer Churn Overview
The first page provides a high-level overview of customer churn using:

- Total Customers
- Average Monthly Charges
- Churned Customers
- Churn Rate
- Churn Rate by Contract
- Churn Rate by Payment Method
- Churn Rate by Internet Service
- Interactive filters for Contract, Senior Citizen Status, and Internet Service

Page 2 – Detailed Churn Analysis
The second page provides deeper analysis of churn across:

- Senior Citizen Status
- Gender
- Tenure Groups
- Total Services Used
- Payment Method and Contract
- Contract
- Payment Method
- Internet Service

Interactive slicers allow users to explore different customer segments.

Key Insights
The dashboard helps identify:
- Customers on month-to-month contracts have substantially higher churn than customers on longer-term contracts.
- Electronic check users show comparatively high churn.
- Churn is higher among customers using fiber optic internet service.
- Customers with shorter tenure have considerably higher churn.
- Customers using fewer services tend to show higher churn rates.

Repository Contents
- `README.md` – Project documentation
- Power BI dashboard file
- Dashboard screenshots
- Dataset/source information

Dataset

The dataset used for this project was obtained from Kaggle and contains telecom customer information including demographics, services, contract details, payment methods, monthly charges, and churn status.

Author

Kahini Kartick
