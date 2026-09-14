# Airbnb Price Prediction Using Machine Learning and Sentiment Analysis

## Project Overview

This project focuses on predicting Airbnb listing prices in New York City using
machine learning techniques and customer review sentiment analysis.

The project combines Airbnb listing information with review-based sentiment
features to build and evaluate multiple predictive models.

## Objectives

* Analyze Airbnb listings in New York City
* Clean and preprocess Airbnb listing and review data
* Perform sentiment analysis on customer reviews
* Engineer relevant features for price prediction
* Apply feature selection techniques
* Train multiple machine learning models
* Compare model performance using MAE, MSE and R²
* Identify the best-performing price prediction model

## Dataset

The NYC Airbnb dataset contains approximately 50,221 records and 96 features.

The project uses Airbnb listing, reviews and geospatial data for analysis and price prediction.

The full `airbnb-averages-001.geojson` dataset is approximately 3 GB and is therefore not included in this GitHub repository due to GitHub's file-size limitations.

A smaller `airbnb-averages-sample.geojson` file is included for reference and demonstration purposes.

## Project Workflow

```text
Data Collection
       ↓
Data Preprocessing
       ↓
Review Sentiment Analysis
       ↓
Feature Engineering
       ↓
Data Scaling
       ↓
Feature Selection
       ↓
Train / Validation / Test Split
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Price Prediction







