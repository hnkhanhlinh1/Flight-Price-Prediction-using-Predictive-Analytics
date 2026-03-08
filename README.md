# Flight-Price-Prediction-using-Predictive-Analytics

Flight Price Prediction

Author: Linh Huynh

Course: DSC630 – Predictive Analytics, Bellevue University

1. Project Overview

Flight ticket prices change based on factors such as airline, route, duration, departure time, and number of stops.
This project uses machine learning to predict flight ticket prices and identify the main factors that influence pricing. 


The goal is to help airlines improve pricing strategies and help travelers choose better booking times.

2. Dataset

Flight Price Prediction Dataset
Source: Kaggle

~10,000 flight records

11 features including airline, source, destination, duration, stops, and price. 

10.2 course Project - Final pap…

3. Methods

Main project steps:

Data cleaning and preprocessing

Feature engineering (date and time extraction)

One-hot encoding for categorical variables

Train-test split (80/20)

Feature scaling

Models tested:

Linear Regression

Random Forest

XGBoost

Models were evaluated using MAE, RMSE, and R². 


4. Results

Tree-based models performed best.

Model	R²

Linear Regression	0.72

Random Forest	0.93

XGBoost	0.93 (best)

XGBoost produced the most accurate flight price predictions. 


5. Tools

Python

Pandas

Scikit-learn

XGBoost

Matplotlib / Seaborn

Jupyter Notebook

6. Author

Linh Huynh

MS Data Science – Bellevue University
