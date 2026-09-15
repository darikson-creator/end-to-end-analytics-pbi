# On-Premise Data Warehouse & Power BI Executive Dashboard

## Description
A comprehensive Business Intelligence solution featuring an on-premise relational Data Warehouse, automated Python batch ingestion, Star Schema dimensional modeling, and interactive reporting deployed to Power BI Service.

## Key Features
* **Relational Database Design:** Architectural design of a 4-table schema (`sucursales`, `productos`, `ventas`, `costos`) in MySQL Workbench with foreign key constraints.
* **Advanced SQL Analysis:** Complex queries for data validation, temporal aggregations, and business logic execution.
* **Automated Python ETL:** Custom `.py` scripts for automated batch ingestion and synchronization between raw files and the MySQL warehouse.
* **Dimensional Modeling & DAX:** Star Schema architecture with dynamic Date Dimension and custom DAX metrics (Margins, Total Revenue, YoY/MoM comparisons).
* **Cloud Deployment:** Interactive dashboard published to Power BI Service for executive decision-making.

## Tech Stack
* **Database:** MySQL Workbench, SQL
* **Automation / ETL:** Python (`pymysql`, `pandas`)
* **Business Intelligence:** Power BI Desktop, Power BI Service, DAX
* **Data Source:** Excel / CSV
