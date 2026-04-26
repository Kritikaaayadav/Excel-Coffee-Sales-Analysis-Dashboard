# ☕Excel-Coffee-Sales-Analysis-Dashboard

This project is a *Coffee Sales Analysis Dashboard* created in *Microsoft Excel* as part of my data analytics portfolio.  
It demonstrates the process of *data cleaning, transformation, and visualization* using Excel formulas, Pivot Tables, and interactive dashboards.  

The goal was to analyze coffee sales data from different countries, coffee types, and time periods to uncover key sales insights and trends.

## Dataset Information
The dataset consists of three tables:
- Orders
- Customers
- Products

These tables were linked using lookup formulas to gather complete information for analysis.

## Data Cleaning & Transformation Steps
Performed step-by-step in Excel:
1. Gathered data from multiple tables using:
   - XLOOKUP() to fetch customer and product information  
   - INDEX-MATCH for product details (like coffee type)
2. Cleaned missing values
3. Standardized text and date formats
4. Expanded abbreviations for readibility:<br>
   *Coffee type:*<br>
   'Rob'-'Robusta'<br>
   'Ex'-'Excelsa'<br>
   'Ara'-'Arabica'<br>
   'Lib'-'Liberica'<br>
   *Roast Type:*<br>
   'M'-'Medium',<br>
   'L'-'Light',<br>
   'D'-'Dark'<br>
5. Created calculated columns:
   - Sales = Unit Price × Quantity
   - Total Sales for aggregation
6. Formatted data:
   - Currency → USD ($)
   - Size column → added “kg” suffix (0.0 "kg")
7. Removed duplicates and ensured all tables were named as structured
## Dashboard Creation Process
1. Inserted *Pivot Tables* from cleaned dataset  
2. Created multiple visualizations:
   - Line Chart → Total Sales Over Time
   - Bar Chart → Sales by Country
   - Bar Chart → Top 5 Customers
3. Added *slicers and filters* for:
   - Date range
   - Coffee Type
   - Roast Type
   - Loyalty Card
   - Size
4. Applied professional formatting and theme (pink & light pink background)
## Tools Used
- Microsoft Excel
  - Data Cleaning
  - Pivot Tables
  - Pivot Charts
  - Dashboard Design
## Key Insights
   -**United States** generated the highest revenue(~$35,639).<br>
   -**Arabica** and **Liberica** are the top-selling coffee types by total revenue.<br>
   -**Medium roast** generated the highest sales compared to other roast types.<br>
   -Peak sales occur in mid-year months,showing strong seasonal patterns.<br>
   -Customers from **United States** and **Ireland** contribute the most to total sales.<br>

## Data Source
Dataset inspired by [Mo Chen's Excel Portfolio Project On Youtube]


