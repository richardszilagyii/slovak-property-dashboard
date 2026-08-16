# Slovak Residential Property Market Dashboard

An interactive Power BI dashboard analysing residential property prices across all 8 Slovak regions from 2002 to 2026, built from official National Bank of Slovakia (NBS) data.

## What it shows
- **Average price per m² by region** over time, with drill-down from year to quarter
- **Year-over-year price growth** by region
- **KPI cards**: latest average price and latest YoY growth
- Interactive **region and year filters**

## Key findings
- Bratislava is consistently the most expensive region; Nitra the most affordable
- Prices across all regions rose sharply from around 2020 onward
- Košice and Prešov showed the strongest recent year-over-year growth

## Tools & techniques
- **Power BI** — data model, report design, interactivity
- **Power Query** — cleaning and reshaping (unpivoting regional columns, deriving quarterly dates)
- **DAX** — measures for average price, YoY growth, and latest-period KPIs

## Files
- `Slovak-Property-Dashboard.pdf` — preview of the dashboard
- `Slovak-Property-Dashboard.pbix` — the interactive Power BI file (open in Power BI Desktop)

**Data source:** National Bank of Slovakia (NBS), residential property prices by region.
