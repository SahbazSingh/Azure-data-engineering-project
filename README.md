# Azure Data Engineering End-To-End Project  
**Technologies Used:** Azure Data Factory | Azure Data Lake | Azure Databricks | PySpark | Azure Synapse Analytics  

This project demonstrates the development of an **end-to-end data engineering pipeline** on Microsoft Azure, leveraging modern cloud tools and technologies to ingest, transform, and analyze data efficiently.

---

## 🔍 What You’ll Learn

✅ How to design and implement robust ETL pipelines using **Azure Data Factory**  
✅ Performing data transformations with **Azure Databricks** using **PySpark**  
✅ Building analytical data models and views in **Azure Synapse Analytics**  
✅ Understanding real-world Azure project architecture  

---

## 🏗️ Architecture Overview

The project follows the **Bronze → Silver → Gold** data lake architecture:

1. **Bronze Layer** (Raw Data Ingestion)  
   - Data is ingested from a public GitHub repo using Azure Data Factory  
   - Stored in Azure Data Lake Gen2  

2. **Silver Layer** (Cleaned & Transformed)  
   - PySpark transformations are applied using Azure Databricks  
   - Transformed data is written back to the data lake  

3. **Gold Layer** (Analytics & Reporting)  
   - Final views are created in Azure Synapse Analytics using `OPENROWSET`  
   - Data is ready for BI tools like Power BI  

---

## 📂 Data Source

- **Original Dataset:** [Kaggle – AdventureWorks Dataset](https://www.kaggle.com/datasets/ukveteran/adventure-works)

---

## 🧠 Topics Covered

- Azure Resource Provisioning (Data Factory, Storage, Databricks, Synapse)  
- Data Lake Gen2 Storage Structure  
- Ingestion Pipelines with Azure Data Factory  
- PySpark Transformations in Azure Databricks  
- View Creation in Azure Synapse using `OPENROWSET`  
- Layered Data Architecture: Bronze → Silver → Gold  

---
