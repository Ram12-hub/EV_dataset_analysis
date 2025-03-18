# EV_dataset_analysis
EV Data Analysis using Python — Filtered and analyzed electric vehicle data based on budget and performance. Grouped manufacturers, detected outliers in energy consumption, and explored the correlation between battery capacity and range. Built using Pandas, NumPy, Matplotlib, and Seaborn.

🚗 Electric Vehicle (EV) Data Analysis using Python
This project analyzes electric vehicle (EV) data to uncover insights about pricing, battery capacity, range, and energy consumption. The goal is to help customers identify the best EV options based on their budget and performance needs.

# Project Overview
Data Cleaning and Preparation

Imported data from an Excel file.
Cleaned missing values and duplicates using Pandas.
Standardized inconsistent naming conventions.
Customer Budget-Based Filtering

Filtered EVs within a budget of 350,000 PLN and a minimum range of 400 km.
Identified Tesla and Volkswagen as top performers in this segment.
Manufacturer Grouping and Battery Capacity

Grouped filtered data by manufacturer.
Calculated the average battery capacity for each manufacturer.
Found Audi and BMW had the highest battery capacities.
Outlier Detection in Energy Consumption

Applied Z-score method to identify outliers in energy consumption.
Verified results using a box plot — no significant outliers found.
Battery Capacity vs Range Relationship

Created a scatter plot showing a positive correlation between battery capacity and range.
Found that higher battery capacities generally result in longer driving ranges.
**Tech Stack**
Python
Pandas, NumPy
Matplotlib, Seaborn
Scipy
 # Insights and Recommendations
✔️ Tesla and Volkswagen offer the best range within a 350,000 PLN budget.
✔️ Audi and BMW lead in battery capacity but come at a higher cost.
✔️ Efficiency and customer-specific requirements affect performance beyond battery size alone.
