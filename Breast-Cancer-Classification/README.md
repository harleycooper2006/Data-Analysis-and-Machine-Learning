# Breast Cancer Classification

## Overview
This project uses machine learning to classify breast tumours as **benign or malignant** using the Wisconsin Breast Cancer dataset. It explores how cell-nuclei measurements can be used to predict tumour diagnosis.

## What the Notebook Does
- **Data preparation:** Loads the dataset using Pandas, encodes diagnosis labels and removes unnecessary columns.
- **Exploratory data analysis:** Examines the dataset, checks for missing values and visualises the distribution of diagnoses.
- **Data splitting:** Separates the data into training, validation and testing sets while maintaining class proportions.
- **Baseline model:** Uses Scikit-learn's `DummyClassifier` to establish a benchmark.
- **Machine learning:** Builds a Logistic Regression model using `StandardScaler` to standardise the input features.
- **Model evaluation:** Compares accuracy and recall and uses confusion matrices to examine classification errors.
- **Final testing:** Evaluates the trained model on a separate test set.

## Technologies
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## How to Run
Open the notebook in Google Colab and run the cells in order. The dataset must be available at the Google Drive path specified in the notebook, or the path must be updated to match your own dataset location.

## Skills Demonstrated
Data cleaning, exploratory data analysis, data preprocessing, supervised machine learning, classification and model evaluation.

*This project was completed as part of my Computer Science studies.*
