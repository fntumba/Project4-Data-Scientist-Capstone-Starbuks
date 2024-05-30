# Project4-Data-Scientist-Capstone-Starbuks

This repository has all the code and report for my Data Scientist Capstone project.

## Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Starbucks Capstone Challenge: Using Starbucks app user data to predict effective offers

### 1. Installations <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.
However, the relevant Python packages for this project are as follows:

- pandas
- numpy
- math
- json
- sklearn.model_selection (train_test_split module)
- sklearn.preprocessing (StandardScaler, PolynomialFeatures)
- from sklearn.tree (DecisionTreeClassifier,DecisionTreeRegressor)
- sklearn.ensemble (RandomForestClassifier)
- sklearn.metrics (mean_squared_error,classification_report)
- sklearn.linear_model (Ridge)
- time
- sklearn.model_selection (GridSearchCV)
- matplotlib

### 2. Project Motivation <a name="motivation"></a>

This project is the Capstone project of my Data Scientist nanodegree with Udacity. As students in the nanodegree, we have the option to take part in the Starbucks Capstone Challenge.
For the challenge, Udacity provided simulated data that mimics customer behavior on the Starbucks rewards mobile app.

Because this is a capstone project, we are free to analyze the data any way we see fit. For example, build a machine learning model that predicts how much someone will spend based on demographics and offer type. Or we could build a model that predicts whether or not someone will respond to an offer. 

In this project, we use the data to answer 2 business questions:

    A) What are the main drivers of an effective offer on the Starbucks app?
  
    B) Could the data provided, namely offer characteristics and user demographics, predict whether a user would take up an offer?

 

### 3. File Descriptions  <a name="files"></a>

This repo contains 8 files. The report of my project is called 'Starbucks_Capstone_new_francis.ipynb'. 
The data used in the project is in the files portfolio.json, profile.json and transcript.json (however you need to unzip the file transcript.zip), the remaining files are my report in HTML format and the 2 picture files used by the report.

### 4. Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@franciskongolo2002/starbucks-offers-exploration-b72692961b55)


### 5. Licensing, Authors, Acknowledgements, etc.  <a name="licensing"></a>

Data for coding project was provided by Udacity.
