# Titanic Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques.

## Overview

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, resulting in the deaths of a large number of passengers and crew. In this project, we attempt to analyze the passenger data and predict whether a passenger survived or not.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/c/titanic/data) and contains two CSV files: `train.csv` and `test.csv`. The `train.csv` file is used for training the machine learning model, while the `test.csv` file is used for predictions.

## Features

The dataset includes the following features:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Whether the passenger survived (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1st, 2nd, or 3rd)
- **Name**: Passenger's name
- **Sex**: Passenger's sex (male or female)
- **Age**: Passenger's age
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Methodology

1. **Data Visualization**: Exploratory data analysis was conducted using various visualizations like pie charts and histograms to understand the distribution of survivors, genders, etc.
2. **Feature Engineering**: Features were modified, created, and dropped to enhance the predictive power of the model. This includes handling missing values, converting categorical data to numerical, and creating new features.
3. **Model Training**: A Random Forest Classifier was trained using the processed data to predict the survival of passengers.
4. **Prediction**: The trained model was used to predict survival on the test dataset, and the results were saved in a CSV file.

## Results

The trained model achieved an accuracy score of 83.24% on the validation set.

## Files

- `train.csv`: Training dataset
- `test.csv`: Testing dataset
- `resultfile.csv`: CSV file containing predicted survival for passengers in the test dataset

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/titanic-survival-prediction.git
