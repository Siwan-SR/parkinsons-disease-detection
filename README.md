# Parkinson's Disease Detection

A machine learning model that can detect whether a patient has Parkinson's disease or not.

## Data

The data is from: https://www.kaggle.com/datasets/dipayanbiswas/parkinsons-disease-speech-signal-features

Data Information:

* Data Set Characteristics: Multivariate
* Number of Instances: 756
* Area: Computer
* Attribute Characteristics: Integer, Real
* Number of Attributes: 754
* te Donated: 2018-11-05
* Associated Tasks: Classification
* Missing values?: N/A
* Number of Web Hits: 34405

Columns Description:

* Baseline Features: Col3 to Col23
* Intensity Parameters: Col24 to Col26
* Formant Frequencies: Col27 to Col30
* Bandwidth Parameters: Col31 to Col34
* Vocal Fold: Col35 to Col56
* MFCC: Col57 to Col140
* Wavelet Features: Col141 to Col322
* TQWT Features: Col323 to Col754
* Class: Col_755

## How the model was made

The model was made using [Scikit-Learn](https://scikit-learn.org/) an excellent machine learning library. I used Random Forest Classifer as the model.

## How the notebook is structured

* Explore the data
* Visualize our data
* Fit and instantiate the model
* Describe our model

### What you will find

* Awesome Graphs that visualize the data
* Use of [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/)
* Use of Scikit-Learn's manu features
* Testing with many models
* A ROC Curve
* Many Visual Confusion Matrix
* A custom Classification Report
