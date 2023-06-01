# Breast Cancer Classification using Decision Trees

This repository contains code for classifying breast cancer using decision trees. The dataset used is the "Breast Cancer Wisconsin (Diagnostic) Data Set" obtained from the UCI Machine Learning Repository.

## Dataset
The dataset contains information about various characteristics of cell nuclei, such as radius, texture, perimeter, and more. The goal is to predict whether a given sample is benign or malignant. The dataset consists of 569 instances with 32 attributes, including the diagnosis label.

The dataset can be accessed from the following link:
- [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

## Code Overview
The code performs the following steps:

1. Import the necessary libraries including pandas, numpy, matplotlib, scikit-learn, and graphviz.
2. Load the dataset and preprocess it by dropping irrelevant columns and converting the diagnosis label to binary values.
3. Normalize the feature data to ensure all features are on the same scale.
4. Split the data into training and testing sets.
5. Create and train a decision tree classifier using information gain as the criterion.
6. Visualize the decision tree using graphviz and save it to a file.

## Results
The decision tree classifier trained on the breast cancer dataset can be visualized using graphviz. The resulting decision tree provides insights into the important features for classification.


