# NYC Yellow Taxi — Hourly Operating Efficiency

This project analyzes operational efficiency in New York City’s Yellow Taxi network,
focusing on time-based productivity rather than raw demand volume.

## Problem Statement
High trip volume does not necessarily imply high driver earnings.
This analysis investigates when a driver's time is monetized most efficiently.

## Dataset
The analysis uses NYC Taxi & Limousine Commission (TLC) Yellow Taxi trip records
for January 2019, representing a pre-pandemic baseline period.

Raw data is publicly available via NYC TLC but is not included in this repository.

## Methodology
- Rule-based data validation and cleaning using physical and economic constraints
- Feature engineering aligned with operational KPIs
- Median-based aggregation to reduce outlier distortion
- Hourly analysis focused on revenue efficiency, not trip volume

## Key KPIs
- Revenue per hour
- Revenue per mile
- Trip duration
- Trip share (%)

## Key Insights
- Peak demand hours are not the most profitable
- Early morning hours maximize revenue per hour despite lower trip volume
- Operational inefficiency is primarily time-driven, not distance-driven

## Dashboard
The accompanying dashboard translates analytical findings into a decision-support tool.

![Dashboard Preview](dashboard/dashboard_preview.png)

## Tools
Python (Pandas, NumPy) · Jupyter Notebook · Power BI · Excel

## Author
John Koutnas
