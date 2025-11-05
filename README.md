# 🏒 :Generations Capstone Project: NHL Game Data Pipeline — End-to-End Data Engineering in Microsoft Fabric 

This project demonstrates a **complete end-to-end data pipeline** built on **Microsoft Fabric**, using the *NHL Game Data* dataset from Kaggle.  
It covers the full data lifecycle — from raw data ingestion to analytics visualization — leveraging **Python**, **SQL**, **Azure SQL Database**, and **Power BI**.

---

## 🚀 Project Overview

**Goal:** Build an automated data pipeline that ingests, transforms, and visualizes NHL game statistics to uncover insights into team performance and player metrics.

**Pipeline Flow:**
1. **Ingest** — Download raw data from Kaggle using `kagglehub`  
2. **Transform** — Clean and shape data using Python (`pandas`)  
3. **Load** — Push curated tables into **Azure SQL Database** within Microsoft Fabric  
4. **Visualize** — Connect **Power BI** to Fabric for dynamic dashboards

---

## 🧱 Tech Stack

| Component | Technology |
|------------|-------------|
| **Extraction / Ingestion** | Python (`kagglehub`, `pandas`) |
| **Transformation** | Python, SQL |
| **Storage** | Azure SQL Database (Fabric-integrated) |
| **Orchestration** | Microsoft Fabric Data Pipeline |
| **Visualization** | Power BI (Fabric workspace) |

---

## 📂 Repository Structure
<pre>
  
📦 nhl-data-pipeline/
│
├── data/ # Datasets (anonymized or sample)
│ ├── raw/ # Original Kaggle dataset
│ ├── processed/ # Cleaned dataset ready for modeling
│ └── data_dictionary.md
│
├── src/
│ ├── ingest/ # Ingestion scripts
│ │ └── ingest_data.py
│ ├── transform/ # Data cleaning, joins, validation
│ │ └── transform_data.py
│ ├── load/ # Load data into Azure SQL / Fabric
│ │ └── load_to_powerbi.py
│ ├── utils/ # Helper functions
│ │ └── helpers.py
│ └── pipeline.py # Main orchestration entrypoint
│
├── sql/ # SQL queries for transformation
│ ├── staging_queries.sql
│ ├── transformation_queries.sql
│ └── data_validation.sql
│
├── powerbi/ # Dashboards and visual reports
│ ├── dashboard_preview.png
│ └── report_description.md
│
├── docs/ # Architecture & documentation
│ ├── architecture_diagram.png
│ ├── pipeline_flow.md
│ ├── setup_instructions.md
│ └── learnings.md
│
├── requirements.txt
├── environment.yml
├── LICENSE
├── .gitignore
└── README.md

</pre>
---


## 🔧 Tech Stack
- **Languages:** Python, SQL  
- **Tools:** Microsoft Fabric, Power BI, Azure Data Lake  
- **Libraries:** pandas, pyodbc, requests, etc.

## ▶️ How to Run
1. Clone the repo  
2. Set up your environment using `requirements.txt`  
3. Update your credentials in `config/connections.yaml`  
4. Run `python src/pipeline.py`

## 🧠 Learnings
- Hands-on with Microsoft Fabric data pipelines  
- Best practices for modular ETL design  


---

## ⚙️ How to Run the Pipeline

### 1️⃣ Setup Environment
Install dependencies locally or in Microsoft Fabric Notebook:
```bash
pip install -r requirements.txt
- Data validation and automation scripting

