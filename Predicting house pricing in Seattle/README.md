# Predicting house pricing in Seattle

In this project, I implemented learning algorithms "from scratch" by using a **Tensorflow** framework and coded them in **object oriented programming** as shown in [Regression.py](https://github.com/hsuanhao/Projects/blob/master/Predicting%20house%20pricing%20in%20Seattle/Regression.py). I used data on house sales, located in Seattle, in King County to predict house prices by implementing various models to improve the precision of predictions:

- **Cycle 1**. [Simple Linear Regression](https://github.com/hsuanhao/Projects/blob/master/Predicting%20house%20pricing%20in%20Seattle/Simple_Linear_Regression.ipynb), including one feature only
- **Cycle 2**. Multiple Regression by using [closed form](https://github.com/hsuanhao/Projects/blob/master/Predicting%20house%20pricing%20in%20Seattle/Multiple_Regression_Closed_Form.ipynb) and [gradient descent algorithm](https://github.com/hsuanhao/Projects/blob/master/Predicting%20house%20pricing%20in%20Seattle/Simple_or_Multiple_Regression_GradientDescent.ipynb)
- **Cycle 3**. Polynomial Regression
- **Cycle 4**. Ridge Regression
- **Cycle 5**. LASSO to select features
- **Cycle 6**. k-nearest Neighbors Regression

## Datasets
- kc_house_data.csv: whole data set
- kc_house_test_data.csv: test set
- kc_house_test_data.csv: training set

## Files
- Regression.py: library for linear regression with generalized features by gradient descent or closed form
- FeatureProcessing.py: module including functions to rescale values of features or convert Pandas Dataframe to numpy array

## Requirements

Python packages:
- Python3
- Jupyter Notebook
- Tensorflow
- Pandas
- Numpy
- Matplotlib
- seaborn
