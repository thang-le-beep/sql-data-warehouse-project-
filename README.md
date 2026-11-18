# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse from scratch to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
* **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
* **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
* **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
* **Scope:** Focus on the latest dataset only; historization of data is not required.
* **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analytics)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
* **Customer Behavior:** Understand purchasing patterns, lifetime value, and segmentation.
* **Product Performance:** Identify top-selling products, category performance, and profit margins.
* **Sales Trends:** Track monthly and yearly revenue growth to uncover seasonal trends.

---

## Architecture & Layers (Medallion Architecture)
* **Bronze Layer:** Stores raw, unprocessed data as-is directly from source systems (`Full Load`).
* **Silver Layer:** Cleansed, standardized, and integrated data ready for transformation.
* **Gold Layer:** Business-ready data modeled using Dimensional Modeling (`Star Schema`) to power analytics and reporting tools.

---

## Tech Stack & Tools
* **Database Management System:** Microsoft SQL Server (SSMS)
* **Version Control:** Git & GitHub
* **Language:** T-SQL
