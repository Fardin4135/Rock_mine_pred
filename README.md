Introduction
Sonar is a technology that uses sound propagation (usually underwater) to navigate, communicate, or detect objects. In this project, we use a dataset of sonar signals to classify objects as either rocks or mines. This classification problem is particularly relevant in the field of underwater exploration and defense.

Dataset
The dataset used in this project is the "Sonar, Mines vs. Rocks" dataset from the UCI Machine Learning Repository. It consists of 208 instances with 60 attributes each, representing the energy of the sonar signal at different frequencies. The target variable indicates whether the object is a rock or a mine.

Features: 60 attributes representing sonar energy at different frequencies.
Target: Binary classification with classes:
R for rocks
M for mines
Usage
Data Exploration: Use the data_exploration.ipynb notebook to explore the dataset and visualize important features.
Model Training: Use the model_training.ipynb notebook to preprocess the data, train various machine learning models, and select the best performing model.
Prediction: Use the model.py script to load the trained model and make predictions on new sonar data.
Model Performance
The best performing model achieved the following metrics on the test set:

Accuracy: 85%
Precision: 86%
Recall: 84%
The model was evaluated using a confusion matrix, ROC curve, and other standard classification metrics.
