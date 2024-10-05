# Iris Classification Using Logistic Regression

This project uses the well-known Iris dataset to classify iris species based on their features using the Logistic Regression algorithm.

## Project Overview
The Iris dataset contains 150 samples from three iris species: *Iris setosa*, *Iris versicolor*, and *Iris virginica*. Each sample has four features: sepal length, sepal width, petal length, and petal width. The goal is to classify iris species using logistic regression.

## Technologies Used
- Python
- Pandas
- scikit-learn

## Dataset
The Iris dataset is included in the `sklearn.datasets` module, with 150 rows and 4 features:
- **Sepal Length**: Length of the sepal (cm)
- **Sepal Width**: Width of the sepal (cm)
- **Petal Length**: Length of the petal (cm)
- **Petal Width**: Width of the petal (cm)

The dataset is divided into three classes:
1. *Iris setosa* (class 0)
2. *Iris versicolor* (class 1)
3. *Iris virginica* (class 2)

## Model Training
- The dataset is split into training (80%) and testing (20%) sets using `train_test_split`.
- Logistic Regression is used as the classification algorithm.
  
## Evaluation
The following metrics are calculated after training the model:
- **Accuracy Score**: Measures how often the model predicts the correct class.
- **Confusion Matrix**: Shows the number of true/false positives and true/false negatives.
- **Classification Report**: Includes precision, recall, F1-score, and support for each class.
