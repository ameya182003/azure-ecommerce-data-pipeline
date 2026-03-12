# End-to-End Azure Data Engineering Pipeline for Brazilian E-Commerce Dataset

## 📌 Project Overview
This project demonstrates an **end-to-end Data Engineering pipeline built on Microsoft Azure using PySpark** to process and analyze the Brazilian E-Commerce dataset.

The pipeline ingests raw data, stores it in **Azure Data Lake Storage**, performs distributed data transformations using **PySpark in Azure Databricks**, and organizes data using the **Medallion Architecture (Bronze, Silver, Gold layers)** for efficient analytics.

This project showcases practical data engineering concepts such as **data ingestion, ETL pipelines, distributed data processing, and cloud-based data storage**.

---

## 🛠️ Tech Stack

### Programming
- Python
- PySpark

### Cloud Platform
- Microsoft Azure

### Azure Services
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks

### Data Processing
- SQL
- Delta Lake

---

## 📂 Dataset
The dataset used in this project is the **Brazilian E-Commerce Public Dataset**, which contains real-world transactional data from an online marketplace.

The dataset includes multiple tables such as:

- Customers  
- Orders  
- Order Items  
- Payments  
- Products  
- Sellers  
- Reviews  
- Geolocation  

This dataset is widely used for **data analytics and data engineering practice**.

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

## 🔄 Data Pipeline Workflow

1. Upload raw dataset to **Azure Data Lake Storage Gen2**
2. Use **Azure Data Factory** to orchestrate the data pipeline
3. Transform data using **PySpark in Azure Databricks**
4. Store processed data in **Delta Lake tables**
5. Prepare final datasets for analytics

---

## 📊 Key Features
- End-to-end **Azure Data Engineering pipeline**
- Distributed data processing using **PySpark**
- Implementation of **Medallion Architecture**
- Scalable cloud data storage using **Azure Data Lake**
- Data transformation using **Delta Lake**

---

## 📈 Key Learnings

Through this project I learned:

- Building **end-to-end data pipelines on Azure**
- Processing large datasets using **PySpark**
- Implementing **ETL workflows**
- Using **Azure Data Factory for orchestration**
- Organizing data using **Bronze, Silver, Gold architecture**
- Managing data with **Delta Lake**

---

## 🚀 Future Improvements

- Implement **real-time data ingestion**
- Add **data quality validation checks**
- Build **Power BI dashboards**
- Implement pipeline monitoring and logging

---

## 👤 Author

**Ameya Prakash Modak**  
Final Year Computer Science Engineering (Data Science) Student  

Interested in **Data Engineering, Data Analytics, and Machine Learning**

---

## 📚 Acknowledgement

This project was implemented as part of a **learning exercise inspired by a Data Engineering course**.
