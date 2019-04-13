# Data-Preprocessing
The goal of this article is a practical Guide on Data Preprocessing in Python using Scikit Learn.Learning algorithms have affinity towards certain data types on which they perform incredibly well. They are also known to give reckless predictions with unscaled or unstandardized features. Algorithm like XGBoost, specifically requires dummy encoded data while algorithm like decision tree doesn’t seem to care at all (sometimes)!

In simple words, pre-processing refers to the transformations applied to your data before feeding it to the algorithm. In python, scikit-learn library has a pre-built functionality under sklearn.preprocessing. There are many more options for pre-processing which we’ll explore.For this article, I have used a subset of the Loan Prediction (missing value observations are dropped) data set from You can download the final training and testing data set.
