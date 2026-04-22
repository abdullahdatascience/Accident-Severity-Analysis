# 🚗 Traffic Accident Analysis & Severity Prediction

## 📌 Project Overview
This project analyzes large-scale traffic accident data from multiple sources to understand patterns in time, location, demographics, environmental conditions, and risk factors. It also builds machine learning models to predict accident severity.

The goal is to support data-driven road safety decisions and identify high-risk conditions.

---

## 🎯 Objectives
- Identify when and where accidents occur most frequently
- Analyze demographic and environmental risk factors
- Understand severity patterns in accidents
- Build ML models to predict accident severity

---

## 📊 Dataset Description
Multiple datasets were merged:
- Severity Analysis
- Spatial Analysis
- Demographic Analysis
- Temporal Analysis
- Risk Factors Analysis

Final dataset size:
- **1.19M+ rows**
- **24 features (after cleaning)**

---

## 🧹 Data Preprocessing
- Removed duplicate records
- Handled missing values
- Standardized categorical values
- Imputed missing coordinates using KNN Imputer
- Removed highly missing columns (>99% missing)
- Encoded target variable (accident severity)

---

## 📈 Exploratory Data Analysis (EDA)
Key insights:
- Most accidents occur during afternoon rush hours (3–6 PM)
- Night-time accidents have higher fatality rates
- Weekdays have significantly more accidents than weekends
- Rural areas show higher fatal accident rates
- Weather and road conditions strongly impact severity

---

## 🤖 Machine Learning Models
The following models were trained:

- LightGBM Classifier
- CatBoost Classifier
- Ensemble Model (LightGBM + CatBoost)

### Evaluation Metrics:
- Accuracy
- Macro F1 Score
- ROC AUC Score

---

## 🏆 Results
- Best Macro F1 Score: **0.53**
- Best ROC AUC Score: **0.79**
- Ensemble model performed best overall

---

## 📌 Key Takeaways
- Severity is highly influenced by time, road type, and weather conditions
- Night and rural conditions significantly increase fatality risk
- Ensemble models improve stability across imbalanced classes

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- LightGBM
- CatBoost
- Optuna

---

## 📁 Project Structure

traffic-accident-analysis/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
│
├── data/
│ └── raw/
│
└── outputs/


---

## 🚀 Future Improvements
- Deep learning models (Neural Networks / CNN)
- Real-time prediction system
- Deployment using Flask/FastAPI
- Geographic visualization (maps)

---

## 👨‍💻 Author
Muhammad Abdullah  
Data Analyst | ML Enthusiast