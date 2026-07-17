# saas-financial-model-forecasting
Dynamic SaaS financial model and KPI dashboard built in Excel using subscription customer data.

## Project Overview

This project was developed as part of FIN 423 at the University of Illinois Chicago.

The objective of this project was to build a dynamic financial analytics and forecasting model for a subscription-based Software-as-a-Service (SaaS) company using realistic customer, subscription, and revenue datasets.

The model was designed to simulate the type of financial planning and analysis work performed in FP&A, strategic finance, and revenue operations teams within subscription businesses.

By combining historical operating data with forecasting assumptions, the model allows management to analyze performance trends, evaluate customer economics, and project future Monthly Recurring Revenue (MRR) under multiple business scenarios.

---

## Business Problem

Subscription businesses depend heavily on recurring revenue, customer retention, and efficient customer acquisition.

Companies that fail to accurately forecast revenue or understand churn behavior risk overestimating growth and misallocating resources.

The goal of this project was to transform raw operating data into actionable financial insights that support strategic decision-making.

---

## Data Sources

The model integrates three cleaned datasets:

### Customer Dataset
Includes:

- Customer ID
- Signup Date
- Subscription Plan
- Monthly Fee
- Customer Acquisition Cost (CAC)
- Churn Status
- Churn Date

### Subscription Revenue Dataset
Includes:

- Subscription ID
- Customer ID
- Monthly Revenue
- Subscription Tier
- Acquisition Cost
- Monthly Revenue History

### Revenue Dataset
Includes:

- Subscription ID
- Customer ID
- Revenue Amount
- Revenue Type
- Monthly Revenue Activity

---

## Data Cleaning & Preparation

Prior to analysis, the datasets were cleaned and standardized by:

- Standardizing date formats
- Removing duplicate records
- Aligning subscription plan names
- Creating churn indicators
- Building monthly cohort structures
- Combining multiple datasets into a single analytical model

---

## KPI Dashboard

The dashboard tracks key SaaS performance metrics including:

- Monthly Recurring Revenue (MRR)
- Annual Recurring Revenue (ARR)
- Active Customers
- Monthly Churn Count
- Monthly Churn Percentage
- Average Customer Acquisition Cost (CAC)
- Average Revenue Per User (ARPU)
- Customer Lifetime Value (LTV)
- LTV/CAC Ratio
- Revenue Lost Due to Churn
- Revenue by Subscription Tier

---

## Dashboard Visualizations

The dashboard includes:

- MRR trend over time
- Active customer growth
- Monthly churn trends
- Revenue by pricing tier
- Executive KPI scorecards
- Revenue mix analysis

---

## Forecasting Model

A dynamic 12-month forecasting model was created using assumptions for:

- Monthly customer acquisition
- Monthly churn rate
- Average Revenue Per User (ARPU)
- Customer mix by subscription tier
- Customer Acquisition Cost (CAC)

The model includes three forecasting scenarios:

- Base Case
- Best Case
- Worst Case

A dropdown selector dynamically updates the forecast outputs and charts based on the selected scenario.

---

## Key Business Insights

Several important insights emerged from the analysis:

- Customer retention has a larger impact on long-term growth than customer acquisition alone.
- Enterprise customers generate a disproportionate share of total recurring revenue.
- Lower churn rates significantly increase customer lifetime value.
- Improvements in retention generate stronger long-term returns than increases in marketing spend.

---

## Skills Demonstrated

### Financial Analysis
- Revenue Forecasting
- Scenario Analysis
- Sensitivity Analysis
- KPI Development
- Strategic Finance

### Technical Skills
- Microsoft Excel
- Financial Modeling
- Dashboard Design
- Data Cleaning
- Data Visualization
- Business Analytics

### SaaS Metrics
- MRR
- ARR
- CAC
- ARPU
- LTV
- LTV/CAC
- Churn Analysis

---

## Technologies Used

- Microsoft Excel
- CSV Data Integration
- Financial Modeling
- Dashboard Development

---

## Future Improvements

Future enhancements could include:

- Marketing spend optimization
- Cash flow forecasting
- Cohort retention analysis
- Churn prediction modeling
- Regression analysis for churn drivers
- Automated ETL pipelines
- Real-time dashboard updates using Power BI or Tableau

---

## Repository Contents

```
├── SaaS_Financial_Model.xlsx
├── FIN423_Final_Project.pdf
├── dashboard.png
├── forecast_model.png
├── kpi_analysis.png
├── customer_dataset.png
├── subscription_dataset.png
└── revenue_dataset.png
```

---

## Author

Wendy Alpizar  
University of Illinois Chicago  
B.S. Information & Decision Sciences  
Minor in Finance
