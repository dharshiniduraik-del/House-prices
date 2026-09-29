

# Project Title

Heart Disease Prediction using Machine Learning

## About the Project

This project demonstrates a basic Machine Learning classification model using Python.
The Heart Disease dataset is loaded and analyzed to predict whether a person is likely to have heart disease.

## Two machine learning algorithms are used:

- Logistic Regression
- K-Nearest Neighbors (KNN)

The models are evaluated using different performance metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.

## Objectives

- Load and analyze the heart disease dataset.
- Separate the input features and target variable.
- Split the dataset into training and testing data.
- Build a Logistic Regression classification model.
- Build a KNN classification model.
- Compare model performance using accuracy.
- Visualize the confusion matrix.

## Technologies Used

- Python 
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses a Heart Disease dataset stored as:

"heartfile.csv"

The "target" column is used as the prediction variable.

## Project Workflow

Heart Disease Dataset
        ↓
Data Loading
        ↓
Data Analysis
        ↓
Feature & Target Separation
        ↓
Train-Test Split
        ↓
Logistic Regression
        ↓
Model Prediction
        ↓
Performance Evaluation
        ↓
Confusion Matrix
        ↓
KNN Classification
        ↓
Accuracy Comparison

## Machine Learning Models

1. Logistic Regression

Logistic Regression is used for binary classification.
The model is trained using the training dataset and then used to predict the target values of the test dataset.

2. K-Nearest Neighbors (KNN)

KNN classifies data based on the nearest data points.

Different values of K (1 to 8) are tested to observe how the accuracy changes.

K = 1
K = 2
K = 3
K = 4
K = 5
K = 6
K = 7
K = 8

## Evaluation Metrics

The Logistic Regression model is evaluated using:

- Accuracy – Measures the overall correctness of predictions.
- Precision – Measures how many predicted positive cases are actually positive.
- Recall – Measures how many actual positive cases are correctly identified.
- F1-Score – Provides a balance between precision and recall.
- Confusion Matrix – Shows correct and incorrect predictions.

## Confusion Matrix

A heatmap is created using Seaborn to visualize the confusion matrix.

sns.heatmap(cm, annot=True, fmt="d")

This helps to understand the model's classification performance.

## Project Structure

Day-7-Python/
│
├── day 7 python.ipynb
├── heartfile.csv
└── README.md

## How to Run

1. Clone or download this repository.
2. Open the Jupyter Notebook.
3. Make sure "heartfile.csv" is in the same folder.
4. Install the required libraries:

pip install pandas scikit-learn matplotlib seaborn

5. Run the notebook cells step by step.

## Key Learning Outcomes

## Through this project, I learned:

- Basics of Machine Learning classification.
- Loading datasets using Pandas.
- Feature and target selection.
- Train-test data splitting.
- Logistic Regression.
- K-Nearest Neighbors (KNN).
- Model prediction.
- Classification evaluation metrics.
- Confusion matrix visualization.
- Comparing KNN models with different K values.

## Author

Dharshini N
B.Tech Information Technology
Vivekanandha College of Engineering for Women



