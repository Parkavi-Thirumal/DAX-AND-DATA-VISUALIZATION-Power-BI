# 📊Ecommerce_Sales-_Analysis-Power-BI
## Objective
This project focuses on E-Commerce Sales Analysis using Power BI. The objective was to analyze sales data, create key business metrics using DAX (Data Analysis Expressions), and build an interactive dashboard to monitor sales performance, profitability, target achievement, and business trends for data-driven decision-making.
## Project Workflow
- Import Data
- Data Cleaning and Transformation
- Data Modeling and Relationships
- DAX Calculated Columns & Measures
- Dashboard Development and Visualization
## Tools Used
- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Visualization for Dashboard
## Data Preparation
### Import Data
Imported datasets using Get Data → Text/CSV
- Data Cleaning & Transformation
    - List of Orders
        - Promoted first row as headers
        - Removed blank rows
        - Validated data using count and distinct count statistics
        - Extracted month names from order dates
    - Order Details
        - Converted Amount and Profit to Fixed Decimal Number
        - Converted Quantity to Whole Number
        - Cleaned and trimmed Category values
    - Sales Target
        - Extracted month names from order dates
        - Converted Target column to Fixed Decimal Number
        - Loaded transformed data into Power BI using Close & Apply
### Data Modeling
Created relationships by connecting:
- Order Details (Fact Table)
- List of Orders using Order ID as the primary key
### DAX Calucation
  - DAX Columns
      - Category Type
      - Revenue
      - Sales Category
      - Profit Status
      - Order Size
  - DAX Measures
      - Total Orders
      - YTD Sales
      - Total Sales
      - Total Profit
### Dashboard Visualizations
- 📈 Sales Target Achievement by Category- Clustered Column Chart
    - Compares Total Sales against Total Target across categories
- 🥧 Max Profit Margin by Category- Donut Chart
    - Displays profit margin contribution by category
- 📊 Max Profit Margin and Revenue by Sub-Category- Line and Stacked Column Chart
    - Analyzes profit margin and revenue distribution by sub-category
- 📉 Monthly Sales Target Trend- Line Chart
    - Shows monthly target performance by category
- 🔵 Profit vs Quantity Analysis- Scatter Chart
    - Compares profitability against quantity sold for each sub-category
- 🎯 KPI Cards
  KPIs included:
    - Total Sales
    - Total Profit
    - Total Orders
    - Total Target
    - Sales Achievement %
    - Profit Margin %
    - Average Profit in Delhi
    - YTD Sales
## Key Insights
- Built a complete end-to-end Power BI solution from data preparation to reporting.
- Applied DAX functions for business calculations and KPI creation.
- Designed an interactive dashboard for sales performance monitoring.
- Implemented data modeling, calculated columns, measures, and calculated tables.
- Created multiple visualizations to support business analysis and decision-making.
## Conclusion
This project demonstrates the effective use of Power BI for e-commerce sales analysis. Through data modeling, DAX calculations, and interactive visualizations, the dashboard provides valuable insights into sales performance, profitability, and target achievement. The analysis supports informed business decisions and highlights opportunities for growth and optimization
## Author
Parkavi Thirumal
- Technology: Power BI | DAX | Data Visualization | Business Intelligence
- Project Type: E-Commerce Sales Analysis Dashboard
       
