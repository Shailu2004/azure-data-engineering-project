# Azure End-to-End Data Engineering Project 🌟

This repository contains a comprehensive Azure Data Engineering project that demonstrates real-world data handling and processing workflows using Azure Data Factory, Databricks, PySpark, Delta Lake, and Power BI.

## 🚀 Overview
This project is centered around ingesting, transforming, and visualizing the **2023 New York Taxi dataset** using cutting-edge cloud technologies.

### Key Steps:
1. **Dynamic Data Ingestion**:  
   - Pulled data using APIs with Azure Data Factory's dynamic pipelines.
   - Configured parameterized datasets and loops for efficient ingestion.
   -![Screenshot 2025-01-07 224016](https://github.com/user-attachments/assets/97faa2e3-574a-45c8-9e28-738295d468d2)
   - ![Screenshot 2025-01-07 224128](https://github.com/user-attachments/assets/6267f06a-4f6b-467e-b4ac-429e82fa0d03)


2. **Data Transformation**:  
   - Processed data in Databricks using PySpark.  
   - Applied the Medallion Architecture to store data in **Bronze**, **Silver**, and **Gold** layers.
   - ![Screenshot 2025-01-07 223641](https://github.com/user-attachments/assets/fea9d06c-1cbb-4692-b019-b0132c4038b2)
   - ![Screenshot 2025-01-07 223720](https://github.com/user-attachments/assets/60f3461f-3adc-4e20-b850-56b9ef8488ac)


3. **Delta Lake Integration**:  
   - Leveraged Delta Lake for efficient data storage, querying, and versioning.
   - ![Screenshot 2025-01-07 224424](https://github.com/user-attachments/assets/f9fb9b03-ad0f-4c4c-88d3-03d39859a014)
   - 

4. **Visualization**:  
   - Connected Power BI to Delta Lake and designed dashboards to analyze key trends in taxi data.
   - ![1_DlTsSQ1frNRg02DttY88Rw](https://github.com/user-attachments/assets/413bf151-c00a-47ac-8f68-dae5d84f2ce4)

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
   git clone https://github.com/Shailu2004/azure-data-engineering-project.git
   cd azure-data-engineering-project

