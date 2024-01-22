# Diabetes Prediction using Random Forest Classifier

## Overview

This project aims to predict diabetes outcomes using a Random Forest Classifier. The dataset, 'diabetes.csv,' is analyzed through exploratory data analysis (EDA) and then used to train a Random Forest model for predicting diabetes outcomes.

## Dataset

The dataset, 'diabetes.csv,' contains various features related to diabetes, including 'Pregnancies,' 'Glucose,' 'BloodPressure,' 'SkinThickness,' 'Insulin,' 'BMI,' 'DiabetesPedigreeFunction,' 'Age,' and the target variable 'Outcome.'

## Exploratory Data Analysis (EDA)

Descriptive statistics and boxplots are used to gain insights into the dataset. Boxplots are plotted for numerical features grouped by the 'Outcome' variable, providing a visual representation of feature distributions.

## Model Building

1. **Data Preprocessing:**
   - Standardization of features using `StandardScaler`.
   - Splitting the dataset into training and testing sets.

2. **Random Forest Classifier:**
   - Building a Random Forest Classifier with 100 estimators.
   - Training the model on the scaled training data.

3. **Model Evaluation:**
   - Making predictions on the test set.
   - Evaluating model accuracy using `accuracy_score`.
   - Displaying the confusion matrix for further insights.

## Instructions

To run the code locally, follow these steps:

1. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Run the main script:

    ```bash
    python diabetes_prediction.py
    ```

## Dependencies

- pandas
- matplotlib
- scikit-learn

## Results

The model's accuracy on the test set is displayed along with the confusion matrix, providing information on true positives, true negatives, false positives, and false negatives.

## Acknowledgments

- The project acknowledges the importance of exploring and understanding the dataset through EDA.
- The Random Forest Classifier is employed for predicting diabetes outcomes.
- The project uses standard machine learning libraries for model building and evaluation.
