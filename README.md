# Traffic Accident Severity Analysis using Machine Learning

## Overview

This project analyzes and predicts the severity of traffic accidents using machine learning techniques on a large-scale dataset containing over 1.2 million records. The objective is to identify key factors influencing accident severity and build predictive models that classify accidents into three categories: Slight, Serious, and Fatal.

The project demonstrates an end-to-end machine learning pipeline including data extraction, preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

---

## Data Source

The dataset used in this project was extracted using the STAT19 data extraction package, which provides structured traffic accident data for research and analysis.

After extraction, the dataset was used for:

- Data cleaning and preprocessing  
- Exploratory data analysis  
- Feature engineering  
- Machine learning model development and evaluation  

---

## Problem Statement

Traffic accidents are influenced by multiple factors such as time, location, weather conditions, road type, and demographic attributes. Understanding these factors is important for improving road safety and supporting data-driven decision-making.

---

## Objectives

- Analyze accident patterns using exploratory data analysis  
- Identify key factors affecting accident severity  
- Build machine learning models for severity prediction  

---

## Dataset Description

The dataset contains more than 1,200,000 accident records with the following feature groups:

- Temporal features (hour, day, month, year)  
- Spatial features (location, urban/rural classification, road type)  
- Demographic features (driver age, casualty type)  
- Environmental features (weather conditions, lighting, road surface)  

---

## Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- LightGBM  
- CatBoost  
- Jupyter Notebook  

---

## Methodology

Data Extraction → Data Cleaning → Feature Engineering → Exploratory Data Analysis → Model Training → Model Evaluation  

---

## Machine Learning Models

- LightGBM Classifier  
- CatBoost Classifier  
- Ensemble Model (LightGBM + CatBoost)  

---

## Model Performance

| Model       | ROC AUC | Macro F1 Score |
|-------------|--------|---------------|
| LightGBM    | 0.78   | 0.52          |
| CatBoost    | 0.79   | 0.52          |
| Ensemble    | 0.79   | 0.53          |

---

## Key Findings

- Night-time accidents show higher severity rates compared to daytime  
- Rural areas have a higher proportion of fatal accidents  
- Weather and lighting conditions significantly impact accident severity  
- Speed limits and road types are strong predictive factors  
- Weekdays have more total accidents than weekends  

---

## Visualizations

- Confusion Matrix  
- Feature Importance Analysis  
- Accident Distribution by Time  
- Severity Distribution  
- Road Type and Weather Impact Analysis  

---

## Example Visuals

![Confusion Matrix](images/Confusion_matrix.png)

![Feature Importance](images/feature-importance.png)

---



## About the Author

Muhammad Abdullah is a Computer Science graduate with a strong interest in data science, machine learning, and artificial intelligence. He has experience in data analysis, exploratory data analysis, and building machine learning models using Python.

His focus is on turning raw data into meaningful insights and building practical solutions using real-world datasets. He is continuously improving his skills in machine learning, deep learning, and data-driven problem solving.

**GitHub:** https://github.com/abdullahdatascience  
**LinkedIn:** https://www.linkedin.com/in/abdullahumer12/  
**Location:** Faisalabad, Pakistan
