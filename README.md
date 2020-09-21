# General-Assembly-Data-Science-Immersive
## Projects and Capstone Project

This repository has been made public to show case the work that I completed through June to August 2020 during my time with General Assembly on their Data Science Immersive course.All projects were solo projects. 
The projects were as follows:

[**Project 1:**](https://github.com/mensah50/General-Assembly-Data-Science-Immersive/blob/master/project-1-v2-starter-code.ipynb)
Pokedex - Programming a prototype version of the game and analyze the planned content to help the team calibrate the design using Python

[**Project 2:**](https://github.com/mensah50/General-Assembly-Data-Science-Immersive/blob/master/project-02-v2-starter-code.ipynb)
Exploratory Data Analysis (EDA)  - Performing EDA on Maths and English SAT Scores

**Project 3:**
Regression and Classification with the Ames Housing Data - Estimating the value of homes from fixed characteristics: Using Lasso, Ridge modelling techniques.I have broken this down into two parts as I was unable to upload the code in its entirety

[**Project 3 - Part 1:**](https://github.com/mensah50/General-Assembly-Data-Science-Immersive/blob/master/project-03-starter-pt1.ipynb)
Through this link you can view the code that relates to the EDA steps taken before proceeding with modelling the data 

[**Project 3 - Part 2:**](https://github.com/mensah50/General-Assembly-Data-Science-Immersive/blob/master/project-03-starter-pt2.ipynb)
Through this link you can view the code that related to the modelling of the Housing Data 

[**Project 4:**]()
Web Scraping Data roles from Indeed.com and Predicting Salaries

[**Capstone Project:**]()
Flu Shot Learning - Predict H1N1 AND Seasonal Flu Vaccine (Data Driven Competition)

This includes the code and presentation related to my Capstone Project for the Data Science Immersive I completed in September 2020 with General Assembly. The Project was based on predicting the probability of various respondents with different socio-economic backgrounds having the the H1N1 vaccine, seasonal vaccine or both. This was based on a Driven Data competition.

## Background

At the time of writing this the UK and the majority of the world are under lockdown restrictions due to the Coronavirus. Discussions around the requirement of a vaccine have reached fever pitch with varying schools of thought around the development of a vaccine and also those that are for and opposed to even receiving the vaccine. This sparked my interest into whether there were any determining factors that could impact individuals likelihood to accept a potential vaccine. Coincidentially when considering the approach on how to accquire the data I came across the Data Driven Competition which provided a data set for me to work with. Please not that the data will not be shared on in this repository.

## Methodology and Approach

Aimed to predict the probability of individuals with varying socio-economic factors getting the H1N1 and or seasonal vaccines. Used the Multi-Output Classifier with Logistic Regression, Random Forest, and Decision trees classifiers to model the probabilities and gain insights into the important features of the data.

[Data Preparation and Cleaning]()

[Exploratory Data Analysis]()

## Modelling - Multi-Output Classifier
As the requirement is to predicit the probability of whether the respondents receive the H1N1 vaccine and, or the seasonal vaccine I used the Multi-output classification model. This allows our models to accomodate more than two possible probability values.

[Logistic Regression](https://github.com/mensah50/General-Assembly-Data-Science-Immersive/blob/master/Logistic%20Regression%20-%20Flu%20Capstone.ipynb)

[Random Forests](https://github.com/mensah50/General-Assembly-Data-Science-Immersive/blob/master/Model-2_RandomF.ipynb)

[Decision Trees](https://github.com/mensah50/General-Assembly-Data-Science-Immersive/blob/master/Flu%20Capstone%20-%20Decision%20Trees.ipynb)

[Presentation](https://github.com/mensah50/General-Assembly-Data-Science-Immersive/blob/master/Flu_vaccine.pptx)

## Findings and Overview

The best results were achieved with the Random Forest model with a ROC AUC score of 0.85. When looking at the important features, it was apparent that the respondents' opinion of the risk of the seasonal flu vaccine and its effectiveness, whether their doctor had recommended the vaccines, and whether they had health insurance were critical influencers in determining the probability of them having the vaccines or not.
