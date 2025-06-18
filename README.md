# Azure-Data-Pipeline-Project

This repository contains assets for an **Azure Data Pipeline Project** that integrates various Azure services to build a robust data engineering workflow.  

## 📌 Project Overview  
This project demonstrates an **end-to-end data pipeline** that:  
- Extracts data from SQL sources.  
- Ingests data into **Azure Data Lake Storage (ADLS)** (Bronze layer).  
- Processes and transforms data in **Azure Databricks** (Silver and Gold layers).  
- Stores processed data back into ADLS or other destinations.  

Technologies used:  
- **Azure Data Factory (ADF)** — Orchestration & pipeline control  
- **Azure Data Lake Storage (ADLS)** — Data storage  
- **Azure Databricks** — Data transformation  
- **GitHub** — Source control  

---

## 💻 Repository Structure  

## 🚀 Pipeline Flow  

1️⃣ **Extract**:  
   - Use ADF to pull data from SQL database.  

2️⃣ **Load (Bronze Layer)**:  
   - Save raw data into ADLS in the Bronze layer.

3️⃣ **Transform (Silver Layer)**:  
   - Use Databricks notebooks for cleansing and basic transformation.  

4️⃣ **Enrich (Gold Layer)**:  
   - Join, and create business-ready data sets.

5️⃣ **Store / Publish**:  
   - Save enriched data to ADLS or target systems.  

---

## 🔗 Related Azure Resources  

- Azure Data Factory  
- Azure Data Lake Storage Gen2  
- Azure Databricks  
- Azure SQL Database  

---

## 📝 How to Use  

👉 Clone the repository:
```bash
git clone https://github.com/anisdumilah/Azure-Data-Pipeline-Project.git
👉 Open notebooks in Databricks.
👉 Import ADF pipeline JSONs into your ADF instance.

