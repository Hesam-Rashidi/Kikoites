# Kikoites

# The Eutrophication of Gull Lake

This repository contains the scripts developed by Kikoites Ltd. in their study of the eutrophication of the Big Gull Lake, site of the civil engineering survey camp facilities owned by the University of Toronto. 

The goal of the work carried out in this repository was first of all to do an extensive exploratory data analysis (EDA), with the aim of identifying the interesting sites and key variables which could be considered through the rest of the analysis. 

## Table of contents
The code contains the following sections:
* [Geospatial analysis](#Geospatial-analysis)
* [Time series analysis](#Time-series-analysis)
* [Cleaning and modeling](#Cleaning-and-modeling)
* [Technologies](#Technologies)

## Geospatial analysis
Preparation of maps showing the location of points from which samples were taken, as well as the dissolved oxygen (DO) level at these different points.

![image](https://user-images.githubusercontent.com/61752640/206346374-480e4f90-3c4f-4bb5-a903-6779e63c08b5.png)


## Time series analysis
Studying the daily and monthly evolution of DO and the different indicators of the lake's health.


## Cleaning and modeling
The final data preparation and the logistic regression that was carried out to predict when eutrophication would take place based on other variables for which data was collected.

![image](https://user-images.githubusercontent.com/61752640/206345994-20fdaa21-0374-41d4-8430-21b634a5bf17.png)

## Technologies
The analysis was carried out with:
- sklearn 1.1.3
- seaborn 0.12.1
- matplotlib 3.6.2
- geopandas 0.12


