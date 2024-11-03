<br />
<div align="center">
  <h3 align="center">Heart Disease Prediction using Machine Learning</h3>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about">About</a></li>
    <li><a href="#proposed-system">Proposed System</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#future-work">Future Work</a></li>
  </ol>
</details>

------

## <a id="about"></a>About

This project aims to predict the likelihood of heart disease at an early stage using various machine learning models. 

Since coronary diseases are a major cause of global mortality, an accurate prediction model can significantly aid in preventive healthcare.

**Objective**

The goal is to build a predictive model that identifies significant features contributing to heart disease and to test various machine learning models to determine the most effective approach.

**Dataset**
- **Source**: UCI Cleveland dataset [![UCI ML Repo](https://img.shields.io/badge/UCI%20ML%20Repository-Dataset-blue)](https://archive.ics.uci.edu/dataset/45/heart+disease)
- **Size**: 303 records, 13 features per record

## Demonstration

Try the Application Now - 
<a href="">HeartMetrics</a>

## <a id="proposed-system"></a>Proposed System

**A. Workflow**

<img src="https://github.com/SejalWagh19/Heart-Disease-Prediction-using-ML/blob/main/workflow.png" width="500" height="500" />

## 

**B. Feature Selection**

- Since the dataset contains many incompatible features that affect the accuracy of the algorithms. Thus, the feature selection techniques reduces those unconnected features hereby improving the algorithm's performance. 

- It uses different feature ranking techniques to find the most important feature based on their scores. 

- In this project, three feature selection techniques are used for identifying the significant features.
<ol>
  <li><b><i>ANOVA</i></b> - Calculates analysis of variance (ANOVA) between features for classification algorithms.</li>
  <li><b><i>Chi-Square</i></b> - Calculates the chi-squared score, which is used to select the highest valued feature between each non-negative feature.</li>
  <li><b><i>Mutual Information</i></b> - Calculates mutual information between the attributes, which measures the relation between the features.</li>
</ol>

## 

**C. Classification**

Four classifiers are applied which are as follows:
<ol>
  <li><b><i>Logistic Regression</i></b></li>
  <li><b><i>K-Nearest Neighbors</i></b></li>
  <li><b><i>Support Vector Machine</i></b></li>
  <li><b><i>AdaBoost</i></b></li>
</ol>

## 

**D. Performance Evaluation Metrics**

In order to evaluate the performance of the model, five evaluation metrics are used.
<ol>
  <li><b><i>Accuracy</i></b></li>
  <li><b><i>Sensitivity</i></b></li>
  <li><b><i>Specificity</i></b></li>
  <li><b><i>AUROC</i></b></li>
  <li><b><i>Log Loss</i></b></li>
</ol>

## <a id="results"></a>Results

## <a id="future-work"></a>Future Work

To enhance the results further, future work must focus on applying the same analysis to larger, real-world datasets, such as live data from hospitals. 

Additionally, the use of deep learning algorithms could be explored to achieve more accurate predictions for heart disease.
