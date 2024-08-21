# spotify_models
## Overview
This project aims to find the best model to predict the popularity score of songs on Spotify. An MAE score determines the best-performing model that stores the results in a data frame.

## Dependencies
pandas: For data manipulation and analysis.
numpy: For numerical operations.
scikit-learn: For machine learning algorithms and utilities.
other models or libraries: Depending on the specific models used (e.g., XGBoost, Random Forest, etc.).

## Understanding the data and data preparation

Load the song data into a pandas data frame.
Handle missing values by dropping irrelevant columns and checking for missing values.

## scaling
Scale the date using the MinMax Scaler.

## encoding
this involves encoding the data.

## data preprocessing 
It involves the train test split.

## modelling
We use dictionaries to loop over the models and store the results in a dictionary.
Evaluate the performance of each model using mean absolute error(MAE)

## Loading
Create a data frame to store the predicted popularity scores.
Include columns for song ID, predicted popularity, and other relevant information.
