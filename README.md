# CO-AirQuality-Prediction-and-Temperature-forecast
## Aim :
### In this project we will be building a CO Predictor with the help of XGBest Models and Temoerature forecast with LSTM
This repository contains code to predict the air quality based on the given parameters.

##Dataset
- [Source](https://www.kaggle.com/datasets/fedesoriano/air-quality-data-set) Kaggle
#### Context
This dataset contains the responses of a gas multisensor device deployed on the field in an Italian city. Hourly responses averages are recorded along with gas concentrations references from a certified analyzer. This dataset was taken from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/index.php

### Feature abbreviation and meaning:
- Date (DD/MM/YYYY)
- Time (HH.MM.SS)
- True hourly averaged concentration CO in mg/m^3 (reference analyzer)
- PT08.S1 (tin oxide) hourly averaged sensor response (nominally CO targeted)
- True hourly averaged overall Non Metanic HydroCarbons concentration in microg/m^3 (reference analyzer)
- True hourly averaged Benzene concentration in microg/m^3 (reference analyzer)
- PT08.S2 (titania) hourly averaged sensor response (nominally NMHC targeted)
- True hourly averaged NOx concentration in ppb (reference analyzer)
- PT08.S3 (tungsten oxide) hourly averaged sensor response (nominally NOx targeted)
- True hourly averaged NO2 concentration in microg/m^3 (reference analyzer)
- PT08.S4 (tungsten oxide) hourly averaged sensor response (nominally NO2 targeted)
- PT08.S5 (indium oxide) hourly averaged sensor response (nominally O3 targeted)
- Temperature in Â°C
- Relative Humidity (%)
- AH Absolute Humidity

## Time Line of the Project:
- Data Analysis
- Fearure Engineering
- Model Building and Prediction using XGB Regressor  models
- Model Building and Forecast using LSTM
- Deployment ---

## Machine Learning Models:
Below are the machine learning models used for this project
- [Xgboost Regressor]
- [LSTM]

## Outputs
- data_from_hours_2days (The average daily value for all selected features)
- co_XGBreg_model (XGBoost Regressor model)
- model (LSTM model). Not included because of file size.

![Temperature TS Forecast](https://user-images.githubusercontent.com/112252681/188776041-24f7c266-678a-4d62-af49-8d3d754bc9f8.png)


## Acknowledgements
Saverio De Vito (saverio.devito '@' enea.it), ENEA - National Agency for New Technologies, Energy and Sustainable Economic Development

## Citation Request
S. De Vito, E. Massera, M. Piga, L. Martinotto, G. Di Francia, On field calibration of an electronic nose for benzene estimation in an urban pollution monitoring scenario, Sensors and Actuators B: Chemical, Volume 129, Issue 2, 22 February 2008, Pages 750-757, ISSN 0925-4005. (https://www.sciencedirect.com/science/article/abs/pii/S0925400507007691)
