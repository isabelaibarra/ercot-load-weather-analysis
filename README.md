# ERCOT Load Forecasting Using Weather Data

This project analyzes how temperature influences electricity demand in the ERCOT power grid using Python.

## Project Overview

Hourly ERCOT electricity load data (2022–2024) was combined with NOAA weather observations from Houston to analyze how weather variability affects electricity demand.

The goal of this project was to explore temperature-driven electricity demand patterns and build a simple regression-based demand sensitivity model.

## Methods

- Cleaned and merged ERCOT load data with NOAA hourly weather observations
- Converted NOAA temperature observations into usable numerical variables
- Aggregated weather observations to hourly resolution
- Built a regression model to estimate the relationship between temperature and electricity demand
- Visualized load patterns across time and temperature

## Tools Used

- Python
- pandas
- matplotlib
- scikit-learn
- Google Colab

## Key Findings

- Electricity demand in ERCOT shows a clear relationship with temperature.
- Higher temperatures correspond with increased electricity load, likely driven by air conditioning demand.
- The regression model indicates a moderate positive relationship between temperature and system load.
- Temperature alone explains a meaningful portion of electricity demand variability, though additional variables (such as humidity, day-of-week, and economic activity) would likely improve forecasting performance.
- Electricity demand directly affects pricing and market conditions, so understanding how external factors like weather drive demand is critical for forecasting, risk management, and trading decisions.

## Example Visualizations

### Load vs Temperature

![Load vs Temperature](images/load_vs_temperature.png)

### Load Over Time

![Load Over Time](images/load_vs_time.png)
