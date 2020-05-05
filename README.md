# Payment Fraud Detection using linear models with Amazon Sagemaker

This repository contains code to train and deploy linear models with Amazon sagemaker to predict fraudulent payment transactions.

## General Project Outline

1. Loading and exploring the data
2. Splitting the data into train/test sets
3. Defining and training a LinearLearner, binary classifier
4. Making improvements on the model
5. Evaluating and comparing model test performance

The project will focus on making prediction improvements starting from a baseline model. Specifically, it will address techniques for:

- Tuning a model's hyperparameters and aiming for a specific metric, such as high recall or precision
- Managing class imbalance, which is when we have many more training examples in one class than another (in this case, many more valid transactions than fraudulent).
