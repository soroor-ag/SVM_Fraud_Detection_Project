# SVM and Fraud Detection Project

## Overview

This project aims to explore the application of Support Vector Machine (SVM) on the famous Iris dataset and to implement and analyze a custom SVM from scratch. Additionally, the project involves studying a research paper on fraud detection, implementing the proposed model, and comparing its performance with and without noise removal and oversampling techniques.

## Project Structure

1. **Iris Dataset Analysis**
    - Load and explore the Iris dataset.
    - Calculate statistics (dimensions, sample count, mean, variance, correlations).
    - Visualize the dataset using t-SNE.
    - Analyze the potential for dimensionality reduction based on the obtained data.

2. **SVM with Linear Kernel**
    - Classify the data using SVM with a linear kernel.
    - Obtain the confusion matrix.
    - Plot decision boundaries in a 2D space (after dimensionality reduction).

3. **SVM with Polynomial Kernels**
    - Implement SVM with polynomial kernels (degrees 1 to 10) using `scikit-learn`.
    - Report and compare the results using appropriate metrics.
    - Create a GIF visualizing the decision boundaries for each polynomial degree.

4. **Custom SVM Implementation**
    - Implement SVM from scratch without using `scikit-learn`.
    - Define a `SVM` class with methods `kernel_Polynomial`, `Fit`, and `Predict`.
    - Report the accuracy of the custom SVM as the polynomial degree increases.
    - Compare the results with the `scikit-learn` implementation.
    - Create a GIF visualizing the decision boundaries for each polynomial degree.

5. **Fraud Detection Paper Review**
    - Identify major challenges in developing fraud detection models and the methods used in the paper to address these challenges.
    - Summarize the network architecture proposed in the paper.
    - Implement and train the model using the provided dataset.
    - Avoid overfitting by returning the best model weights based on validation error at the end of training.
    - Plot the confusion matrix on the test data and report Accuracy, Precision, Recall, and F1-score.
    - Discuss the limitations of using Accuracy alone for imbalanced datasets and suggest complementary metrics.
    - Evaluate model performance with varying thresholds for oversampling and plot Accuracy & Recall similar to figure 7 in the paper.
    - Train the model with unbalanced data and noise included, then report and compare the results with the previous model.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries:
  - numpy
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
  - imageio


