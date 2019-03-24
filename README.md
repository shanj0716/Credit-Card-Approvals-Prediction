# Credit-Card-Approvals-Prediction
Building a logistic regression model to predict if a credit card application will get approved.

## Project Description

Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming. Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. 

In this project, we build an automatic credit card approval predictor using machine learning techniques.The dataset used in this project is from the [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/credit+approval). The process of work is as follows:
1) loading and viewing the dataset;
2) handling missing data and perprocessing data for modeling;
3) building a logistic regression model, making prediction and evaluating performance with accuracy(84.6%) and confusion matrix;
4) fine-tuning the parameters using GridsearchCV to find the best model (impove accuracy by 0.5%).

Ipython notebook used can be found [here](https://github.com/shanj0716/Credit-Card-Approvals-Prediction/blob/master/credit-card-approvals.ipynb).
