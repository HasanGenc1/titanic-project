# Titanic Exploratory Data Analysis

## Overview
This project presents an Exploratory Data Analysis (EDA) of the Titanic dataset using Python. The analysis focuses on understanding how passenger characteristics such as gender, age, passenger class, fare, title, family size, and traveling alone affected survival outcomes.

## Objectives
- Analyze survival patterns among Titanic passengers
- Handle and investigate missing values
- Explore relationships between passenger features and survival
- Create new features for better interpretation
- Visualize survival trends using statistical plots
- Prepare insights for future machine learning modeling

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
- Passenger title provided useful information about survival patterns.
- Higher fare values were generally associated with higher survival rates.
- Children and younger passengers showed different survival patterns compared to adults.
- Passengers traveling with family had different survival outcomes than those traveling alone.
- The **IsAlone** feature showed that traveling alone was associated with lower survival probability.
- Deck information provided useful insight, although many cabin values were missing.

## Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
