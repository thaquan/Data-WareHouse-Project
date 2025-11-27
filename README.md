# 📊 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project**! 🚀

This repository showcases a complete end-to-end data warehousing and analytics solution — from raw data ingestion to business-ready dashboards. 
Designed as a portfolio project, it demonstrates industry-standard practices in Data Engineering, Data Modeling, and Analytics.

## 🏗️ Data Architecture (Medallion Architecture)

This project follows the Medallion Architecture with three structured layers:

### 🥉 Bronze Layer – Raw Data
- Stores data exactly as received from source systems
- Data ingested from CSV files (ERP & CRM systems) → SQL Server

### 🥈 Silver Layer – Cleaned Data
- Performs data cleansing, standardization, and normalization
- Prepares data for downstream analytical modeling

### 🥇 Gold Layer – Business-Ready Data
- Contains Star Schema models (Fact + Dimensions)
- Optimized for BI, reporting, and advanced analytics

You can view the design in `docs/data_architecture.drawio`.

## 📖 Project Overview

This project includes:

- ✔️ **Data Architecture**: Designing a modern Data Warehouse using Medallion Architecture
- ✔️ **ETL Pipelines**: Extracting, transforming, and loading data from raw CSV files (Implemented in SQL: Bronze → Silver → Gold)
- ✔️ **Data Modeling**: Building Fact and Dimension tables for analytics workloads and creating a clean, intuitive model for business users
- ✔️ **Analytics & Reporting**: Writing SQL queries to generate business insights:
  - Customer behavior analysis
  - Product performance
  - Sales trends

## 🎯 Built For

This project is ideal for showcasing skills in:

- SQL Development
- Data Engineering
- Data Architecture
- ETL Pipeline Development
- Data Modeling
- Business Intelligence & Reporting

Perfect for students or professionals building a data engineering portfolio. 

## 🛠️ Tools & Resources (All Free)

- **Datasets**: CSV files
- **SQL Server Express**: Database engine
- **SSMS** (SQL Server Management Studio): Database GUI
- **GitHub**: Version control
- **DrawIO**: Architecture, models & diagram design
- **Notion Template**: Project planning
- **Notion Project Steps**: All tasks & project phases

## 🚀 Project Requirements

### 📌 1. Data Warehouse (Data Engineering)

**Objective:**
Build a modern SQL Server–based data warehouse to consolidate sales data and support analytics. 

**Specifications:**
- Import from two sources: ERP & CRM
- Clean and resolve data quality issues
- Integrate sources into a unified analytical model
- Work with the latest dataset only (no historization)
- Provide full documentation for business & analytics teams

### 📌 2. Analytics & Reporting (Data Analysis)

**Goal:**
Develop SQL-based analytics to generate insights into:
- Customer behavior
- Product performance
- Sales trends

These insights support strategic decision-making for stakeholders.

More details available in `docs/requirements.md`.

## 📂 Repository Structure

```
data-warehouse-project/
│
├── datasets/                         # Raw datasets (ERP & CRM)
│
├── docs/                             # Project documentation & diagrams
│   ├── etl. drawio                    # ETL architecture and techniques
│   ├── data_architecture.drawio      # Overall project architecture
│   ├── data_catalog.md               # Dataset descriptions & metadata
│   ├── data_flow.drawio              # Data flow diagram
│   ├── data_models.drawio            # Star schema modeling
│   └── naming-conventions.md         # Naming standards & guidelines
│
├── scripts/                          # SQL scripts for ETL
│   ├── bronze/                       # Load raw data
│   ├── silver/                       # Clean & transform data
│   └── gold/                         # Build analytical models
│
├── tests/                            # Data quality checks & validation
│
├── README.md                         # Project overview (this file)
├── LICENSE                           # Repository license
├── .gitignore                        # Git ignore rules
└── requirements.txt                  # Project dependencies
```

## 🚀 Getting Started

1. Clone the repository
2. Set up SQL Server Express and SSMS
3. Import datasets from the `datasets/` folder
4. Run SQL scripts in order: Bronze → Silver → Gold
5.  Explore analytics queries in the `scripts/gold/` folder



---

