# Building Energy Consumption Analysis in Southern California
This is the project done during exchange at the University of Illinois Urbana-Champaign Fall Semester 2024

## Overview
Energy efficiency is a critical concern in modern urban settings, particularly in regions with high electricity demands and varying environmental conditions. By analyzing energy consumption data, we aim to identify patterns and factors that drive electricity usage, offering insights for energy optimization. 

This project analyzes factors influencing building energy consumption in Southern California using statistical modeling approaches. The analysis is based on a comprehensive dataset containing hourly electricity usage data from residential, commercial, and industrial buildings.

This analysis aims to:
Identify the key factors that significantly impact building energy consumption.
Develop predictive models for energy usage based on available data.
Provide actionable insights for optimizing energy strategies in Southern California buildings.

## Dataset
- **Source**:  Kaggle(https://www.kaggle.com/datasets/datasetengineer/southern-california-energy-consumption)
- **Time Period**: January 2018 to January 2024
- **Size**: 52,586 records with 12 variables
- **Key Variables**: Timestamp, building type, energy consumption, temperature, solar radiation, HVAC consumption, etc.

## Features
- Data cleaning and preprocessing
- Exploratory data analysis
- Multiple statistical modeling approaches:
  - Simple linear regression
  - Multiple linear regression
  - Stepwise regression
  - Polynomial regression
  - Exhaustive search

## Key Findings
- Building size and peak demand reduction are significant predictors of energy consumption
- Models demonstrated consistent performance across different approaches:
  - Train RMSE: 17.53-17.56
  - Test RMSE: 19.39-19.41
- Stepwise model showed optimal balance of complexity and performance

## Technical Stack
- R
- Key Libraries:
  - ggplot2
  - dplyr
  - leaps
  - MASS
  - car
  - lmtest

## Future Work
- Extend analysis to multiple years of data
- Implement advanced machine learning techniques
- Develop time series models for better predictions

## Contributors
- Xingzhi Du
- Chen Liu
- Banghao Chi
