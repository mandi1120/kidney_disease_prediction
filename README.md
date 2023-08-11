# Kidney Disease Prediction & Risk Stratification Through Machine Learning  
- Description: Capstone Project for NWMSU Master of Science in Data Analytics Program
- Author: Amanda Hanway
- Date: 8/11/23

## Overview: 
- In this project, I created a machine learning model to predict kidney disease based on associated risk factors. I then ran the model on a new dataset and developed a Tableau dashboard to present the predicted outcomes for the population.  

### Files & Links:  
- Data Source: Centers for Disease Control & Prevention  
    - [Behavioral Risk Factor Surveillance System - 2021](https://www.cdc.gov/brfss/annual_data/annual_2021.html)
    - [Behavioral Risk Factor Surveillance System - 2019](https://www.cdc.gov/brfss/annual_data/annual_2019.html)
- Source Code: [View Jupyter Notebook](https://github.com/mandi1120/kidney_disease_prediction/blob/main/Capstone.ipynb)
- Tableau Dashboard: [View on Tableau Public website](https://public.tableau.com/app/profile/amanda.hanway/viz/BRFSS2019KidneyDiseasePredictions/Dashboard)
- Written Report: [View Report](https://github.com/mandi1120/kidney_disease_prediction/blob/main/Capstone_Project_Report.pdf)

## Abstract:  
Kidney disease affects millions of Americans and often goes undiagnosed. In the absence of medical care, data science can be leveraged to alert individuals who are at risk of developing the disease. This paper details the process of developing and evaluating machine learning models to predict the disease based on associated risk factors. Three machine learning models were trained using 2021 survey data collected by state health departments in combination with Centers for Disease Control & Prevention. Each model was run using four different sets of features. The XGBoost algorithm outperformed Random Forest and SGD using the features: diabetes, angina_coronary_heart_disease, high_blood_pressure, and age_group. This model achieved an F1 score of 80.98. The finalized model was applied to 2019 survey data to generate disease predictions and stratify individuals into risk levels. The survey data and model output were imported to a SQL database for storage. Data visualizations were developed in Tableau to summarize the results, which showed that 30% of the respondents are at risk of developing the disease. People aged 65 years and older are at the highest risk with a median risk score of 62.

## Methodology:
<img src="https://github.com/mandi1120/kidney_disease_prediction/blob/main/images/methodology.png?raw=true" name="methodology">

Project Summary:  
1. I first downloaded Behavioral Risk Factor Surveillance System (BRFSS) data collected in 2021 from the CDC website.  
2. I conducted exploratory data analysis to understand the dataset, then cleaned the data and engineered features in preparation for the machine learning model.  
3. I trained three machine learning models using the BRFSS 2021 data - XGBoost, Random Forest, and Linear SGD. I evaluated the outcomes for each model and selected the model that performed best.   
4. I ran the final model on a new dataset of BRFSS 2019 data, also from CDC, to generate predictions. I saved the data and model results to a SQL database, then wrote a query to load the data into Tableau. I created data visualizations in a dashboard form to present the results.   

View the written report for an in depth description of the project.

## Dashboard:
<img src="https://github.com/mandi1120/kidney_disease_prediction/blob/main/images/dashboard.png?raw=true" name="dashboard">

## SQL Query: 
<img src="https://github.com/mandi1120/kidney_disease_prediction/blob/main/images/sql.png?raw=true" name="sql">

## Written Report:
https://github.com/mandi1120/kidney_disease_prediction/blob/main/Capstone_Project_Report.pdf

<object data="../blob/main/Capstone_Project_Report.pdf" width="1000" height="1000" type='application/pdf'></object>

<embed src="https://drive.google.com/viewerng/viewer?embedded=true&url=https://github.com/mandi1120/kidney_disease_prediction/blob/main/Capstone_Project_Report.pdf" width="500" height="375">

<embed src="https://github.com/mandi1120/kidney_disease_prediction/blob/main/Capstone_Project_Report.pdf" width="500" height="375" type="application/pdf">
 
<br/>  
<br/>  
<br/>  
<br/>  
<br/>  
<br/>
