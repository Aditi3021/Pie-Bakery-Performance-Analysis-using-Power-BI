# Pie-Bakery-Performance-Analysis-using-Power-BI

Power Bi Dashboard Insights:
 🥯Analyzing Pie Bakery Industry Revenue Trends:-

Problem Statement:
In the competitive bakery industry, optimizing operations and understanding revenue trends are critical for maintaining growth and profitability. 

Objective:
The goal is to analyze and visualize bakery revenue trends using dimensions such as order types, organic status, pie flavors, and pie types. 

Organic vs Non-Organic Revenue Trends:
Organic pies have a smaller share of total orders, but they generate a higher average revenue per order. This suggests that customers are willing to pay a premium for organic bakery products.

Pie Type Preferences: (Whole vs Slice Pies)
Whole pies generate the highest revenue, but slices are showing a growing trend, especially in online orders.

Revenue Trends by Day of the Week:
The ribbon chart highlights that weekends, especially Saturdays and Sundays, are the most profitable days, generating the majority of revenue.

Quarterly Revenue Trends:
The column chart shows that the 4th quarter (October–December) generates the highest revenue, driven largely by holiday season orders and seasonal pies.

DAX Measures and Data Model:
Calendar Table:
A DAX-based calendar table was created to facilitate time-based analysis.

Custom DAX Measures:
Total Revenue: Aggregates overall sales.
Cumulative Revenue: Tracks cumulative revenue over time.
2020 Revenue and 2021 Revenue: Separates yearly revenue for year-over-year comparison.
Total Orders, Total Transactions, Average Revenue per Order, and Last Transaction Date.

Data Modeling:
The data model connects the fact table to dimension tables such as Dim_OrderTypes, Dim_Organic, Dim_PieFlavors, and Dim_PieTypes.

Data Visualizations:
Stacked Area Chart (Cumulative Revenue Over Time):
This chart shows the cumulative growth in revenue across the entire period.

Column Chart (Total Revenue by Quarters):
The column chart breaks down total revenue by quarter, with Q4 standing out as the highest revenue-generating period due to the seasonal demand.

Ribbon Chart (Revenue by Weekday):
This chart shows total revenue by weekday, emphasizing how weekend days outperform weekdays in terms of sales.

Slicer (Pre-Order vs In-Store):
A slicer enables users to filter the dashboard based on Pre-Order or In-Store purchases.

Table (Price Type, Order Means, Total Orders, and Total Revenue):
This table provides a breakdown of key metrics such as price type (slice or whole), order means, total orders, and total revenue for a comprehensive view of performance.

Conclusion:
This dashboard enables bakery managers and stakeholders to uncover critical insights about sales performance, product preferences, and revenue trends. By leveraging the insights from these visualizations, the bakery can fine-tune its product offerings, run more effective promotions, and optimize its overall strategy to maximize growth in a competitive market.
