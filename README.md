# AtliQ Hardware:Sales & Finance Report 

## About Company

- AtliQ Hardware is a multinational company that sells products such as printers, mice, PCs, etc., to two customer types: e-commerce platforms (e.g., Amazon, Flipkart) and brick-and-mortar stores (e.g., Croma, Best Buy). The company uses three sales channels:
  - Retailer: Croma, Amazon
  - Distributor: Neptune
  - Direct Channel: AtliQ e Store, AtliQ Exclusive

## Project Objective

- The primary goal of this project is to analyze AtliQ Hardware's sales and financial performance from 2019 to 2021. This analysis will support the company in making informed decisions for growth, identifying sales trends, and evaluating market performance. The fiscal year for AtliQ Hardware runs from September to August.



## Techniques Used


 
### 1. Data Extraction & Transformation (ETL via Power Query)

* Extracted raw data from multiple source files, standardized inconsistent values, corrected headers, and sanitized negative quantities into positive absolute values.

### 2. Time Intelligence & Calendar Architecture

* **Date Table Creation:** Built a dedicated Date Table using Power Query to establish unique date dimensions for precise time-series analysis.
* **Fiscal Calendar Setup:** Derived custom fiscal months and quarters in Power Pivot to align reporting with the company's September–August fiscal calendar cycle.



### 3. Data Modeling & Integration

* **Data Modeling:** Established robust, multi-tier relationships between fact and dimension tables within Power Pivot to guarantee structural integrity and query reliability.
* **Supplementary Data Integration:** Seamlessly merged auxiliary datasets into the relational model to enrich overall business insights.

### 4. Advanced Analytics & Reporting

* **DAX Calculations:** Utilised Data Analysis Expressions (DAX) to program dynamic calculated columns and measures for flexible modelling.
* **Pivot Table Reporting:** Engineered advanced Pivot Tables to distill large datasets into clean, digestible financial summaries.


* **Conditional Formatting:** Applied targeted conditional formatting across reports to instantly highlight critical variances, growth trends, and key performance indicators.

  

## Reports

1. **P&L Statement by Fiscal Year**: Net Sales, COGS, Gross Margin and GM % for FY2019–FY2021, with a 21 vs 20 comparison
2. **P&L Statement by Months**: the same P&L by fiscal month and quarter (Sep–Aug) for each fiscal year, with YoY monthly comparison
3. **P&L Statement by Markets**: P&L by country for a selected fiscal year, filterable by region and sub-zone
4. **Customer Performance Report**: net sales by customer across all three years, with growth
5. **Market Performance vs Target**: net sales by country against the FY2021 target

   


## Business Insights



**1. Rapid Growth vs. Shrinking Profit Margins**:

•Net sales expanded dramatically by 6.8x over a two-year span, scaling from 87.5M in FY2019 to 598.9M in FY2021. 

•Despite massive revenue expansion, the overall Gross Margin percentage (GM%) dropped by roughly 5 percentage points (falling from 41.4% in 2019 to 36.4% in 2021).   

•In FY2021, Cost of Goods Sold (COGS) grew slightly faster than net sales (+208.6% vs. +204.5%), highlighting rising cost pressures.   

•Monthly profitability remained tightly consistent throughout each year (ranging between 36.3% and 36.7% across every month of FY2021), proving that the margin decline is structural and long-term rather than seasonal.   


**2. Seasonality & Sales Trends**:

•The business exhibits strong seasonality, with the October–Dec quarter (Q2) accounting for roughly 35% of total FY2021 sales.   

•Peak months like November and December surge significantly, hitting roughly 74M–78M in net sales compared to a baseline of about 44M in a typical month.   


**3. COVID-19 Operational Impact**:

•The pandemic's disruption is clearly visible in early 2020: Net sales plummeted to 2.1M in March 2020 (down sharply from 15.9M in February).   

•Business operations steadily rebounded, returning to normal pre-shock levels by August 2020.   


**4. Market Dynamics: India's Scale vs. Profitability**:

•India is by far the largest revenue-generating market, capturing about 27% of FY2021 sales (161.26M out of 598.9M).   

•However, India operates at a below-average profitability with a 32.0% GM, compared to 38.1% for all other global markets combined.   

•India's overall market share has gradually diluted from roughly 35% in FY2019 as other international regions like the USA expanded at a faster pace.   


**5. Regional Margins: Leaders and Laggards**:

•Highest Margins: New Zealand (48.2%), Japan (46.5%), and the United Kingdom (45.1%) lead global profitability.   

•Lowest Margins: Germany (26.2%), Norway (29.5%), Austria (30.1%), and Italy (30.1%) trail at the bottom.  


**6. FY2021 Target Attainment & Variances**:

•Every single market missed its FY2021 target, resulting in a collective global shortfall of 54.9M.   

•Largest Absolute Gaps: The USA (−10.2M), India (−9.6M), and Canada (−5.1M) missed by the largest cash amounts.   

•Largest Percentage Gaps: Poland (−18.1%), Canada (−14.5%), and Spain (−14.2%) suffered the steepest relative target deficits.   


**7. Customer Concentration & Channel Shifts**:

•Key Accounts: Amazon, AtliQ Exclusive, and AtliQ e Store combined make up roughly 33% of total FY2021 sales, while 30 out of 67 total customers drive 80% of the business.   

•E-commerce Slowdown: Major online channels (Amazon, AtliQ e Store, Flipkart, and Ebay) grew slower than traditional brick-and-mortar partners. Specifically, Amazon's contribution to total sales slipped from about 19% in FY2020 down to 14% in FY2021.
## Skills

- Microsoft Excel (Power Query, Power Pivot / Data Model, PivotTables, Conditional Formatting), DAX
 

