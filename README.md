# ECommerce_project2

##  Project Overview

This project performs **end-to-end data analysis** on an E-Commerce dataset to uncover insights on sales, profit, and business performance. The analysis identifies key trends, loss-making areas, and the impact of discount strategies using Python and Power BI.

---

## Problem Statement

E-commerce businesses often face challenges such as:

* High sales but low or negative profit
* Ineffective discount strategies
* Uneven performance across regions and categories
* Lack of visibility into seasonal trends

 This project aims to:

* Identify factors affecting profitability
* Detect loss-making products and regions
* Analyze sales trends over time
* Provide data-driven recommendations

---

## Objectives

* Analyze overall sales and profit
* Identify profitable and loss-making categories
* Understand regional performance
* Analyze monthly and seasonal trends
* Evaluate the impact of discounts on profit

---

##  Tools & Technologies

* **Python** (Pandas, NumPy)
* **Data Visualization**: Matplotlib, Seaborn
* **Power BI** 
* Jupyter Notebook

---

##  Dataset

* Source: Kaggle (Global Superstore / E-Commerce Dataset)
* Records: 50,000+ rows
* Features: Orders, Sales, Profit, Discount, Category, Region, Dates

---

## Project Workflow

### 1️ Data Cleaning (Python + Power BI)

* Handled missing values in `order_date`
* Converted date columns to datetime format
* Cleaned `sales` column (removed commas, converted to numeric)
* Fixed data types and removed inconsistencies
* Checked and handled duplicates

---

### 2️ Feature Engineering

* Extracted `month` and `month_name`
* Created `profit_margin` using safe calculation
* Created discount bins for analysis

---

### 3️ Exploratory Data Analysis (EDA)

####  Overall Performance

* Total Sales: **12.6M+**
* Total Profit: **1.46M+**
* Total Orders: **25K+**

---

### Category Analysis

* Technology → Highest profit
* Furniture → Lowest profit

---

### Sub-Category Analysis

* High Profit: Copiers, Phones
* Loss-Making: Tables 

---

###  Region Analysis

* Central → Highest performance
* Southeast Asia → Low profit despite good sales ⚠

---

###  Monthly Trend

* Peak Sales: November & December
* Lowest Sales: February
* Strong seasonal trend (Q4 peak)

---

###  Discount vs Profit Analysis

| Discount Range | Avg Profit      |
| -------------- | --------------- |
| 0 – 0.17       | Positive        |
| 0.17 – 0.34    | Low Profit      |
| 0.34+          | Negative (Loss) |

 **Key Finding:**
Discounts above **30% lead to losses**

---

##  Power BI Dashboard

### Features:

* KPI Cards (Sales, Profit, Orders, Profit Margin)
* Category & Sub-category analysis
* Region-wise performance
* Monthly trend (Sales & Profit)
* Discount vs Profit analysis
* Interactive filters (Year, Region, Category)

---

##  Key Insights

* Business shows strong **seasonality (Q4 peak)**
* Some products generate **loss despite high sales**
* **Discounting is the main reason for losses**
* Regional performance varies significantly

---

##  Business Recommendations

* Limit discounts below **30%**
* Focus on high-profit products (Copiers, Technology)
* Re-evaluate pricing for loss-making items (Tables)
* Improve performance in low-profit regions

---

##  Project Outcome

This project demonstrates:

* Data cleaning & preprocessing
* Feature engineering
* Data visualization
* Business insight generation
* Dashboard creation using Power BI

---

##  Author

**Aditya Kaushal**
Aspiring Data Analyst | Aerospace Engineering (Dual Degree)




