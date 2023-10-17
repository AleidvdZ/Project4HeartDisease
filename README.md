# Project4HeartDisease
Project 4 Predicting Heart Disease

## Overview
The industry selected by the analysis team was healthcare. 

## Questions
* What are the best clinical variables for predicting the probability of heart disease?  
* The variables include, demographics (age, sex), EKG data, and other heart condition related variables   
* Inform patients what are the highest risk factors in developing heart disease  
* This data could be used to advice, provide interventions, treatment plans   

## Timeline of Activities/Things Learned
1005 Created and submitted proposal for project  

1009 Created some Tableau visuals of data to understand relationships between variables  
https://public.tableau.com/app/profile/aleid.van.der.zel/viz/Heart_Disease_16968920407140/CorrelationofClinicalVariablestoHeartDiseaseDiagnosis?publish=yes    
  
1010 Worked in Google Colab to upload data, create SparkSQL queries, determine preprocessing need for machine modeling, added neural network model code

1012 Worked in Google Colab: Preprocessing and neural network model  

1016 Worked in Google Colab reviewing other predictive models, limiting features.  Completed most of presentation.  

## Conclusions
Trimmed less predictive columns (determined via Feature Importance after RandomForest) from the original dataframe, then ran the same neural network on the trimmed version. The accuracy faired much worse, shown here: https://colab.research.google.com/drive/1C7SYGXmBdGKel9R5Oayl-UzqOfUvHwTL#scrollTo=V_-C7Wqx9IaS  

The purpose of this project was to analyze a dataset using various models to predict heart disease.  The dataset consisted of 270 individuals classified as having heart disease based on cardiac catheterizations using 14 features.    

The models that were tested were:  Random Forest, Neural Network, Logistic Regression, and SVM.  

It was determined that Logistic Regression was the best predictive model with an accuracy score of 0.92  

### Link to Presentation
tableau link: https://public.tableau.com/views/Heart_Disease_16968920407140/CorrelationofClinicalVariablestoHeartDiseaseDiagnosis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link  

pdf link:  

### Installing
The following applications are necessary to manage, clean the data, and create visualizations for the project.  
Google Colab  
Tableau  
Spark SQL  
Python  

### Sources
Sources of Data: [Predicting Heart Disease Using Clinical Variables (kaggle.com)](https://www.kaggle.com/datasets/thedevastator/predicting-heart-disease-risk-using-clinical-var/code)      
Attributes: https://archive.ics.uci.edu/dataset/45/heart+disease   
Credit: Robert Hoyt MD  
  
### Contributing
Contributors: Kailey Carbone, Michaela Johnson, Tahseen Shaik, Aleid van der Zel  

Assisting: Ryan Coble (Instructor) and Andrew Kriger (TA)

