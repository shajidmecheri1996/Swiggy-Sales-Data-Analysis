# 🍔 Swiggy Sales Data Analysis Project

## Overview

This project is an end-to-end **exploratory and trend analysis** of Swiggy food order data. The goal is not just to calculate metrics, but to understand **how sales, demand, and customer behavior change over time** using practical data analytics techniques.

The analysis focuses on **time-based trends (weekly & quarterly)**, revenue contribution, and basic performance indicators that are commonly expected in real-world business analysis and entry-level data analyst roles.

This project is built to reflect **industry-style thinking**, not just academic exercises.

---

## Objectives

* Analyze **overall sales performance**
* Identify **weekly and quarterly trends** in revenue
* Understand **order volume patterns**
* Evaluate **average customer ratings over time**
* Present insights in a clean, business-readable format

---

## Dataset Description

The dataset represents Swiggy food order transactions and includes the following key fields:

* **Order Date** – Date of order placement
* **Food Category** – Category of food ordered
* **Price (INR)** – Order value
* **Rating** – Customer rating for the order

Each row represents a **single order**.

---

## Key Analysis Performed

### 1. Overall Business Metrics

* **Total Sales (₹)** – Overall revenue generated from all food orders
* **Average Rating** – Overall customer satisfaction across restaurants
* **Average Order Value (₹)** – Revenue generated per order
* **Ratings Count** – Total number of customer reviews
* **Total Orders** – Number of food orders received

### 2. Time-Based Trend Analysis

* **Monthly Sales Trend** – Examines how total sales fluctuate month by month
* **Daily Sales Trend** – Analyzes order and revenue variations across days of the week
* **Weekly Trend Analysis** – Monitors weekly sales fluctuations to identify consistency and peak demand periods
* **Quarterly Performance Summary** – Combined view of sales, ratings, and order volume by quarter

### 3. Revenue Distribution Analysis

* **Total Sales by Food Type (Veg vs Non-Veg)** – Compares revenue contribution by food preference
* **Total Sales by State (Map Visualization)** – Displays state-wise revenue distribution across India
* **Top 5 Cities by Sales** – Identifies cities contributing the highest revenue

---

## Tools & Technologies Used

* **Python**
* **Pandas** – Data manipulation and aggregation
* **NumPy** – Numerical operations
* **Plotly** – Interactive data visualizations
* **Google Colab** – Analysis environment

---

## Key Insights (High-Level)

* Revenue shows **clear monthly and weekly seasonality**, with specific periods consistently outperforming others
* Daily trends highlight **demand concentration on certain weekdays**, indicating customer ordering behavior patterns
* Veg vs Non-Veg analysis reveals **distinct revenue contribution differences** across food types
* A small number of cities and states contribute a **disproportionately high share of total revenue**
* Weekly and quarterly aggregation helps separate **short-term noise from long-term performance trends**

---

## Project Structure

```
Swiggy_Sales_Analysis/
│
├── Swiggy_Sales.ipynb   # Main analysis notebook
├── README.md           # Project documentation
```

---

## Why This Project Matters

This project demonstrates:

* Practical use of **time-series aggregation**
* Business-oriented thinking (not just code execution)
* Clean, reproducible analysis suitable for **real-world datasets**

It is designed to reflect how a **data analyst would actually explore sales data** in a food delivery or e-commerce company.

---

## Future Improvements

* Add city-level or restaurant-level segmentation
* Forecast future demand using time-series models
* Build an interactive dashboard for stakeholders

---

## Author

**Shajid**
Aspiring Data Analyst | Python | SQL | Data Visualization

---
