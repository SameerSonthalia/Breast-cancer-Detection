# Project Overview:
* This project implements a breast cancer detection system using machine learning, specifically a Decision Tree classifier. The goal is to classify whether a tumor is malignant or benign based on features derived from breast cancer cell data.
  
# Dataset
* The dataset used in this project contains measurements of various features extracted from breast cancer cell images. The features include attributes like radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension, which are used to classify the tumor type.
  
#Libraries Used:
* pandas: For data manipulation and handling the dataset.
* matplotlib & seaborn: For data visualization (optional).
* sklearn: For building and evaluating the Decision Tree classifier.

# Steps Involved:
* Data Loading: The dataset is loaded using pandas' read_csv() function.
* Feature Selection: The target variable (diagnosis) is separated from the feature columns, which are used to train the model.
* Data Splitting: The dataset is split into training and testing sets using train_test_split() from sklearn.model_selection.
* Model Training: A DecisionTreeClassifier is created and trained on the training data (x_train and y_train).
* Model Evaluation: The model's performance is evaluated by calculating its accuracy on both the training and testing datasets using score()
