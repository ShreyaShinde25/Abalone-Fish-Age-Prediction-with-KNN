# Abalone-Fish-Age-Prediction-with-KNN
This repository contains code and resources for predicting the age of abalone fish using a K-nearest neighbors (KNN) classifier. The project aims to analyze the Abalone dataset, explore its features, and implement KNN classification to predict the age (Rings) of the fish.

## Topics Covered:

### Data Exploration and Preprocessing:

* Loading the Abalone dataset and examining its features, ranges, and distribution.
* Identifying missing data and addressing any necessary preprocessing steps.
* Computing moments and summarization statistics to gain insights into different features.

### Exploratory Data Analysis:

* Using pairsplot to visualize relationships between features.
* Highlighting important features that may influence the prediction of the fish age.
* Determining if the dataset is balanced and discussing potential correction techniques.

### Classification with KNN:

* Training the KNN classifier with default parameters on the training set.
* Evaluating the model's performance on the test set.
* Performing 5-fold cross-validation on the training set to find the optimal value of k.
* Plotting and analyzing mean validation accuracy vs. k across all folds to choose the best k.
* Retraining KNN using the chosen k on the entire training data and reporting accuracy on the test set.

### Improving KNN with Weighting:

* Implementing weighted KNN by considering various weighting schemes (default, Manhattan, Euclidean).
* Comparing the accuracy of different weighting methods with the chosen k value.
* Optional task: Plotting accuracy vs. k for all three weighting schemes to observe their effects.


## Software Stack:
The analysis and classification tasks are carried out using Python. Key libraries used include Pandas for data manipulation, Seaborn for data visualization, and Scikit-learn for KNN classification and cross-validation.

## Data Source:
The Abalone dataset used in this project can be accessed from the UCI Machine Learning Repository.
