# ECommerce_project2

## Project Overview
This project performs an **end-to-end data analysis** on an E-Commerce dataset to uncover insights regarding sales, profit, and overall business performance. By utilizing **Python** for data processing and **Power BI** for visualization, the analysis identifies key trends, identifies loss-making areas, and evaluates the impact of discount strategies on the bottom line.

## Problem Statement
E-commerce businesses frequently struggle with:
*   High sales volumes that result in low or even negative profit.
*   **Ineffective discount strategies** that erode margins.
*   Uneven performance across different geographical regions and product categories.
*   A lack of visibility into seasonal trends and performance fluctuations.

## Objectives
*   Identify the primary factors affecting overall profitability.
*   Detect specific **loss-making products** and regions.
*   Analyze historical sales trends to understand seasonality.
*   Evaluate how different discount levels impact profit margins.
*   Provide actionable, data-driven recommendations for business improvement.

## Tools & Technologies
*   **Language:** Python (Pandas, NumPy).
*   **Visualization:** Matplotlib, Seaborn, Power BI.
*   **Environment:** Jupyter Notebook.

## Dataset Information
*   **Source:** Kaggle (Global Superstore / E-Commerce Dataset).
*   **Size:** 50,000+ records.
*   **Key Features:** Order Date, Sales, Profit, Discount, Category, Sub-Category, and Region.

## Project Workflow

### 1. Data Cleaning (Python + Power BI)
*   Handled missing values in date fields and converted columns to proper `datetime` formats.
*   Cleaned the 'Sales' column by removing special characters and converting it to a numeric type.
*   Removed duplicates and resolved data type inconsistencies.

### 2. Feature Engineering
*   Extracted `month` and `month_name` for seasonal analysis.
*   Calculated **Profit Margin** using safe division methods.
*   Created **discount bins** to categorize and analyze the impact of various discount ranges.

### 3. Exploratory Data Analysis (EDA)
*   **Overall Performance:** Total Sales reached **12.6M+**, with a Total Profit of **1.46M+** across **25K+** orders.
*   **Category Insights:** **Technology** is the most profitable category, while **Furniture** shows the lowest profit.
*   **Loss Leaders:** While Phones and Copiers are high-profit items, **Tables** are consistently loss-making.
*   **Regional Performance:** The **Central** region performs best, whereas **Southeast Asia** sees low profit despite strong sales volumes.
*   **Seasonality:** There is a clear **Q4 peak**, with highest sales in November and December and lowest in February.

## Key Finding: The Discount Impact
The analysis revealed a critical threshold for discounting:
*   **0 – 17% Discount:** Positive Profit.
*   **17 – 34% Discount:** Low Profit.
*   **34%+ Discount:** Negative Profit (Loss).
*   **Conclusion:** Discounts exceeding **30%** are the primary driver of business losses.

## Power BI Dashboard Features
The interactive dashboard includes:
*   **KPI Cards:** Real-time visibility into Sales, Profit, Orders, and Profit Margin.
*   **Trend Analysis:** Monthly sales and profit tracking to visualize seasonality.
*   **Granular Views:** Category, sub-category, and regional performance breakdowns.
*   **Interactive Filters:** Ability to slice data by Year, Region, and Category.

## Business Recommendations
*   **Limit discounts to below 30%** to prevent margin erosion.
*   Focus marketing and inventory efforts on high-profit sub-categories like **Copiers** and **Technology**.
*   Re-evaluate pricing or supply chain costs for loss-making items such as **Tables**.
*   Investigate and improve operational efficiencies in low-profit regions like Southeast Asia.

---

**Author:** [Aditya Kaushal]
*Aspiring Data Analyst | Aerospace Engineering (Dual Degree )*
