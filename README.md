# Diabetes Prediction Project

## Overview

This project aims to build a machine learning model to predict diabetes in patients based on their medical history and demographic information using the Diabetes Prediction Dataset from Kaggle.

## Dataset

The dataset used in this project is the **Diabetes Prediction Dataset** available on Kaggle. 

**Dataset Source:**
https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset


**About the Dataset:**

The Diabetes prediction dataset is a collection of medical and demographic data from patients, along with their diabetes status (positive or negative). The data includes features such as:

*   Age
*   Gender
*   Body Mass Index (BMI)
*   Hypertension
*   Heart Disease
*   Smoking History
*   HbA1c Level
*   Blood Glucose Level

This dataset is valuable for building machine learning models to predict diabetes and can be useful for healthcare professionals and researchers.

## Project Steps

1.  **Data Loading and Preprocessing:** The dataset is loaded using Pandas, and data cleaning steps are performed, including handling missing values, converting categorical features, and removing duplicates.

2.  **Exploratory Data Analysis:** Data visualization techniques are used to understand the relationships between variables and gain insights into the dataset's characteristics.


3.  **Model Selection and Training:** Suitable machine learning models, such as K-Nearest Neighbors (KNN), are selected and trained on the preprocessed data.

4.  **Model Evaluation:** The trained model is evaluated using appropriate metrics, such as accuracy and confusion matrix, to assess its performance.

5.  **Hyperparameter Tuning:** Model parameters are optimized to achieve the best possible results.

6.  **Prediction and Interpretation:** The model is used to predict diabetes risk on new data, and the results are interpreted to provide insights for healthcare decision-making.


## Code

The project code is written in Python and utilizes libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn. The code is organized into Jupyter Notebooks for easy execution and reproducibility.

## Results

The project achieved an `accuracy of 94.74%` in predicting diabetes using the K-Nearest Neighbors model with `k = 13`.

## Conclusion

This project demonstrates the potential of machine learning in diabetes prediction. The developed model can assist healthcare professionals in identifying individuals at risk and enabling early interventions. Further research and model refinement can lead to even more accurate and reliable predictions.
