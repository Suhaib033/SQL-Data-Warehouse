# 🚀 SQL Data Warehouse & Analytics Project 📊

**Data enthusiast | SQL craftsman | Building data-driven solutions, one warehouse at a time. 🚀**

This repository showcases a complete data warehousing and analytics project, demonstrating end-to-end skills in building a modern data warehouse using SQL Server and creating actionable insights.  Designed as a portfolio piece, it highlights best practices in data engineering and business intelligence.

**Key Project Features:**

*   **🏗️ Medallion Data Architecture:** Implemented Bronze, Silver, and Gold layers for organized data flow and quality management.
*   **💧 Automated ETL Pipelines (SQL):** Developed robust SQL-based ETL processes to extract, transform, and load data from CSV sources.
*   **⭐ Star Schema Data Model:** Designed fact and dimension tables in the Gold layer optimized for analytical queries and reporting.
*   **📈 SQL-Based Analytics & Reporting:** Demonstrated SQL proficiency in generating insights for Customer Behavior, Product Performance, and Sales Trends.

**🎯 Showcase of Expertise:**

This project is ideal for demonstrating skills in:

*   SQL Development 💻
*   Data Architecture 🏛️
*   Data Engineering ⚙️
*   ETL Pipeline Development 🔗
*   Data Modeling 🗂️
*   Data Analytics 🔍

**🛠️ Tools & Resources (All Free!):**

*   **Datasets** 
*   **Database:** [SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) (Local server)
*   **Database Client:** [SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-ssms-sql-server-management-studio-ssms?view=sql-server-ver16) (GUI)
*   **Version Control:** [Git & GitHub](https://github.com/) (Collaboration & code management)
*   **Diagrams:** [DrawIO](https://draw.io/) (Data architecture, models, flows)
*   **Project Management:** [Notion](https://www.notion.so/) (Project planning & organization)
*   **Project Steps:** [Notion Project Phases & Tasks](Link to your Notion page if you are sharing) (Replace with your actual Notion link if you are sharing)

**📜 Project Requirements & Objectives:**

*   **Data Engineering (Data Warehouse Building):**
    *   **Objective:** Consolidate sales data from ERP & CRM using SQL Server for analytical reporting and informed decision-making.
    *   **Specifications:** CSV data sources, data quality cleansing, data integration into user-friendly model, focus on latest data, data model documentation.
*   **Data Analysis (BI & Reporting):**
    *   **Objective:**  Deliver SQL-based analytics for detailed insights into Customer Behavior, Product Performance, and Sales Trends, empowering strategic decisions.

**📂 Repository Structure:**
```
└── 📁Data_Warehouse
    └── 📁datasets
        └── 📁source_crm
            └── cust_info.csv
            └── prd_info.csv
            └── sales_details.csv
        └── 📁source_erp
            └── CUST_AZ12.csv
            └── LOC_A101.csv
            └── PX_CAT_G1V2.csv
    └── 📁docs
        └── data_architecture.png
        └── data_flow.png
        └── data_integration.png
        └── data_model.png
    └── 📁Scripts
        └── 📁bronze
            └── ddl_bronze.sql
            └── proc_load_bronze.sql
        └── 📁gold
            └── ddl_gold.sql
        └── init_database.sql
        └── 📁silver
            └── ddl_silver.sql
            └── proc_load_silver.sql
    └── 📁tests
        └── quality_checks_gold.sql
        └── quality_checks_silver.sql
```

**🛡️ License**

This project is licensed under the [MIT License](LICENSE).  Feel free to use, modify, and share with proper attribution.

**🙏 Credits:**

This project was inspired and guided by the excellent tutorials from [Data with Baraa](https://www.youtube.com/@DataWithBaraa). Thank you for the invaluable learning resource!
