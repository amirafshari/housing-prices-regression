# Goal
Predicting Housing Prices
# Dataset
Download: [kaggle](https://www.kaggle.com/camnugent/california-housing-prices), [StatLib](http://lib.stat.cmu.edu/datasets/houses.zip)  
or
```
from sklearn.datasets import fetch_california_housing
fetch_california_housing()
```
# EDA
## Ocean Proximity Count
Ocean Proximity is our only categorical data in this dataset.

![ocean_proximity](https://user-images.githubusercontent.com/17769927/138718362-f419fed8-b34c-41cb-9cb2-09f3ce13e5e5.png)
![ocean_proximity-pie](https://user-images.githubusercontent.com/17769927/138718371-c17dede1-247e-4090-b54f-6d650121d9cb.png)


## Where are the most populated areas?
### Population Density Recongnition
![density1](https://user-images.githubusercontent.com/17769927/138718413-3e29fa00-2f4f-4967-a752-39ce56fb455b.png)
![density2](https://user-images.githubusercontent.com/17769927/138718424-6f6cd0c6-c5a6-4442-a058-80968fc29035.png)
![density](https://user-images.githubusercontent.com/17769927/138718446-ca1aab50-45b3-4094-86ef-bcb9a4fb07fc.png)


## Correlations

### Median Income vs Median House Value (Strongest Correlation)
![correlations](https://user-images.githubusercontent.com/17769927/138719144-34f2ed03-e332-4646-811b-3569a8d5f7ae.png)

## Distribution of Features
![feature-distribution](https://user-images.githubusercontent.com/17769927/138719163-09cf03d6-64e9-409e-b647-66529e2abb73.png)

## Outliers
![outliers](https://user-images.githubusercontent.com/17769927/138719182-5addddd8-398f-4cb5-9bd7-b293820d9ff2.png)

# Feature Engineering
* Categorical Data Handling (One-hot Encoding)
* Scaling (Normalization)
* Clipping
* Imputing
* Spliting
* Feature Crosses

# Learning
### Algorithms
* Linear Regression
* Decision Tree
* Random Forest
* SVM
### Cost Function
* Root Mean Squared Error (RMSE)

# Other
* Cross-Validation
