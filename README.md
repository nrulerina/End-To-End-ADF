# 📊 Azure End-to-End Data Engineering Project

<p align="center">
  <img src="img/1.png" alt="Azure Data Engineering Project Diagram" width="700"/>
</p>

## 🚀 Project Overview

This project simulates a real-time business scenario and demonstrates how to build a complete data engineering pipeline on Azure. It extracts customer and sales data from an on-prem SQL database, processes it in the cloud, and visualizes insights through a Power BI dashboard.

## 🎯 Business Goal

The goal is to understand customer demographics especially gender and how they impact product sales.

### Key Requirements:
- **Sales by Customer Title (Mr, Mrs, Sra) & Product Category**
- **Interactive Filtering** by category and customer title (Mr, Mrs, Sra)
- **User-Friendly Dashboard** for stakeholders

## 🛠️ Solution Summary

### 1. **Data Ingestion**
- Extract data from SQL Server
- Load into **Azure Data Lake Storage (ADLS)** via **Azure Data Factory (ADF)**

### 2. **Data Transformation**
- Clean & transform data using **Azure Databricks**
- Apply **Bronze → Silver → Gold** data layering

### 3. **Data Loading & Reporting**
- Load final data into **Azure Synapse Analytics**
- Build an interactive **Power BI Dashboard**

### 4. **Automation & Monitoring**
- Schedule pipelines to run **daily**
- Monitor pipelines using ADF & Synapse tools

### 5. **Security**
- Manage secrets using **Azure Key Vault**
- Apply **RBAC** with **Azure Entra ID**

## 🧰 Tech Stack

| Tool                  | Purpose                          |
|-----------------------|----------------------------------|
| Azure Data Factory    | Data orchestration               |
| Azure Data Lake       | Raw & processed data storage     |
| Azure Databricks      | Data transformation              |
| Azure Synapse         | Data warehousing & analytics     |
| Power BI              | Data visualization               |
| Azure Key Vault       | Secret management                |
| SQL Server (On-Prem)  | Source database                  |

## 📈 Power BI Dashboard

The dashboard displays:
- ✅ Total products sold  
- 💰 Total sales revenue  
- 👥 Gender distribution  
- 🎯 Filters for product category and customer title (Mr, Mrs, Sra)

---

📚 *This project was created as part of my learning journey in cloud data engineering by following a YouTube tutorial.*
