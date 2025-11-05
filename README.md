# Generations-Capstone-NHL-Analytics

## 🚀 Overview
This project demonstrates a complete data engineering workflow — from raw data ingestion to visualization in Power BI — using Microsoft Fabric, SQL, and Python.

## 🔧 Tech Stack
- **Languages:** Python, SQL  
- **Tools:** Microsoft Fabric, Power BI, Azure Data Lake  
- **Libraries:** pandas, pyodbc, requests, etc.

## 🏗️ Pipeline Architecture
![Pipeline Diagram](docs/architecture_diagram.png)

1. **Ingest:** Collects raw data from [source name] via API/CSV.
2. **Transform:** Cleans and processes data using Python & SQL scripts.
3. **Load:** Loads processed data into Microsoft Fabric Lakehouse / SQL DB.
4. **Visualize:** Power BI dashboard for insights and metrics.

## 📂 Repository Structure
(Insert the folder tree or a brief summary)

## ▶️ How to Run
1. Clone the repo  
2. Set up your environment using `requirements.txt`  
3. Update your credentials in `config/connections.yaml`  
4. Run `python src/pipeline.py`

## 📊 Power BI Dashboard
![Dashboard Preview](powerbi/dashboard_preview.png)

## 🧠 Learnings
- Hands-on with Microsoft Fabric data pipelines  
- Best practices for modular ETL design  
- Data validation and automation scripting

