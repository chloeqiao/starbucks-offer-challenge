# starbucks-offer-challenge
This is the capstone project for AWS MLE NadoDegree, it contains two notebooks, `The main target is to make promotion offer events more effective` and `train_and_deploy.ipynb`, and you can also find html version here. The first one is for data analysis and processing, including one basline model, it can run locally or on AWS Sagemaker. The second one runs on AWS Sagemaker, which train XGBoost classifier and deploy an endpoint. There are three original json files provided by the program. You can also find sagemaker profiler report and xgboost training report in this repo.
<br> </br>
Libraries needed: pandas, numpy, json, sklearn, os, boto3, s3fs, datetime, sagemaker
<br> </br>
