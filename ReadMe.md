Sales Analysis and Performance Dashboard

Project Overview

This project involves the creation of a comprehensive Power BI dashboard to analyze sales data from 2017 to 2019. The goal was to transform raw data into actionable insights, covering financial performance, product trends, and geographic sales distribution.

Data Sources

The analysis is based on four primary datasets:

Sales Orders: The core transactional table containing order dates, quantities, prices, and costs.

Customers: A list of all customers indexed by ID.

Products: A catalog of products indexed by ID.

Regions: Geographic data linking sales to specific suburbs and cities.

Data Transformation (Power Query)

To enable deeper analysis, the raw data was transformed using Power Query. Key transformations included:

New Calculated Columns:

Total Revenue = Order Quantity * Unit Selling Price

Total Cost = Order Quantity * Unit Cost

Total Profit = Total Revenue - Total Cost

Profit Margin = Total Profit / Total Revenue

Shipping Time (Days) = Ship Date - Order Date

Data Modeling

A Star Schema model was implemented to ensure efficient reporting:

Fact Table: Sales Orders

Dimension Tables: Customers, Products, Regions

Relationships: All dimension tables are linked to the Sales Orders table via one-to-many relationships.

Dashboard Structure

1. Introduction (Landing Page)

A professional navigation hub featuring:

A clean header with the project title.

High-level KPI cards for Total Revenue, Profit, Quantity, and Customers.

Interactive buttons for navigating to all other report pages.

2. Financial Summary

A high-level executive view of the company's financial health, featuring:

DAX Measures: Custom calculations for Total Revenue, Total Cost, and Total Profit.

Visuals:

KPI Cards for core metrics.

Line & Stacked Column Chart showing Revenue and Profit trends over time.

Donut chart for Profit by Channel.

Bar charts ranking Revenue by City and Customer (Top 10).

3. Logistics & Profitability Analysis

A focused analysis of operational efficiency, highlighting:

Average Shipping Time: Visualized by city to identify logistical bottlenecks.

Profitability: Bar charts identifying the most profitable products and channels.

4. Product & Regional Analysis

Detailed breakdowns of sales performance:

Treemap: Visualizing the Top 10 Products by Revenue.

Map Visual: Geographic distribution of sales across different regions.

5. Advanced Analytics (R Visuals)

Incorporation of R scripts for statistical visualization:

Violin Plot: To analyze profit distribution and density across sales channels.

Frequency Polygon: To visualize the distribution of profit per order.

Scatter Plot with Trendline: To assess the correlation between Order Cost and Revenue.

Hexagonal Heatmap: To identify concentrations of cost vs. revenue data points.

6. Performance & Trends

A review of historical performance using advanced Power BI visuals:

Matrix Heatmap: A conditional formatting visual showing Profit by Month and Year to spot seasonal trends.

Gauge Chart: Tracking the Average Profit Margin against a corporate target.

Key Findings & Conclusion

Financials: The company generated over $21.4M in revenue and $7.1M in profit, with strong seasonal peaks in Q4.

Channel Strategy: The Wholesale channel is the primary revenue driver.

Product Mix: Product 7 and Product 11 are the top-performing SKUs.

Geography: Sales are heavily concentrated in Auckland, Christchurch, and Hamilton.

Operations: Shipping times vary significantly by region, presenting an opportunity for logistical optimization.

Tools Used

Microsoft Power BI Desktop

R (ggplot2, dplyr libraries)

Power Query Editor

DAX (Data Analysis Expressions)