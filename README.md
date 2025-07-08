Iris Flower Classification Using Machine Learning – Full Project Description
This repository presents a complete machine learning pipeline to classify Iris flowers into their respective species — Iris-setosa, Iris-versicolor, and Iris-virginica — based on four key morphological features: sepal length, sepal width, petal length, and petal width.

The project begins with thorough data exploration and preprocessing, including checks for missing values, duplicate entries, and outliers. Visualizations such as pair plots, heatmaps, boxplots, and bar charts are used to understand the feature distributions and relationships between variables.

A series of supervised ML models were implemented and evaluated:

Logistic Regression (as a baseline model)

K-Nearest Neighbors (KNN)

Decision Tree Classifier

To optimize model performance, GridSearchCV was used for hyperparameter tuning. The Decision Tree model, after optimization, achieved a perfect 100% accuracy on the test dataset, outperforming other models in terms of precision, recall, and F1-score.

The final model is not only accurate but also interpretable, as feature importance analysis revealed that petal length and petal width were the most significant predictors for classifying the species. This makes the model suitable for real-world applications, including:

Real-time plant species prediction

Educational purposes in botany and data science

Interactive ML demonstrations

In addition, the project includes:

A clean, reproducible Jupyter notebook

Code for evaluation metrics and visualizations

Model explainability tools (feature importance plots)

A requirements.txt for easy environment setup

This project is ideal for beginners and intermediate learners looking to understand how to implement a full machine learning pipeline — from data loading and cleaning to model selection and evaluation — using a simple yet powerful dataset.
