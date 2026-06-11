# European Luxury Sector - Pricing Power Index (PPI) Dashboard

An executive-level business intelligence application engineered in Power BI to diagnose pricing power, revenue trajectories, and market position across 8 premier European luxury houses (2019–2024).

## Architecture & Insights
* **Executive Overview (Page 1):** Features macro sector KPIs, historical index timelines, and a custom strategic matrix plotting Price Index against Volume Mix to isolate market tiers.
* **Brand Deep-Dive (Page 2):** A diagnostic view leveraging a custom-built DAX table relationship to break down performance across 4 core pillars: Price Premium, Margin Stability, Price-led Growth, and Brand Desirability.

## Technical Implementation Details
* **Data Modeling:** Star-schema architecture connecting dimensional brand metadata to multi-year fact records.
* **Advanced DAX:** Implemented filter-proof context isolation via `ALL()` parameters to preserve macro benchmarks during micro-slicer selections.
* **Dynamic Analytics:** Leveraged calculated relational tables to enable a responsive, cross-filtered brand diagnostic chart.

## Interactive Demonstration
![Luxury Index Dashboard Preview](https://github.com/AaronVis/luxury-pricing-power-index/blob/main/Dashboard.gif)
