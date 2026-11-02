ABC Executive Sales Dashboard | Power BI

Project Overview

An interactive Executive Sales Dashboard developed using Microsoft Power BI to analyze sales performance, revenue, profitability, customer segments, and product categories.

Dataset

The project uses a Sales Data table containing the following columns:

- ID, Order Date, Country, Region
- Customer Type, Product, Product Category
- Sales Channel, Units Sold
- Unit Cost, Unit Price, COGS
- Discount, Revenue, Gross Profit, Gross Margin

Data Modeling

The Power BI data model consists of three tables:

- Sales Data: Original sales transaction data.
- Date Table: Created using DAX with Date, Day Name, Month Name, Month Number, Quarter, and Year columns.
- Measures Table: Created to organize important DAX measures.

A relationship was established between the Sales Data and Date Table for time-based analysis.

Key DAX Measures

- Total Revenue
- Total Gross Profit
- Total Orders
- Total Sold Quantity
- Gross Margin

Dashboard Visualizations

- KPI Cards: Revenue, Gross Profit, Gross Margin, Orders, and Sold Quantity.
- Line Chart: Month-wise Revenue and Profit.
- Bar Chart: Top 5 Countries by Revenue.
- Bar Chart: Bottom 5 Countries by Revenue.
- Column Chart: Revenue by Customer Type.
- Pie Chart: Sales Channel Revenue Comparison.
- Donut Chart: Product Category-wise Revenue.

Interactive Filters

- Month Name
- Product Category
- Region

Tools & Technologies

- Microsoft Power BI
- DAX
- Data Modeling
- Data Visualization

Project Objective

To analyze sales data, track key business performance indicators, compare sales across different categories, and present useful insights through an interactive executive dashboard.
