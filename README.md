# Diabetes Prediction

This is a machine learning project aimed at predicting the likelihood of diabetes in patients based on various health metrics. The project uses a Support Vector Machine (SVM) model to analyze patient data and assist in early diagnosis, allowing for timely interventions and better management of diabetes.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Diabetes is a serious health condition affecting millions of people globally. Early detection can significantly improve patient outcomes by enabling better treatment and lifestyle changes. This project leverages machine learning, specifically the Support Vector Machine (SVM) algorithm, to predict the risk of diabetes based on health metrics such as glucose level, blood pressure, BMI, and more.

## Features

- **Diabetes Prediction**: Predicts whether a patient is likely to have diabetes based on input health metrics.
- **Data Preprocessing**: Cleans and prepares medical data, handling missing values and normalizing the data for optimal model performance.
- **Feature Engineering**: Selects relevant health indicators to improve prediction accuracy.
- **SVM Model**: Trains a Support Vector Machine model for reliable binary classification of diabetes risk.

## Data

The dataset used for this project can be found [here](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database), which includes features such as:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (whether the patient has diabetes or not)

### Data Preprocessing Steps

1. **Data Cleaning**: Handle missing values and remove any outliers.
2. **Normalization**: Scale health metrics to ensure consistent model input.
3. **Feature Selection**: Select key features to enhance prediction.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
 https://github.com/nikhilyedelli/DIABETES-PREDICTION/edit/main/README.md

##  Model
The Support Vector Machine (SVM) algorithm is used in this project, which is well-suited for binary classification tasks and can effectively handle datasets with complex feature relationships.

Other models, such as Logistic Regression or Random Forest, may also be explored to compare performance.

## Results
After training, model performance results are saved in the results/ folder. These results include metrics like accuracy, precision, recall, F1 score, and confusion matrix.

## Future Work
- Hyperparameter Tuning: Experiment with different SVM kernels and parameters to further improve accuracy.
- Model Comparison: Compare with other algorithms (e.g., Logistic Regression, Random Forest) for best results.
- Feature Engineering: Test additional features or data sources to enhance model performance.
- Real-time Prediction: Build an API for real-time diabetes risk prediction.
