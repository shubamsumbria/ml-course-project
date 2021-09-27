# Home Credit Default Risk [Machine Learning Project]

This is a Python-based implementation of two different types of machine learning models *[mentioned below]* on the task of "Home Credit Default Risk".

## About Dataset:
Home Credit Default Risk DataSet from [Kaggle Competitions](https://www.kaggle.com/c/home-credit-default-risk)

### [Data Set Information](https://www.kaggle.com/c/home-credit-default-risk/data)

<a><img src="https://storage.googleapis.com/kaggle-media/competitions/home-credit/home_credit.png" alt="Data" align="center"/></a>

### Libraries Used:

<table>
<tbody>
<tr>
<td><a><img src="https://pandas.pydata.org/docs/_static/pandas.svg" alt="Pandas" align="center" width="75"/></a></td>
<td><a><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/330px-NumPy_logo_2020.svg.png" alt="Numpy" align="center" width="75"/></a></td>
<td><a><img src="https://matplotlib.org/_static/logo2_compressed.svg" alt="cplusplus" align="center" width="75"/></a></td>
<td><a><img src="https://seaborn.pydata.org/_static/logo-wide-lightbg.svg" alt="Seaborn" align="center" width="75"/></a></td>
<td><a><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" align="center" width="75"/></a></td>
<td><a><img src="https://lightgbm.readthedocs.io/en/latest/_static/LightGBM_logo_grey_text.svg" alt="LightGBM" align="center" width="75"/></a></td>
</tr>
</tbody>
</table>

## Table of Content:

### Data Loading

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
