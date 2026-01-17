# Energy-Load-Forecasting-OpenSTEF-Study-Implementation
I. Summary
This project is a self‑implemented study of short‑term electrical load forecasting, inspired by industry tools such as OpenSTEF. Goal: Understand how energy demand can be predicted using historical data and basic statistical models, while gaining hands‑on experience with data preprocessing, modeling, and evaluation.

This project was built independently as a learning and portfolio exercise and does not claim authorship of OpenSTEF or related industry frameworks.

As an electrical engineering student interested in safety‑critical systems and data‑driven decision‑making, this project helped bridge power systems concepts with practical data analysis.

II. Data
- Source: ISO New England (ISO-NE)
- Resolution: Hourly
- Variables:
  - Date
  - HourEnding
  - TotalLoad (MW)

Raw CSV files are not included due to size and data ownership.
They can be downloaded directly from ISO-NE.

III. Process:
- Loaded and merged multi-file ISO-NE hourly load data
- Constructed datetime from Date + HourEnding
- Analyze peak demand and daily average
- Compute daily peak and daily average data using 'groupsummary' function
- Visualized system load trends using MATLAB

IV. Results
- Daily average and daily peak load trends were identified
- Peak demand significantly exceeded average load, highlighting
  operational constraints on the power grid
