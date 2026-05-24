# Superstore Sales Dashboard — Power BI

## Overview
An interactive sales analytics dashboard built in Power BI 
using the Sample Superstore dataset. The dashboard analyzes 
$2.3M in retail sales across regions, categories, and 
customer segments.

## Dashboard Features
- **Total Sales** — $2.3M
- **Total Profit** — $286K
- **Profit Margin** — 12%
- **Total Orders** — 5K

## Visuals Included
- KPI Cards (Sales, Profit, Margin, Orders)
- Sales Trend by Month (Line Chart)
- Sales by Category (Bar Chart)
- Sales by Region (Donut Chart)
- Sales by Segment (Pie Chart)
- Top Customers (Bar Chart)
- Year Slicer (Filter)

## Tools Used
- Power BI Desktop
- Power Query (Data Transformation)
- DAX (Measures)

## Data Source
Sample Superstore Dataset — publicly available on Kaggle
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

## Key DAX Measures
- Total Sales = SUM(Sales)
- Total Profit = SUM(Profit)
- Profit Margin % = DIVIDE(Total Profit, Total Sales)
- Total Orders = DISTINCTCOUNT(Order ID)

#Includes dashboard screenshot 

## Author
Amnshu Khanal
