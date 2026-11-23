# Olist E-Commerce Data Engineering Architecture

## 1. Project Overview
This project implements an end-to-end cloud data engineering solution using Microsoft Azure services and PySpark to process Brazilian e-commerce data.

## 2. Architecture

The project follows the Medallion Architecture.

### Bronze Layer – Raw Data
- Stores original Olist datasets in Azure Data Lake Storage Gen2.
- Maintains raw source data for further processing.

### Silver Layer – Data Transformation
- Processes raw data using Azure Synapse Analytics.
- Performs data cleaning and transformation using PySpark.
- Standardizes datasets for analytical processing.

### Gold Layer – Business Analytics
- Creates aggregated datasets for business analysis.
- Generates 13 analytical outputs covering customers, products, revenue, payments and delivery performance.
- Stores analytical results in Parquet format.

## 3. Azure Services Used

| Service | Purpose |
|---|---|
| Azure Data Lake Storage Gen2 | Cloud data storage |
| Azure Synapse Analytics | PySpark processing |
| Apache Spark | Distributed data processing |
| PySpark | Data cleaning and transformation |

## 4. Data Flow

Raw Olist datasets → Bronze → Silver → Gold → Business Analytics

Each notebook is executed individually in Synapse Studio.

## 5. Gold Layer Datasets

1. Category Analysis
2. Customer Analysis
3. Delivery Analysis
4. Delivery Performance
5. Delivery Summary
6. Installment Analysis
7. Monthly Delivery Analysis
8. Monthly Payment Analysis
9. Payment Method Analysis
10. Product Analysis
11. Revenue Analysis
12. State Customer Analysis
13. Top Products

## 6. Project Outcomes

- Implemented a cloud-based data lake architecture.
- Processed e-commerce data using PySpark.
- Created 13 analytical datasets.
- Organized data into Bronze, Silver and Gold layers.
- Prepared data for business intelligence and reporting.
