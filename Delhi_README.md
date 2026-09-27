# Delhi Air Quality Index (AQI) Analysis

## Internship Task

Level: Intermediate

This project analyzes air quality data from Delhi to understand pollutant
concentrations, temporal variations, relationships between pollutants, and
patterns in air quality.

## Objective

The objective of this project is to conduct an in-depth analysis of Delhi's
air quality using statistical analysis and data visualization techniques.

## Research Questions

1. Which pollutants show the highest concentrations in the dataset?
2. How do pollutant concentrations change over time?
3. How are PM2.5 and PM10 related to other pollutants?
4. How do air pollutant concentrations vary during the study period?
5. What relationships exist between the different pollutants?
6. What geographical analysis is possible from the available dataset?

## Dataset

The dataset contains hourly air-quality observations from Delhi.

### Dataset Columns

- date – Date and time of observation
- co – Carbon Monoxide
- no – Nitric Oxide
- no2 – Nitrogen Dioxide
- o3 – Ozone
- so2 – Sulfur Dioxide
- pm2_5 – PM2.5
- pm10 – PM10
- nh3 – Ammonia

The dataset contains 561 observations covering January 1, 2023 to
January 24, 2023.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

- Dataset inspection
- Data type conversion
- Missing-value analysis
- Duplicate-value analysis
- Daily aggregation of hourly observations
- Descriptive statistical analysis
- Pollutant trend analysis
- Data visualization
- Correlation analysis
- AQI-related analysis

## Visualizations

The project includes visualizations such as:

- Daily pollutant concentration trends
- Pollutant distribution plots
- Correlation heatmap
- AQI analysis and trends

## Geographical Analysis

The available dataset does not contain monitoring-station, latitude,
longitude, or location-level information. Therefore, detailed geographical
differences cannot be directly analyzed from this dataset.

## Key Findings

The findings are derived from the statistical analysis and visualizations
presented in the accompanying Jupyter Notebook.

## Limitations

- The dataset covers a limited period from January 1 to January 24, 2023.
- No station or geographical information is provided.
- The dataset does not contain a pre-calculated AQI column.
- AQI calculations require appropriate pollutant units and averaging periods.

## Conclusion

This project provides an exploratory analysis of air pollutant concentrations
in Delhi using Python-based data analysis and visualization techniques. The
analysis helps identify temporal patterns and relationships among major
pollutants and provides a foundation for further air-quality investigation.

## Project File

The complete analysis and Python code are available in:

Delhi_AQI_Analysis_Intermediate.ipynb
