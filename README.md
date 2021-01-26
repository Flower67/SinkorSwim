# Sink or Swim

## Overview 

Our group initially wanted to do a project that took sentiment scores from news stories about the election to see if this information could be used to predict stock market performance. However, we ran into challenges pulling a prolonged history of news stories for free with various APIs and being able to incorporate this into a ML model.  We ultimately changed our project to use data on Titanic passengers to predict the passengers' likelihood of survival.  We decided to run multiple ML models and compare the results of several models to determine the most effective and accurate model. The data was sourced from Kaggle as a part of their Titanic ML competition and was separated into two datasets--a training and a testing csv. Both datasets had the same features--survival, pclass, sex, age, number of siblings & spouses, number of parents & children, ticket number, fare price, cabin number, and lastly, port of embarkation--with survival being excluded from the testing dataset. We opted to only use survival, pclass, sex, age, number of siblings & spouses, number of parents & children, fare price, and port of embarkation for our analysis. We elected to use the training dataset to build our models with the goal of predicting survival in the testing dataset. The Neural Network model with multiple layers proved to be the most effective model in predicting survival. 


## Data Analysis 


## Models used and Conclusion 


### Dependencies 

To run our code, you will need to install the following packages not previously used in class: 

Yellowbrick: pip install yellowbrick 
