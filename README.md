# Used Car Price Prediction Model

## Overview
This repository contains code for predicting the price of used cars based on various features such as car brand, kilometers driven, fuel type, and more. The model leverages machine learning algorithms to provide accurate price estimations for used cars.

## Data Preprocessing and Cleaning
The dataset used for training the model was preprocessed and cleaned to ensure accurate predictions. Steps involved in preprocessing and cleaning include:

Extracting brand names from the 'car_name' column
Converting car price values to a standardized format
Handling missing values and outliers in the dataset
Encoding categorical variables using one-hot encoding
Creating a new feature for categorizing price ranges

## Model
The model employs the following machine learning classifiers:

Naive Bayes Classifier
Support Vector Machine (SVM) Classifier
Simple K Nearest Neighbors (KNN) Classifier
Weighted KNN Classifier

These classifiers are trained and evaluated using various train-test split ratios to determine the optimal combination for predicting car prices accurately.

## Data Visualization
Data visualization techniques were used to gain insights into the relationships between different features and the target variable (car price). Visualizations include histograms, correlation matrix heatmaps, and scatter plots, providing a comprehensive understanding of the dataset's characteristics.

## Conclusion
The used car price prediction model showcased promising performance in accurately estimating car prices based on relevant features. By leveraging machine learning algorithms and thorough data preprocessing, the model offers valuable insights for both buyers and sellers in the used car market.

For detailed implementation and code execution, refer to the Jupyter Notebook provided in this repository.
