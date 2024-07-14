# Exploratory Analysis and Training Different Models on Titanic Data

## Overview
This project aims to explore and analyze the Titanic dataset and apply various machine learning models to predict the survival of passengers. The analysis includes data cleaning, feature engineering, and model training using Logistic Regression, SVM, and Decision Tree algorithms. The project also involves creating and saving pipelines for the Decision Tree and Logistic Regression models. The accuracy achieved is not great beacause the dataset is better suited for classification models, but this implementation is solely for demonstration of usage of regression models and creating and saving pipelines.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Training](#model-training)
- [Pipelines](#pipelines)
- [Results](#results)
- [Contributing](#contributing)


## Dataset
The dataset used for this project is the Titanic dataset, which can be downloaded from Kaggle. It contains information about the passengers on the Titanic, including whether they survived or not.

## Installation
To run this project locally, follow these steps:

Clone the repository:
```bash
git clone https://github.com/Ich-Asadullah/Exploratory_Analysis_and_Training_different_models_on_Titanic_data
```
Navigate to the project directory:
```bash
cd Exploratory_Analysis_and_Training_different_models_on_Titanic_data
```
Install the required packages:
```bash
pip install sklearn pandas seaborn matplotlib
```
## Usage
- Open the Jupyter Notebook
- Run the notebook cells to perform EDA and train the models.
  
## Exploratory Data Analysis
The EDA section includes:

- Data Cleaning: Handling missing values and outliers.
- Feature Engineering: Creating new features from existing ones.
- Data Visualization: Visualizing the distribution of features and their relationships with the target variable.
  
## Model Training
The following models are trained and evaluated in the notebook:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree

## Pipelines
Pipelines for the `Decision Tree` and `Logistic Regression` models have been created and saved to ensure smooth model training and evaluation. These pipelines include all the necessary preprocessing steps and the model itself.

## Results
The performance of each model is evaluated using appropriate metrics. The results are compared to determine the best-performing model for this dataset.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
