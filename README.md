# Exploring Classification Models: A Comparative Study on a Simple Dataset

## Overview

This project is a comparative analysis of various classification models applied to the **Heart Attack Analysis & Prediction Dataset**. The primary objective is to evaluate and understand the performance of different machine learning algorithms in predicting the likelihood of a heart attack based on several health-related features.

## Models Used

In this notebook, I explore and compare the following models:

- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**
- **Logistic Regression**
- **Support Vector Machines (SVM)**
- **Neural Networks**

## Performance Metrics

The models were primarily evaluated based on two metrics:

- Accuracy (from the classification_report): The percentage of correctly classified instances out of the total instances.
- Mean Absolute Error (MAE): The average magnitude of the errors in predictions, without considering their direction.

## Key Findings:
**Naive Bayes** and **Neural Networks**: Interestingly, both the Naive Bayes and Neural Network models performed equally well in both metrics, achieving the highest accuracy and the lowest MAE among all the models tested. This result indicates that these two models are particularly effective for this dataset.

Note: For the Support Vector Machine (SVM) and Neural Network models, I conducted a more in-depth exploration to optimize their parameters. While this was aimed to enhance the models' effectiveness, it may also have contributed to the comparable performance of these models against the rest. The impact of parameter tuning on model performance is something to keep in mind when comparing results.

## Conclusion
This project provides insights into how different machine learning models perform on a heart attack prediction task. The surprising tie in performance between Naive Bayes and the Neural Network highlights the potential of simpler models like Naive Bayes in certain contexts, as well as the effectiveness of well-tuned Neural Networks in others.
