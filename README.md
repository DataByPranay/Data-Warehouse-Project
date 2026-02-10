# 🏢 Data-Warehouse-Project

Building a **modern data warehouse using SQL Server**, implementing **data modeling, ETL workflows**, and creating **reporting-ready datasets** for analytics.

Welcome to the **Data Warehouse & Analytics Project** repository!  
This project demonstrates an **end-to-end data warehousing solution**, from raw data ingestion to analytics-ready datasets, following **industry best practices in data engineering**.

---

## 📖 Project Overview

This portfolio project showcases how to design and implement a **scalable data warehouse** that supports analytical reporting and business decision-making.

The project covers:
- Modern **data architecture design**
- Robust **ETL pipelines**
- Analytical **data modeling**
- Reporting-ready datasets for **analytics & dashboards**

---

## 🏗️ Data Architecture

The data architecture follows the **Medallion Architecture** pattern with **Bronze, Silver, and Gold layers**.

![Data Architecture](https://github.com/user-attachments/assets/cb7a8d52-36db-4d3c-827a-0f9a51f202a9)

### 🔹 Bronze Layer
- Stores **raw data** ingested directly from source systems
- Data is loaded **as-is** from CSV files into SQL Server
- Acts as the single source of truth for raw data

### 🔹 Silver Layer
- Performs **data cleansing, standardization, and normalization**
- Handles data quality issues and prepares data for transformation
- Creates structured, reliable datasets for analytics

### 🔹 Gold Layer
- Contains **business-ready data**
- Modeled using a **star schema** (fact & dimension tables)
- Optimized for **reporting and analytical queries**

---

## 🔄 Project Components

### 1️⃣ Data Architecture
- Designed a **Modern Data Warehouse** using Medallion Architecture
- Clear separation of raw, refined, and analytics-ready data

### 2️⃣ ETL Pipelines
- Extract data from multiple source systems
- Transform data to resolve quality and consistency issues
- Load transformed data into analytical models

### 3️⃣ Data Modeling
- Developed **fact and dimension tables**
- Optimized schema for fast analytical queries
- Designed to support reporting and BI tools

### 4️⃣ Analytics & Reporting
- Created **SQL-based analytical datasets**
- Enabled insights for sales and business performance
- Ready for integration with BI dashboards

---

## 🚀 Project Requirements

### 🎯 Objective
Develop a **modern data warehouse using SQL Server** to consolidate sales data, enabling **analytical reporting** and **data-driven decision-making**.

---

### 📌 Specifications

1. **Data Sources**
   - Two source systems: **ERP** and **CRM**
   - Data provided in **CSV file format**

2. **Data Quality**
   - Cleanse and resolve data quality issues
   - Ensure consistency before analysis

3. **Data Integration**
   - Merge both source systems into a **single analytical data model**
   - Designed for ease of querying and reporting

4. **Scope**
   - Focus on the **latest dataset only**
   - No historization or slowly changing dimensions required

5. **Documentation**
   - Clear documentation of:
     - Data architecture
     - Data model
     - ETL process
   - Supports both **business stakeholders** and **analytics teams**

---

## 🛠️ Tools & Technologies
- SQL Server
- SQL (T-SQL)
- CSV Data Sources
- Data Warehousing Concepts
- Star Schema Modeling

---

