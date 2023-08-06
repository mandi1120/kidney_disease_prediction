# Kidney Disease Prediction & Risk Stratification Through Machine Learning  
- Description: Capstone Project for NWMSU Master of Science in Data Analytics Program
- Author: Amanda Hanway
- Date: 8/11/23

## Overview: 
- In this project I created a machine learning model to predict kidney disease based on associated risk factors.
- The model generates a True/False prediction as well as assigns a risk level stratification to the individual.
- I created a PostgresSQL database to store the data and model results.
- Finally, I developed data visualizations in Tableau to summarize the results.

### Files & Links:  
- Data Sources: 
    - [Behavioral Risk Factor Surveillance System 2021](https://www.cdc.gov/brfss/annual_data/annual_2021.html)
    - [Behavioral Risk Factor Surveillance System 2019](https://www.cdc.gov/brfss/annual_data/annual_2019.html)
- Jupyter Notebook: [View Source Code](https://github.com/mandi1120/kidney_disease_prediction/blob/main/Capstone.ipynb)
- Tableau Dashboard: [View on Tableau Public website](https://public.tableau.com/app/profile/amanda.hanway/viz/BRFSS2019KidneyDiseasePredictions/Dashboard)
- Written Report: []()

### Abstract:  
Kidney disease affects millions of Americans and often goes undiagnosed. In the absence of medical care, data science can be leveraged to alert individuals who are at risk of developing the disease. This paper details the process of developing and evaluating machine learning models to predict the disease based on associated risk factors. Three machine learning models were trained using 2021 survey data collected by state health departments in combination with Centers for Disease Control & Prevention. Each model was run using four different sets of features. The XGBoost algorithm outperformed Random Forest and SGB using the features: diabetes, angina_coronary_heart_disease, high_blood_pressure, and age_group. This model achieved an F1 score of 80.98. The finalized model was applied to 2019 survey data to generate disease predictions and stratify individuals into risk levels. The survey data and model output were imported to a SQL database for storage. Data visualizations were developed in Tableau to summarize the results. The results showed that 30% of the respondents are at risk of developing the disease, while ages 65 and older are at the highest risk with a median risk score of 61.

### Methodology:
<img src="https://github.com/mandi1120/kidney_disease_prediction/blob/main/images/methodology.png?raw=true" name="methodology">

Summary:  
- I first downloaded BRFSS 2021 data from the CDC website.  
- I conducted exploratory data analysis, then cleaned the data and engineered features in preparation for the model.  
- I trained, tested, and evaluated three machine learning models to predict kidney disease using the BRFSS 2021 data. The XGBoost model performed the best of the three.   
- I ran the final model on a new dataset of BRFSS 2019 data to generate predictions. I saved the data and model results to a SQL database, then wrote a query to load the data into Tableau. I created data visualizations in a dashboard to present the results of the model.   
- View the written report for an in depth description of the project.

### Dashboard:
<img src="https://github.com/mandi1120/kidney_disease_prediction/blob/main/images/dashboard.png?raw=true" name="dashboard">

### Written Report:
will be linked here




<br/>  
<br/>  
<br/>  
<br/>  
<br/>  
<br/>