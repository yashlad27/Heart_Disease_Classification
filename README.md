# Heart_Disease_Classification

## Predicting heart disease using machine learning:
this notebook looks into using various python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes
we are going to take the following approach:
Problem definition
data
Evaluation
features
modelling
experimentation
--
## 1. Problem Definition:
In a statement,
Given clinical parameters about a patient, can we predict whether or not they have heart disease?
## 2. Data:
Original data came from the Cleveland data from the UCI Machine learning Repo.
There is also a version of it available on Kaggle. https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci
## 3. Evaluation:
If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we will pursue the project.
## 4. Features:
This is where you get different information about each features in our data. create a data dictionary:
age: age in years
sex: sex (1 = male; 0 = female)
cp: chest pain type – Value 0: typical angina – Value 1: atypical angina – Value 2: non-anginal pain – Value 3: asymptomatic
trestbps: resting blood pressure (in mm Hg on admission to the hospital)
chol: serum cholestoral in mg/dl
fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
restecg: resting electrocardiographic results – Value 0: normal – Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) – Value 2: showing probable or definite left ventricular hypertrophy by Estes’ criteria
thalach: maximum heart rate achieved
exang: exercise induced angina (1 = yes; 0 = no)
oldpeak = ST depression induced by exercise relative to rest
slope: the slope of the peak exercise ST segment – Value 0: upsloping – Value 1: flat – Value 2: downsloping
ca: number of major vessels (0-3) colored by flourosopy
thal: 0 = normal; 1 = fixed defect; 2 = reversable defect and the label
condition: 0 = no disease, 1 = disease

--
