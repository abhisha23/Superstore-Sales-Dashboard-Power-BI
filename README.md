# 🛒 Superstore Sales Dashboard — Power BI

## Overview
An intermediate-level interactive Power BI dashboard 
analyzing US retail performance across 4 years (2014–2017) 
using the Kaggle Superstore dataset (9,994 rows). 
Built to demonstrate real-world BI skills including 
data modeling, DAX, and interactive report design.

## 📊 Dashboard Pages

### Page 1 — Executive Overview
- 4 KPI cards: Total Sales, Total Profit, 
  Profit Margin %, Total Orders
- Line chart: Monthly Sales & Profit trend
- Bar chart: Sales by Region with Profit Margin tooltip
- Donut chart: Sales by Customer Segment
- Slicers: Year, Region, Category

### Page 2 — Product Analysis
- Column chart: Sales vs Profit by Category
- Matrix: Sub-Category x Region with red/green 
  conditional formatting highlighting loss-making areas
- Scatter plot: Sales vs Profit bubble chart 
  identifying discount problem areas

### Page 3 — Customer Drillthrough
- Drillthrough page filtered per customer
- KPI cards, order history table, 
  monthly trend, shipping breakdown
- Back button navigation

## 🔧 Technical Features
- Star schema data model
- Dedicated DAX Date table with time intelligence
- DAX measures: Total Sales, Total Profit, 
  Profit Margin %, Total Orders, Sales YoY %, 
  Sales LY, Sales YTD, Product Rank
- Conditional formatting on matrix visual
- Drillthrough navigation between pages
- Dynamic slicers cross-filtering all visuals
- Power Query transformations:
  - Data type enforcement
  - Days to Ship calculated column
  - Year and Month extraction

## 📁 Files
| File | Description |
|------|-------------|
| Superstore_PowerBI_Dashboard.pbix | Power BI report file |
| Sample_Superstore.csv | Source dataset |

## 📷 Screenshots
![Executive Overview](page1_overview.png)
![Product Analysis](page2_products.png)
![Customer Drillthrough](page3_drillthrough.png)

## 🗂️ Dataset
Kaggle Superstore Dataset
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final
- 9,994 rows
- US retail orders 2014–2017
- Columns: Order ID, Date, Customer, 
  Region, Category, Sales, Profit, Discount

## 🛠️ Tools Used
- Power BI Desktop
- Power Query (ETL & data cleaning)
- DAX (calculated measures & columns)
