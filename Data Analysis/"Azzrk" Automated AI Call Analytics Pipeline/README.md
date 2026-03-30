# "AZZRK" Automated AI Call Analytics Pipeline

## 📌 Project Overview
This project was developed to solve a critical data silo issue at **Azzrk e-commerce company**. The AI calling platform used for lead generation lacked API access, making it impossible to perform cross-campaign analysis or client benchmarking. 

I engineered a custom **ETL (Extract, Transform, Load) pipeline** that automates the transition from fragmented CSV exports to a centralized **Google BigQuery Data Warehouse**, powering a real-time **Looker Studio** dashboard[cite: 137, 140, 144].

## 🛠️ Technical Stack
* **Language:** Python (Pandas)
* **Cloud Database:** Google BigQuery [cite: 129]
* **BI Tool:** Looker Studio [cite: 122]
* **Automation:** Python OS & Service Account Integration

## 🚀 Key Features
* **Dynamic Metadata Extraction:** Automated logic to extract Company Names and Campaign IDs from filenames (`Leads_CompanyName_Campaign.csv`) to enable multi-tenant reporting.
* **Idempotent Data Loading:** Implemented a "Delete-before-Insert" strategy using SQL queries via Python to prevent record duplication during re-runs.
* **Data Cleaning & Normalization:** Standardized phone formats, converted timestamps, and handled null values across millions of rows of lead data.
* **Business Logic Mapping:** Integrated DTMF (Keypress) choices to filter "Hot Leads" from general dials, providing immediate ROI insights for clients.

## 📊 Business Impact
* **80% Reduction** in manual reporting time for the General Manager and Department Heads[cite: 144].
* **Performance Benchmarking:** Enabled the company to compare conversion rates across 5+ different clients for the first time[cite: 139].
* **Lead Quality Optimization:** Identified high "Drop-off" points in AI scripts, allowing for real-time script adjustments.

## 📁 Repository Structure
* [etl_pipeline.py](./etl_pipeline.py): The core Python script handling the BigQuery ingestion.
* [data_generator.py](./data_generator.py): A utility script to generate synthetic call data for testing.
* [Sample Data](./sample_data/): Example CSV files following the `Leads_Company_Campaign` naming convention.
* [cite_start][Dashboard Preview](./Dashboard_Preview.pdf): Visual representation of the final BI tool.

---
*Note: The data provided in the sample files and dashboard preview is synthetic/fake to protect company privacy.*
