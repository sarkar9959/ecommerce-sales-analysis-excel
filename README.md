# ecommerce-sales-analysis-excel
Excel dashboard project | Power Pivot | DAX | Data Cleaning | Data Modeling | Sales &amp; Customer Analytics
# 📊 E-Commerce Sales Analysis Dashboard

An interactive Excel dashboard analyzing e-commerce sales performance, built with Power Pivot and DAX, covering sales trends, customer segmentation, product categories, and payment behavior.

## 🔍 Overview

This project analyzes e-commerce transaction data to uncover insights on sales performance, customer tiers, product categories, and regional trends. The dashboard is fully interactive, allowing users to filter data by year using a slicer.

## 📁 Dataset

- **Source:** Kaggle
- **Tables used:** Customers, Products, Sales, Date (custom-built calendar table)
- **Data preparation:**
  - Cleaned raw data and handled inconsistencies
  - Validated multiple columns for accuracy
  - Built a custom Date/Calendar table for time intelligence
  - Established relationships between Customers, Products, Sales, and Date tables in the data model

## 🛠️ Tools & Techniques

- Microsoft Excel
- Power Pivot (Data Modeling)
- DAX Measures
- Pivot Tables & Pivot Charts
- Slicers for interactivity
- Waterfall, Combo, Donut, and Map charts

## 📈 Dashboard Features

- **KPI Cards:** Total Sales, Total Orders, Total Quantity, Overall AOV, Total Customers — each with sparklines and YoY growth (calculated using the Same Period Last Year / SPLY method)
- **Sales by Top 6 States:** Bar chart with corresponding map visualization
- **Sales by Age Category:** Combo chart (sales amount vs. order count)
- **Orders by Customer Tier:** Waterfall chart showing Platinum/Gold/Silver contribution
- **Sales by Category:** Category-wise revenue breakdown
- **Top 10 Brands:** Brand-wise sales performance
- **Payment Mode Distribution:** Donut chart (UPI, COD, Credit Card, Debit Card)
- **Date Slicer:** Year-wise filtering (2024–2026)

## 💡 Key Findings

1. **Category concentration:** Electronics contributes 72.68% of total sales, making it the primary revenue driver.
2. **Customer tier:** Platinum customers account for 76.68% of tier-eligible orders, showing strong reliance on the top tier.
3. **Age group:** Adult, Middle Age, and Young customers together generate 90.55% of total sales.
4. **Payment mode:** UPI and COD together account for 84.62% of all payments.

## 📝 Notes

- Charts (waterfall, map) were intentionally included to demonstrate a variety of Excel visualization techniques.
- Customers not eligible for the tier program are excluded from the Orders by Customer_Tier chart.
- YoY growth is calculated using the Same Period Last Year (SPLY) method.


## 📸 Preview

![Dashboard Screenshot](#) 
