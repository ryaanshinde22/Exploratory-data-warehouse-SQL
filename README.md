# Exploratory-data-warehouse-SQL Project
Built a SQL based Data Warehouse using the Bronze–Silver–Gold architecture. Performed data cleaning, transformation, and Exploratory Data Analysis (EDA) to generate business-ready insights using advanced SQL queries.
# Data Warehouse & Analytics Project

# Data Warehouse & Analytics Project

## Overview

This repository contains an **end-to-end Data Warehouse and Analytics project** developed to understand and apply modern data engineering and analytics concepts in a practical way. The project focuses on designing a structured data warehouse, implementing ETL pipelines, and enabling analytical reporting using clean, well-modeled data.

The solution is based on the **Medallion Architecture (Bronze, Silver, Gold)** and uses **SQL Server** as the core database platform. The goal of this project is learning-by-building: applying best practices used in real analytics systems while strengthening foundational and intermediate data engineering skills.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

#### Objective

Design and implement a **modern data warehouse using SQL Server** to consolidate sales data from multiple source systems and prepare it for analytical reporting.

#### Specifications

* **Data Sources**: Ingest data from two operational systems—**ERP** and **CRM**—provided as CSV files.
* **Data Quality**: Identify, clean, and resolve data quality issues (missing values, duplicates, inconsistencies) before analysis.
* **Integration**: Integrate both source systems into a **single, consistent analytical data model** optimized for querying and reporting.
* **Scope**: Work only with the **latest available dataset**; historization and slowly changing dimensions are out of scope.
* **Documentation**: Maintain clear and structured documentation of the data architecture and data models to support both business users and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective

Develop **SQL-based analytical queries** to generate insights related to:

* **Customer Behavior**
* **Product Performance**
* **Sales Trends**

The resulting metrics and summaries are intended to support data-driven understanding of business performance.

For detailed functional and analytical requirements, see: `docs/requirements.md`.

---

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                           # Raw source datasets (ERP and CRM CSV files)
│
├── docs/                               # Project documentation and design artifacts
│   ├── etl.drawio                      # ETL techniques, logic, and workflow diagrams
│   ├── data_architecture.drawio        # Overall data warehouse architecture
│   ├── data_catalog.md                 # Dataset catalog with field definitions and metadata
│   ├── data_flow.drawio                # End-to-end data flow diagram
│   ├── data_models.drawio              # Dimensional data models (star schema)
│   ├── naming-conventions.md           # Naming standards for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Raw data extraction and loading scripts
│   ├── silver/                         # Data cleansing and transformation scripts
│   ├── gold/                           # Analytics-ready models and views
│
├── tests/                              # Data validation and quality check scripts
│
├── README.md                           # Project overview and usage instructions
├── LICENSE                             # License information
├── .gitignore                          # Git ignore rules
└── requirements.txt                    # Project dependencies and requirements
```

---

## 🛡️ License

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this project with appropriate attribution. The license details can be found in the `LICENSE` file.
