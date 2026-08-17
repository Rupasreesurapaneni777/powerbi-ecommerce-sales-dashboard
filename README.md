# PowerBI E-Commerce Sales Dashboard

## 📊 Project Overview

This project is an **Interactive E-Commerce Sales and Profit Analysis Dashboard** developed using **Microsoft Power BI**.

The dashboard helps analyze sales performance, profit, product categories, customer segments, regional performance, and customer demographics.

## 🛠 Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX
* Microsoft Excel
* Data Visualization

## 📌 Key KPIs

* Total Sales
* Total Profit
* Total Orders
* Total Quantity
* Profit Margin %

## 📈 Dashboard Analysis

The dashboard includes:

* Total Sales by Category
* Total Profit by Region
* Total Sales by Product
* Sales Trend by Order Date
* Total Sales by Customer Segment
* Total Sales by City
* Total Sales by Age Group
* Total Sales by Gender
* Product Sales vs Profit Analysis

## 🎯 DAX Measures

```DAX
Total Sales = SUM(Sales_Data[Sales])

Total Profit = SUM(Sales_Data[Profit])

Total Orders = DISTINCTCOUNT(Sales_Data[Order_ID])

Total Quantity = SUM(Sales_Data[Quantity])

Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)
```

## 📷 Dashboard Preview

![E-Commerce Sales Dashboard](dashboard.png)

## 📂 Project Files

```text
PowerBI-Ecommerce-Sales-Dashboard/
│
├── Ecommerce_Sales_Dashboard.pbix
├── PowerBI_Ecommerce_Sales_Project_Data.xlsx
├── dashboard.png
└── README.md
```

### File Description

* **Ecommerce_Sales_Dashboard.pbix** – Power BI dashboard file
* **PowerBI_Ecommerce_Sales_Project_Data.xlsx** – Dataset used for analysis
* **dashboard.png** – Dashboard preview
* **README.md** – Project documentation

## 💡 Project Insights

This dashboard helps identify:

* Best-performing product categories
* Regions generating the highest profit
* Top-selling products
* Customer segment contribution to total sales
* Sales trends over time
* Customer purchasing patterns based on age and gender
* Cities contributing the most revenue

## 🚀 How to Use

1. Download the repository.
2. Open `Ecommerce_Sales_Dashboard.pbix` using Power BI Desktop.
3. Review the interactive dashboard.
4. Use slicers to filter the dashboard by Region, Category, Customer Segment, and Order Date.

## 📌 Project Objective

The main objective of this project is to convert raw e-commerce sales data into an interactive Power BI dashboard and generate meaningful business insights that can support data-driven decision-making.

