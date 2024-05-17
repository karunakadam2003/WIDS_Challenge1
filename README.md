# WIDS_Challenge1
WiDS Datathon 2024 Challenge #1 Equity in Healthcare


# WiDS Datathon 2024

## Overview

The WiDS Datathon 2024 focuses on a prediction task using a dataset of approximately 18,000 records (split into training and test sets). The dataset represents patients and their characteristics, including:

- **Patient Characteristics**: age, race, BMI, zip code.
- **Diagnosis and Treatment Information**: breast cancer diagnosis code, metastatic cancer diagnosis code, metastatic cancer treatments, etc.
- **Geo Demographic Data (at zip-code level)**: income, education, rent, race, poverty, etc.
- **Toxic Air Quality Data**: Ozone, PM2.5, and NO2 levels.

Each row in the dataset corresponds to a single patient and her Diagnosis Period. The task is to predict whether the likelihood of the patient’s Diagnosis Period being less than 90 days is predictable using these characteristics and information.

## Task

The primary objective is to assess whether it is possible to predict if a patient’s Diagnosis Period is less than 90 days using the provided dataset. The dataset includes a variety of features related to the patients' personal characteristics, medical diagnosis, treatment information, and environmental conditions.

## Datasets

You are provided with two datasets:

1. **Training Dataset (`train.csv`)**: This dataset includes the observed values of the outcome (Diagnosis Period being less than 90 days) for each row. You will use this dataset to train your predictive models.
2. **Test Dataset (`test.csv`)**: This dataset withholds the observed values of the outcome for each row. You will use this dataset to test the performance of your predictive models.

## Data Structure

The datasets include the following types of information:

- **Patient Characteristics**:
  - Age
  - Race
  - BMI
  - Zip code

- **Diagnosis and Treatment Information**:
  - Breast cancer diagnosis code
  - Metastatic cancer diagnosis code
  - Metastatic cancer treatments
  - Other relevant diagnosis and treatment details

- **Geo Demographic Data** (at zip-code level):
  - Income
  - Education level
  - Rent
  - Race distribution
  - Poverty levels

- **Toxic Air Quality Data**:
  - Ozone levels
  - PM2.5 levels
  - NO2 levels

## Goal

Your goal is to develop a predictive model that can accurately determine whether the Diagnosis Period for a patient is less than 90 days based on the given characteristics and information.

## Submission

Submit your predictions for the test dataset. Ensure that your model is well-documented and reproducible, with clear instructions on how to run the model and generate the predictions.

## Getting Started

1. **Download the Datasets**:
   - `train.csv`: Contains the training data with observed outcomes.
   - `test.csv`: Contains the test data without observed outcomes.

2. **Explore the Data**:
   - Understand the features and their distributions.
   - Check for missing values and data inconsistencies.

3. **Preprocess the Data**:
   - Handle missing values.
   - Encode categorical variables.
   - Scale/normalize numerical features if necessary.

4. **Develop Your Model**:
   - Experiment with different machine learning algorithms.
   - Tune hyperparameters for optimal performance.
   - Evaluate model performance using appropriate metrics.

5. **Make Predictions**:
   - Use the trained model to make predictions on the test dataset.
   - Ensure predictions are in the required format for submission.

6. **Document Your Work**:
   - Provide clear documentation on data preprocessing, model training, and prediction generation.
   - Include any assumptions or decisions made during the process.

## Evaluation

Models will be evaluated based on their accuracy in predicting whether the Diagnosis Period is less than 90 days. Further details on evaluation metrics and scoring will be provided.


---

Good luck and happy coding!
