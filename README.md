Traffic Accident Severity Analysis using Machine Learning
Overview

This project analyzes and predicts the severity of traffic accidents using machine learning techniques on a large-scale dataset containing over 1.2 million records. The objective is to identify key factors influencing accident severity and build predictive models that classify accidents into three categories: Slight, Serious, and Fatal.

The project demonstrates an end-to-end machine learning pipeline including data extraction, preprocessing, exploratory data analysis, feature engineering, model training, and evaluation.

Data Source

The dataset used in this project was extracted using the STAT19 data extraction package, which provides structured traffic accident data for research and analysis.

After extraction, the data was processed and used for:

Data cleaning and preprocessing
Exploratory data analysis
Feature engineering
Machine learning model development and evaluation
Problem Statement

Traffic accidents are influenced by multiple factors such as time, location, weather conditions, road type, and demographic attributes. Understanding these factors is important for improving road safety and supporting data-driven decision-making.

Objectives:
Analyze accident patterns using exploratory data analysis
Identify key factors affecting accident severity
Build machine learning models for severity prediction
Dataset Description

The dataset contains more than 1,200,000 accident records with the following feature groups:

Temporal features (hour, day, month, year)
Spatial features (location, urban/rural classification, road type)
Demographic features (driver age, casualty type)
Environmental features (weather conditions, lighting, road surface)
Tools and Technologies
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
LightGBM
CatBoost
Jupyter Notebook
Methodology

The project follows a structured machine learning pipeline:

Data Extraction → Data Cleaning → Feature Engineering → Exploratory Data Analysis → Model Training → Model Evaluation

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
Night-time accidents show higher severity rates compared to daytime
Rural areas have a higher proportion of fatal accidents
Weather and lighting conditions significantly impact accident severity
Speed limits and road types are strong predictive factors
Weekdays have more total accidents than weekends
Visualizations

The project includes the following visual analyses:

Confusion Matrix
Feature Importance Analysis
Accident Distribution by Time
Severity Distribution
Road Type and Weather Impact Analysis
Example Visuals
![Confusion Matrix](images/Confusion_matrix.png)
![Feature Importance](images/feature-importance.png)
Project Structure
Accident-Severity-Analysis/
│
├── Accident_Severity_Analysis.ipynb
├── README.md
├── requirements.txt
├── images/
│   ├── Confusion_matrix.png
│   ├── feature-importance.png
│   ├── roc_curve.png
│   ├── model_comparison.png
│   └── other plots
How to Run This Project
git clone https://github.com/abdullahdatascience/Accident-Severity-Analysis.git
cd Accident-Severity-Analysis
pip install -r requirements.txt
jupyter notebook
Author

Muhammad Abdullah
Faisalabad, Pakistan
GitHub: https://github.com/abdullahdatascience

LinkedIn: https://www.linkedin.com/in/abdullahumer12/

Future Improvements
Hyperparameter tuning for improved performance
Deep learning models for comparison
Deployment using Flask or FastAPI
Real-time accident severity prediction system
