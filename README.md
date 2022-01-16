# Home Credit Default Risk [Machine Learning Project]

This is a Python-based implementation of two different types of machine learning models *[mentioned below]* on the task of "Home Credit Default Risk".

#### Language and Libraries

<p>
<a><img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen" alt="Seaborn"/></a>
 <a><img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit_learn"/></a>
<a><img src="https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white" alt="Seaborn"/></a>
<a><img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" alt="numpy"/></a>
 <a><img src="https://matplotlib.org/_static/logo2_compressed.svg" alt="cplusplus" width="110"/></a>
<a><img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" alt="Seaborn"width="110"/></a>
</p>

## About Dataset:
Home Credit Default Risk DataSet from [Kaggle Competitions](https://www.kaggle.com/c/home-credit-default-risk)

### [Data Set Information](https://www.kaggle.com/c/home-credit-default-risk/data)

<a><img src="https://storage.googleapis.com/kaggle-media/competitions/home-credit/home_credit.png" alt="Data" align="center"/></a>

## Table of Content:

### Data Loading

`!kaggle competitions download home-credit-default-risk`

### Exploratory Data Analysis

1. Checking Missing Values (Data contains lots of null values and need to be clean or replace using Imputation Techniques)
2. Checking Duplicate Data (The no. of duplicates in the data: 0)
3. Data Visualization

### Feature Engineering

1. Feature Engineering Application Train Data

### Data Prepration
1. Merging all 6 Datasets - Key = SK_ID_CURR

### Data Preprocessing

1. Imputing Categorical & Numerical Data (SimpleImputer)
2. Scaling Numerical Data (StandardScaler) 
3. Encoding Categorical Data (OneHotEncode)
4. Class Balancing (RandomOverSampling)

### Feature Selection

Model Used - LGBMClassifier

### Classification

#### Models Used:

1. LGBM Classifier [About](https://lightgbm.readthedocs.io/en/latest/pythonapi/lightgbm.LGBMClassifier.html)
2. RandomForest Classifier [About](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)

#### Model Evaluation

#### HyperParameter Tunning

### Results
