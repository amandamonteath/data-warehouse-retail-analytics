# 🏪 Data Warehouse Design & Implementation — Retail Sales Analytics

## 📌 Overview
Designed and implemented an end-to-end data warehouse solution for retail sales analytics,
covering database schema design, ETL pipeline development, and BI reporting dashboards.

## 🛠️ Tools & Technologies
- **Database:** MySQL
- **ETL:** KNIME Analytics Platform
- **Schema Design:** OLTP & Star Schema (Dimensional Modelling)
- **Reporting:** Dashboard visualisation

## 📐 Architecture
- **OLTP Schema:** 5 normalised tables — Store, Product, Employee, Discount, Order
- **Data Warehouse Schema:** Star architecture with `fact_sales` table and 5 dimension tables
- **ETL Workflows:** 3 pipelines built in KNIME to load and transform data

## 📊 Key Features
- SQL views for BI queries (e.g. top-performing product categories by revenue)
- Sales trend dashboards and product performance reporting

## 🎯 Outcomes
- Delivered a fully functional DW pipeline from raw data to business-ready insights
- Demonstrated end-to-end BI workflow: schema design → ETL → reporting

## 📁 Repository Structure
├── schema/ # OLTP and DW schema diagrams
├── etl/ # KNIME workflows
├── sql/ # SQL views and queries
├── dashboards/ # Dashboard screenshots
└── README.md
