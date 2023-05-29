
---
# MNIST Digit-5 Classifier

This repository contains a binary classification model to predict whether a given image from the MNIST dataset represents the digit 5 or not. The aim of this project is to illustrate basic machine learning techniques using Python and Scikit-Learn.

## Dataset

The dataset used is the MNIST dataset, a set of 70,000 small images of digits handwritten by high school students and employees of the US Census Bureau. Each image is labeled with the digit it represents. In this project, we convert this multi-class classification problem into a binary classification problem - the digit 5 or not-5.

## Project Structure

1. **Loading the Data:** The MNIST dataset is loaded using Scikit-Learn's `fetch_openml()` function.

2. **Visualizing the Data:** The images in the dataset are visualized using Matplotlib.

3. **Preparing the Data:** The dataset is split into training and test sets. Also, the target variable is transformed into a binary variable (5 or not-5).

4. **Training the Model:** We train a Stochastic Gradient Descent (SGD) classifier model and a RandomForest classifier on the training set.

5. **Evaluating the Model:** We evaluate the models on the test set using metrics like Precision, Recall, F1 Score, and ROC Curve.

## Running the Project

You will need Python 3 and the following Python libraries installed:

- NumPy
- Pandas
- Scikit-Learn
- Matplotlib

To run the project, simply execute the Jupyter notebook in the repository.
