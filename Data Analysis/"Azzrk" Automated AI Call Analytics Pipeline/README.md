# "AZZRK" Automated AI Call Analytics Pipeline

##  Project Overview
This project was developed to solve a critical data silo issue at **Azzrk e-commerce company**. The AI calling platform used for lead generation lacked API access, making it impossible to perform cross-campaign analysis or client benchmarking. 

I engineered a custom **ETL (Extract, Transform, Load) pipeline** that automates the transition from fragmented CSV exports to a centralized **Google BigQuery Data Warehouse**, powering a real-time **Looker Studio** dashboard.

##  Technical Stack
* **Language:** Python (Pandas)
* **Cloud Database:** Google BigQuery 
* **BI Tool:** Looker Studio 
* **Automation:** Python OS & Service Account Integration

##  Key Features
* **Dynamic Metadata Extraction:** Automated logic to extract Company Names and Campaign IDs from filenames (`Leads_CompanyName_Campaign.csv`) to enable multi-tenant reporting.
* **Idempotent Data Loading:** Implemented a "Delete-before-Insert" strategy using SQL queries via Python to prevent record duplication during re-runs.
* **Data Cleaning & Normalization:** Standardized phone formats, converted timestamps, and handled null values across millions of rows of lead data.
* **Business Logic Mapping:** Integrated DTMF (Keypress) choices to filter "Hot Leads" from general dials, providing immediate ROI insights for clients.

##  Business Impact
* **90% Reduction** in manual reporting time for the General Manager and Department Heads
* **Leveraging The Sales Team Power** No more wasted potentials in the cold leads
* **Performance Benchmarking:** Enabled the company to compare conversion rates across 5+ different clients for the first time.
* **Lead Quality Optimization:** Identified high "Drop-off" points in AI scripts, allowing for real-time script adjustments.


##  Repository Structure
* [etl_pipeline.ipynb](./etl_pipeline.ipynb): The core Python script handling the BigQuery ingestion.
* [Sample Data](Data Analysis/"Azzrk" Automated AI Call Analytics Pipeline/Sample Data.csv): Example CSV files following the `Leads_Company_Campaign` naming convention.
* [Dashboard Preview](./Dashboard_Preview.pdf): Visual representation of the final BI tool.

---
*Note: The data provided in the sample files and dashboard preview is synthetic/fake to protect company privacy.*
