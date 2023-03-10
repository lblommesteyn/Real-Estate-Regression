# Machine Learning Regression with Kaggle House Prices

This is a deep dive into learning to solve machine learning regression problems.  Supervised learning with a continuous target value.

The data set used is from the the Kaggle Competition [House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)

Given several dozen predictors/featues, we want to accurately predict the sale price of a house.

## Notebooks

- [Quickstart](house-prices-quickstart.ipynb)
- [Lasso, Ridge, and ElasticNet Regression](house-prices-lasso-and-ridge.ipynb)
- [Polynomial Features](house-prices-polynomial.ipynb)
- [Target and Feature Distributions](house-prices-target-feature-distributions.ipynb)
- [Simple Imputer and Label Encoding](house-prices-simple-imputer.ipynb)
- [Robust Regression - RANSAC](house-prices-robust-regression.ipynb)
- [Stochastic Gradient Descent](house-prices-sgd.ipynb)
- [Lasso, Ridge, and ElasticNet with log(target)](house-prices-lasso-ridge-log-target.ipynb)
- [Decision Tree and Random Forests](house-prices-decision-tree-and-random-forest.ipynb)
- [GridSearchCV](house-prices-rf-gridsearchcv.ipynb)
- [MLPRegressor](house-prices-mlpregressor.ipynb)
- [Gradient Boosted Trees - XGBoost/Catboost/LightGBM](house-prices-xgboost.ipynb)
- [Support Vector Machines](house-prices-support-vector-regression.ipynb)
- [Tensorflow](house-prices-tensorflow.ipynb)
- [PyTorch](house-prices-pytorch.ipynb)
- [Basic EDA](house-prices-eda.ipynb)
- [Linear Regression from Scratch](house-prices-lr-from-scratch.ipynb)

## Machine Learning Models Covered

- Linear Regression
  - Lasso - L1
  - Ridge - L2
  - Polynomial
  - Residuals
  - Collinearity
  - Interactions
  - Mathematics
    - Solving Ax=b using numpy
    - Normal Equations
- Decision Trees  
- Gradient Boosted Decision Trees (GBDT)
- Support Vector Machines
- [Principal Component Analysis](pca.md) (PCA)
- Stochastic Gradient Descent
- Deep Neural Networks (DNN)
  - Activation Functions

In addition, I use other topics important to machine learning:

- Feature Engineering
  - Data Transformation
    - Scaling
    - Gaussian Normal
    - log transform
    - skew, kurtosis
- Missing Values
- Outliers
  - Z-score
  - IQR Method
  - https://www.kaggle.com/code/nareshbhat/outlier-the-silent-killer
  - Hypothesis Testing
  - DBSCAN Clustering
- Loss Functions
  - MAE
  - RMSE
  - Huber
- Feature Selection
  - Forward Selection
  - Reverse Selection
  - SHAP
    - https://h2o.ai/blog/shapley-values-a-gentle-introduction/
  - Permutation Importance
  - Mutual Information
- Hyperparameter Optimization

## MAE


[Mean Absolute Error](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_absolute_error.html)

$$MAE = \frac{\sum_{i=1}^n |y_i - x_i|}{n}$$

## RMSE

[RMSE](https://en.wikipedia.org/wiki/Root-mean-square_deviation)

$$RMSE = \sqrt{\frac{1}{n}\Sigma_{i=1}^{n}{\Big(\frac{\hat{y}_i -y_i}{\sigma_i}\Big)^2}}$$

