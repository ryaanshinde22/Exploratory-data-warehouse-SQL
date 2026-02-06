# Exploratory-data-warehouse-SQL Project
Built a SQL based Data Warehouse using the Bronze–Silver–Gold architecture. Performed data cleaning, transformation, and Exploratory Data Analysis (EDA) to generate business-ready insights using advanced SQL queries.
# Data Warehouse & Analytics Project

## Overview

This repository contains an **end-to-end Data Warehouse and Analytics project** developed to understand and apply modern data engineering and analytics concepts in a practical way. The project focuses on designing a structured data warehouse, implementing ETL pipelines, and enabling analytical reporting using clean, well-modeled data.

The solution is based on the **Medallion Architecture (Bronze, Silver, Gold)** and uses **SQL Server** as the core database platform. The goal of this project is learning-by-building: applying best practices used in real analytics systems while strengthening foundational and intermediate data engineering skills.

---

## 🏗️ Data Architecture

The data platform follows the **Medallion Architecture**, which separates data into logical layers to improve data quality, maintainability, and analytical usability.

![Data Architecture](docs/data_architecture.png)

### 🔹 Bronze Layer — Raw Data

* Stores **raw data exactly as received** from source systems
* Source format: **CSV files**
* Data ingested into **SQL Server** without transformation
* Serves as a historical record and reprocessing source

### 🔹 Silver Layer — Cleaned & Standardized Data

* Focuses on **data cleansing and transformation**
* Includes:

  * Data type standardization
  * Handling missing or invalid values
  * Removing duplicates
  * Applying consistent naming conventions
* Produces reliable datasets ready for analytical modeling

### 🔹 Gold Layer — Analytics-Ready Data

* Contains **business-level, analytics-ready datasets**
* Data modeled using a **Star Schema**
* Includes fact and dimension tables designed for:

  * Aggregations
  * Trend analysis
  * Reporting and dashboards

---

## 📖 Project Components

### 1️⃣ Data Architecture Design

* Designed a layered data warehouse using Medallion Architecture principles
* Clearly separated raw, refined, and analytics-ready data
* Focused on clarity, scalability, and ease of analysis

### 2️⃣ ETL Pipelines

* Implemented ETL workflows to move data across Bronze → Silver → Gold layers
* Applied transformation logic using **SQL Server**
* Ensured data consistency and correctness at each stage

### 3️⃣ Data Modeling

* Built **fact and dimension tables** following dimensional modeling concepts
* Optimized schema structure for analytical queries
* Enabled efficient joins and aggregations

### 4️⃣ Analytics & Reporting

* Developed **SQL-based analytical queries**
* Enabled insight generation such as:

  * Performance trends
  * Summary metrics
  * Data-driven observations
* Structured data for easy integration with BI tools

---

## 🛠️ Tools & Technologies

* SQL Server
* SQL (DDL, DML, analytical queries)
* CSV data sources
* Dimensional Modeling (Star Schema)
* Medallion Architecture concepts

---

## 🎯 Learning Objectives

This project was created to:

* Practice designing a structured data warehouse
* Understand data flow across multiple transformation layers
* Apply data modeling concepts in a real dataset
* Strengthen SQL skills for analytics and reporting

---

## 📌 Possible Enhancements

* Automating pipelines using orchestration tools
* Adding incremental data loading
* Implementing data validation and quality checks
* Connecting BI dashboards (Power BI / Tableau)
* Extending the solution to a cloud data platform

---

This project serves as a **hands-on learning implementation** of modern data warehousing and analytics concepts, emphasizing clarity, structure, and practical understanding.
