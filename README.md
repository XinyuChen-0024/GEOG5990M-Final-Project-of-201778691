# Analysis of Fuel Poverty and Crime Rates in Leeds

## Background/Context

This project explores the relationship between fuel poverty and crime rates in Leeds for the year 2022. Fuel poverty is a significant issue in many urban areas, and understanding its correlation with crime rates can provide insights into social and economic conditions that affect communities. This analysis aims to identify and visualize the associations between different types of crime and fuel poverty across various regions in Leeds.

## Data

The repository contains the following data files:
- `2022-01-west-yorkshire-street.csv` to `2022-12-west-yorkshire-street.csv`: Monthly crime data for West Yorkshire, including Leeds, for the year 2022.
- `Fuel poverty by LSOA.csv`: Data on the proportion of households in fuel poverty by Lower Layer Super Output Area (LSOA) in Leeds.
- `Leeds.geojson`: Geographical boundaries of LSOA regions in Leeds.
- `leeds_crime_and_fuel_poverty_cleaned.csv`: A cleaned dataset combining crime data and fuel poverty data, used for the final analysis.

## Objectives

The code in this repository aims to:
1. Load and clean the raw data files.
2. Merge crime data with fuel poverty data by LSOA codes.
3. Calculate the correlation between different crime types and fuel poverty rates.
4. Visualize the spatial distribution of fuel poverty and crime rates in Leeds.
5. Provide statistical insights into the relationship between fuel poverty and crime.

## Instructions for Running the Code

### Prerequisites

Make sure you have the following Python packages installed:
- pandas
- geopandas
- matplotlib
- seaborn
- scipy

You can install them using pip:
```bash
pip install pandas geopandas matplotlib seaborn scipy
```
##Running the Analysis
Clone the repository to your local machine:
```bash
git clone https://github.com/XinyuChen-0024/GEOG5990M-Final-Project-of-201778691.git
```
Navigate to the project directory:
```
cd GEOG5990M-Final-Project-of-201778691
```
