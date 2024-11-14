# Data Science and Analytics Lecture Overview

This lecture covers core principles in Data Science and Analytics, with a specific emphasis on handling missing data within the data science lifecycle.

## Weather Data Overview

The dataset for this lecture consists of weather data collected from the University of Missouri weather station in Columbia, Missouri. Sourced from the National Centers for Environmental Information (NCEI) and provided by the National Oceanic and Atmospheric Administration (NOAA), this data encompasses daily temperature and precipitation records.

- **Location**: Columbia, Missouri  
- **Source**: [NCEI Climate Data](https://www.ncei.noaa.gov/cdo-web/)  
- **Provider**: National Oceanic and Atmospheric Administration (NOAA)  
- **Data Type**: Daily temperature and precipitation readings  

### Dataset Structure

The dataset includes eight CSV files structured for analysis across different periods and units, offering both complete and incomplete data for handling missing values.

#### 10-Day Dataset (2010-10-01 to 2010-10-10)

This subset provides daily records for a 10-day period in both metric and standard units, with complete and missing-value variants.

| Filename | Description | Units |
|----------|-------------|-------|
| `data_10day_metric_full.csv` | Complete data in metric units | TMIN, TMAX: °C |
| `data_10day_metric_missing.csv` | Data with intentional missing values (NaNs) | TMIN, TMAX: °C |
| `data_10day_standard_full.csv` | Complete data in standard units | TMIN, TMAX: °F |
| `data_10day_standard_missing.csv` | Data with intentional missing values (NaNs) | TMIN, TMAX: °F |

**Variables**:  
- **TMIN**: Minimum Daily Temperature  
- **TMAX**: Maximum Daily Temperature  

#### Full 2024 Dataset (2010-01-01 to 2010-11-05)

The 2024 dataset spans most of 2010, providing daily records in both metric and standard units, with versions that include and omit missing values.

| Filename | Description | Units |
|----------|-------------|-------|
| `data_2024_metric_full.csv` | Complete data in metric units | PRCP: mm, TMIN/TMAX: °C |
| `data_2024_metric_missing.csv` | Data with intentional missing values (NaNs) | PRCP: mm, TMIN/TMAX: °C |
| `data_2024_standard_full.csv` | Complete data in standard units | PRCP: in, TMIN/TMAX: °F |
| `data_2024_standard_missing.csv` | Data with intentional missing values (NaNs) | PRCP: in, TMIN/TMAX: °F |

**Variables**:  
- **PRCP**: Daily Precipitation  
- **TMIN**: Minimum Daily Temperature  
- **TMAX**: Maximum Daily Temperature  

## Learning Objectives

This dataset is designed to support educational exercises in data cleaning, imputation, and handling missing values within time series analysis. The files with missing data provide a realistic context for developing data preparation and analytical skills in Python.

## Important Note

The datasets provided here are modified versions intended solely for instructional purposes. While they are based on accurate historical records, they should not be used for formal weather analysis or forecasting.