# Walmart sales performance analysis


**Project Title** - Walmart Sales Performance \& Marketing Insights Dashboard Using Power BI



**Executive Summary**



This project analyses Walmart's weekly sales data to understand sales performance across different stores and identify the impact of holiday periods on sales performance across different stores and identify the impact of holiday periods on sales 


The main objective is to identify sales patterns, compare store performance, and understand how holiday periods influence sales. The analysis helps management make informed decisions regarding promotional planning, sales strategies, and store performance improvement.

The project uses interactive Power BI dashboards to present key performance indicators (KPIs), sales comparisons, and business insights.



&#x20;**2. Tech Stack**



Power BI - Interactive dashboards and data visualization.

Power Query - Data cleaning, transformation, and preparation.

DAX - Calculated measures, sales analysis, and time-based calculations.

Excel/CSV - Source dataset and data handling.


**3. Data Architecture \& Modeling**



The project follows a Star Schema data model consisting of three tables:



Walmart Store Sales: Main fact table containing weekly sales and other store-related information.

Calendar: Dimension table containing date information for time-based analysis.

Store: Dimension table containing unique store IDs.



Relationships:

Calendar is connected to the sales table through Date.

Store is connected to the sales table through Store ID.



This model helps organize the data and makes sales analysis easier and more efficient.








**4. Key DAX Formulas Used**



1.Total Sales: Calculates the total weekly sales across all stores.

2.Average Weekly Sales: Calculates the average weekly sales value.

3.Holiday Sales: Calculates sales recorded during holiday periods.

4.YTD Sales: Calculates cumulative sales from the beginning of the year.



These measures help compare sales performance, understand holiday trends, and monitor business performance over time.


**5. Dashboard Preview**



The project contains two interactive dashboard pages:



Page 1 – Sales Performance Dashboard: Displays overall sales KPIs, store-wise sales comparisons, sales trends, and economic indicators.

Page 2 – Marketing Insights: Highlights holiday and non-holiday sales performance and store-level comparisons.

**6. Business Insights \& Recommendations**



&#x20;Identify stores with higher and lower weekly sales to improve store-level planning.

&#x20;Analyse holiday and non-holiday sales patterns to support promotional planning.

&#x20;Use historical sales trends to plan inventory and marketing activities.

&#x20;Monitor economic factors such as fuel prices and unemployment alongside sales performance.

&#x20;Use sales data to make informed decisions about future promotional periods.
















