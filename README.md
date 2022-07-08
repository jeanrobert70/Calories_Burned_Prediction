# Calories Burned Prediction

This project explores a topic near and dear to my heart: calories burned. The goal of this project is to predict  the amount of calories an individual will burned based of the following attributes:

RangeIndex: 15000 entries, 0 to 14999
Data columns (total 9 columns):
    Column      Non-Null Count  Dtype  
---  ------      --------------  -----  
 0   User_ID     15000 non-null  int64  
 1   Gender      15000 non-null  object 
 2   Age         15000 non-null  int64  
 3   Height      15000 non-null  float64
 4   Weight      15000 non-null  float64
 5   Duration    15000 non-null  float64
 6   Heart_Rate  15000 non-null  float64
 7   Body_Temp   15000 non-null  float64
 8   Calories    15000 non-null  float64


This is a another simple dataset but I utilize XGBoost Regressor to obtain our objective. 

We're going to take the follow approach:

Problem Defintiion
Data
Evaluation
Features
Modelling
Experimentation
