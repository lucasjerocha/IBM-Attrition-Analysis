# The IBM Attrition Dataset

## Overview

Welcome to the "The IBM Attrition Dataset" repository. This repository focuses on analyzing and predicting personnel attrition using the IBM attrition dataset. The dataset, sourced from the IBM Watson Analytics Lab, consists of fictional data created by IBM data scientists, comprising 1470 rows.

## Purpose

The primary objective of this project is to predict the binary `attrition` target variable using various machine learning models. The repository includes steps for data cleaning, preprocessing, model selection, and evaluation to achieve this goal.

## Contents

- **Data Cleaning and Preprocessing**: Initial steps involve cleaning the dataset and preparing it for modeling. This includes adjusting the target variable `attrition` and exploring its distribution.
  
- **Model Selection**: Two main models are considered for predicting attrition: logistic regression and random forest. These models are chosen based on their suitability for classification tasks and their ability to handle imbalanced datasets.
  
- **Cross Validation and Evaluation**: The models are evaluated using cross-validation with five folds to ensure robust performance metrics such as accuracy, sensitivity, and specificity.
  
- **Best Model Selection**: The best-performing model is selected based on its ability to effectively identify positive cases of attrition. This model is then trained on the entire dataset and evaluated on a test set to assess its predictive performance.

## Repository Structure

- **Data Cleaning Scripts**: Includes R scripts for data cleaning and preprocessing steps.
  
- **Modeling Scripts**: Contains R scripts for model selection, evaluation, and cross-validation.
  
- **Documentation**: Additional documentation and README files for detailed instructions and explanations.

## Usage

To explore or replicate the analysis:

1. Clone or download the repository to your local machine.
  
2. Navigate through the folders to access the scripts and documentation.
  
3. Execute the scripts in your preferred environment to analyze and predict personnel attrition using the IBM attrition dataset.

## Contributors

- Lucas Rocha
  
## Acknowledgments

This project draws inspiration and methodology from business analytics and machine learning courses, focusing on real-world applications of predictive modeling in HR analytics.
