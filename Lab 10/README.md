# Support Vector Machines (SVM) Assignment

## Overview
This assignment demonstrates the use of Support Vector Machines (SVM) using the Iris dataset.

The notebook includes:
- Loading and exploring the Iris dataset
- Data visualization using Seaborn
- Splitting the dataset into training and testing sets
- Training an SVM model
- Evaluating model performance
- Improving performance using GridSearchCV

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Dataset
The project uses the built-in Iris dataset from Scikit-learn.

Dataset features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target classes:
- Setosa
- Versicolor
- Virginica

---

## Machine Learning Steps

### 1. Data Loading
The Iris dataset was loaded and converted into a Pandas DataFrame.

### 2. Data Visualization
Different visualization techniques were used:
- Pairplot
- KDE plots

### 3. Train/Test Split
The dataset was divided into:
- 70% training data
- 30% testing data

### 4. Model Training
An SVM classifier was trained using Scikit-learn.

### 5. Model Evaluation
The model was evaluated using:
- Confusion Matrix
- Classification Report

### 6. Hyperparameter Tuning
GridSearchCV was used to improve model performance by testing:
- Different C values
- Different gamma values
- RBF kernel

---

## Results
The final SVM model achieved high classification accuracy on the Iris dataset.

---

## Author
Prepared for the SVM Assignment Lab.
