# 📊 End-to-End Customer Behavior & Trends Analysis Portfolio Project

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

An end-to-end data analytics project uncovering customer purchasing patterns, segmenting consumer behavior, and identifying key revenue drivers using **Python**, **SQL**, and an interactive **Power BI** dashboard.

---

## 📌 Executive Summary
Understanding customer purchasing drivers and churn triggers is vital for optimizing marketing spend and product merchandising. This project analyzes multi-dimensional customer transaction data to address critical business questions:
* What demographic factors correlate highest with lifetime purchase value?
* Which product categories and seasonal trends drive the highest revenue?
* How can customer segmentation optimize loyalty and promotional campaigns?

---

## 🛠️ Tech Stack & Tools
* **Data Processing & EDA:** Python (`pandas`, `numpy`, `matplotlib`, `seaborn`)
* **Database & Querying:** SQL (PostgreSQL / MySQL) — CTEs, Window Functions, Aggregate Joins
* **Business Intelligence:** Microsoft Power BI (DAX, Power Query, Dynamic Dashboards)
* **Environment:** Jupyter Notebook, VS Code, Git

---

## 📂 Repository Structure
```text
├── data/
│   ├── raw_customer_data.csv          # Raw transactional data
│   └── cleaned_customer_data.csv      # Processed dataset
├── sql/
│   ├── schema_setup.sql               # Database DDL
│   └── business_analysis_queries.sql  # SQL queries answering key business questions
├── notebooks/
│   └── customer_behavior_eda.ipynb    # Python EDA, data cleansing & statistical analysis
├── power_bi/
│   └── customer_insights_dashboard.pbix # Interactive Power BI report file
├── assets/
│   └── dashboard_overview.png         # Report screenshots
└── README.md
