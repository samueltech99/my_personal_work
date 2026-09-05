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

## Dashboard
<a href="https://github.com/samueltech99/my_personal_work/blob/main/cafe_sales_screenshot.png">cafe_sales_dashboard</a>


## Project Insights

* Top Revenue Generator: Salad leads overall revenue at $17K with the highest unit price sum ($5.4K), despite having moderate sales volume (3.3K units).
* High-Volume Driver: Juice generates the highest unit volume (3.4K units) but yields lower revenue ($10K), indicating a lower margin/unit price structure.
* Data Logging Anomaly: 30.55% of transactions fall under an Uncategorized payment method, outnumbering valid methods like Credit Card (23.40%), Cash (23.14%), and Digital Wallet (22.92%).
* Location Variance: Sales vary significantly across branches, dipping to $18.1K before peaking sharply at $24.6K at the top location.
* Optimal Price Point: Item counts peak at mid-tier price levels (2.2K and 2.1K transactions), showing lower customer demand at extreme low or high price bands.

---
## Final Conclusion
The cafe business demonstrates strong baseline revenue ($84.43K) driven heavily by high-margin items like Salads and high-volume items like Juices. 
To maximize growth, management should expand marketing for top-performing menu pairings and investigate the highest-performing location ($24.6K) to replicate its operational model across underperforming branches. Additionally, resolving the POS logging error causing 30.55% in "Uncategorized" payment methods is critical for accurate financial reconciliation.




