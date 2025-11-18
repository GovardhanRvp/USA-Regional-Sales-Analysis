# USA_Regional-Sales-Analysis
## Problem Statement
Sales teams often lack a clear, data-driven understanding of regional performance, making it difficult to identify growth opportunities and optimize resources. This project aims to analyse and visualize regional sales data to uncover trends, evaluate profitability, and support strategic decision-making.
## Objective
Deliver actionable insights from Acme Co.’s 2014–2018 sales data to:

Identify top-performing products, channels, and regions driving revenue and profit
Uncover seasonal trends and anomalies for optimized planning
Spot pricing and margin risks from outlier transactions
Inform pricing, promotion, and market-expansion strategies
These findings will guide the design of a Power BI dashboard to support strategic decision-making and sustainable growth.
## Data Cleaning & Preparation

Removed duplicate orders based on order_number
Handled missing values in categorical and numerical fields
Converted order_date into proper datetime format
Standardized numerical columns (quantity, revenue, cost, profit)
Verified financial formulas:
revenue = quantity × unit_price
profit = revenue – total_cost
## Exploratory Data Analysis

Analyzed distributions of key metrics: quantity, unit price, revenue, profit
Checked for outliers in sales and cost-related columns
Performed value counts for categorical variables:
-Channel
-State
-Region
-Product
Identified sales patterns at customer, product, state, and regional levels

EDA:
1. Monthly Sales Trend Over Time
2. Monthly Sales Trend (All Years Combined)
3. Top 10 Products by Revenue (in Millions)
4. Top 10 Products by Avg Profit Margin
5. Sales by Channel (Pie Chart)
6. Average Order Value (AOV) Distribution
7. Profit Margin % vs. Unit Price
8. Unit Price Distribution per Product
9. Top 10 States by Revenue and Order Count
10. Average Profit Margin by Channel
11. Correlation Heatmap of Numeric Features
12. Customer Segmentation: Revenue vs. Profit Margin
 
## Key Insights
1. Monthly Revenue Cycle:
Revenue stays stable between ≈$23M–$26.5M across 2014–2017, with no consistent seasonal spikes. Sharpest drop (≈$21.2M) occurs in early 2017, indicating a possible one-time disruption.
2. Channel Mix:
Wholesale: 54%. Distributors: 31%. Exports: 15% — opportunity to scale international presence.
3. Top Products (Revenue):
Product 26: $118M; Product 25: $110M; Product 13: $78M. Mid-tier: $68–75M; bottom performers: $52–57M.
4. Profit Margins:
Profit margins range broadly from ≈18% to ≈60%, with no strong correlation to unit price. Dense horizontal bands suggest standardized pricing strategies across tiers.
5. Seasonal Volume:
No strong monthly pattern, but slight volume uptick appears around May–June. Early 2017 dip (≈$21.2M) may require investigation.
6. Regional Performance:
California leads: ≈$230M Revenue & 7500+ orders. Illinois/Florida/Texas: ≈$85M–$110M & ≈3500–4500 orders. NY/Indiana: ≈$54M & 2000+ orders.

## Recommendations
1. Outlier Strategy: Exclude or formalize bulk-order and promotional SKUs when calculating averages.
2. Margin Uplift: Apply top-product pricing levers to mid/low tiers; cut costs on underperformers.
3. Export Growth: Invest in targeted overseas marketing and distributor partnerships.
4. Seasonal Planning: Shift spend toward January trough and May–June peak; investigate the 2017 anomaly.
5. Dashboard Prep: Build aggregated tables for time series, channel mix, and product performance for Power BI.

## Dashboard
Page-1:Home 
<img width="1327" height="736" alt="Regional Sales Analysis Page-1" src="https://github.com/user-attachments/assets/83754f0f-5ffb-417f-b79b-7fb137d25d6b" />
Page-2:Execitive Overview & Trends
<img width="1322" height="739" alt="Regional Sales Analysis Page-2" src="https://github.com/user-attachments/assets/c3697f17-c91a-4c3a-b96d-fb0d7e0ef5ac" />
Page-3:Product & Channel Performence
<img width="1323" height="741" alt="Regional Sales Analysis Page-3" src="https://github.com/user-attachments/assets/3d1f21c3-1886-440b-bb29-2b836caa0c7b" />
Page-4:Geographic & Customer Insighgs
<img width="1325" height="739" alt="Regional Sales Analysis Page-4" src="https://github.com/user-attachments/assets/961874ef-3211-4fbd-8680-a992c9fd14bb" />

## Conclusion

--> Completed end‑to‑end EDA and interactive Power BI dashboard, surfacing seasonality, SKU, channel & regional insights.

--> Insights inform sales policies and operational planning (store & warehouse prep aligned with annual trends).

--> Stakeholders can self‑serve real‑time analysis and confidently onboard new datasets for additional use cases.



