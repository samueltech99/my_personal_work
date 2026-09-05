# Cafe_ Sales_Analysis

## Project Objective
To analyze cafe sales transactions across multiple locations and product categories to uncover revenue drivers, 
customer purchasing patterns, and operational data quality issues, enabling data-driven inventory and financial optimization.


## Dataset Used
<a href="https://github.com/samueltech99/my_personal_work/blob/main/Cafe_Sales.csv">cafe_sales_dataset</a>


## KPI Questions
* What is the overall financial performance across all locations (Total Revenue, Volume, and Avg Unit Price)?
* Which menu items generate the highest total revenue compared to volume sold?
* How are payment methods distributed, and are there transaction tracking anomalies?
* Which cafe locations are driving sales, and how do they compare?
* What price points hit the sweet spot for transaction frequency?


## Project Process
1. Data Ingestion & Cleaning: Loaded transaction data into Power BI, normalized data types, and flagged missing/uncategorized payment parameters.
2. Data Modeling & DAX Calculation: Created aggregated measures for `Sum of Unit Price`, `Total Revenue`, `Total Volume`, and 
distinct counts for `Products` and `Locations`.
3. Visual Layout & Dashboard Design:
* Built top-level card visuals for quick executive KPI assessment.
* Constructed horizontal bar charts to rank product spend, unit price, and volume.
* Formatted a donut chart to visualize payment method percentages.
* Plotted line and area charts to evaluate location trends and price-point volume distributions.
