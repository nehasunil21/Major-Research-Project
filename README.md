# Breast Cancer Classification

# Prediction and Classification of Breast Cancer using Machine Learning techniques

This repository contains the source code and results of developing a breast cancer prediction model to help classify whether the breast cancer is benign or malignant.

## Table of Contents
- [Overview](#overview)
- [Dataset Description](#datasetdescription)
- [Methodology](#methodology)
- [Results](#results)

<a id='overview'></a>
## Overview

The aim of this study is to train different classifier models that can help classify whether the tumor in the breast is benign or malignant and help predict the reoccurrence of cases classified as malignant by observing the most important features. To identify the best trained classifier, 7 different algorithms were applied and their statistic results were analyzed to determine the appropriate approach for this analysis. 

Helping women with early diagnosis of breast cancer could lower the risk of prolonged treatment and sometimes death. Since early-stage breast cancer is easier to treat considering the tumor isn’t too large and has not spread, it is important that we develop a more efficient, accurate and reliable approach to do so. This can be achieved by dint of machine learning classifiers. 

<a id='datasetdescription'></a>
## Dataset Description

The Breast Cancer Wisconsin Dataset, available on the UCI Machine Learning repository defines features that were computed from digitized images of a fine needle aspirant (FNA) of a breast mass. These features report the characteristics of the cell nuclei from the image. Breast mass FNA is considered to play a key role in assessing malignancy in breast cell tissue. This dataset was put together by Dr. William H. Wolberg while he was at the University of Wisconsin-Madison Hospital. This dataset comprises of 569 samples of breast cell tissue which were medically assessed focusing on 32 characteristics of the cell nucleus.

Dataset used for this analysis: https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)

<a id='methodology'></a>
## Methodology

An exploratory analysis is conducted using descriptive analytics as well as data visualization to help identify some patterns, or relationships that could help shed light on hidden information in the data available to us. This was followed by the second part of the analysis stemming from training different classifier models that can help classify the tumor in the breast as benign or malignant and predict the reoccurrence of cases classified as malignant by observing the most important features, which was achieved by applying different feature selection techniques to identify features that would contribute the most to our prediction variable. The performance of the different classifiers was compared using precision, recall as well as Area Under the Curve. 

The project has been divided into different segments:
* Exploratoy Data Analysis & Visualization [Exploratory Data Analysis.ipynb](https://github.com/nehasunil21/Breast_Cancer_Classification/blob/main/Exploratory%20Data%20Analysis.ipynb)
* Feature Selection Techniques [Feature Selection Techniques.ipynb](https://github.com/nehasunil21/Breast_Cancer_Classification/blob/main/Feature%20Selection%20Techniques.ipynb)
* Modeling using the different feature selection techniques:
* i) Correlation [
Modeling using Correlation approach.ipynb](https://github.com/nehasunil21/Breast_Cancer_Classification/blob/main/Modeling/Modeling%20using%20Correlation%20approach.ipynb)
* ii) Univariate Feature Selection (chi-square) [Modeling using Univariate (chi_square) approach.ipynb](https://github.com/nehasunil21/Breast_Cancer_Classification/blob/main/Modeling/Modeling%20using%20Univariate%20(chi_square)%20approach.ipynb)
* iii) Recursive Feature Elimination with Random Forest [Modeling using RFE approach.ipynb](https://github.com/nehasunil21/Breast_Cancer_Classification/blob/main/Modeling/Modeling%20using%20RFE%20approach.ipynb)
* iv) Recursive Feature Elimination using Cross-Validation with Random Forest [Modeling using RFECV approach.ipynb](https://github.com/nehasunil21/Breast_Cancer_Classification/blob/main/Modeling/Modeling%20using%20RFECV%20%20approach.ipynb)
* v) Tree based Feature Selection (ExtraTrees) [Modeling using Extra Trees approach.ipynb](https://github.com/nehasunil21/Breast_Cancer_Classification/blob/main/Modeling/Modeling%20using%20Extra%20Trees%20approach.ipynb)
* vi) Vote based Feature selection [Modeling using Vote based approach.ipynb](https://github.com/nehasunil21/Breast_Cancer_Classification/blob/main/Modeling/Modeling%20using%20Vote%20based%20approach.ipynb)

<a id='results'></a>
## Results

This project put to practice a machine learning approach to classify whether the tumor in the breast is benign or malignant and help predict the reappearance of cases classified as malignant by identifying those features that had a significant impact on the prediction of the target variable. We were able to implement different feature selection techniques to minimize redundancy and consequently build different machine learning models with improved accuracy.
According to our findings, Support Vector Machine outperformed all the other models in analysis and prediction of cancer.
