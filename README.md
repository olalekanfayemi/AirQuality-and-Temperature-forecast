# AQI-Deployment
## Aim :
### In this project we will be building an Air Quality Index Predictor with the help of Machine Learning Models and Auto ML library i.e. TPOT
This repository contains code to predict the air quality based on the given parameters.

##Dataset
Dataset of Bangalore city with the Air Quality Index information from the year 2013-2018. 
- [Data](https://github.com/evon0101/Air-Quality-index-Prediction/blob/main/Data/city_hour.csv)
The data was taken from the website: (https://en.tutiempo.ne

### Feature abbreviation and meaning:
- T	 = Average annual temperature
- TM = Annual average maximum temperature
- Tm = Average annual minimum temperature
- SLP = Sea Level Pressure
- H = Humidity
- V	= Annual average wind speed
- VM = Maximum wind speed
- PM 5 : This is our Dependent variable i.e. our Air Quality Index

## Time Line of the Project:
- Data Analysis
- Fearure Engineering
- Model Building and Prediction using ML models
- Model Building and Prediction using TPOT(Auto ML)
- Deployment on Heroku

## Machine Learning Models:
Below are the machine learning models used for this project
- [Linear Regression]
- [Xgboost Regressor]
- [Random Forest Regress]
- [TPOTRegressor]

## :gear: Project Demo
- Application is hosted on Heroku. You can see the [demo](https://air-quality-index-aq1.herokuapp.com/)

Deploy using CLI
****
Install the Heroku CLI
Download and install the Heroku CLI.

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.

$ heroku login
Clone the repository
Use Git to clone air-quality-index-aq1's source code to your local machine.

$ heroku git:clone -a air-quality-index-aq1 
$ cd air-quality-index-aq1
Deploy your changes
Make some changes to the code you just cloned and deploy them to Heroku using Git.

$ git add .
$ git commit -am "make it better"
$ git push heroku master
****
