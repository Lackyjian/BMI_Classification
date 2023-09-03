# BMI_Classification

![BMI](https://images.app.goo.gl/dVBXn3FHNLZ3h5USA)

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
The BMI Classification project is focused on predicting Body Mass Index (BMI) categories using machine learning models. BMI is an important health indicator, and accurate classification can provide valuable insights into an individual's health. This project uses machine learning to classify individuals into BMI categories based on their height and weight.

## Dataset
The dataset used in this project was obtained from Kaggle and can be found at [BMI Dataset](https://www.kaggle.com/datasets/sjagkoo7/bmi-body-mass-index). It contains features like height and weight, along with the corresponding BMI categories. The goal is to predict these BMI categories using machine learning models.

## Models
We have trained several machine learning models to classify BMI categories. The following models were used:
- CatBoost Classifier
- k-Nearest Neighbor (k-NN) Classifier
- Random Forest Classifier
- Support Vector Classifier (SVC)
- XGBoost Classifier

Each of these models was trained on the dataset to predict the BMI category. After training, the model with the best accuracy, which was the XGBoost Classifier, was selected for making the final predictions.

## Usage
To use this project, follow these steps:
1. Clone this repository to your local machine.
2. Download the dataset from [BMI Dataset](https://www.kaggle.com/datasets/sjagkoo7/bmi-body-mass-index) and place it in the project directory.
3. Install the required Python libraries listed in the `requirements.txt` file.
4. Run the Jupyter notebook or Python script provided to train the models and make predictions.

## Results
The final accuracy achieved by this project is an impressive 99.15%. The high accuracy demonstrates the effectiveness of machine learning in classifying BMI categories. The XGBoost Classifier was chosen as the final model due to its superior performance.

## Contributing
Contributions to this project are welcome. If you have ideas for improving the models, optimizing the code, or adding new features, please feel free to submit a pull request.
