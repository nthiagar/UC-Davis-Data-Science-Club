# UC Davis Data Science Club Projects and Workshops

## Overview
This repository contains a group project and workshops I co-led for the Davis Data Science Club.

### 1. Credit Card Fraud Project
- **File:** `Credit Card Fraud Project.ipynb`
- **Description:** Using a machine learning model to identify fradulent credit card cases. This project was a collaborative effort with Ru Han Wang.
  - Loads a pickled DataFrame containing transaction data and prepares it for analysis.
  - Handles missing values by replacing them with the mean of each respective column to ensure data completeness.
  - Plots categorical feature distributions such as 'DeviceType' to understand their distribution across fraudulent and non-fraudulent transactions.
  - Uses a Decision Tree classifier to predict fraud based on transaction attributes.
  - Computes and displays key performance metrics such as accuracy, AUC score, confusion matrix, and classification report to assess model effectiveness.
  - Visualizes the ROC curve and Precision-Recall curve to illustrate the classifier's performance in distinguishing between fraud and non-fraud transactions.
- **File:** `Credit Card Fraud Presentation.pptx`
- **Description:** Presentation that I gave to the club to explain my findings
  - Went over visualizations to explain data
  - Feature engineering and frequency encoding explanation fro decision tree
  - model accuracy and results inlduing hyperparameter improvements

### 2. Titanic Competition
- **File:** `Titanic ML Submission.ipynb`
- **Description:** Predicts survival on the Titanic using machine learning models.
  - Handles missing data in 'Age', 'Fare', and 'Embarked'.
  - Applies one-hot encoding to categorical features.
  - Trains RandomForest, XGBoost, KNeighbors, and GradientBoosting classifiers, stacking predictions with XGBoost for final submission.

### 3. Predict Future Sales Competition
- **File:** `Predict Future Sales Submission 1.ipynb`
- **Description:** Predicts total sales for the next month using machine learning.
  - Prepares data by dropping unnecessary columns and training a RandomForestRegressor model.
  - Generates predictions and saves results to submission.csv.

- **File:** `Predict Future Sales Submission 2.ipynb`
- **Description:** Collaborative effort with Ajay Kumaar.
  - Cleans data by handling missing values, extracting date-related features, and encoding categorical variables.
  - Trains multiple classifiers (RandomForestClassifier, XGBClassifier, KNeighborsClassifier, SVC) and uses stacking for final predictions.

## Data Sources
- [Daily Temperature of Major Cities](https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities)
- [Titanic Data](https://www.kaggle.com/competitions/titanic/data)
- [Predict Future Sales Data](https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales/data)

## Collaboration
- The `Predict Future Sales Submission 2.ipynb` notebook was a collaboration with Ajay Kumaar.

## Usage
To explore these projects:
- Load respective data on Kaggle.
- Run the notebooks to reproduce the analyses and results.
