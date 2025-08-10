# Superstore Sales & Profit Dashboard

## Overview
This Power BI dashboard analyzes sales, profit, and orders from the Superstore dataset.  
It provides insights by category, state, and month-year trends, with key performance metrics.

## Dataset
- Name: Superstore.csv
- Source: GitHub Superstore dataset
- Contains order details including Order Date, Sales, Profit, Quantity, Discount, Category, Region, and State.

## Key Metrics (DAX Calculations)
- **Total Sales**: SUM('Superstore'[Sales])
- **Total Profit**: SUM('Superstore'[Profit])
- **Total Orders**: COUNTROWS('Superstore')
- **Profit Margin**: DIVIDE([Total Profit], [Total Sales])

## Visuals Created
- KPI Cards: Total Sales, Total Profit, Total Orders, Profit Margin
- Bar Chart: Total Sales by Category
- Map: Total Sales by State
- Line Chart: Total Sales & Total Profit over Time
- Table: Category-wise & Sub-category-wise Sales & Profit
- Slicers: Region, Year, Category

## Insights
- Technology leads in total sales.
- East region shows higher profit margins.
- Peak sales observed in November–December.
- Some sub-categories, despite high sales, have low profit margins.

## How to Open
1. Download the `.pbix` file from the `PBIX_File` folder.
2. Open it in Power BI Desktop.
3. Use slicers to explore the data.

---

**Author**: Ajay Yadav  
