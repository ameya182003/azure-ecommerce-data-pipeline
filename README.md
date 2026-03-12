# End-to-End Azure Data Engineering Pipeline for Brazilian E-Commerce Dataset

## 📌 Project Overview
This project demonstrates an **end-to-end Azure Data Engineering pipeline** built using **PySpark and Azure services** to process the Brazilian E-commerce dataset.

The pipeline ingests data from **HTTP and MongoDB sources**, processes it using **Azure Databricks**, and stores transformed data in **Azure Data Lake Storage Gen2** before loading it into **Azure Synapse Analytics**.

---

## 🏗️ Architecture Diagram

![Architecture Diagram](Architecture%20Diagram.png)

---

## 📂 Dataset

Dataset: **Brazilian E-commerce Public Dataset (Kaggle)**  
Total datasets used: **8**

### Data Sources

**HTTP Source (Kaggle) – 7 datasets**
- customers
- orders
- order_items
- products
- sellers
- geolocation
- reviews

**MongoDB Source – 1 dataset**

The **order_payments dataset** was uploaded to **MongoDB using files.io** and ingested using a **MongoDB connection**.

---

## 🔄 Data Pipeline Workflow

1. **Data Sources**
   - Kaggle datasets via **HTTP**
   - Payments dataset via **MongoDB**

2. **Data Ingestion**
   - Ingested using **Azure Data Factory**

3. **Raw Data Storage**
   - Stored in **Azure Data Lake Storage Gen2**

4. **Data Transformation**
   - Processed using **PySpark in Azure Databricks**

5. **Transformed Data Storage**
   - Written back to **ADLS Gen2**

6. **Data Warehouse**
   - Loaded into **Azure Synapse Analytics**

---

## 🏗️ Project Architecture

The pipeline follows the **Medallion Architecture** approach.

### Bronze Layer
- Raw data is ingested into **Azure Data Lake Storage**
- Data is stored without transformation

### Silver Layer
- Data cleaning and transformation are performed using **PySpark in Azure Databricks**
- Data quality issues are handled

### Gold Layer
- Business-level aggregated data is created
- Final datasets are prepared for analytics and reporting

---

## 🛠️ Tech Stack

**Programming**
- Python
- PySpark

**Azure Services**
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- Azure Synapse Analytics

**Database**
- MongoDB

**Processing**
- SQL
- Delta Lake

---

## 📈 Key Learnings
- Building **end-to-end Azure data pipelines**
- Data ingestion from **HTTP and MongoDB**
- Processing large datasets using **PySpark**
- Implementing **Medallion Architecture**
- Orchestrating pipelines with **Azure Data Factory**
- Integrating **Databricks, ADLS, and Synapse**
