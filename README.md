# House Pricing Prediction Project

This project focuses on predicting house prices using machine learning techniques. The goal is to build a model that accurately estimates the price of a house based on various features, providing valuable insights for buyers and sellers in the real estate market.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Data Exploration](#data-exploration)
- [Data Preprocessing](#data-preprocessing)
- [Model Building](#model-building)

## Overview
House price prediction is a critical task in the real estate industry. This project utilizes machine learning to develop predictive models, assisting users in making informed decisions related to property values.

## Dataset
The dataset used for this project contains various attributes, including:
- Avg. Area Income
- Avg. Area House Age
- Avg. Area Number of Rooms
- Avg. Area Number of Bedrooms
- Area Population
- Price
- Address

You can access the dataset [https://www.kaggle.com/datasets/vedavyasv/usa-housing]

## Prerequisites
Before running the code, ensure that you have the following libraries installed:

- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost
```

## Getting Started
1. Load the dataset using the provided link or replace it with your dataset.
2. Explore the data to understand its structure, including data types and any missing values.

## Data Exploration
- Utilize data visualization to gain insights into feature relationships and distributions.
- Generate histograms, box plots, pair plots, and correlation heatmaps.

## Data Preprocessing
- Handle missing data if necessary.
- Standardize or normalize the data.
- Encode categorical variables if applicable.

## Model Building
This project includes building multiple regression models:
- Linear Regression
- Support Vector Regressor
- Lasso Regression
- Random Forest Regressor

For each model:
1. Train the model.
2. Make predictions.
3. Evaluate the model using R-squared, mean absolute error, and mean squared error.
