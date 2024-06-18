# NYC Temperature Prediction Model for Kalshi Demo

## Project Overview

This project focuses on developing a machine learning model for predicting the maximum temperature in New York City, particularly at the Central Park weather station. The aim is to leverage this model for temperature trading on Kalshi Demo, a platform where users can bet on temperature outcomes.

### Key Features

The model is built using the following five features:
- **Ordinal Time:** To capture temperature trends over time.
- **Maximum Temperature:** Used for better prediction accuracy.
- **Relative Humidity:** To assess the likelihood of storms and precipitation.
- **Dew Point:** Another factor for predicting precipitation and weather patterns.
- **Wind Speed:** To consider the effects of wind chill on temperature readings.

### Basic Regression Analysis [Basic Regression](ML_Weather.ipynb)

The model applies three types of regression analysis methods:
- L1 Regression
- L2 Regression
- Linear Regression

### Neural Network Regression Analysis [Nerual Network Based Regression](MLPNeuralNetwork_Weather_Prediction.ipynb)
- Neural Network Based Regression (MLPRegressor)

## Kalshi Purchase Strategy

The model's predictions are utilized for a strategic approach on the Kalshi Demo platform. Rather than betting on specific temperatures, the algorithm places multiple "no" spread bets based on the predicted temperature range. This strategy involves:

- Avoiding bets within the predicted temperature range.
- Placing "no" bets on all options outside the predicted range.

## Installation and Usage
1. Download the ML_30_data.zip file and unzip it.
2. Open the Google Collab notebook, and follow the instructions for loading the training data.
3. Run each block of code in the Collab notebook as desired. 

# Please note that utilizing this algorithm for actual betting is not recommended. I AM NOT LIABLE FOR ANY OUTCOMES FROM IT'S USE. USE AT YOUR OWN RISK!
