# FlightDelayPrediction-Project
A two stage classifier and predictor model for estimating on-time performance of flights from the given datasets.

Datasets - Weather and flight data considered from airports across US from 2016-17.

There are three modules - 
1) Data Preprocessing
2) Classification
3) Regression

Module one invloves merging these two data appropriately such that each record of the flight should have the corresponding weather data available

Module two involves modeling a classifier that classifies whether a given flight will be delayed or not using the features.
 
Module three involves choosing the flights that were classified to be delayed and train a regression engine which predicts the Arrival delay period (in minutes)
