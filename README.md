# Student Dropout Prediction

A machine learning project that predicts student dropout risk using logistic regression based on academic and demographic features.

## Overview

This project analyzes student data to identify patterns that indicate dropout risk, helping educational institutions intervene early and improve student retention rates.

## Features Used

- Age
- Study Time
- Number of Failures
- Number of Absences
- Grade 1, Grade 2, Final Grade

## Model

- **Algorithm**: Logistic Regression
- **Accuracy**: 100% (on test set)
- **Train/Test Split**: 80/20

## Dataset

The dataset (`student_dropout.csv`) contains 34 columns including:
- Demographic information (School, Gender, Age, Address)
- Family background (Family Size, Parental Status, Education, Jobs)
- Academic performance (Grades, Absences, Failures)
- Lifestyle factors (Free Time, Going Out, Alcohol Consumption, Health)
- Target variable: Dropped_Out (Boolean)

## Requirements

```
pandas
matplotlib
seaborn
scikit-learn
```

## Usage

1. Load the dataset
2. Select relevant features
3. Train the logistic regression model
4. Make predictions on new student data
5. Evaluate model performance with confusion matrix and classification report

## Results

The model achieves perfect classification on the test set, accurately identifying both students who stay and those at risk of dropping out.
