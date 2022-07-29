# Heart-disease-classification

This project looks into using various python-based machine learning libraries in an attempt to building a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

## 1. Problem Definiftion

Given clinical parameters about a patient, can we predict whether or not they have heart disease?

## 2. Data

The original data came from the Cleavland data from the UCI machine learning repository.
https://archive.ics.uci.edu/ml/datasets/heart+disease

There is also version of it available on kaggle https://www.kaggle.com/ronitf/heart-disease-uci

## 3. Evaluation

> If we can reach 95% accuracy at predicting whether or not a patient has a heart disease during the proof of concept, we will pursue the project.

## 4. Features

1. age - age in years
2. sex - (1 : male, 0 : female)
3. cp - chest pain type (4 values)
    - 0: typical angina
    - 1: atypical angina
    - 2: non-anginal pain
    - 3: asymptomatic
4. trestbps - resting blood pressure (in mm Hg on admission to the hospital)
5. chol - serum cholestoral in mg/dl
    - serum = LDL + HDL + 0.2 * triglycerides 
    - above 200 is cause for concern
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
