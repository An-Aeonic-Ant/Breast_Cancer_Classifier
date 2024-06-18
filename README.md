# Breast_Cancer_Classifier
This repository contains a Jupyter Notebook demonstrating how to build and evaluate a breast cancer classifier using the scikit-learn library. The classifier is trained on the well-known Breast Cancer Wisconsin dataset, and various machine-learning models are employed to classify whether a tumor is benign or malignant.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn


## Methodology
Data Visualization and Outlier Detection:

Visualized the scaled data using a boxplot to identify outliers, which were either removed or handled using Winsorization.

Feature Selection:

Performed pair plotting to analyze the relationships between features and identify which features provide distinctions for classification.
Removed features that did not show significant distinctions.


Correlation Analysis:

Created a correlation matrix to observe the relationships between features.
Applied Principal Component Analysis (PCA) to reduce dimensionality since many features exhibited high correlation, thereby reducing multicollinearity. 

The optimal number of features for decomposition was determined by plotting a graph that relates retained variance to the number of features.

## Prediction Results

The transformed data was trained on multiple models:
- Logistic Regression
- Support Vector Machine
- Decision tree classifier
- Random Forest Classifier

All these models, except the Decision Tree Classifier, were able to classify the test data with more than 99% accuracy and provide reliable classification performance

