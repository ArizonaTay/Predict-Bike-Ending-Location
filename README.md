# Bike Sharing Demand Prediction
This repository contains code for a machine learning model that predicts the demand for bike sharing services in Boston. The model uses data on weather conditions, bike station locations, and historical bike usage patterns to predict the number of bikes that will be rented from each bike station on a given day.

## Table of Contents
- [Context](#context)
- [Data Loading](#data-loading)
- [Data Cleaning](#data-cleaning)
- [Feature Engineering](#feature-engineering)
- [Model Building](#model-building)
- [Conclusion](#conclusion)

## Context
Wheelie Wonka is a bike sharing company in Boston that wants to improve the mobile app experience for its users. To achieve this goal, the company wants to predict the ending bike station at the beginning of a bike trip, which will help users plan their trips effectively.

## Data Loading
The project starts by loading the necessary data, including information about bike trips, weather conditions, and station locations.

## Data Cleaning
The data is then cleaned, and duplicate values are removed. Irrelevant columns are dropped, and missing values are identified and handled appropriately. The project also handles incorrect data and data types and deals with outliers.

## Feature Engineering
The project includes feature engineering techniques such as mean Euclidean distance from other stations, zipcode feature extraction, age binning, and date and time feature extraction and encoding.

## Model Building
Finally, the project builds three models to predict the ending bike station at the beginning of a bike trip: Random Forest, Gradient Boost, and SVM.

## Conclusion
The project provides valuable insights into predicting the ending bike station at the beginning of a bike trip for Wheelie Wonka, a bike sharing company in Boston. The models built can be used to enhance the mobile app experience for users and help them plan their trips effectively.
