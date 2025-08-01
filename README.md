# 🍕 Pizza Sales Dashboard (Power BI + SQL)

## 🚀 Project Summary  
A data-driven visual analysis of pizza sales using SQL for validation and Power BI for interactive dashboards. This project delivers insights into sales trends, customer preferences, and product performance while enabling better business decisions with clean, layered visuals and smart DAX calculations.

## 📌 Core Analysis Objective  
- Tracks overall pizza performance across categories, days, and times  
- Identifies top-selling and underperforming products  
- Highlights sales trends and peak hours/days  
- Supports informed planning using clean, reliable data  

## 🧰 Tools & Technologies Used  
- **SQL** – For validating and analyzing raw data  
- **Power BI Desktop** – For building dashboards  
- **Power Query Editor** – For data transformation  
- **DAX (Data Analysis Expressions)** – For KPIs and calculated logic  
- **CSV Files** – As source datasets  

## ✨ Features & Highlights  
- **KPIs**: Revenue, Orders, AOV, Quantity Sold, and more  
- **Dynamic Slicers**: Filter by Pizza Category, Size, Month  
- **Drill-through Pages**: Deep dive into performance by type/size  
- **Visual Highlights**: Top & Bottom 5 pizzas by sales, quantity, orders  
- **Smart Layout**: Clean, branded theme with focus on usability  
- **Combined SQL + Power BI workflow**  

## 🧠 Data Analysis & SQL Insights  
Performed initial data validation and analysis using SQL before importing into Power BI. Key SQL insights included:  
- Total Revenue, Orders, AOV, and Pizzas Sold  
- Daily & Monthly Order Trends  
- Percentage of Sales by Category & Size  
- Top/Bottom 5 Pizzas by Revenue, Quantity, and Orders  

## 📈 Power BI Dashboard Insights  
The dashboard is split into two clean, interactive pages that provide both high-level KPIs and deep-dives into trends and sales performance:

### 🔹 Page 1: KPI & Sales Overview  
A high-level snapshot of performance metrics and product insights.

- 🧾 **KPI Cards**: Total Revenue, Average Order Value, Total Orders, Pizzas Sold  
- 📊 **Stacked Bar Chart**: Revenue comparison across Pizza Categories  
- 🍩 **Donut Charts**:  
  - % of Sales by Pizza Size  
  - % of Sales by Pizza Category  
- 📉 **Top & Bottom Performers**:  
  - Bar Charts for Top & Bottom 5 Pizzas by Revenue  
  - Top & Bottom by Quantity & Orders  
- 🎛️ **Dynamic Slicers**: Filter data by Month, Category, and Size  

### 🔹 Page 2: Trend Analysis  
This page dives into temporal and behavioral trends.

- 📈 **Line Chart**: Monthly Trend of Total Orders  
- 📅 **Bar Chart**: Orders by Day of the Week  
- 🍕 **Clustered Bar**: Category-wise Quantity Sold (Filtered for Specific Months)  
- 🔎 **Comparative Visuals**: Enables time-series and category-wise performance comparison  
- 🧠 **User Interactivity**: Designed with slicers and drill-down to promote exploration  

## 🧮 DAX Measures Created  
- `Total Revenue = SUM(total_price)`  
- `Average Order Value = Total Revenue / DISTINCTCOUNT(order_id)`  
- `Total Orders = DISTINCTCOUNT(order_id)`  
- `Avg Pizzas per Order = SUM(quantity) / DISTINCTCOUNT(order_id)`  
- More detailed DAX used for visuals & dynamic interactivity  
 
## 📸 Dashboard Previews  
**[Screenshot 1 – Home Dashboard](https://raw.githubusercontent.com/charitha1204/Pizza-Sales-Dashboard/main/Screenshots/Home%20Dashboard.png)**  
**[Screenshot 2 – Best/Worst Seller Dashboard](https://raw.githubusercontent.com/charitha1204/Pizza-Sales-Dashboard/main/Screenshots/Best%20or%20Worst%20Seller%20Dashboard.png)**

