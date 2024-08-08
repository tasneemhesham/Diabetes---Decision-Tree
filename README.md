# Diabetes Decision Tree Classifier

## Overview
This project demonstrates the process of building a simple decision tree classifier to predict diabetes outcomes based on the Diabetes dataset. It provides a step-by-step guide to creating a decision tree, calculating entropy and information gain, and visualizing the decision tree. The implementation includes the ID3 algorithm for recursively building the decision tree based on the highest information gain.

## Features
- **Dataset Loading**: Loads the Diabetes dataset and displays its structure.
- **Entropy and Information Gain Calculation**: Functions to calculate entropy (data impurity) and information gain (feature effectiveness).
- **Feature Evaluation**: Iterates through features to print entropy and information gain values.
- **Decision Tree Classifier**: Creates and trains a decision tree classifier using the 'DiabetesPedigreeFunction' feature with a maximum depth of 1.
- **Visualization**: Visualizes the decision tree for better understanding.
- **ID3 Algorithm**: Implementation of the ID3 algorithm for recursive decision tree building based on information gain.

## Dataset
The project uses the Diabetes dataset, which contains medical records of female patients. The dataset includes features such as glucose levels, blood pressure, BMI, Pregnancies, SkinThickness, Age and Insulin.
