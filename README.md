## 🍕 Pizza Sales Analysis – MySQL & Excel (Pivot Tables)
- This project analyzes pizza sales data using **MySQL** and **Microsoft Excel** to extract actionable business insights through KPIs and visual dashboards. The goal is to help a hypothetical pizza restaurant understand its sales trends, customer preferences, and 
  performance by pizza type, size, and time.

## Dataset Used
- <a href="https://github.com/VrajPachchigar/Pizza-Sales-Analysis-Dashboard/blob/main/Pizza%20Sales%20Data.xlsx">Pizza_Sales_Data_2015</a>

## 🔧 Tools & Technologies
- **MySQL** – Data cleaning, aggregation, and analysis  
- **Microsoft Excel** – Pivot Tables, Charts, and Dashboards  
- **SQL** – Queries to transform and summarize data 

## 📌 Key KPIs Generated
- ✅ **Total Revenue by Pizza Sales**
- ✅ **Average Order Value per Order**
- ✅ **Total Pizzas Sold**
- ✅ **Total Orders Received**
- ✅ **Average Pizzas per Order**
- ✅ **Daily Trends for All Orders**
- ✅ **Hourly Trends for All Orders**
- ✅ **Percentage of Sales by Pizza Category**
- ✅ **Percentage of Sales by Pizza Size**
- ✅ **Total Pizza Sold by Pizza Category**
- ✅ **Top 5 Best-Selling Pizzas**
- ✅ **Bottom 5 Least-Selling Pizzas**

## 🔍 KPI Generation Process
1. **📥 Data Cleaning & Importing**
   - Loaded raw CSV sales data into MySQL.
   - Cleaned inconsistent values and standardized columns.
   - Parsed date/time and normalized categorical fields (e.g., pizza size, category).
2. **🧮 SQL Data Transformation**
   - Used SQL queries for data aggregation:
     - `SUM(quantity * price)` → Total Revenue
     - `COUNT(DISTINCT order_id)` → Total Orders
     - `SUM(quantity)` → Total Pizzas Sold
     - Calculated average values, grouped sales by time (day/hour), pizza size, and category.
3. **📤 Export to Excel**
   - Exported query results from MySQL to Excel for visualization.
4. **📈 Pivot Table Dashboards**
   - Built dynamic dashboards using Pivot Tables and Charts:
     - Tracked sales trends by day and hour.
     - Compared pizza size and category performances.
     - Visualized top/bottom selling pizzas.
    
## 📸 Dashboard Visuals
![Dashboard](https://github.com/user-attachments/assets/935314b8-2402-4db7-9c28-d920d7700018)

    

