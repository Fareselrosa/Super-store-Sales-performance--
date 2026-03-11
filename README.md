
📊 Super Store Profitability Investigation (SQL & Power BI)



🎯 Project Objective

This project aims to investigate the root causes behind the 17% overall profit margin of a Super Store dataset. 
The goal was to identify structural profitability risks across products, regions, segments, and discount strategies to provide actionable business recommendations.



<img width="1920" height="1080" alt="Screenshot (44)" src="https://github.com/user-attachments/assets/cadb675d-ce20-4945-aabc-34a16e4e302e" />

<img width="1920" height="1080" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/6227069b-29a8-4efe-bc73-a4acbb6e0a04" />




🛠️ Tech Stack
Database: SQL Server (Complex Queries, Joins, CTEs, Data Cleaning).

Visualization: Power BI (Interactive Dashboards, DAX, Tooltips).

Analysis: Descriptive & Diagnostic Analytics.

🔍 SQL Investigation Highlights (The "Kitchen" Work)
I performed a 13-case investigation using SQL to deep-dive into the data. Key technical implementations include:

Data Aggregation: Calculated total sales, profits, and margins at multiple granularities.

Conditional Logic: Used CASE statements to create "Discount Buckets" to analyze margin erosion.

Data Integrity: Implemented NULLIF to handle division-by-zero errors in margin calculations.

Performance Optimization: Created summary tables using TRUNCATE and INSERT to streamline the Power BI data model.

💡 Key Business Insights
The Discount Trap: Orders with discounts above 30% resulted in a severe margin erosion of -37.9%.

High-Risk Categories: Identified that Binders, Appliances, and Phones are the most sensitive to high discounts.

Regional Variance: The East Region showed specific inefficiencies in the Corporate segment.

🚀 Recommendations
Implement a Discount Governance Policy: Limit blanket discounts and cap them at 20% for low-margin sub-categories.

Product-Level Controls: Revise pricing strategies for the Supplies sub-category which is currently underperforming.


📂 Dataset

The dataset used in this project is the Superstore Sales dataset from kaggle , commonly used for business analytics practice.

It contains information about:
- Orders
- Products
- Customer 
- Regions
- Discounts
- Profit



