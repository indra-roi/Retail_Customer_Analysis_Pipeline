# Retail_Customer_Analysis_Pipeline
🚀 End-to-End Data Pipeline: Python (ETL) ➔ Neon Cloud (PostgreSQL) ➔ Power BI. 


![Power BI](https://img.shields.io/badge/Data_Visualization-Power_BI-yellow) 
![Python](https://img.shields.io/badge/Language-Python-blue) 
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL(Neon)_-blue)
![Cloud](https://img.shields.io/badge/Platform-Neon_Cloud-green)

## 🚀 Dashboard
<img width="1247" height="732" alt="Screenshot 2026-01-12 110517" src="https://github.com/user-attachments/assets/f522a7ea-7934-49f8-92fd-190490c8cd3b" />


---

## 📌 Project Overview
🚀 Strategic Overview
This project transforms raw, fragmented retail data into a cloud-native business intelligence solution. By architecting a pipeline that bridges Python-based ETL, Cloud SQL storage, and Interactive Visualization, I’ve created a scalable system that tracks 4,000+ customers to drive data-informed retail strategies.

This isn't just a static report—it's a scalable architecture designed for modern data-driven organizations.

---

🏗️ Technical Pipeline Architecture

1. Data Engineering & ETL (Python)
Environment: Google Colab.

Action: Automated the cleaning of 4,000 records, including data type conversion and handling null values.

Feature Engineering: Segmented customers by age and category to enable deeper demographic analysis.



2. Cloud Data Warehousing (PostgreSQL)
Platform: Neon Cloud (Serverless Postgres).

Action: Established a remote connection via SQLAlchemy to move processed data from the notebook to the cloud.

Security: Successfully managed secure cloud-to-cloud credentials to allow Power BI Service to refresh data directly from Neon.


3. Business Intelligence (Power BI)
Analysis: Developed a multi-page dashboard to track high-level KPIs:

Average Transaction Value: $59.76.

Customer Satisfaction: 3.75/5.0 Average Rating.

Connectivity: Used DirectQuery to ensure the dashboard reflects the state of the SQL database in real-time.



🛠️ Engineering Challenges Overcome
Environment Persistence: Solved Colab's ephemeral storage issues by implementing a "Save to Drive" workflow for script durability.

Cloud Credentialing: Fixed a "Data Source Credentials Missing" error by configuring Basic Authentication in the Power BI Service, enabling the report to live online.



📈 Key Business Insights
After processing the dataset and visualizing the metrics in Power BI, the following strategic insights were identified:

Revenue Performance: The retail operations maintain a consistent flow with an Average Purchase Amount of $59.76 per transaction.

Customer Base: Successfully tracked and analyzed a diverse demographic of 4,000 unique customers.

Quality Benchmarking: The current Average Review Rating stands at 3.75/5.0, highlighting specific product categories that require quality-of-service optimization to reach a 4.0+ target.

Data Reliability: By resolving the Data Source Credentials hurdle, the dashboard now provides a "Single Source of Truth" directly from the Neon Cloud PostgreSQL database, ensuring stakeholders view live, verified data rather than static snapshots.


📂 Repository Structure

├── Dashboard/           # Power BI (.pbix) file
├── Notebooks/           # Python ETL (.ipynb)
├── SQL/                 # Table schema and logic scripts
├── Project_Docs/        # Problem Statement & Deliverables PDF
└── images/              # Dashboard screenshots and architecture diagrams


📬 Contact & Portfolio
Name: Indranil Sinha Roy                LinkedIn: [www.linkedin.com/in/indranil-sinha-roy-7b9510216]
