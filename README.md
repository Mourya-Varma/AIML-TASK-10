# AIML-TASK-10

This project implements K-Nearest Neighbors (KNN) to classify handwritten digits using the Scikit-learn Digits dataset.
The dataset is loaded using load_digits() and contains 8×8 pixel images of digits (0–9).
The data is split into training and testing sets using train_test_split.
StandardScaler is applied because KNN is a distance-based algorithm.
A KNN model with K = 3 is trained and tested for accuracy.
Multiple K values (3, 5, 7, 9) are evaluated to find the best performance.
An Accuracy vs K graph is plotted to visualize results.
A confusion matrix is generated to analyze misclassified digits.
The project demonstrates distance-based classification and K tuning.
Tools used: Python, Scikit-learn, Matplotlib.
