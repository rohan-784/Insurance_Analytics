# Insurance_Analytics
To analyze insurance business performance across New Business, Cross Sell, and Renewals by consolidating data from multiple sources and building an interactive analytics solution that tracks revenue growth, target achievements, and pipeline health.

## Dataset Used
- <a href= "https://github.com/rohan-784/Insurance_Analytics/commit/6594010997cdb26853e3402d0a4de4a1b05c2c71">Insurance Dataset</a>

## Key KPIs
- Target FY: Annual revenue target by income class.
- Placed Achievement: Total revenue placed (Brokerage + Fees).
- Invoiced Achievement: Total revenue invoiced.
- Achievement %: Placed / Target and Invoiced / Target.
- Growth %: Year-over-year revenue growth.
- Open Opportunities: Count and value of opportunities by stage.
- Conversion Ratio: Closed Won / Total Opportunities.

## Process

1. Data Preparation
- Cleaned and transformed raw Excel files using MySQL queries, Excel Power Query, and pivot tables.
- Performed joins between brokerage, fees, invoice, and budget data for a unified data model.

2. Data Modeling & KPI Calculation
- Created calculated fields such as Last Year Amount, Growth %, and Achievement %.
- Validated totals and relationships using Excel and MySQL.

3. Visualization
- Built dashboards in Power BI and Tableau for interactive KPI tracking and trend analysis.
- Designed custom visuals including side-by-side bar/line combo charts, dual-axis growth trends, and funnel views.

## Excel Dashboard <a href="">View</a>
## Power BI Dashboard <a href="">View</a>
## Tableau Dashboard <a href="">View</a>
## SQL Output <a href="">View</a>

## Project Insights
- Revenue Growth: Achieved a peak growth of 585% in 2018, followed by declines in later years—signaling dependency on a few large deals.
- Business Mix: Renewals outperformed targets (150% achievement) while Cross Sell (59%) and New Business (18%) lagged, indicating need for strategic focus.
- Pipeline Health: Majority of revenue is concentrated in the Qualify Opportunity stage, creating conversion risk if deals fail to progress.
- Top Drivers: A handful of executives and products (e.g., Fire, EL-Group Mediclaim, Mega Policy) contribute the bulk of revenue.

## Final Conclusion

The project demonstrates how an integrated analytics ecosystem (MySQL → Excel → Power BI/Tableau) can transform raw insurance data into actionable insights.
The dashboards enable management to:
- Monitor targets vs. achievements in real time.
- Identify high-risk opportunities and growth gaps.
- Support data-driven sales strategies for sustainable business growth.
