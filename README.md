# Azure End-to-End Data Engineering Project 🌟

This repository contains a comprehensive Azure Data Engineering project that demonstrates real-world data handling and processing workflows using Azure Data Factory, Databricks, PySpark, Delta Lake, and Power BI.

## 🚀 Overview

This project is centered around ingesting, transforming, and visualizing the **2023 New York Taxi dataset** using cutting-edge cloud technologies.

### Key Steps:
1. **Dynamic Data Ingestion**:  
   - Pulled data using APIs with Azure Data Factory's dynamic pipelines.
   - Configured parameterized datasets and loops for efficient ingestion.
   - ![Screenshot (125)](https://github.com/user-attachments/assets/7c100c11-97e9-4d0b-a9f0-3030d6c5d6e4)


2. **Data Transformation**:  
   - Processed data in Databricks using PySpark.  
   - Applied the Medallion Architecture to store data in **Bronze**, **Silver**, and **Gold** layers.

3. **Delta Lake Integration**:  
   - Leveraged Delta Lake for efficient data storage, querying, and versioning.

4. **Visualization**:  
   - Connected Power BI to Delta Lake and designed dashboards to analyze key trends in taxi data.

---

## 📂 Repository Structure
- `azure-data-factory/`: JSON files for pipelines, parameterized datasets, and triggers.
- `databricks-notebooks/`: PySpark scripts and SQL queries for data transformations and Delta Lake queries.
- `data-lake-structure/`: Sample data files for each storage layer.
- `power-bi/`: Power BI dashboard file.
- `docs/`: Documentation for setup, usage, and detailed guides.

---

## 🛠️ Technologies Used
- **Azure Data Factory**: For dynamic pipelines and data ingestion.
- **Databricks**: For data transformation and processing.
- **Delta Lake**: For scalable and efficient data storage.
- **Azure Data Lake**: To store data in Bronze, Silver, and Gold layers.
- **Power BI**: For building interactive dashboards.

---

## 📝 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/azure-data-engineering-project.git
   cd azure-data-engineering-project

