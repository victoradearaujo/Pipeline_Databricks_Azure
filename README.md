# 🏗️ Data Engineering Pipeline with Azure and Databricks

This project demonstrates the development of a complete data engineering pipeline using **Microsoft Azure** integrated with **Databricks**, focusing on data ingestion, transformation, and orchestration for real estate data.

## 🚀 Technologies Used

- **Microsoft Azure**
  - Azure Data Lake Storage Gen2
  - Azure Data Factory
  - Azure Active Directory
- **Databricks**
  - Apache Spark
  - Notebooks in **Scala**
- **GitHub** (for version control and integration)

## 📌 Project Objective

The goal of this project is to develop a scalable and automated pipeline to process real estate data. The data is ingested and organized into a multi-layer **Data Lake**, transformed using **Spark** on **Databricks**, and orchestrated through **Azure Data Factory**.

## 🧱 Data Lake Structure

The Data Lake is structured into three layers:

- `Inbound`: Raw incoming data.
- `Bronze`: Initial data processing and basic cleaning.
- `Silver`: Refined and structured data ready for analytics.

<p align="center">
  <img src="assets/data-lake-structure.png" alt="Data Lake Structure" width="600"/>
</p>

## 🔧 Project Steps

1. **Provision and configure resources on Azure**
2. **Create and structure the Data Lake (Gen2)**
3. **Configure app registration and permissions**
4. **Set up and integrate Databricks environment**
5. **Develop Scala notebooks with Spark transformations**
6. **Build and test Bronze and Silver data layers**
7. **Create and configure Azure Data Factory pipelines**
8. **Set up scheduled triggers for automation**

## 📂 Data Organization

<p align="center">
  <img src="assets/data-organization.png" alt="Data Organization Flow" width="600"/>
</p>

## 🔄 Orchestration

Pipeline execution is fully automated using **Azure Data Factory**, with time-based **triggers** defined according to business requirements.

<p align="center">
  <img src="assets/data-factory-pipeline.png" alt="Azure Data Factory Pipeline" width="600"/>
</p>

## 📈 Expected Outcomes

- Scalable, automated pipeline
- Clean and structured data lake
- GitHub version control and full integration

## 🧪 How to Run

> ⚠️ **Prerequisites**: Azure account with permissions to create and manage resources (Data Lake, Databricks, Data Factory)

1. Clone the repository:
   ```bash
   git clone https://github.com/victoradearaujo/Pipeline_Databricks_Azure.git
