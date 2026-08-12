# Vehicle Trading Performance Analysis

A profitability analysis of 10,208 vehicle sales, identifying the biggest drivers of Metal Margin (profit per unit) performance.

## What's in this repo

- **Interactive Power BI dashboard** (`.pbix`) — KPI cards, a stock-aging chart, a valuation-type comparison, and an affiliate performance chart
- **Data quality review** — audited 14 anomalies before analysis; 4 records corrected, 4 flagged for source verification, 6 noted as low-risk
- **Written report** — full findings and recommendations

## Key Findings

1. **Stock Aging** — Margin drops from £475 (0-3 days in stock) to -£854 (30+ days). Cars that sit too long stop being profitable.
2. **Valuation Method** — CAP-valued vehicles have a 5.0% loss rate vs. 22.6% for PRO-valued vehicles.
3. **Affiliate Performance** — Similar-scale affiliates diverge sharply: Affiliate 9 (10.1% loss rate) significantly outperforms Affiliate 8 (18.5% loss rate).

## Tools Used

- Power BI Desktop (data modeling, DAX, visuals)
- Power Query (M) for data cleaning
- Excel (source data review)

## Recommendations

- Tighten reappraisal triggers around day 10–14 to catch aging stock before it becomes a loss
- Audit the PRO valuation process to close the gap with CAP
- Use Affiliate 9's process as an internal benchmark

## Files

- `Vehicle-Trading-Performance-Dashboard.pbix` — Power BI report
- ## Dashboard preview
- <img width="608" height="333" alt="Screenshot 2026-08-12 213951" src="https://github.com/user-attachments/assets/f6b9295b-5b3f-4abc-8a2e-993bd3d353aa" />
<img width="508" height="285" alt="Screenshot 2026-08-12 213804" src="https://github.com/user-attachments/assets/6fed8584-41e6-45ff-b0ef-08e729b4d246" />
<img width="596" height="336" alt="Screenshot 2026-08-12 214108" src="https://github.com/user-attachments/assets/fdfa576c-4141-496d-9693-25c607fe8210" />


