# Module5-Project
## Introduction:
This project aims to analyze the Titanic data set by applying Machine Learning Model. Training and testing model to predict the survival rate of passengers based on the given criteria that is Age, Sex and Class.
We will apply basic concept of cleaning and preprocessing and train and test the model and with visualization narrate our data story. The data set containing information for 891 passengers. 

# https://www.kaggle.com/datasets/zain280/titanic-data-set

# Primary Objective:
The main idea is to apply a machine learning model to predict how many passengers survived based on Age Sex and Class. We are trying to predict if a passenger survived(1) or didn’t survive(0). This can lead us to understand how this disaster affected the survival rate.

# Steps:
After cleaning raw data we encoded the categorical features and scaled the numerical values to get the preprocess data to train the model. This process helps to remove unnecessary value and let us focus on more relevant data to get better results.
## Data Cleaning & Preprocessing:
Dropped Columns:
Name, PassengerId, Ticket, Cabin
All these columns were dropped to avoid unique values and making data too complex for models. 
Handling Missing Values:
Embarked: We applied handle_known=’ignore’ 
Age & Fare: We applied median values to avoid missing values.
Feature Encoding:
Feature Sex is converted to binary (0 or 1)

## Model Training & Testing:
We choseLogistic Regression Model to train and predict. This is a better model as the target is binary (Survived or not Survived) . This model is also useful for its effectiveness and interpretability for target variable. 

## Visualizations:

Barcharts and pie charts are visually showing that age, gender and class impacted the survial rate.
# Results:

The Logistic Model predicted survival rate with almost 73% accuracy. Based on the features the survival rate among women was higher than men. Passengers in the first class also had a better chance to survive than people who were class 2 and 3. The price of the ticket also impacted the survival rate. Age and location of boarding the ship had less effect on the survival but they were the considerable factors. 




