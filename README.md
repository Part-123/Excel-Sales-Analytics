# AtliQ Hardware:Sales & Finance Report 

## About Company

- AtliQ Hardware is a multinational company that sells products such as printers, mice, PCs, etc., to two customer types: e-commerce platforms (e.g., Amazon, Flipkart) and brick-and-mortar stores (e.g., Croma, Best Buy). The company uses three sales channels:
  - Retailer: Croma, Amazon
  - Distributor: Neptune
  - Direct Channel: AtliQ e Store, AtliQ Exclusive

## Project Objective

- The primary goal of this project is to analyze AtliQ Hardware's sales and financial performance from 2019 to 2021. This analysis will support the company in making informed decisions for growth, identifying sales trends, and evaluating market performance. The fiscal year for AtliQ Hardware runs from September to August.



## Techniques Used

**ETL Process with Power Query**
- Extracted data from multiple sources, cleaned inconsistent values, fixed headers, and transformed negative quantities into absolute values.

**Date Table Creation**
- Built a dedicated Date Table in Power Query to ensure unique dates for accurate time-based analysis.

**Fiscal Calendar Setup**
- Derived fiscal months and quarters in Power Pivot to align reporting with AtliQ Hardware's fiscal year.

**Data Modeling**
- Created relationships between fact and dimension tables using Power Pivot for structured and reliable data analysis.

**Supplementary Data Integration**
- Added additional datasets into the model through Power Pivot to enhance overall insights.

**DAX Calculations**
- Used DAX to build dynamic calculated columns and measures for deeper analytical flexibility.

**Pivot Table Reporting**
- Designed Pivot Tables to summarize sales and financial performance effectively.

**Conditional Formatting**
- Applied conditional formatting to highlight key trends, variances, and important metrics.

  

## Reports

1. **P&L Statement by Fiscal Year**: Net Sales, COGS, Gross Margin and GM % for FY2019–FY2021, with a 21 vs 20 comparison
2. **P&L Statement by Months**: the same P&L by fiscal month and quarter (Sep–Aug) for each fiscal year, with YoY monthly comparison
3. **P&L Statement by Markets**: P&L by country for a selected fiscal year, filterable by region and sub-zone
4. **Customer Performance Report**: net sales by customer across all three years, with growth
5. **Market Performance vs Target**: net sales by country against the FY2021 target

   


## Business Insights



- **Rapid growth, shrinking margin.** Net sales grew about 6.8x in two years, but GM % fell about 5 points. COGS grew slightly faster than sales in FY2021 (+208.6% vs +204.5%). Margin is steady within each year (about 36.3–36.7% every month of FY2021), so the decline is structural rather than seasonal.
  
  
- **Strong seasonality.** Oct–Dec account for about 35% of FY2021 sales; Nov and Dec run at roughly 74–78M against about 44M in a typical month.

  
- **COVID impact is visible.** March 2020 net sales dropped to 2.1M (from 15.9M in February), then recovered to normal levels by August 2020.

  
- **India is the largest market but has below-average margin.** It is about 27% of FY2021 sales at a GM of 32.0%, against 38.1% for all other markets combined. Its share of sales has fallen from about 35% in FY2019 as markets such as the USA grew faster.

  
- **Best and weakest margins.** New Zealand (48.2%), Japan (46.5%) and the UK (45.1%) lead; Germany (26.2%), Norway (29.5%), Austria and Italy (30.1% each) trail.

  
- **Every market missed its FY2021 target.** The total shortfall is about 54.9M. The USA (−10.2M), India (−9.6M) and Canada (−5.1M) have the largest absolute gaps; Poland (−18%), Canada (−14.5%) and Spain (−14%) have the largest percentage gaps.

  
- **Customer concentration.** Amazon, AtliQ Exclusive and AtliQ e Store together make up about 33% of FY2021 sales, and 30 of 67 customers account for 80%.

  
- **Online platforms are growing slower than the rest.** Amazon, AtliQ e Store, Flipkart and Ebay grew more slowly than most brick-and-mortar customers, and Amazon's share of sales fell from about 19% in FY2020 to about 14% in FY2021.

## Skills

- Microsoft Excel (Power Query, Power Pivot / Data Model, PivotTables, Conditional Formatting), DAX
 

