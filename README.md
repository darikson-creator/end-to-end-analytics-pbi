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

---

## 🛠️ Workflow (Images)

### Create DB
 ![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/f316e7483f4bafce31cfbbe120f13260b03296b4/1.%20Create%20DB.png)
 
### Query DB
 ![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/f316e7483f4bafce31cfbbe120f13260b03296b4/2.%20Query%20DB.png)
 
### Semantic Model
 ![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/f316e7483f4bafce31cfbbe120f13260b03296b4/3.%20Load%20tables%20to%20PBI.png)
 
### DAX Queries
 ![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/f316e7483f4bafce31cfbbe120f13260b03296b4/4.%20DAX%20queries.png)
 
### New Data Uploaded with Python
![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/efb1685eb0afb3cf2c1ef8246c0f79328e80649c/5.%20New%20data%20upload%20with%20Py%202.png)

### PBI Report
![image alt](https://github.com/darikson-creator/end-to-end-analytics-pbi/blob/efb1685eb0afb3cf2c1ef8246c0f79328e80649c/6.%20Publish%20to%20PBI.png)



