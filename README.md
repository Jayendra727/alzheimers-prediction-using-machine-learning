# alzheimers-prediction-using-machine-learning
Masters project

Alzheimer's Disease Prediction Using Machine Learning
Project Overview
This project implements a comprehensive machine learning approach to predict Alzheimer's Disease using clinical, demographic, and lifestyle data. The implementation follows the methodology outlined in the project design document, focusing on feature engineering, recursive feature elimination, and class balancing to achieve optimal predictive performance.
Dataset
The dataset (alzheimers_prediction_dataset.csv) includes 74,283 records with 25 features, covering:

Demographic factors (age, gender, education level)
Clinical measurements (BMI, cognitive test scores)
Comorbid conditions (diabetes, hypertension)
Lifestyle factors (physical activity, smoking, alcohol consumption)
Genetic information (APOE-ε4 allele status)

Implementation Steps
1. Data Loading and Initial Inspection

Loaded the dataset from CSV file
Examined the first 5 rows to understand data structure
Identified column types and data characteristics

2. Data Cleansing

Identified and handled missing values
Detected and removed duplicate records
Ensured data integrity for downstream analysis

3. Statistical Summary

Generated descriptive statistics for all numerical features
Analyzed the distribution of key variables

4. Exploratory Data Analysis (EDA)

Created visualizations to understand data distributions and relationships:

Age distribution histogram
Cognitive test score distribution
Correlation heatmap of numerical features
Comparative boxplots for key variables
Distribution analysis by Alzheimer's diagnosis status



5. Feature Engineering and Balancing

Preprocessed categorical and numerical features
Created interaction terms between important variables
Implemented Recursive Feature Elimination (RFE) to identify optimal feature subset
Applied SMOTE to balance the class distribution

Current Status
The preprocessing, exploratory analysis, and feature engineering phases have been completed. The dataset is now ready for model training and evaluation.
Next Steps

Implement multiple machine learning models (Random Forest, Gradient Boosting, Logistic Regression)
Perform hyperparameter tuning using GridSearchCV
Create an ensemble model to improve prediction accuracy
Evaluate models using precision, recall, F1-score, and ROC-AUC metrics
Analyze feature importance and develop clinical interpretations

Dependencies

Python 3.9+
pandas
numpy
scikit-learn
imbalanced-learn
matplotlib
seaborn

Author
Jayendra
[University of Herfordshire ]
[Date: 30 jun 2025]--Last Updated
