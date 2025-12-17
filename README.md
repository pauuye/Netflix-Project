# Netflix Customer Churn Analysis

**Project Overview**

This project analyzes customer churn behavior for a Netflix-style subscription platform using structured data analysis and visualization tools. The objective is to identify key factors associated with subscription cancellation and to present insights across multiple dimensions, including age group, subscription type, device usage, and content preference.

**Purpose**

This repository demonstrates end-to-end analytical workflow, including data exploration, transformation, visualization, and insight generation, using SQL, Excel, and Power BI.


```
Netflix-Project/
│
├── data/
│     └── netflix_customer_churn.csv
│
├── MySQL/
│     ├── README.md
│     ├── Netflix_EDA.sql
│     └── Screenshots/
│       ├── Churned by Age-Bracket.png
│       ├── Churned by Device.png
│       ├── Duplicate.png
│       └── Subs-Type.png
│
├── Excel/
│     ├── README.md
│     ├── Netflix_Churn.xlsx
│     └── Screenshots
│       ├── Dashboard.png
│       ├── Pivot Tables.png
│       └── Summary.png
│
└── PowerBI/
      ├── README.md
      ├── Churned Analysis.pbix
      └── Screenshots/
         ├── Dashboard.png
         └── Summary.png
```

**Project Structure**
**MySQL**

The MySQL folder contains SQL-based exploratory data analysis used to validate data quality and uncover churn-related patterns.

SQL scripts for aggregation and churn analysis

Screenshot evidence of query results, including churn by age bracket, device type, and subscription plan

Identification of duplicates and data consistency checks


**Excel**

The Excel folder focuses on data summarization and dashboard development.

Pivot tables used to analyze churn across multiple dimensions

An interactive dashboard highlighting churn rate, customer segments, and usage patterns

Summary sheets consolidating key findings


**Power BI**

The Power BI folder is intended for advanced data modeling and interactive visual reporting.

Data modeling and relationships for accurate filtering

DAX measures for churn rate and key performance indicators

Visual analysis of churn by age group, subscription plan, device usage, and genre preference

Consolidated view of high-risk customer segments

The Power BI report provides an integrated and interactive perspective of churn drivers.


**Key Analysis Areas**

Overall churn rate assessment

Churn distribution by age group

Subscription plan comparison

Device usage impact on churn

Genre preference and churn relationship


**Dataset**

File: netflix_customer_churn.csv

Description: Contains customer-level subscription data, including demographic attributes, device usage, subscription plans, genre preferences, and churn indicators.
