# Project4HeartDisease
### Project 4 Predicting Heart Disease

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

1017 Reviewed code and finalized presentation

## GitHub Repository Files  
Proposal: Final Project- Proposal.pdf  
Data: Heart_Disease_Prediction.csv  
Python utilizing Google Colab Final file: Final_Project.ipynb  
Trimmed (not optimal) Google Colab file: Trimmed_Final_Project.ipynb    
Presentation: Heart_Disease_Prediction.pdf   
.gitignore file = ignore Python  

(WIP folder stored in progress stop points for Google Colab)

## Conclusions
### Modeling  
The purpose of this project was to analyze a dataset using various models to predict heart disease.  The dataset consisted of 270 individuals classified as having heart disease based on cardiac catheterizations using 14 features.    

The models that were tested were:  Random Forest, Neural Network, Logistic Regression, and SVM.  

It was determined that Logistic Regression was the best predictive model with an accuracy score of 0.92

Trimmed less predictive columns (determined via Feature Importance after RandomForest) from the original dataframe, then ran the same neural network on the trimmed version. The accuracy faired much worse, shown here: https://colab.research.google.com/drive/1C7SYGXmBdGKel9R5Oayl-UzqOfUvHwTL#scrollTo=V_-C7Wqx9IaS  

### Application
* Features such as Sex, BP and Cholesterol which are available before admission will be useful to predict the onset of heart disease  

* Explore other clinical features for these prediction to be useful for medical professional to raise awareness and potential prevent heart disease 

* Select high risk patients for frequency EKG

### Possible next steps to optimize model 
* Split sex in dataset based on our data exploration    
* Bigger Dataset    
* Use different methods for feature selection     
* Handling outliers    
* Feature splitting    
* Backward selection    

## Link to Presentation
pdf link: https://drive.google.com/file/d/1xRdcdXATBeSt8eREUGYCMqXUL2wPE9VA/view?usp=share_link  

tableau link: https://public.tableau.com/views/Heart_Disease_16968920407140/CorrelationofClinicalVariablestoHeartDiseaseDiagnosis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link  

## Installing
The following applications are necessary to manage, clean the data, and create visualizations for the project.  
Google Colab  
Tableau  
Spark SQL  
Python  

## Sources
Sources of Data: [Predicting Heart Disease Using Clinical Variables (kaggle.com)](https://www.kaggle.com/datasets/thedevastator/predicting-heart-disease-risk-using-clinical-var/code)      
Attributes: https://archive.ics.uci.edu/dataset/45/heart+disease   
Credit: Robert Hoyt MD  
  
## Contributing
Contributors: Kailey Carbone, Michaela Johnson, Tahseen Shaik, Aleid van der Zel  

Acknowledgements: Thank you Ryan Coble (Instructor) and Andrew Kriger (TA)!
