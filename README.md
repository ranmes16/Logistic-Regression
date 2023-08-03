# Logistic Regression for Heart Attack Prediction

## Overview

This project demonstrates the use of logistic regression to predict the likelihood of a heart attack based on various features such as age, sex, chest pain type, blood pressure, cholesterol level, etc. The dataset used in this project is "Heart.csv," which contains information about patients and their heart attack occurrences.

## Requirements

- Python 3
- Libraries: NumPy, Pandas, Matplotlib

## Usage

1. Clone the repository:
2. Install the required libraries: NumPy, Pandas, Matplotlib
3. Run the Jupyter Notebook
4. The notebook contains the implementation of logistic regression, data preprocessing, model training, and evaluation.

## Dataset

The dataset "Heart.csv" contains the following columns:

- age: Age of the patient
- sex: Gender (0 = female, 1 = male)
- cp: Chest pain type (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)
- trestbps: Resting blood pressure
- chol: Serum cholesterol level
- fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- restecg: Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy)
- thalach: Maximum heart rate achieved
- exang: Exercise induced angina (1 = yes, 0 = no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: The slope of the peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping)
- ca: Number of major vessels colored by fluoroscopy
- thal: Thallium stress test (0 = normal, 1 = fixed defect, 2 = reversible defect)
- target: Heart attack occurrence (1 = yes, 0 = no)

## Results

The logistic regression model's performance is evaluated using accuracy, precision, recall, and F1-score on a test dataset.
