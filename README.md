
# 🍕 Pizza Sales Analysis — SQL + Excel Project

## 📌 Project Overview

This project presents a complete end-to-end analysis of Pizza Sales data using SQL for KPI calculation and business queries, followed by Excel for validation, additional analysis, and dashboard creation.

The aim is to understand ordering patterns, sales performance, peak times, revenue drivers, and product-level insights using a structured workflow.

---

## 🎯 Objectives

This analysis focuses on:

* Key KPIs: Total Revenue, Total Orders, Total Pizzas Sold, Avg Order Value, Avg Pizzas per Order

* Daily & Hourly Sales Patterns

* Sales by Pizza Category & Size

* Best & Worst Selling Pizzas

* Busiest Days & Peak Order Times

* Category-wise & Size-wise revenue contribution

---

## 📂 Project Files

* **[Pizza_Sales_Dataset.csv](Pizza_Sales_Dataset.csv)** – Dataset used for SQL & Excel analysis
* **[Pizza_Sales_Analysis.xlsx](Pizza_Sales_Analysis.xlsx)** – Excel analysis, pivots, trend charts
* **[Pizza_Dashboard.png](Pizza_Dashboard.png)** – Final Excel dashboard
* **[Pizza_Sales_Sql_Report.docx](Pizza_Sales_Sql_Report.docx)** – SQL queries
* **README.md** – Project explanation

---

## 🧵 Dataset Details

### **Columns in the CSV**

| Column                | Description                                  |
| --------------------- | -------------------------------------------- |
| **pizza_id**          | Unique ID for each pizza item                |
| **order_id**          | Unique order transaction ID                  |
| **pizza_name_id**     | Mapping ID for the pizza name                |
| **quantity**          | Number of pizzas ordered                     |
| **order_date**        | Date when the order was placed               |
| **order_time**        | Time when the order was placed               |
| **unit_price**        | Price per pizza                              |
| **total_price**       | Total bill amount for the order              |
| **pizza_size**        | Size of the pizza (S, M, L, XL, XXL)         |
| **pizza_category**    | Category (Classic, Supreme, Chicken, Veggie) |
| **pizza_ingredients** | List of ingredients used in the pizza        |
| **pizza_name**        | Full name of the pizza                       |

---

## 🧵 Methodology

### **1️⃣ SQL Analysis**

I wrote SQL queries to calculate:

* Total revenue
* Total pizzas sold
* Average order value
* Best/worst sellers
* Sales by category & size
* Daily & hourly trends

All queries and findings are documented here:
👉 **[Pizza_Sales_Sql_Report.docx](Pizza_Sales_Sql_Report.docx)**

---

### **2️⃣ Excel Analysis & Visualization**

Using the dataset, I performed:

* Data formatting
* Pivot tables
* Trend charts
* Category & size-based analysis
* Top/Bottom performers
* Dashboard creation

Full Excel analysis here:
👉 **[Pizza_Sales_Analysis.xlsx](Pizza_Sales_Analysis.xlsx)**

Dashboard preview:

<img width="1091" height="616" alt="Pizza_Dashboard" src="https://github.com/user-attachments/assets/3ed5678b-ae11-40e5-b6f2-72efd6c80730" />


---

## 📊 Key Insights

* **Classic pizzas** are the top revenue-generating category
* **Large size pizzas** contribute the most orders
* **Peak hours** fall between 12–1 PM and 5–8 PM
* **Thursday–Saturday** show maximum sales
* **Top seller:** Classic Deluxe Pizza
* **Least seller:** Brie Carre Pizza

(Insights fully detailed inside Excel & SQL report.)

---

## 🛠 Tools Used

* **SQL(Microsoft SQL Server)** – Querying, validation, KPI calculations
* **Excel** – Analysis, pivot tables, charts, dashboard
* **Word** – SQL report documentation

---

## 📘 Conclusion

This project demonstrates how SQL and Excel together provide powerful insights into sales performance.
I validated SQL results using Excel to ensure accuracy and created a clean dashboard that highlights revenue patterns, top sellers, and customer ordering behaviour.


