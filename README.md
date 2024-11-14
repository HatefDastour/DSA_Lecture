# Data Science and Analytics Lecture

Welcome to this short lecture on Data Science and Analytics, focusing on weather data analysis.

## Dataset Overview

We'll be working with weather data for Columbia, Missouri, specifically from the University of Missouri weather station. The data covers various periods in 2010 and has been sourced from the National Centers for Environmental Information (NCEI).

### Data Source

The data is obtained from [NCEI Climate Data](https://www.ncei.noaa.gov/cdo-web/), a division of the National Oceanic and Atmospheric Administration (NOAA). NCEI provides comprehensive climate data and information, ensuring accuracy and reliability in our dataset.

## Dataset Description

Our dataset comprises eight CSV files, each serving a specific purpose in our analysis. Here's a breakdown of the files:

### 10-Day Datasets

These datasets cover the period from 2010-10-01 to 2010-10-10.

| Filename | Description | Units |
|----------|-------------|-------|
| data_10day_metric_full.csv | Complete data in metric units | TMIN, TMAX: °C |
| data_10day_metric_missing.csv | Data with intentional missing values (NaNs) | Same as above |
| data_10day_standard_full.csv | Complete data in standard units | TMIN, TMAX: °F |
| data_10day_standard_missing.csv | Data with intentional missing values (NaNs) | Same as above |

### Full 2024 Datasets

These datasets cover the period from 2010-01-01 to 2010-11-05.

| Filename | Description | Units |
|----------|-------------|-------|
| data_2024_metric_full.csv | Complete data in metric units | PRCP: mm, TMIN/TMAX: °C |
| data_2024_metric_missing.csv | Data with intentional missing values (NaNs) | Same as above |
| data_2024_standard_full.csv | Complete data in standard units | PRCP: in, TMIN/TMAX: °F |
| data_2024_standard_missing.csv | Data with intentional missing values (NaNs) | Same as above |

## Data Fields

- **PRCP**: Precipitation
- **TMIN**: Minimum Daily Temperature
- **TMAX**: Maximum Daily Temperature

## Educational Purpose

This dataset is designed for educational purposes, specifically to demonstrate various techniques for handling missing data in time series analysis using Python. The files with missing values (NaNs) are particularly useful for practicing data cleaning and imputation techniques.

## Disclaimer

While the original data is from a reputable source, the modified versions in this repository are intended solely for learning and practicing data manipulation techniques. They should not be used for actual weather analysis or forecasting.