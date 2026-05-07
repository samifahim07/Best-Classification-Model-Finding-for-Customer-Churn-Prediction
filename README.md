## Best-Classification-Model-Finding-for-Customer-Churn-Prediction part-1
Comparative study of 8 ML classifiers (Random Forest, GBM, ANN, SVM, KNN, DT, LR, NB) on a customer churn dataset. Random Forest achieved the best accuracy of 95.6%.


# Customer Churn Prediction Using Multiple Classification Algorithms

## Overview

This project focuses on applying and comparing multiple Machine Learning classification algorithms to identify the most effective model for predicting customer churn. The project is based on the **Customer Churn Dataset** and follows a complete Machine Learning workflow including data preprocessing, model training, evaluation, model selection, and deployment preparation.

In addition to the implementation, this project is also being prepared as a **basic research paper following the IEEE paper format**. This is my **first attempt at writing a research paper and developing a complete ML-based prediction system**, making it an important learning experience in both Machine Learning and academic research.

---

## About Machine Learning

Machine Learning (ML) is generally divided into three major categories based on how models learn from data:

### Supervised Learning

Supervised Learning is a type of Machine Learning where the model learns from labeled data. Each input feature has a corresponding output label, allowing the model to learn patterns and make predictions.

### Unsupervised Learning

Unsupervised Learning works with unlabeled data. The model automatically identifies hidden patterns, structures, or similarities within the dataset without predefined outputs.

### Reinforcement Learning

Reinforcement Learning (RL) is a learning approach where an agent learns through interaction with an environment by maximizing rewards through trial and error.

---

## Project Type

The **Customer Churn Dataset** contains multiple independent features and one dependent target column. Since the dataset includes labeled outputs, this project falls under **Supervised Machine Learning**.

Supervised learning is mainly divided into two types:

* **Classification**

  * Used when the target column contains categorical values such as:

    * `0 / 1`
    * `Yes / No`
    * `True / False`

* **Regression**

  * Used when the target column contains continuous numerical values.

As the target column in this dataset contains categorical churn values, this project is considered a **Classification Problem**.

---

## Classification Algorithms Used

The following classification algorithms were implemented and compared to identify the best-performing model:

* Logistic Regression
* Decision Tree
* Random Forest
* Naive Bayes
* Support Vector Machine (SVM)
* Gradient Boosting Machine (GBM)
* K-Nearest Neighbors (KNN)
* Artificial Neural Network (ANN)

---

## Project Workflow

### Part 1 — Model Development

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Encoding
* Feature Scaling
* Model Training
* Performance Evaluation
* Best Model Selection

### Part 2 — Deployment Preparation

* Saving the Best Performing Model
* Building Prediction API
* Preparing for Real-World Deployment

---

## Evaluation Metrics

Models were evaluated using multiple performance metrics, including:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Research Paper

This project is also being documented as a **basic IEEE format research paper**.
As a beginner researcher and ML enthusiast, this is my **first attempt at writing a research paper**, implementing multiple classification models, and understanding practical research workflow.

The goal of this work is not only to build a prediction model but also to gain hands-on experience in:

* Machine Learning Research
* Model Comparison
* Academic Writing
* Research Methodology
* Real-World Deployment Concepts

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Flask / FastAPI *(for deployment phase)*

---

## Future Improvements

* Hyperparameter Optimization
* Cross Validation
* Advanced Deep Learning Models
* Deployment on Cloud Platform
* Interactive Web Application
* Real-Time Prediction API

---

## Author Note

This project represents my learning journey in Machine Learning and research writing. As this is my first research-oriented project and first IEEE-style paper attempt, feedback and suggestions are always appreciated.

**For a more detailed explanation of this project, please review the accompanying DOCX document.**

## ⭐ Give a star if you like this project!
