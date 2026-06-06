# heart-disease-project

# Heart Disease Prediction Using Machine Learning

## Overview

This project aims to predict the presence of heart disease using machine learning techniques. The dataset contains clinical and medical information about patients, and several classification models were trained and compared to identify the most effective approach.


## Objectives

* Perform data cleaning and preprocessing.
* Explore and analyze the dataset.
* Train multiple machine learning models.
* Compare model performance.
* Identify the most suitable model for heart disease prediction.


## Dataset

The dataset contains 297 patient records and 14 medical features, including:

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG Results (restecg)
* Maximum Heart Rate (thalach)
* Exercise-Induced Angina (exang)
* ST Depression (oldpeak)
* Slope
* Number of Major Vessels (ca)
* Thalassemia (thal)
* Condition (Target Variable)

Target:

* 0 = No Heart Disease
* 1 = Heart Disease


## Data Preprocessing

The following preprocessing steps were performed:

* Missing value check
* Duplicate record check
* Data type verification
* One-hot encoding of categorical features
* Feature scaling for KNN and Logistic Regression
* Outlier analysis using boxplots


## Machine Learning Models

Three classification models were implemented:

1. Decision Tree Classifier
2. K-Nearest Neighbors (KNN)
3. Logistic Regression


## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Decision Tree       | 64%      |
| KNN                 | 80%      |
| Logistic Regression | 84%      |

Logistic Regression achieved the highest accuracy and was selected as the best-performing model for this dataset.


## Key Findings

* Medical variables such as cholesterol, maximum heart rate, and ST depression are important predictors of heart disease.
* Feature scaling significantly improved KNN performance.
* Logistic Regression provided the most reliable results among the tested models.


## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Google Colab


## Project Files

* `NoteBook.ipynb` – Jupyter/Colab notebook
* `Report.pdf` – Project report
* `heart_cleveland_upload.csv` – Dataset


## Future Improvements

* Additional feature engineering
* Testing advanced ensemble models
* Training on larger medical datasets


## Author

Mariam El Sayed

Data Science Student
