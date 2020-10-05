# Weekly-Dengue-Cases-forecasting-at-Iquitos-and-San-Juan-with-Machine-Learning-Methods

In this respository we explored the temporal pattern of Dangue Diease Transmission at Iquito and San Juan
and build several regression models to forecast weekly new cases at this two places

![validation output at San Juan](https://github.com/SiqiHuang18/Weekly-Dengue-Cases-forecasting-at-Iquitos-and-San-Juan-with-Machine-Learning-Methods/blob/main/images/Validation_Plot.png)

## Motivation

Dangue is one of the world’s fast-spreading mosquito-borne diseases transmitted by the bite of an Aedes mosquito infected with a dengue virus.
Dengue epidemics tend to have seasonal patterns, with transmission often peaking during and after rainy seasons. 

There are several factors contributing to this increase and they include:
- High mosquito population levels, 
- Susceptibility to circulating serotypes, 
- Favourable air temperatures, 
- Precipitation and humidity

We want to build a machine learning model using environmental factors to forecast the weekly Dengue fever cases.

## Data
DRIVENDATA hosts the dataset that contains environmental data collected by various U.S. Federal Government agencies—from the Centers for Disease Control and Prevention to the National Oceanic and Atmospheric Administration in the U.S. Department of Commerce at San Juan and Iquitos

## Method
Time series regression with
- Support Vector Regression
- Xgboost
- Random Forest
- Gaussian Process

