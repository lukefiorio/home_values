# Residential Home Value Prediction
### UW Data Science Milestone Project - Price Prediction

This project uses data from the Kaggle on residential homes in King County, WA to predict home value and make binary classifaction predictions.  The data can be found and downloaded here: 
- https://www.kaggle.com/harlfoxem/housesalesprediction/download

For this project, we download directly from a link made available through University of Washington (https://library.startlearninglabs.uw.edu/DATASCI410/Datasets/kc_house_data.csv).

Our goal is to predict home prices based on several features related to each home (e.g. home size, location, quality, etc.).  Specifically, we aim to build a model using linear regression that maximizes r<sup>2</sup>.  Or, in other words, we aim to explain as much of the variance in home price as possible by using the provided features (including feature engineering).  We will also binarize homes based on their value (above or below $450K) and maximize overall accuracy of our linear classifier.

**This repo contains 2 files:**
| File                                   | Description |
| -------------------------------------- | ----------- |
| LukasFiorio-M02-Milestone2.ipynb.pptx  | Python Notebook used to identify relationships between our features and target, including hypothesis testing |
| LukasFiorio-M03-Milestone3.ipynb.ipynb | Python Notebook used to build and evalute Linear Regression and classifier models |

**Problem Description:**

The dataset that we use to build and test our model contains several features, and the sale price, of 21,600 homes in King County, WA from May 2014 - May 2015.  Sales Price is our target variable, which we will predict using linear regression.
