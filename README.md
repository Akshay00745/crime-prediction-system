# 🚔 Crime Prediction System using Machine Learning (San Francisco Dataset) – Day 10

## 📌 Project Overview
This project focuses on analyzing and predicting crime patterns using the San Francisco Crime Dataset.  
The objective is to understand crime distribution across time and locations and build machine learning models to classify crime categories based on historical data.

This project is part of my **30 Days Real-World Data Science Project Challenge**.

---

## 🎯 Problem Statement
Law enforcement agencies require data-driven insights to:
- Identify high-crime areas  
- Understand crime trends by time and location  
- Predict crime categories using machine learning  
- Support proactive policing strategies  

Target variable:
- **Crime Category**

---

## 🗂 Dataset
**San Francisco Crime Dataset**

Key columns used:
- Dates  
- Category (Target)  
- DayOfWeek  
- PdDistrict  
- Longitude (X)  
- Latitude (Y)  

---

## 🛠 Tools & Technologies
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔍 Exploratory Data Analysis (EDA)

### Analyses Performed:
- Crime distribution by type  
- Crimes by time of day  
- Crimes by district (location)  
- Crimes by day of week  
- Yearly crime trend  

### Visualizations:
- Bar chart → Top 10 crime types  
- Heatmap → Crime frequency by hour and day of week  
- Bar chart → Crimes by district  
- Bar chart → Crimes by day of week  
- Line plot → Yearly crime trend  

---

## 🤖 Model Building
Two machine learning models were trained:

- Decision Tree Classifier  
- Random Forest Classifier  

---

## 📊 Model Evaluation
Models were evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  
- ROC-AUC  

Both models demonstrated strong performance in classifying crime categories based on temporal and spatial features.

---

## 📈 Key Insights

- **Larceny/Theft** is the most common crime type in San Francisco.  
- Crime activity is highest during afternoon and evening hours.  
- **Southern and Mission districts** report the highest number of crimes.  
- Crime frequency peaks on **Fridays and Saturdays**.  
- Yearly trend analysis shows fluctuations in crime levels over time.  
- Random Forest outperformed Decision Tree in terms of generalization and stability.  

---

## 🏙 Social & Business Impact

- Supports predictive policing and smarter resource allocation  
- Helps identify high-risk areas and peak crime hours  
- Enables data-driven decision-making for public safety  

---

## 🚀 Future Improvements
- Hyperparameter tuning for Random Forest  
- Feature importance analysis  
- Handle class imbalance  
- Deploy model using Streamlit for real-time predictions  

---

## 👤 Author
**Akshay Kumar**  
30 Days Real-World Data Science Project Challenge  
Aspiring Data Scientist
