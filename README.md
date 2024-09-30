Bacterial Identification Programs
This repository contains two Python programs for identifying bacteria based on their characteristics: a traditional decision tree-based approach and a machine learning-based approach using scikit-learn.
Table of Contents

Overview
  Requirements
  Decision Tree-Based Program
  Machine Learning-Based Program
  Comparison

Overview
Both programs aim to identify bacterial species based on user input about the bacteria's characteristics. They differ in their approach:

The decision tree-based program uses a series of if-else statements to navigate through a predefined decision tree.
The machine learning-based program uses a DecisionTreeClassifier from scikit-learn to make predictions based on trained data.

Requirements
For the Decision Tree-Based Program:

Python 3.x

For the Machine Learning-Based Program:

Python 3.x
NumPy
scikit-learn

Basic Decision Tree Features

  Uses a predefined decision tree based on common bacterial identification tests.
  Covers both Gram-positive and Gram-negative bacteria.
  Includes tests such as Gram staining, catalase test, coagulase test, and more.


Machine learning Features

  Uses a DecisionTreeClassifier from scikit-learn.
  Trains on a predefined dataset (which can be easily expanded).
  Converts user inputs into features for the machine learning model.
  Provides predictions based on learned patterns in the data.
