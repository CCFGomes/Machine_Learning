# Wine Quality Prediction Project

## Project Overview

This project aims to predict the quality of wine based on various physicochemical properties. The dataset used for this analysis contains information about red and white variants of the Portuguese "Vinho Verde" wine. We explore exploratory data analysis (EDA) and machine learning models to determine essential properties affecting wine quality and build predictive models for both quality scores and wine types.

## Table of Contents
- [Project Overview](#project-overview)
- [Data](#data)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Machine Learning Models](#machine-learning-models)
  - [Objective 1: Determine Essential Physicochemical Properties Affecting Wine Quality](#objective-1-determine-essential-physicochemical-properties-affecting-wine-quality)
  - [Objective 2: Build Regression Models for Predicting Wine Quality](#objective-2-build-regression-models-for-predicting-wine-quality)
  - [Objective 3: Build Classification Models for Predicting Wine Type](#objective-3-build-classification-models-for-predicting-wine-type)
  - [Model Comparison](#model-comparison)
- [Conclusion](#conclusion)
  - [Summary of Findings](#summary-of-findings)
  - [Practical Implications](#practical-implications)
  - [Suggested Future Work](#suggested-future-work)
- [How to Run](#how-to-run)
- [Requirements](#requirements)
- [Contact](#contact)

## Data

The dataset used for this project can be found at the UCI Machine Learning Repository: [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

## Exploratory Data Analysis

We performed an in-depth exploratory data analysis (EDA) to understand the distribution and relationships of the data features. Key findings include:

- Red wines generally have higher acidity and lower residual sugar.
- White wines exhibit higher alcohol content and greater sweetness variability.
- Quality distribution varies significantly between red and white wines.

## Machine Learning Models

### Objective 1: Determine Essential Physicochemical Properties Affecting Wine Quality

We trained a Random Forest Classifier to identify the most important features affecting wine quality. The feature importances were visualized to highlight the key properties.

### Objective 2: Build Regression Models for Predicting Wine Quality

We employed Random Forest Regressor and XGBoost Regression to predict the exact quality score of the wine. The models were evaluated using RMSE, and feature importances were analyzed.

### Objective 3: Build Classification Models for Predicting Wine Type

We used Support Vector Machine (SVM) and k-Nearest Neighbors (k-NN) for predicting the type of wine (red or white). The models were evaluated using accuracy, precision, recall, and F1 scores.

### Model Comparison

We compared the models based on their performance metrics and chose the best-performing model for further analysis and practical applications.

## Conclusion

### Summary of Findings

- The key physicochemical properties affecting wine quality are alcohol content, volatile acidity, and sulphates.
- Random Forest models generally perform well for both regression and classification tasks.
- SVM and k-NN models also provide valuable insights for wine type classification.

### Practical Implications

- Winemakers can focus on adjusting specific properties like alcohol and acidity to improve wine quality.
- Quality prediction models can assist in quality control processes, reducing the need for labor-intensive testing.

### Suggested Future Work

- Explore deep learning models for better accuracy.
- Investigate other wine datasets for broader applicability.
- Develop real-time quality prediction tools for use in wineries.

## How to Run

1. Clone the repository:
   
git clone https://github.com/CCFGomes/wine-quality-prediction.git
cd wine-quality-prediction


2. Install the required packages:

pip install -r requirements.txt


3. Run the Jupyter notebook:
 
jupyter notebook wine_quality_prediction.ipynb


For detailed code and implementation, please refer to the respective Jupyter notebooks in this repository.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required packages listed in `requirements.txt`

## Contact

For any questions or suggestions, feel free to contact me:

- GitHub: [CCFGomes](https://github.com/CCFGomes)
