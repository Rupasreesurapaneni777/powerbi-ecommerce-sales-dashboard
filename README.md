# 📊 Power BI E-Commerce Sales & Profit Dashboard

## 📌 Project Overview

This project is an **Interactive E-Commerce Sales and Profit Analysis Dashboard** developed using **Microsoft Power BI**.

The dashboard analyzes e-commerce sales data to understand:

* Sales Performance
* Profitability
* Product Performance
* Customer Segments
* Regional Performance
* Customer Demographics
* Sales Trends

The main objective of this project is to transform raw sales data into meaningful and interactive business insights using **Power Query, DAX, and Power BI visualizations**.

---

# 📷 Dashboard Output

## 1️⃣ E-Commerce Sales Dashboard

![E-Commerce Sales Dashboard](dashboard-overview.png)

### Dashboard Output Includes

* Total Sales: **₹7.80M**
* Total Profit: **₹1.52M**
* Total Orders: **300**
* Total Quantity: **887**
* Profit Margin: **~19.5%**
* Total Profit by Region
* Total Sales by Product
* Total Sales by Category
* Monthly Sales Trend
* Sales by Customer Segment
* Sales by Gender
* Product Sales vs Profit Analysis

---

## 2️⃣ Sales & Profit Analysis Dashboard

![Sales and Profit Analysis Dashboard](sales-profit-analysis.png)

### Dashboard Output Includes

* Total Sales by City
* Total Sales by Age Group
* Category and Sub-Category Analysis
* Product Sales vs Profit
* Quantity Analysis
* Regional Analysis
* Customer Analysis

---

# 📊 Key KPIs

| KPI            | Result |
| -------------- | -----: |
| Total Sales    | ₹7.80M |
| Total Profit   | ₹1.52M |
| Total Orders   |    300 |
| Total Quantity |    887 |
| Profit Margin  | ~19.5% |

---

# 💡 Key Business Insights

### 🥇 Highest Sales Category

**Electronics** generated the highest total sales.

### 💰 Highest Profit Category

**Electronics** also generated the highest overall profit.

### 🌍 Best Performing Region

The **South Region** performed the best.

### 📅 Highest Sales Month

**July** recorded the highest sales.

### 👥 Highest Spending Customer Segment

The **Consumer** segment contributed the highest share of sales.

### 📱 Best Performing Sales Channel

The **Mobile App** channel generated the highest sales.

### 🏙️ Top Revenue City

**Delhi** was one of the highest revenue-contributing cities.

### 📈 Overall Profit Margin

The business achieved an overall profit margin of approximately **19.5%**.

### 🛍️ Top Products

Products such as:

* AeroBook 14
* Nova X
* Study Table
* Air Fryer
* Office Chair

were among the top-performing products based on sales.

---

# 🛠 Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX
* Microsoft Excel
* Data Cleaning
* Data Analysis
* Data Visualization
* Business Intelligence

---

# 🎯 DAX Measures

## Total Sales

```DAX
Total Sales =
SUM(Sales_Data[Sales])
```

## Total Profit

```DAX
Total Profit =
SUM(Sales_Data[Profit])
```

## Total Orders

```DAX
Total Orders =
DISTINCTCOUNT(Sales_Data[Order_ID])
```

## Total Quantity

```DAX
Total Quantity =
SUM(Sales_Data[Quantity])
```

## Profit Margin %

```DAX
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)
```

## Average Order Value

```DAX
Average Order Value =
DIVIDE(
    [Total Sales],
    [Total Orders],
    0
)
```

---

# 📈 Visualizations Used

The dashboard contains:

* KPI Cards
* Bar Charts
* Column Charts
* Line Chart
* Donut Charts
* Scatter Chart
* Matrix
* Slicers
* Interactive Filters

---

# 🔍 Business Questions Answered

1. Which category generates the highest sales?
2. Which category generates the highest profit?
3. Which region performs best?
4. Which month has the highest sales?
5. What are the top-performing products?
6. Which customer segment spends the most?
7. Which sales channel performs best?
8. Which products have high sales but low profit?
9. What is the overall profit margin?
10. Which cities contribute the most revenue?
11. Which age group contributes the most sales?
12. How does sales performance differ by gender?
13. How do sales and profit compare across products?

---

# 📂 Project Structure

```text
PowerBI-Ecommerce-Sales-Dashboard/
│
├── Ecommerce_Sales_Dashboard.pbix
├── PowerBI_Ecommerce_Sales_Project_Data.xlsx
├── dashboard-overview.png
├── sales-profit-analysis.png
└── README.md
```

---

# 📁 Project Files

### `Ecommerce_Sales_Dashboard.pbix`

Power BI dashboard containing visualizations, DAX measures, slicers, and interactive reports.

### `PowerBI_Ecommerce_Sales_Project_Data.xlsx`

Dataset used to build the Power BI dashboard.

### `dashboard-overview.png`

Screenshot of the main E-Commerce Sales Dashboard.

### `sales-profit-analysis.png`

Screenshot of the detailed Sales & Profit Analysis dashboard.

### `README.md`

Complete project documentation.

---

# 🚀 How to Use

1. Clone or download this repository.
2. Open `Ecommerce_Sales_Dashboard.pbix` using Microsoft Power BI Desktop.
3. Explore the dashboard visuals.
4. Use slicers to filter data based on:

   * Region
   * Category
   * Customer Segment
   * Sales Channel
   * Order Date
5. Analyze sales, profit, product, customer, and regional performance.

---

# 🎯 Project Objective

The objective of this project is to demonstrate how raw e-commerce sales data can be transformed into an interactive and meaningful business intelligence dashboard.

This project demonstrates practical skills in:

* Power BI
* Power Query
* DAX
* Excel
* Data Cleaning
* Data Analysis
* KPI Development
* Data Visualization
* Business Insight Generation

---

# ✅ Conclusion

The **E-Commerce Sales & Profit Dashboard** provides a clear overview of business performance and helps identify:

* Best-selling categories
* Top products
* Profitable regions
* Customer purchasing patterns
* Revenue-driving cities
* Sales trends
* Overall profitability

This project demonstrates practical **Power BI, DAX, Power Query, Excel, Data Analysis, and Data Visualization skills**.
