# Power BI Superstore Sales & Forecast Dashboard
This repository contains a comprehensive Power BI project focused on analyzing sales performance and forecasting future trends for a superstore. The dashboard is built to provide actionable insights for        stakeholders, allowing them to understand historical performance and anticipate future sales.

# Project Overview
The primary goal of this project is to create an all-in-one analytical tool for the superstore's management team. It answers key business questions such as:

 1. What are our top-line metrics for profit, sales, and quantity?
 2. Which regions and states are driving the most sales and profit?
 3. What are the most popular product categories and shipping methods?
 4. What are the sales and profit trends over time (Year-over-Year)? 
 5. What is our 15-day sales forecast, and how does it vary by state?

The report is divided into two main pages: a Main Sales Dashboard for a high-level overview and a Sales Forecast Dashboard for predictive analytics.

# Dashboard Showcase
## Main Sales Dashboard (Page 1)
This page provides a 360-degree view of the superstore's KPIs and sales breakdowns.

https://github.com/TashuAgrahari/Super-Store-Sales-Forecast-Dashboard/blob/main/sales%20dashboard.png

## Sales Forecast Dashboard (Page 2)
This page is dedicated to time-series analysis, allowing users to select a state and view its historical sales data and a 15-day forward-looking forecast.

https://github.com/TashuAgrahari/Super-Store-Sales-Forecast-Dashboard/blob/main/forecast%20dashboard.png

# Key Features & In-Depth Analysis
## Page 1: Main Sales Dashboard
This dashboard is a powerful high-level summary, fully interactive and filterable by Region (Central, East, South, West).

1. KPI Cards: At-a-glance metrics for overall performance:
   
    . Profit
   
    . Sales
   
    . Quantity
   
    . Avg. Delivery Date

3. Geospatial Analysis: An interactive "Sales and Profit by State" map provides a clear visual of geographic hotspots.

4. Performance by Segment: A donut chart breaks down sales by Consumer, Corporate, and Home Office segments.

5. Customer Behavior:
    "Sales by Payment Mode" (e.g., Cards, COD) shows how customers are paying.
    
    "Sales by Ship Mode" (e.g., Standard Class, Second Class) highlights the most used shipping options.

6. Product Performance: A "Sales by Category & Subcategory" bar chart identifies top-performing product lines.

7. Year-over-Year (YoY) Trend Analysis:
   
     Monthly Sales YoY: A line chart compares monthly sales for the selected years (2018-2020), making it easy to spot seasonal trends and growth.
     
     Monthly Profit YoY: A corresponding line chart tracks profit trends over the same period.

## Page 2: Sales Forecast Dashboard
1. This page leverages Power BI's built-in analytics to provide predictive insights.

2. Interactive State Filter: A "Sales by State" visual acts as a filter. Users can click on any state (e.g., Texas, Utah, Washington) to update the entire page.

3. Historical Sales Trend: A line chart displays the complete sales history for the selected state from 2018 to 2021.

6. 15-Day Sales Forecast:
   
     This visual shows recent historical sales data (Aug 2020 - Jan 2021) and projects a 15-day sales forecast.
     
     The forecast includes upper and lower confidence bounds, providing a realistic range of expected sales.
     
     This allows managers to make data-driven decisions regarding inventory, staffing, and marketing for the upcoming weeks.
     
# Technical Details
  1. Tool: Power BI Desktop
  2. Visualizations: KPI Cards, Donut Charts, Bar Charts, Line Charts, Filled Map, Time-Series Forecasting.
  3. Interactivity: Slicers, Cross-filtering (visuals interact with each other), and Drill-down.
