# E-Commerce Sales & Profit Analytics

## Project Overview

This project analyzes the Superstore e-commerce dataset to understand
sales, profitability, customer segments, product performance, regional
performance, and the relationship between discounts and profit.

## Objectives

-   Analyze overall sales and profit performance
-   Identify high- and low-performing categories, regions, products, and
    segments
-   Analyze yearly sales and profit trends
-   Examine the relationship between discount levels and average profit
-   Build an interactive Power BI dashboard

## Dataset

**Dataset:** Sample Superstore\
**Rows:** 9,994\
**Columns:** 21

Key fields include Order Date, Ship Date, Segment, Region, Category,
Product Name, Sales, Quantity, Discount, and Profit.

## Tools & Technologies

Python, Pandas, NumPy, Matplotlib, SQLite/SQL, Power BI, Google Colab

## Project Workflow

**CSV → Python/Pandas → SQL → Power BI**

## Analysis Performed

-   Data structure, missing-value, and duplicate checks
-   Date conversion and shipping-days calculation
-   Sales, profit, quantity, and profit-margin calculations
-   Category, region, segment, product, and shipping analysis
-   Year-over-year analysis
-   Discount vs. average profit analysis
-   SQL business queries for product, region, category, segment, year,
    shipping mode, and discount analysis

## Power BI Dashboard

The dashboard includes: - Total Sales, Total Profit, Total Quantity, and
Profit Margin KPIs - Yearly Sales & Profit trend - Profit by Category
and Region - Top 10 Products by Profit - Sales & Profit by Segment -
Discount vs. Average Profit scatter plot - Year, Region, and Category
slicers

## Key Findings

-   Total Sales: **\$2.297M**
-   Total Profit: **\$286.4K**
-   Total Quantity: **37,873**
-   Overall Profit Margin: **12.47%**
-   Technology generated the highest total profit among categories.
-   West generated the highest total regional profit.
-   Consumer contributed the highest overall sales and profit.
-   Higher discount levels were generally associated with lower average
    profit in the dataset.
-   Canon imageCLASS 2200 Advanced Copier was the highest-profit
    product.

## Business Takeaways

The analysis highlights profitable categories, regions, products, and
customer segments while showing where higher discounts are associated
with weaker profitability. The Power BI dashboard provides an
interactive way to explore these patterns.

## Project Structure

``` text
E-Commerce-Sales-Analytics/
├── Sample - Superstore.csv
├── E-Commerce_Sales_Analytics.ipynb
├── superstore.db
├── E-Commerce_Sales_Dashboard.pbix
└── README.md
```

## Author

**Data Analytics Portfolio Project**

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- SQL (SQLite)
- Power BI
- GitHub

## Project Workflow

CSV Dataset → Python Data Cleaning & EDA → SQL Analysis → Power BI Dashboard

## Key Metrics

- Total Sales: $2.297M
- Total Profit: $286.4K
- Total Quantity: 37,873
- Profit Margin: 12.47%

## Key Insights

- Technology generated the highest profit among the categories.
- West region generated the highest sales and profit.
- 2016 and 2017 showed strong sales and profit growth.
- Higher discount levels were associated with lower average profitability.
- Consumer segment generated the highest total sales and profit.
- Canon imageCLASS 2200 Advanced Copier was the highest-profit product.

## Power BI Dashboard

The interactive dashboard includes KPI cards, yearly sales and profit trends, category and regional analysis, product profitability, segment analysis, discount analysis, and interactive slicers.

## Project Files

- `E-Commerce_Sales_Analytics.ipynb` — Python and SQL analysis
- `E-Commerce_sales_analytics.pbix` — Power BI dashboard
- `README.md` — Project documentation
