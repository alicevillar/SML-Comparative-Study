# SML-for-Predicting-Student-Dropout-and-Academic-Success_A-Comparative-Study

<h1>Predicting students admission with Logistic Regression, Decision Tree, SVM (SVC) and Random Forest</h1>

> In this project, I applied a resampling technique (oversampling) to the imbalanced dataset and compared the performance of different Machine Learning models. I have found the best accuracy score with Random forest (85%).

<h1>Table of Contents</h1>

<!-- TOC -->

- [1. Overview](#1-overview)
    - [1.1. Quick Start](#11-quick-start)
- [2. Problem Statement](#2-problem-statement)
    - [2.1. Dataset](#21-dataset)
- [3. Approach](#3-approach)
- [4. Dependencies](#4-dependencies)
- [5. Results](#5-results)

 
<!-- /TOC -->

## 1. Overview 

The purpose of this project is to create and compare different ML models to predict students admission to graduate school. As a starting point, I used a tutorial from [UCLA](http://stats.idre.ucla.edu/r/dae/logit-regression/). This tutorial applies Logistic Regression with R, but I did it with Python. After predicting students admission with Logistic Regression, I decided to fix the unequal class distribution of the original dataset.  

This imbalancement was not handled in the tutorial, so it was such a great opportunity for me to fix the imbalanced dataset. After the resampling process, I used the Logistic Regression again with the new dataset. To take the project further, I not only used Logistic Regression, but implemented other three algorithms (Decision Tree, SVM-SVC and Random Forest), along with the performance measurement and K-fold for all of the models. In conclusion, I created a graphic to compare the accuracies score for the different ML algorithms (Accuracy Comparison Graph).

## 1.1. Quick Start  
[Check out](https://nbviewer.org/github/alicevillar/SML-for-Predicting-Student-Dropout-and-Academic-Success_Comparative-Study/blob/6f524664599ae2bf609f612fae41ea337e7d75f8/ml-algorithms-usage-and-prediction.ipynb) a static version of the notebook with Jupyter NBViewer from the comfort of your web browser.
 
