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

### Regression Analysis

The model applies three types of regression analysis methods:
- L1 Regression
- L2 Regression
- Linear Regression

## Kalshi Purchase Strategy

The model's predictions are utilized for a strategic approach on the Kalshi Demo platform. Rather than betting on specific temperatures, the algorithm places multiple "no" spread bets based on the predicted temperature range. This strategy involves:

- Avoiding bets within the predicted temperature range.
- Placing "no" bets on all options outside the predicted range.

## Installation and Usage

Simply open the Google Collab notebook, and follow the instructions for loading the training data. 


## Please note that utilizing this algorithm for actual betting is not recommended. I do not assume any responsibility for the consequences or outcomes resulting from its use.
