# AdventureWorks Sales & Customer Analysis 🚴‍♂️📊

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

## 📌 Project Overview
This project involves a comprehensive end-to-end analysis of the **AdventureWorks** database. The goal was to transform raw sales data into actionable insights to support business decision-making regarding sales performance, product profitability, and customer demographics.

The project demonstrates a full data pipeline workflow:
1.  **SQL:** Data extraction, cleaning, and complex logic implementation.
2.  **Excel:** Initial data validation and quick pivot analysis.
3.  **Power BI & Tableau:** Creating interactive dashboards for final stakeholder presentation.

## 📂 Project Structure
| File Name | Format | Description |
| :--- | :--- | :--- |
| `Adventure_Works_Analysis_Project.sql` | .sql | Contains all SQL queries for KPIs, data blending (Union), and window functions. |
| `AdventureWorks_Report.xlsx` | .xlsx | Spreadsheet for data verification and pivot table summaries. |
| `AdventureWorks_Dashboard.pbix` | .pbix | Power BI Dashboard file featuring interactive filtering and DAX measures. |
| `AdventureWorks_Visuals.twbx` | .twbx | Tableau Packaged Workbook focusing on geospatial and storytelling visuals. |

## 🔍 Key Insights & Analysis

### 1. 📈 SQL Analysis (Backend Logic)
The SQL script (`Adventure_Works_Analysis_Project.sql`) covers the following advanced concepts:
* **Data Integration:** Used `UNION` to combine historical and new sales data (`fact_internet_sales` + `fact_internet_sales_new`).
* **Time Intelligence:** Calculated **Year-Over-Year (YoY) Sales Growth** using Window Functions (`LAG` and `OVER`) to track performance trends.
* **Customer Retention:** Identified **Repeat Customers** using subqueries to filter clients with multiple distinct orders.
* **Product Performance:** Identified the **Top 10 Selling Products** and analyzed profit margins by joining Fact tables with `DimProduct` and `DimProdSubCategory`.
* **Demographics:** Segmented sales data by **Marital Status** and Region to understand customer purchasing behavior.

### 2. 📊 Dashboard Features (Frontend Visualization)
The Power BI and Tableau dashboards visualize the SQL insights through:
* **Executive KPI Cards:** Displaying Total Revenue, Profit, Orders, and Average Order Value (AOV).
* **Regional Maps:** Interactive maps showing sales hot-spots by Country and Territory (e.g., strong performance in North America vs. Europe).
* **Product Matrix:** A breakdown of Sales vs. Profit Margin to identify high-revenue/low-margin products.
* **Sales Trends:** Line charts showing monthly revenue fluctuations to identify seasonality.

## 🛠️ Tools & Technologies Used
* **Database:** MySQL / SQL Server
* **Reporting:** Microsoft Power BI, Tableau Desktop
* **Spreadsheet:** Microsoft Excel
* **Key Skills:** Data Modeling, DAX, SQL Joins, Window Functions, Data Storytelling.

## 🚀 How to Run This Project
1.  **Database Setup:** Import the standard `AdventureWorks` dataset into your SQL server.
2.  **Run Queries:** Execute `Adventure_Works_Analysis_Project.sql` to generate the foundational insights.
3.  **View Visuals:**
    * Open `.pbix` file in **Power BI Desktop**.
    * Open `.twbx` file in **Tableau Public/Desktop**.

## 💡 Conclusion
This project highlights the ability to manipulate large datasets using SQL and translate those numbers into visual narratives using industry-standard BI tools. It showcases proficiency in both backend data processing and frontend dashboard design.

---
*Created by [Ajay Kumar]*
