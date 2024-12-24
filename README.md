# Time-Series-forecasting-using-LSTM

This repository contains an implementation of a Long Short-Term Memory (LSTM) model for time series forecasting, with the integration of Approximate Bayesian Computation (ABC) rejection sampling to optimize model hyperparameters. The project demonstrates preprocessing, model training, hyperparameter tuning, and evaluation on a time series dataset of monthly airline passengers.

### Features

LSTM Implementation: A PyTorch-based LSTM model for forecasting future values based on historical data.

ABC Rejection Sampling: An implementation of Approximate Bayesian Computation to sample optimal hyperparameters (hidden size and learning rate).

Custom Time Series Dataset: Prepares data for supervised learning using a sliding window approach.

Evaluation Metrics: Calculates RMSE and MAE on both normalized and original scales.

Visualization: Plots actual vs. predicted values for the test dataset in the original scale.

Dataset

The dataset used is the monthly airline passenger count (AirPassengers.csv). It consists of two columns:

Month: The timestamp.

#Passengers: The number of passengers.

The data undergoes preprocessing to normalize values and create lagged features for supervised learning.
