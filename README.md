# Sales & Performance Analysis Dashboard

## Project Overview
This project is an end-to-end Power BI sales intelligence solution that transforms raw transactional data into actionable strategic insights. Built with an optimized data model and an application-like user interface, this dashboard empowers stakeholders to evaluate revenue trends, isolate profitability drivers, and analyze consumer purchasing behavior across regions.

## Problem Statement
Traditional sales reports often present flat metrics that fail to reveal operational anomalies or consumer behavior. Key business challenges addressed in this project include:
* **Hidden Underperformers:** Standard reporting makes it difficult to seamlessly isolate underperforming segments alongside top drivers.
* **Unstructured Order Metrics:** Raw transactional data fails to show the frequency distribution of order sizes, hiding critical purchasing patterns.
* **Chronological Disconnect:** Text-based date fields sort alphabetically rather than sequentially, distorting time-series trends.

## Dataset Information
The analysis utilizes structured retail sales data (`Sales_data`) containing transactional records. Core data attributes include:
* **Sales Metrics:** Revenue, Cost, Profit, Profit Margin, and Budget allocations.
* **Customer & Geography:** Customer names, states, latitudes, and longitudes.
* **Order Attributes:** Unique order numbers, order dates, quantities, channels, and product names.

## Tools & Technologies Used
* **BI Tool:** Power BI Desktop
* **Data Prep & ETL:** Power Query (M Language) for data cleansing and transformation.
* **Data Modeling:** Star Schema framework utilizing clean Fact-Dimension relationships.
* **Analytics Engine:** Advanced DAX (Data Analysis Expressions) for calculated tables, numeric binned groups, and core business KPIs.

## Dashboard Preview
* **Executive Overview & Trends:** 
<img width="2590" height="1524" alt="image" src="https://github.com/user-attachments/assets/2055fc01-38ef-4b3f-afb0-503bf0314a2e" />

---

* **Product & Channel Performance:**
  <img width="2612" height="1528" alt="image" src="https://github.com/user-attachments/assets/16973f0f-47ae-4877-babb-5c238f40af41" />
---

* **Geographic & Customer Insights:**
<img width="2602" height="1526" alt="image" src="https://github.com/user-attachments/assets/91a765ae-2029-46e2-9c19-8a1d7988f305" />

---

  
## Future Enhancements
* **Predictive Forecasting:** Incorporate time-series forecasting models within Power BI to project upcoming quarterly revenue trends.
* **Automated Data Pipeline:** Migrate local source files to a cloud database (e.g., Azure SQL or PostgreSQL) to enable scheduled cloud refreshes.
* **RFM Segmentation:** Implement Recency, Frequency, and Monetary (RFM) analysis using DAX to group customers into behavioral segments.

## Conclusion
This dashboard successfully bridges the gap between raw backend data and executive decision-making. By converting fragmented rows of sales records into interactive, binned distributions and flexible ranking toggles, it offers a scalable template for modern business performance tracking and margin optimization.
