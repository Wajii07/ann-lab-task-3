# Binary Classification using Single-Layer Perceptron

## Overview
This project implements a Single-Layer Perceptron (SLP) from scratch using Python and NumPy for binary classification. The Banknote Authentication dataset from the UCI Machine Learning Repository is used to classify banknotes into genuine and forged categories.

## Dataset
**Source:** [UCI Machine Learning Repository – Banknote Authentication](https://archive.ics.uci.edu/dataset/267/banknote+authentication)

The dataset contains 1,372 instances, four numerical input features, and one binary target column.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (preprocessing and evaluation utilities)
- Flask

## Implementation
1. Dataset loading and exploration.
2. Data preprocessing and feature scaling.
3. Training and testing data split.
4. Single-Layer Perceptron implementation using NumPy.
5. Model training using the perceptron learning algorithm.
6. Predictions on unseen test data.
7. Performance evaluation using accuracy, precision, recall, and F1-score.
8. Confusion matrix and training error visualization.
9. Flask-based interface for making predictions.

## Model Evaluation
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Flask Interface
The Flask interface allows users to enter four banknote measurements and receive a binary classification prediction from the trained perceptron.

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   `pip install numpy pandas matplotlib seaborn scikit-learn flask jupyter`
3. Open `perceptron_implementation.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells in order.
5. Start the Flask application using the notebook's Flask cell.
6. Open `http://127.0.0.1:5000` in your browser.

## Author
ANN Lab Assignment
