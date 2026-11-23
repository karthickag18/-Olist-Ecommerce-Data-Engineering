# Olist E-Commerce End-to-End Data Engineering Project

## Project Overview
Developed an end-to-end data engineering pipeline using Microsoft Azure to process and transform Brazilian Olist E-Commerce data.

The project follows the Medallion Architecture (Bronze, Silver, and Gold) to convert raw datasets into clean, structured, and analytics-ready data.

## Technologies Used
- Microsoft Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Synapse Analytics
- Apache Spark
- PySpark
- Python
- GitHub

## Architecture

```text
Olist Raw Dataset
       |
       v
Azure Data Lake Storage
       |
       v
  Bronze Layer
   (Raw Data)
       |
       v
Azure Synapse + PySpark
       |
       v
  Silver Layer
 (Cleaned Data)
       |
       v
  Gold Layer
(Aggregated Data)
       |
       v
Business Analytics
```

## Project Workflow

1. Ingested Olist E-Commerce datasets into Azure Data Lake Storage Gen2.
2. Organized raw data in the Bronze layer.
3. Used PySpark in Azure Synapse notebooks for data cleaning and transformation.
4. Stored processed datasets in the Silver layer.
5. Created business-oriented analytical datasets in the Gold layer.
6. Used Azure Data Factory to orchestrate notebook execution.

## Data Analysis

The Gold layer contains analytical datasets covering:
- Customer Analysis
- Order Analysis
- Product Analysis
- Payment Analysis
- Delivery Analysis
- Category Analysis
- Seller Analysis

## Repository Structure

```text
Olist-Ecommerce-Data-Engineering/
│
├── notebooks/
│   ├── notebook_1
│   ├── notebook_2
│   ├── notebook_3
│   └── notebook_4
│
├── screenshots/
│
├── documentation/
│   └── architecture.md
│
└── README.md
```

## Key Learning Outcomes

- Built an Azure-based data engineering workflow.
- Implemented Bronze, Silver, and Gold data layers.
- Performed distributed data transformations using PySpark.
- Worked with Azure Data Factory pipeline orchestration.
- Organized analytical outputs in cloud storage.

## Author
Karthick Ayyappan

M.Sc Computer Science | Aspiring Data Engineer
