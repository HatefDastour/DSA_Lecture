# DSA Lecture
Short Lecture on Data Science and Analytics

## Datasets

### Weather Data for Columbia, MO - September 2024

This dataset contains daily temperature readings for Columbia, Missouri, specifically from the University of Missouri weather station for September 2024. The data has been sourced from the National Centers for Environmental Information (NCEI).

* **Data Source:** [NCEI Climate Data](https://www.ncei.noaa.gov/cdo-web/)

    The National Centers for Environmental Information (NCEI) is a division of the National Oceanic and Atmospheric Administration (NOAA). NCEI provides comprehensive climate data and information, including historical weather data, climate monitoring, and environmental data. The data used in this dataset has been obtained from NCEI's extensive archives, ensuring accuracy and reliability.

* **Dataset Description:**

1. **data_2024_metric.csv**
    - **Description:** This file contains weather data in metric units.
    - **Units:** 
        - Precipitation (PRCP): millimeters (mm)
        - Minimum Daily Temperature (TMIN): degrees Celsius (°C)
        - Maximum Daily Temperature (TMAX): degrees Celsius (°C)

2. **data_2024_metric_missing.csv**
    - **Description:** This file is similar to `data_2024_metric.csv` but includes missing values (NaNs) for educational purposes.
    - **Units:** Same as `data_2024_metric.csv`.
    - **Example Data:** Contains NaNs in the same locations as in the standard dataset.

3. **data_2024_standard.csv**
    - **Description:** This file contains weather data in standard units.
    - **Units:** 
        - Precipitation (PRCP): inches (in)
        - Minimum Daily Temperature (TMIN): degrees Fahrenheit (°F)
        - Maximum Daily Temperature (TMAX): degrees Fahrenheit (°F)

4. **data_2024_standard_missing.csv**
    - **Description:** This file is similar to `data_2024_standard.csv` but includes missing values (NaNs) for educational purposes.
    - **Units:** Same as `data_2024_standard.csv`.
    - **Example Data:** Contains NaNs in the same locations as in the metric dataset.

* **Disclaimer:** This dataset is intended for educational purposes only. It will be used to demonstrate various techniques for handling missing data in time series analysis using Python.

    Please note that while the original data is from a reputable source, the modified version in this repository should not be used for actual weather analysis or forecasting. It is solely for learning and practicing data manipulation techniques.