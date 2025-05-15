# NYC Taxi Trip Duration Analysis

## Description

This project presents a comprehensive analysis of a dataset containing New York City taxi trip durations. The analysis was conducted using Python in a Jupyter Notebook environment with the help of libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

### Data Exploration

- Imported the dataset and examined the first few rows to understand the data structure.
- Computed descriptive statistics including **mean**, **standard deviation**, **minimum**, **maximum**, and **quartiles** for columns such as:
  - `vendor_id`
  - `passenger_count`
  - `trip_duration`

### Data Visualization

- **Bar Graph**: Displayed the frequency distribution of the `store_and_fwd_flag` variable, indicating whether trip data was stored before being forwarded.
- **Count Plot**: Illustrated the distribution of `vendor_id` values in the dataset.
- **Scatter Plot**: Visualized pickup locations using `pickup_longitude` and `pickup_latitude` to identify spatial patterns or clusters.
- **Box Plot**: Explored the relationship between `passenger_count` and `trip_duration`, highlighting outliers and distribution shapes.
- **Hourly Box Plot**: Extracted the hour from `pickup_datetime` and visualized how `trip_duration` varied throughout the day. Also included versions excluding outliers to focus on central tendencies.

### Statistical Analysis

- **T-Test**: Conducted a t-test to compare trip durations between `vendor_id` 1 and 2.
  - Calculated the **t-value** and **p-value** to determine if the differences were statistically significant.

## Key Insights

- Uncovered temporal, spatial, and categorical trends in the dataset.
- Identified relationships and patterns using visualizations.
- Applied statistical tests to validate observed differences between vendor categories.

## Languages and Libraries Used

- **Python**
  - `Pandas`
  - `NumPy`
  - `Matplotlib`
  - `Seaborn`

## Environment

- **Jupyter Notebook**
