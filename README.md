<br />
<div align="center">
  <h3 align="center">Heart Disease Prediction using Machine Learning</h3>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about">About</a></li>
    <li><a href="#proposed-system">Proposed System</a>
      <ol type="A">
        <li><a href="#workflow">Workflow</a></li>
        <li><a href="#feature-selection">Feature Selection</a></li>
        <li><a href="#classification">Classification</a></li>
        <li><a href="#performance-evaluation-metrics">Performance Evaluation Metrics</a></li>
      </ol>
    </li>
    <li><a href="#results-and-discussions">Results and Discussions</a></li>
    <li><a href="#future-work">Future Work</a></li>
  </ol>
</details>

------

## About

This project aims to predict the likelihood of heart disease at an early stage using various machine learning models. 

Since coronary diseases are a major cause of global mortality, an accurate prediction model can significantly aid in preventive healthcare.

**Objective**

The goal is to build a predictive model that identifies significant features contributing to heart disease and to test various machine learning models to determine the most effective approach.

**Dataset**
- **Source**: UCI Cleveland dataset [![UCI ML Repo](https://img.shields.io/badge/UCI%20ML%20Repository-Dataset-blue)](https://archive.ics.uci.edu/dataset/45/heart+disease)
- **Size**: 303 records, 13 features per record

## Proposed System  
### Workflow

<img src="https://github.com/SejalWagh19/Heart-Disease-Prediction-using-ML/blob/main/workflow.png" width="500" height="500" />

##   
### Feature Selection

- Since the dataset contains many incompatible features that affect the accuracy of the algorithms. Thus, the feature selection techniques reduces those unconnected features hereby improving the algorithm's performance. 

- It uses different feature ranking techniques to find the most important feature based on their scores. 

- In this project, three feature selection techniques are used for identifying the significant features.
<ol>
  <li><b><i>ANOVA</i></b> - Calculates analysis of variance (ANOVA) between features for classification algorithms.</li>
  <li><b><i>Chi-Square</i></b> - Calculates the chi-squared score, which is used to select the highest valued feature between each non-negative feature.</li>
  <li><b><i>Mutual Information</i></b> - Calculates mutual information between the attributes, which measures the relation between the features.</li>
</ol>

## 
### Classification

Four classifiers are applied which are as follows:
<ol>
  <li><b><i>Logistic Regression</i></b></li>
  <li><b><i>K-Nearest Neighbors</i></b></li>
  <li><b><i>Support Vector Machine</i></b></li>
  <li><b><i>AdaBoost</i></b></li>
</ol>

## 
### Performance Evaluation Metrics 
In order to evaluate the performance of the model, five evaluation metrics are used.
<ol>
  <li><b><i>Accuracy</i></b></li>
  <li><b><i>Sensitivity</i></b></li>
  <li><b><i>Specificity</i></b></li>
  <li><b><i>AUROC</i></b></li>
  <li><b><i>Log Loss</i></b></li>
</ol>

## Results and Discussions
For detailed results, visit: https://ieeexplore.ieee.org/document/10863677  

## Future Work

To enhance the results further, future work must focus on applying the same analysis to larger, real-world datasets, such as live data from hospitals. 

Additionally, the use of deep learning algorithms could be explored to achieve more accurate predictions for heart disease.


## Authors

🔆 [@Aryan Mhalsank](https://github.com/aryanmhalsank19)

🔆 [@Sejal Wagh](https://github.com/SejalWagh19)

🔆 [@Madiha Siddiqui](https://github.com/madihasiddiqui111)
