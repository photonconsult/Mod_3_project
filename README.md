# Mod_3_project

# Medical Appointments No-Shows
Flatiron Module 3 Classification Project

# Project Overview
Working with hospital data about patients and their appointments from brazil, we would be analyzing the patient information and building a classification model to predict whether or not they would show up for their appointments.We would be approaching from the perspective of the hospital administration, it would be more important to have a predictive model that can aid with allocation of resources.

## Approach
* My process had 6 parts:
* Getting my Data
* Cleaning and analyzing the data using Pandas
* Running Statistical tests on my data using scipy
* Visualizing our insights using Seaborn and Matplotlib
* Engineering Features for my model
* Fitting several models and tuning the parameters 
## Getting my data
From Kaggle, contributor; Joni Hoppen and Aquarela Advanced Analytics Aquarela
The data contained patients appointments and some information on each patient.
 
## Cleaning and analyzing the data using Pandas
We spent several hours cleaning the data using Pandas Dataframes and Series to prepare it for analysis. We removed or updated Null values. We grouped relevant information together and created new columns When necessary. We prepared the data until it was convenient to work with.

## Running Statistical tests on my data using Scipy
We ran several statistical tests on the data using scipy. To see the statistical significance of the various features. This guided our feature select process.
## Visualizing our insights using Seaborn and Matplotlib
We  explored our data and provided various visualizations for the statistical tests carried out and also to gain more insight on the factors we considered to have an effect on the target variable (no-show)
## Engineering Features for my model
We  created new features from the information in the data. We were able to explore the engineered features and run statistical tests on them to verify its significance and also saw improvements on our models
## Modelling 
We test our data across several models, they include
* Logistic Regression
* KNN
* Decision Trees
* Random forest 
* Xgboost
 
## Conclusion
We were able to improve on the dummy classifier accuracy, given the class imbalance we got a pretty high F1 score at
## Moving Forward
One of the limitations we discovered exploring the data is the time frame the data spans.The appointment days span just over a month, making predictions difficult since this data is just a snapshot of the patients patterns. Also the appointment exact times were not available which could have been very useful in predictions. In addition more context was needed for certain features to better explain, example; SMS received. Finally context to the reason for the appointment would have been also a helpful tool.
## Presentation

