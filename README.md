# Rain-in-Australia

In this notebook, we're going to predict whether or not it will rain tomorrow by training a binary classification model on target RainTomorrow.

## Data 

The data we're using is from Kaggle : https://www.kaggle.com/jsphyg/weather-dataset-rattle-package

This dataset `weatherAUS.csv` contains daily weather observations from numerous Australian weather stations.

The target variable RainTomorrow means: Did it rain the next day? Yes or No.


## Content

* `rain_in_australia.ipynb`

This file contains in detail the visualization aspect of the data analysis and building a machine learning project. 

Before modeling, we'll parse all input data.

We're using to models for describing classification problem:
1. LogisticRegression
2. KNeighborsClassifier
3. RandomForestClassifier
4. GaussianNB
