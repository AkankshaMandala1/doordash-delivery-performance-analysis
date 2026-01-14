# DoorDash Delivery Performance Analysis (Python • SQL/DuckDB • Tableau)

## Overview
End-to-end analytics project to analyze DoorDash delivery performance and identify SLA risk drivers across markets, restaurants, dasher congestion, peak hours, and order complexity.

## Tools
- Python (Pandas, NumPy)
- DuckDB (SQL analytics)
- Tableau Public (Dashboard)

## Key Questions
- Which markets have the worst late delivery rates?
- Which restaurant categories / stores are highest risk?
- Does dasher congestion correlate with delivery duration?
- What are peak-hour patterns?
- Does order complexity increase delivery time?

## Tableau Dashboard
- Tableau Public: [https://public.tableau.com/shared/YHR6CQ7PX?:display_count=n&:origin=viz_share_link](https://public.tableau.com/shared/YHR6CQ7PX?:display_count=n&:origin=viz_share_link)

## Outputs
- `data/` contains aggregated tables used in Tableau
- `notebooks/` contains the Python notebook used for cleaning + feature engineering + SQL tables
- `screenshots/` contains dashboard images for quick viewing

## Repository Structure
- data/         → Final analytical CSVs
- notebooks/    → Python & DuckDB analysis
- screenshots/  → Dashboard visuals
- tableau/      → Tableau workbook

## Key Insights
- Late delivery rates exceed **99%** in multiple markets
- Certain cuisines consistently show higher median delivery times
- Delivery congestion strongly correlates with dasher availability
- Peak delays occur during lunch & dinner rush hours

## Future Improvements
- Predictive model for late delivery risk
- Automated data ingestion pipeline
- Real-time dashboard integration
