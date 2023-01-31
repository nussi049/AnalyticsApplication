# AnalyticsApplication
Analytics and Application Team 2

To Reproduce:
-------------
- Clone this repository

- Execute the following notebooks in this order, because the data_preparation Notebook is the foundation of plot_data, KPI and prediction_model Notebook.

1. data_preparation Notebook
2. plot_data Notebook
3. KPI Notebook
4. prediction_model Notebook
5. cluster_analysis Notebook

Note:
-----
The data folder must contain the following two csv_files with the bike rental data and the weather data: 
1. sf_2018
2. weather_hourly_sf

These files where to large for the Github upload.

The geoloacations of the stations are gathered with the Google Maps API. Some of the locations were not recognized and thus the locations needed to be cleaned. The cleaned data is in the geo_data_cleaned.csv, which is used for the geodata plots and cluster analysis.
