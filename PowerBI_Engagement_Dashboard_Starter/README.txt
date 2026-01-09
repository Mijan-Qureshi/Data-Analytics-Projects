# Power BI Engagement Optimization Dashboard Starter Kit

This kit contains:
- engagement_dashboard_starter.xlsx → Sample dataset (Users, Sessions, Events, Content, Campaigns, Event Map)
- PowerBI_DAX_Measures.txt → Predefined DAX measures (copy into a Power BI Measures table)
- SQL_snippets.sql → Example SQL for DAU/CTR/Retention if using a data warehouse

## How to use
1. Open Power BI Desktop
2. Import `engagement_dashboard_starter.xlsx`
3. Create relationships as per the step-by-step guide
4. Add a Date table: `Date = CALENDARAUTO()`
5. Copy all measures from `PowerBI_DAX_Measures.txt` into a new Measures table
6. Build visuals:
   - KPI cards (DAU, WAU, MAU, Stickiness, CTR, Revenue, etc.)
   - Line charts for DAU trends
   - Funnel: Impressions → Clicks → Feature Uses → Purchases
   - Matrix heatmap for Retention (use cohort measures)

This gives you a working Engagement Optimization Dashboard you can extend and publish.