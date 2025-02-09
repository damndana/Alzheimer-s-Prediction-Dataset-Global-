Alzheimer's Prediction Dataset (Global)

Project Overview
This project provides a full analysis of the Alzheimer’s Prediction Dataset (Global), including data cleaning, visualization, and machine learning modeling. The goal is to analyze different factors influencing Alzheimer’s and predict diagnoses using machine learning.

Dataset
The dataset contains various attributes such as:
Demographics (Age, Gender, Education Level, Income, Marital Status)
Health Factors (BMI, Hypertension, Diabetes, Cholesterol Level, Depression Level, Sleep Quality)
Lifestyle (Physical Activity Level, Smoking Status, Alcohol Consumption, Dietary Habits, Social Engagement)
Environmental Factors (Urban vs. Rural Living, Air Pollution Exposure)
Genetics (Family History, APOE-ε4 allele)
Cognitive Test Scores
Alzheimer’s Diagnosis (Target Variable: Yes/No)

Libraries Used
The analysis was conducted using the following Python libraries:
pandas – Data manipulation and preprocessing
numpy – Numerical computations
matplotlib & seaborn – Data visualization
scikit-learn – Machine learning modeling
mplfinance – Financial-style data visualization
LabelEncoder & StandardScaler – Encoding categorical variables and scaling features
Key Steps in Analysis

Data Preprocessing:
Handled missing values
Encoded categorical features
Scaled numerical features
Exploratory Data Analysis (EDA):
Visualized distributions of key features
Identified trends in cognitive test scores
Analyzed correlations with Alzheimer’s diagnosis

Machine Learning Model:
Split data into train-test sets
Applied Label Encoding for categorical features
Scaled numerical data using StandardScaler
Used Random Forest Classifier for prediction
Evaluated performance using accuracy, precision, recall, and confusion matrix

Model Performance
Accuracy: 67%
