Traffic Accident Severity Analysis using Machine Learning
Overview

This project analyzes and predicts traffic accident severity using machine learning techniques on a large-scale dataset containing over 1.2 million records. The objective is to identify key factors influencing accident severity and build predictive models to classify accidents into three categories: Slight, Serious, and Fatal.

Problem Statement

Traffic accidents are influenced by multiple factors such as time, location, weather, road conditions, and demographic attributes. Understanding these factors is important for improving road safety and decision-making.

The objectives of this project are:

To analyze accident patterns using exploratory data analysis
To identify significant factors affecting accident severity
To develop machine learning models for severity prediction
Dataset Description

The dataset contains more than 1,200,000 accident records with the following types of features:

Temporal features (hour, day, month, year)
Spatial features (location, urban/rural classification, road type)
Demographic features (driver age, casualty type)
Environmental features (weather conditions, lighting, road surface)
Methodology

The project follows a structured machine learning pipeline:

Data Collection → Data Cleaning → Feature Engineering → Exploratory Data Analysis → Model Training → Model Evaluation

Machine Learning Models

The following models were implemented and evaluated:

LightGBM Classifier
CatBoost Classifier
Ensemble Model (LightGBM + CatBoost)
Model Performance
Model	ROC AUC	Macro F1 Score
LightGBM	0.78	0.52
CatBoost	0.79	0.52
Ensemble	0.79	0.53
Key Findings
Night-time accidents show higher severity levels compared to daytime
Rural areas have a higher proportion of fatal accidents
Weather and lighting conditions significantly affect accident outcomes
Speed limits and road types are strong indicators of severity
Weekdays show a higher number of total accidents compared to weekends
Visualizations

The analysis includes the following visual outputs:

Confusion matrix
Feature importance analysis
Temporal distribution of accidents
Severity distribution across different factors

(Visuals can be found in the images folder)
