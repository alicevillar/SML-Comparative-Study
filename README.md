
<h2>Supervised Machine Learning Algorithms for Predicting Student Dropout and Academic Success: A Comparative Study </h2>

 
 <br> 
<h3>Abstract </h3>


>  * Purpose:  We used a dataset from a higher education institution to compare various machine learning algorithms for predicting student dropout and academic success. Our focus was on algorithms that can handle imbalanced data effectively.
 
>  * Design/Methodology/Approach:  To address class imbalance in the dataset, we use the SMOTE resampling method. We apply Decision Tree (DT), Support Vector Machine (SVM), and Random Forest (RF) as well as boosting algorithms like Gradient Boosting (GB), Extreme Gradient Boosting (XGBoost), CatBoost (CB), and Light Gradient Boosting Machine (LB). We apply hyperparameter tuning using Optuna to further optimize the performance of all supervised algorithms. Finally, we apply Isolation Forest (IF) outliers or anomalies in the dataset.

>  *  Findings: Boosting algorithms outperformed traditional classification algorithms. LightGBM (LB) performed the best, achieving an F1 score of 88%. However, unsupervised anomaly detection using Isolation Forests did not perform well in identifying outliers from the minority class.

>  * Research limitations/implications: Our study is limited to a single dataset, and its generalizability to other settings may be limited.

>  * Practical implications: The practical implication of this study is that it provides insights into the effectiveness of different machine learning algorithms for predicting student dropout and academic success. 

>  * Originality/value: This project contributes to the field by benchmarking the performance of various algorithms for predicting student dropout and academic success, which can guide researchers and practitioners in selecting appropriate approaches.



<h1>Table of Contents</h1>

<!-- TOC -->
 
 
<!-- /TOC -->
 
## 1. Overview 

The purpose of this project is to create and compare different ML models to predict students admission to graduate school. As a starting point, I used a tutorial from [UCLA](http://stats.idre.ucla.edu/r/dae/logit-regression/). This tutorial applies Logistic Regression with R, but I did it with Python. After predicting students admission with Logistic Regression, I decided to fix the unequal class distribution of the original dataset.  

This imbalancement was not handled in the tutorial, so it was such a great opportunity for me to fix the imbalanced dataset. After the resampling process, I used the Logistic Regression again with the new dataset. To take the project further, I not only used Logistic Regression, but implemented other three algorithms (Decision Tree, SVM-SVC and Random Forest), along with the performance measurement and K-fold for all of the models. In conclusion, I created a graphic to compare the accuracies score for the different ML algorithms (Accuracy Comparison Graph).

## 1.1. Quick Start  
[Check out](https://nbviewer.org/github/alicevillar/SML-for-Predicting-Student-Dropout-and-Academic-Success_Comparative-Study/blob/6f524664599ae2bf609f612fae41ea337e7d75f8/ml-algorithms-usage-and-prediction.ipynb) a static version of the notebook with Jupyter NBViewer from the comfort of your web browser.
 
