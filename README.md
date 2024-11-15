# Data Science and Analytics Lecture Overview

This lecture covers core principles in Data Science and Analytics, with a specific focus on handling missing data within the data science lifecycle.

## Lecture Examples

| Filename                        | Description                                       | Google Colab       |
|---------------------------------|---------------------------------------------------|---------------------|
| `Lecture_Examples.ipynb`       | A collection of lecture examples that illustrate key concepts without full code implementations. | <a href="https://colab.research.google.com/github/HatefDastour/DSA_Lecture/blob/main/lecture_examples/Lecture_Examples.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" width="150"/></a> |
| `Lecture_Examples_Complete.ipynb` | Comprehensive lecture examples that include complete code implementations. | <a href="https://colab.research.google.com/github/HatefDastour/DSA_Lecture/blob/main/lecture_examples/Lecture_Examples_Complete.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" width="150"/></a> |

## Datasets Overview

The lecture includes two primary datasets: **Weather Data** and **Missouri Monthly Unemployment Claims by Industry**. Each dataset presents unique structures, types, and levels of missing data to support exercises in data preparation, imputation, and time series analysis.

---

### 1. Weather Data Overview

The weather data is sourced from the [University of Missouri weather station](https://www.ncei.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USC00231801/detail) in Columbia, Missouri, provided by the National Centers for Environmental Information (NCEI) and the National Oceanic and Atmospheric Administration (NOAA). This dataset includes daily temperature and precipitation records, structured for analysis with complete and missing-value variants.

- **Location**: Columbia, Missouri  
- **Source**: [NCEI Climate Data](https://www.ncei.noaa.gov/cdo-web/)  
- **Provider**: National Oceanic and Atmospheric Administration (NOAA)  
- **Data Type**: Daily temperature and precipitation readings  

#### Weather Dataset Structure

The weather dataset includes eight CSV files across two subsets (10-day and 2024 full-year), covering different periods and units (metric and standard) to enable detailed analysis.

**10-Day Dataset (2010-10-01 to 2010-10-10)**

| Filename                    | Description                                      | Units       |
|-----------------------------|--------------------------------------------------|-------------|
| `data_10day_metric_full.csv`| Complete data in metric units                    | TMIN, TMAX: °C |
| `data_10day_metric_missing.csv`| Data with missing values (NaNs) in metric units | TMIN, TMAX: °C |
| `data_10day_standard_full.csv`| Complete data in standard units                  | TMIN, TMAX: °F |
| `data_10day_standard_missing.csv`| Data with missing values (NaNs) in standard units| TMIN, TMAX: °F |

**Full 2024 Dataset (2010-01-01 to 2010-11-05)**

| Filename                    | Description                                      | Units       |
|-----------------------------|--------------------------------------------------|-------------|
| `data_2024_metric_full.csv` | Complete data in metric units                    | PRCP: mm, TMIN/TMAX: °C |
| `data_2024_metric_missing.csv` | Data with missing values (NaNs) in metric units | PRCP: mm, TMIN/TMAX: °C |
| `data_2024_standard_full.csv` | Complete data in standard units                  | PRCP: in, TMIN/TMAX: °F |
| `data_2024_standard_missing.csv` | Data with missing values (NaNs) in standard units| PRCP: in, TMIN/TMAX: °F |

**Variables**:  
- **PRCP**: Daily Precipitation  
- **TMIN**: Minimum Daily Temperature  
- **TMAX**: Maximum Daily Temperature  

---

### 2. Missouri Monthly Unemployment Claims by Industry Overview

This dataset represents monthly unemployment claims in Missouri across five industries from August 2011 to October 2024, with both complete and missing-value variants. It is useful for exploring temporal patterns in unemployment and developing imputation techniques for missing data.

- **Source**: Missouri Monthly Unemployment Claims by Industry, accessible via [Missouri Data Portal](https://data.mo.gov/Labor/Missouri-Monthly-Unemployment-Claims-By-Industry/cj66-t7xq/about_data).
- **Data Type**: Monthly unemployment claims

#### Unemployment Claims Dataset Structure

The dataset includes two CSV files reflecting monthly data across the selected industries, available in both complete and missing-value versions.

| Filename                        | Description                                      |
|---------------------------------|--------------------------------------------------|
| `monthly_unemployment_full.csv` | Complete data with monthly unemployment claims   |
| `monthly_unemployment_missing.csv` | Data with missing values (NaNs) in unemployment claims |

**Industries Included**:  
- **Admin. & Support/Waste Mgmt./Remedia. Serv.**
- **Manufacturing**
- **Construction**
- **Health Care & Social Assistance**
- **Accommodation & Food Services**

**Date Column**:  
- **Date**: First day of each month, marking the period for reported unemployment claims.

---

## Learning Objectives

The datasets provided aim to reinforce data science skills in handling missing data, time series analysis, and data preparation in Python. The missing data variations offer realistic scenarios for practicing data cleaning and imputation techniques.

## Important Note

These datasets are modified for educational purposes only. While based on real-world records, they are not suitable for formal analysis or forecasting.