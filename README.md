# Air_Quality_Prediction_Using_ARIMA
<h3><b>Introduction</b></h3>
<p> The goal of this project is to take the publically available Beijing weather data from 2013 to 2017 and apply Time Series techniques to see if we can predict the amount of PM2.5 concentration in the air given other environmental features.I hope to come up with a predictive model with a high accuracy and a very low Root Mean Square Error (RMSE).</p>
<br>
<h3><b>Dataset Information</b></h3>
<p>This data set includes hourly air pollutants data from 12 nationally-controlled air-quality monitoring sites. The air-quality data are from the Beijing Municipal Environmental Monitoring Center. The meteorological data in each air-quality site are matched with the nearest weather station from the China Meteorological Administration. The time period is from March 1st, 2013 to February 28th, 2017. Missing data are denoted as NA.
Here is the link to access the cleaned dataset https://archive.ics.uci.edu/ml/datasets/Beijing+Multi-Site+Air-Quality+Data </p>
<br>
<h3><b>Project workflow</b></h3>
<p>This project utilizes the Time Series model. The model we hope to succeed in training is a regression model and below are the steps we will go through in this colab notebook for this project:</p>
<ul>
    <li>Import the neccessary libraries and loading the data</li>
    <li>Data preprocessing</li>
    <li>Exploratory Data Ananlysis</li>
    <li>Seasonality Checking</li>
    <li>Model Fitting using ARIMA</li>
    <li>Saving the model</li>
</ul>
<br>
