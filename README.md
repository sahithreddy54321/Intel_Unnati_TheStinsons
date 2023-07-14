# SMART MOBILE PRICE PREDICTION USING MACHINE LEARNING

## Team Name - Intel_Unnati_TheStinsons
Additionally, for easy access to the project, you can also click [here](https://drive.google.com/drive/folders/1V1no_ysIv5EP1tIwCRM_U3MnXE6JJB_e?usp=sharing) in case you encounter any difficulties accessing the code.

This project is a Smart Phone Price Prediction System that utilizes machine learning algorithms, specifically Support Vector Machines (SVM) and Random Forest, to predict the prices of smartphones based on various features.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Algorithms](#algorithms)
- [Contact](#contact)


## Introduction

The Smart Phone Price Prediction System is designed to predict the prices of smartphones using machine learning algorithms. It takes into account various features such as brand, RAM, internal memory, processor, camera specifications, battery capacity, Android version, user interface, display type, resolution, thickness, weight, display size, refresh rate, and more to make accurate price predictions. By utilizing the power of SVM and Random Forest algorithms, this system aims to provide reliable price estimates for smartphones.

## Features

The Smart Phone Price Prediction System offers the following features:

- Data preprocessing: The system performs data preprocessing tasks, including handling missing values, feature encoding, and feature scaling, to prepare the data for model training.
- Feature selection: Chi-squared (chi2) feature selection technique is applied to extract the top 10 most important features from the dataset.
- Model training: SVM and Random Forest algorithms are used to train the prediction models based on the selected features.
- Price prediction: Once the models are trained, the system can accept input for smartphone features and generate price predictions.

## Installation

To run this project locally, please follow these steps:

1. Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/sahithreddy54321/Intel_Unnati_TheStinsons

2. Navigate to the project directory:
   ```bash
   cd smart_phone_price_prediction
3. Install the required dependencies using pip and the requirements.txt file:
   ```bash
   pip install -r requirements.txt
This will install the necessary packages and libraries needed to run the project.

## Usage
To use the Smart Phone Price Prediction System, follow these steps:

1. Ensure that you have completed the installation steps mentioned above.

2. Use the provided dataset for training the models. The dataset should include the following features: brand, RAM, internal memory, processor, back camera, front camera, battery, Android version, user interface, display type, resolution, thickness, weight, display size, refresh rate, and price.

3. Run the notebook to preprocess the data, including handling missing values, encoding categorical features, and scaling numerical features.

4. Apply the chi2 feature selection technique to extract the top 10 most important features from the preprocessed dataset.

5. Run the notebook to train the SVM and Random Forest models using the selected features.

6. Once the models are trained, you can use the provided functions to input smartphone features and generate price predictions.

## Algorithms

[Random Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html): Random Forest is a popular machine learning algorithm that belongs to the supervised learning technique. It can be used for both Classification and Regression problems in ML. It is based on the concept of ensemble learning, which is a process of combining multiple classifiers to solve a complex problem and to improve the performance of the model.

As the name suggests, "Random Forest is a classifier that contains a number of decision trees on various subsets of the given dataset and takes the average to improve the predictive accuracy of that dataset." Instead of relying on one decision tree, the random forest takes the prediction from each tree and based on the majority votes of predictions, and it predicts the final output.

The greater number of trees in the forest leads to higher accuracy and prevents the problem of overfitting.

[Support Vector Machines (SVM)](https://scikit-learn.org/stable/modules/svm.html): Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data point in the correct category in the future. This best decision boundary is called a hyperplane.

SVM chooses the extreme points/vectors that help in creating the hyperplane. These extreme cases are called as support vectors, and hence algorithm is termed as Support Vector Machine.

These algorithms are trained on the preprocessed dataset to learn the relationships between smartphone features and prices, enabling accurate price predictions.

## Contact

| Name  | Email id |
| ------------- | ------------- |
| Vellenki Sahith Reddy  | sahithreddy54321@gmail.com  |
| Vanguri Ghan Shyam Ruthik Rajan  | ghanshyamruthikrajan@gmail.com  |
