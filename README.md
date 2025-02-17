# Car-Sales-Analysis

The Car Sales Dashboard was developed in Power BI to track year-to-date (YTD) and month-to-date (MTD) sales trends, average car prices, and total cars sold across multiple dealerships. Leveraging DAX measures and data modeling, the dashboard provided actionable insights into dealership performance.

# Project Objective:
Monitor $371M+ in total sales, 13.3K+ cars sold, and average car prices across different brands, models, and dealerships.
Identify trends in sales by body style, color, and region to support inventory and pricing decisions.
Improve sales forecasting and strategic planning through data-driven insights.

# Project Steps:
Data Collection & Cleaning: Gathered sales data from various dealership sources.
Data Modeling: Built relationships between tables for a seamless analytical experience.
DAX Measures Creation: Developed key calculations to measure sales growth, total revenue, and car distribution.
Dashboard Development: Designed an interactive Power BI dashboard with filters for dealer, car model, body style, and region.
Performance Evaluation: Tested the accuracy of DAX calculations and visuals for real-time tracking.

# Key DAX Measures Used:
YTD Sales ($) = TOTALYTD(SUM(Sales[Total Sales]), Sales[Date])
MTD Sales ($) = TOTALMTD(SUM(Sales[Total Sales]), Sales[Date])
Total Cars Sold = COUNT(Sales[Car_ID])
Avg. Car Price ($) = AVERAGE(Sales[Price])

# Insights & Conclusions:
$371M in total sales recorded, with a 24.57% YTD increase in cars sold.
SUVs and Sedans were the best-selling body styles, with black and pale white being the most popular colors.
Cadillac and Lexus had the highest YTD average prices ($42.2K & $34.1K, respectively), contributing significantly to revenue.
DAX-driven insights optimized inventory management, ensuring better forecasting and pricing decisions.
