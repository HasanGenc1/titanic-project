# Titanic Survival Analysis and Prediction

## Overview
This project presents an end-to-end data science workflow on the Titanic dataset using Python. The project includes data cleaning, feature engineering, exploratory data analysis (EDA), and machine learning modeling to predict passenger survival.
The goal is to understand the factors that influenced survival outcomes and build a predictive model using engineered features and statistical insights.

## Objectives
- Analyze survival patterns among Titanic passengers
- Handle and investigate missing values
- Perform feature engineering to improve predictive performance
- Explore relationships between passenger characteristics and survival
- Build and evaluate a machine learning classification model
- Identify the most important factors affecting survival

## Dataset
The dataset used in this project is the Titanic dataset from Kaggle.

It includes:
- Passenger demographics
- Ticket and fare information
- Cabin and embarkation details
- Family-related variables
- Survival outcomes

## Project Workflow
1. Importing Libraries
2. Loading the Dataset
3. Initial Data Exploration
4. Data Cleaning
5. Feature Engineering
6. Exploratory Data Analysis
7. Machine Learning

## Feature Engineering
The following new features were created:

- **Deck**: Extracted from the Cabin column
- **Title**: Extracted from passenger names
- **Title_Grouped**: Rare titles were grouped together
- **Age_Group**: Passengers were grouped by age categories
- **FamilySize**: Created using `SibSp + Parch + 1`
- **IsAlone**: Created to indicate whether a passenger traveled alone

## Exploratory Data Analysis
The analysis explored survival rates based on:

- Gender
- Passenger class
- Age group
- Fare
- Deck
- Title
- Family size
- IsAlone status
- Correlations between numerical variables

## Key Findings
- Female passengers had significantly higher survival rates than male passengers.
- First-class passengers had the highest survival probability.
- Passenger titles provided valuable information about social status and survival patterns.
- Higher fare values were generally associated with increased survival chances.
- Family-related features improved the understanding of passenger survival behavior.
- Traveling alone was associated with lower survival probability.
- Feature engineering contributed to improving model performance.
- The machine learning model successfully captured important survival patterns in the dataset.

## Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Results

- The CatBoost model was evaluated using classification metrics and 5-fold cross-validation, demonstrating the effectiveness of feature engineering, data preprocessing, and gradient boosting for predicting passenger survival.
