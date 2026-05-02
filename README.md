# ☕ Coffee Shop – SQL Data Analysis Project

## 📌 Project Overview

This project focuses on analyzing coffee sales data across multiple cities using SQL. The goal is to extract meaningful business insights related to customer behavior, product performance, revenue trends, and market potential for a coffee business.

The analysis is performed using relational datasets such as **city, customers, products, and sales** tables.

---

## 🗂️ Dataset Tables

* **city** – Contains city-level data including population and estimated rent
* **customers** – Customer details mapped to cities
* **products** – Coffee product catalog
* **sales** – Transaction-level sales data

---

## 🧠 Key Business Problems Solved

### 1. Coffee Consumers Estimation

* Estimated coffee consumers per city (assuming 25% consumption rate)

### 2. Total Revenue Analysis

* Total revenue generated in Q4 2023
* City-wise revenue comparison

### 3. Product Performance

* Total units sold per coffee product
* Top-performing products across cities

### 4. Customer Insights

* Average sales per customer by city
* Unique customers purchasing coffee products
* Customer segmentation based on purchasing behavior

### 5. Market & Population Analysis

* Estimated coffee consumers vs actual customers
* City population impact on sales

### 6. Top Products by City

* Top 3 best-selling products in each city using window functions

### 7. Rent vs Revenue Analysis

* Comparison between average customer spending and rent burden per customer

### 8. Monthly Sales Growth

* Month-over-month sales growth rate by city using LAG function

### 9. Market Potential Analysis

* Identification of top 3 high-potential cities based on:

  * Total sales
  * Customer base
  * Rent efficiency
  * Estimated coffee demand

---

## 📊 Key Insights

* Cities like **Pune, Delhi, and Jaipur** show strong market potential
* Certain cities have **high customer base but low revenue efficiency**
* Sales performance varies significantly across cities and product categories
* Rent-to-customer ratio helps identify profitable expansion regions

---

## 📁 Project Structure

```
 coffee-shop-expansion-analysis
 ┣  analysis.sql
 ┣  README.md
```

---

## 🛠️ Tools & Technologies

* SQL (PostgreSQL / MySQL compatible syntax)
* Window Functions (LAG, RANK, DENSE_RANK)
* Aggregations & Joins
* CTEs (Common Table Expressions)

---

## 🚀 Key Learnings

* Advanced SQL querying for business analytics
* Real-world data modeling using relational tables
* Revenue, customer, and market segmentation analysis
* Time-series analysis using SQL window functions

---

## 📌 Conclusion

This project demonstrates how SQL can be used to derive powerful business insights from raw transactional data. It helps in understanding customer behavior, product demand, and identifying high-growth market opportunities.

---

## 👤 Author

**Kshitiz Singh**

---



