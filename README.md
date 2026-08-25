# amazon--walmart
# Amazon & Walmart Sales Analysis Dashboard

## 📊 Project Overview

This project presents a comprehensive sales analysis of Amazon and Walmart sales data using **Microsoft Excel**. The objective is to transform raw transactional data into meaningful business insights through data analysis, Pivot Tables, and an interactive dashboard.

The analysis focuses on important business metrics such as **sales, profit, profit margin, product performance, customer spending, geographical performance, shipping status, and sales trends**.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall sales and profit performance.
- Identify high-performing product categories.
- Track sales and profit trends over time.
- Identify the top-performing states and cities.
- Analyze customer purchasing behavior.
- Compare sales performance based on shipping status.
- Identify the most profitable products.
- Evaluate profit margins across product categories.
- Analyze quarterly business performance.
- Build an interactive and easy-to-understand sales dashboard.

---

## 📁 Dataset Information

The dataset contains **3,203 sales records** with the following key attributes:

| Column | Description |
|---|---|
| `order_id` | Unique identifier for each order |
| `order_date` | Date when the order was placed |
| `ship_date` | Date when the order was shipped |
| `status` | Shipping status, such as On Time or Delay |
| `customer_name` | Name of the customer |
| `country` | Country where the order was placed |
| `city` | Customer's city |
| `state` | Customer's state |
| `category` | Product category |
| `product_name` | Name of the product |
| `sales` | Total sales amount |
| `quantity` | Number of units sold |
| `profit` | Profit generated from the sale |
| `Profit Margin` | Profit earned as a percentage of sales |

---

## 🔍 Business Questions Answered

The project answers the following key business questions:

### Q1. Total Sales and Profit by Category
Analyze which product categories generate the highest sales and profit.

### Q2. Sales and Profit Trend
Track changes in sales and profit over time to identify business growth patterns.

### Q3. Top 10 States by Total Sales
Identify the states generating the highest revenue.

### Q4. Share of Sales by Shipping Status
Compare total sales between orders delivered **On Time** and orders marked as **Delay**.

### Q5. Most Profitable Products
Identify the products generating the highest total profit.

### Q6. Average Profit Margin by Category
Compare the profitability of different product categories.

### Q7. Sales and Profit by Quarter
Analyze quarterly sales and profit performance.

### Q8. Top 10 Customers by Spending
Identify the customers with the highest total purchase value.

### Q9. Average Metrics by Shipping Status
Compare average sales and average quantity sold for different shipping statuses.

### Q10. Top 10 Cities by Quantity Sold
Identify the cities with the highest product demand based on quantity sold.

---

## 🛠️ Tools and Technologies Used

- **Microsoft Excel**
- Pivot Tables
- Pivot Charts
- Excel Dashboard
- Data Cleaning
- Data Analysis
- Business Intelligence Concepts

---

## 📈 Key Performance Indicators

The dashboard focuses on the following KPIs:

- 💰 Total Sales
- 📈 Total Profit
- 📦 Total Quantity Sold
- 📊 Average Profit Margin
- 🏆 Top Performing Categories
- 🌎 Top States and Cities
- 👥 Top Customers
- 🚚 Shipping Performance

---

## 📊 Analysis Performed

### 1. Category Performance Analysis

Sales and profit were analyzed across different product categories to identify the most valuable product segments.

### 2. Sales Trend Analysis

Sales and profit trends were evaluated over time to understand business performance and growth patterns.

### 3. Geographic Analysis

State-wise and city-wise analysis was performed to identify regions with high sales volume and product demand.

### 4. Customer Analysis

The top customers were identified based on their total spending.

### 5. Product Profitability Analysis

Products were compared based on the total profit generated to identify high-performing products.

### 6. Shipping Status Analysis

Orders were divided based on shipping performance:

- On Time
- Delay

The analysis compares sales, average sales, and average quantity between these shipping statuses.

### 7. Profit Margin Analysis

Average profit margins were calculated for each product category to determine which categories are the most profitable.

---

## 📂 Project Structure

```text
Amazon-Walmart-Sales-Analysis/
│
├── _amazon_walmart_sales.xlsx
│
├── _Amazon_walmart_sales
│   └── Raw sales dataset
│
├── Q.1
│   └── Total Sales and Profit by Category
│
├── Q.2
│   └── Sales and Profit Trend
│
├── Q.3
│   └── Top 10 States by Total Sales
│
├── Q.4
│   └── Share of Sales by Shipping Status
│
├── Q.5
│   └── Most Profitable Products
│
├── Q.6
│   └── Average Profit Margin by Category
│
├── Q.7
│   └── Sales and Profit by Quarter
│
├── Q.8
│   └── Top 10 Customers by Spending
│
├── Q.9
│   └── Average Metrics by Shipping Status
│
├── Q.10
│   └── Top 10 Cities by Quantity Sold
│
└── DASHBOARD
    └── Interactive Sales Dashboard
