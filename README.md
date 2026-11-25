Amazon Sales Analysis | Power BI Dashboard

An interactive Power BI dashboard that tracks Amazon sales performance, profit margin, and customer reviews, with YTD and QTD views and an automated data refresh built in Power Query.

Dashboard overview

Problem

Sales data in raw form makes it hard to answer basic business questions quickly:

How are sales performing year-to-date and quarter-to-date?
Which products and categories drive revenue and profit?
How do customer reviews relate to sales performance?

This dashboard puts those answers on one page, with filters so users can drill down.

Approach
Data cleaning (Power Query): Removed duplicates and null values, fixed data types, and standardized column names and date formats.
Automated refresh: Built Power Query batch refresh pipelines so new data loads without manual rework.
Data model: Organized the tables into a clean model with relationships and a date table for time intelligence.
DAX measures: Created measures for Total Sales, Profit, Profit Margin %, YTD Sales, QTD Sales, and review metrics.
Visuals: Designed KPI cards, trend charts, category and product breakdowns, and slicers for interactive filtering.
