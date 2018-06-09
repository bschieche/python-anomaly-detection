# Using object orientation for anomaly detection

This Python3 notebook was written to become familiar with **object orientation in Python**. It shows how to possibly implement an anomaly detector class using **multivariate Gaussians** to represent the training data. It is assumed that the training data isn't labeled. A second data set, which is assumed to be labeled, is used for cross validation, namely to find the best possible threshold to mark an observation as an anomaly / outlier. The performance measure, used, is the **F1 score**.

You will find the following sections:

* Function definitions to evaluate the multivariate normal distribution density, to calculate a performance measure, and to find the best threshold for a given cross validation set.
* 2 class definitions: one that inherits from pandas.DataFrame and adds some small new functionality and one main class that implements properties and methods for initialization, learning, reporting, and plotting for the anomaly detection model.
* Computational results for a small server response dataset with 2 features
* Computational results for a credit card fraud dataset found on kaggle: https://www.kaggle.com/mlg-ulb/creditcardfraud/data

For an improved view please use the following nbviewer URL:

https://nbviewer.jupyter.org/github/bschieche/python-anomaly-detection/blob/master/anomaly_detection.ipynb
