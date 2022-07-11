# Calories Burned Prediction

This project explores a topic near and dear to my heart: calories burned. The goal of this project is to predict  the amount of calories an individual will burned based of the following attributes:

    Column      Non-Null Count  Dtype  
---  ------      --------------  -----  
*    User_ID     15000 non-null  int64  
*    Gender      15000 non-null  object 
*    Age         15000 non-null  int64  
*    Height      15000 non-null  float64
*    Weight      15000 non-null  float64
*    Duration    15000 non-null  float64
*    Heart_Rate  15000 non-null  float64
*    Body_Temp   15000 non-null  float64
*    Calories    15000 non-null  float64


This is a another simple dataset but I utilize XGBoost Regressor to obtain our objective. 

We're going to take the follow approach:

* Problem Defintiion
* Data
* Evaluation
* Features
* Modelling
* Experimentation
