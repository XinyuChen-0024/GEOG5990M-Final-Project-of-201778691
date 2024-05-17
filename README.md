# GEOG5990M-Final-Project-of-201778691

# Analysis of Fuel Poverty and Crime Rate in Leeds

## Project Background
This project explores the relationship between fuel poverty and crime rates in Leeds for the year 2022. Fuel poverty is a significant issue in many urban areas, and understanding its correlation with crime rates can provide insights into social and economic conditions that affect communities. This analysis aims to identify and visualize the associations between different types of crime and fuel poverty across various regions in Leeds.

## Data
The repository contains the following data files:

2022-01-west-yorkshire-street.csv to 2022-12-west-yorkshire-street.csv: Monthly crime data for West Yorkshire, including Leeds, for the year 2022.
Fuel poverty by LSOA.csv: Data on the proportion of households in fuel poverty by Lower Layer Super Output Area (LSOA) in Leeds.
Leeds.geojson: Geographical boundaries of LSOA regions in Leeds.
leeds_crime_and_fuel_poverty_cleaned.csv: A cleaned dataset combining crime data and fuel poverty data, used for the final analysis.

1. Fuel Poverty Data: Sourced from Data Mill North, the data link is as follows:
   [Fuel Poverty Data](https://datamillnorth.org/dataset/2j70l/fuel-poverty-by-lsoa-england)
2. Crime Data: Street crime data of West Yorkshire for the year 2022, including details such as crime type and occurrence time, the data link is as follows:
   [data.police.uk](https://data.police.uk/)

The code in this repository aims to:

Load and clean the raw data files.
Merge crime data with fuel poverty data by LSOA codes.
Calculate the correlation between different crime types and fuel poverty rates.
Visualize the spatial distribution of fuel poverty and crime rates in Leeds.
Provide statistical insights into the relationship between fuel poverty and crime.

##Instructions for Running the Code
Prerequisites
Make sure you have the following Python packages installed:

pandas
geopandas
matplotlib
seaborn
scipy
