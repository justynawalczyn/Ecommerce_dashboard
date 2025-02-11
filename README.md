#  E-commerce Sales Analysis Dashboard

##  Project Overview
This project provides an **interactive sales analysis dashboard** using **Power BI** and **SQL**.  
It explores key business insights such as:
- ** Monthly Sales Trends** (Overall sales growth over time)
- ** Best-Selling Products** (Top-performing items)
- ** Sales by Country** (Global distribution of sales)
- ** Returns & Negative Sales Trends** (Handling refunds and negative quantities)

 **Technologies Used:**
- **Power BI** → Data visualization & interactive dashboards  
- **SQL (PostgreSQL/Oracle)** → Data extraction & transformation  
- **Python (Optional)** → Data cleaning (if needed)  

---

##  Files in Repository
| File Name | Description |
|-----------|-------------|
| **`Ecommerce_Sales_Dashboard.pbix`** | Power BI dashboard file |
| **`Ecommerce_Dashboard.png`** | Screenshot of the dashboard |
| **`SQL_Queries.sql`** | SQL queries used for data extraction |
| **`README.md`** | Documentation of the project |

---

##  **Data Processing Workflow**
1️ **Extract Data using SQL**  
   - Query data from PostgreSQL / Oracle  
   - Handle missing values & clean data  

2️ **Load Data into Power BI**  
   - Import dataset via  CSV
   - Create **DAX measures** for additional calculations  

3️ **Build Visualizations in Power BI**  
   - **Line Chart:** Monthly sales trends  
   - **Bar Chart:** Best-selling products  
   - **Map:** Sales by country  
   - **Heatmap:** Geographic concentration of sales  

---

##  **Key Insights from the Dashboard**
✅ **Sales peaked in November 2011**, likely due to holiday shopping.  
✅ **December drop in sales** could indicate missing data or post-holiday slowdown.  
✅ **The UK is the top sales market**, with strong contributions from Germany & France.  
✅ **Negative `Quantity` values detected**, possibly indicating product returns.  

---


