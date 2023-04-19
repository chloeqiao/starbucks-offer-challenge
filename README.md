# starbucks-offer-challenge
This is the capstone project for AWS MLE NadoDegree. The main target is to make promotion offer events more effective. 
### Project Motivation
The movitation of choosing this project is to build a machine learning model to solve real business problem efficiently and operationize the solution. Data in this project is interesting to manipulate with, and I wanted to predict the offer success given the customer/offer/transaction data. 
### Contents
Check `Proposal` for initial proposal of this project, and all details can be found in `Starbucks_Project_Report`. There are two Jupyter notebooks, `data_analysis_and_processing.ipynb` and `train_and_deploy.ipynb`, and you can find html version as well. The first one is for data analysis and processing, including one basline model, it can run locally or on AWS Sagemaker. The second one runs on AWS Sagemaker, which train XGBoost classifier and deploy an endpoint. You can also find sagemaker profiler report and xgboost training report in this repo. </br> 
There are three original json files provided by the program. Please unzip `data.zip` to extract. 
### Libraries needed
pandas, numpy, json, sklearn, os, boto3, s3fs, datetime, sagemaker
### Summary of the results
The final XGBoost classifier has a AUC score of 0.854, but still some space for improvement on false positive rate. According to the model, `total_amount`, `reward`, and `success_rate` are most important features.
### Acknowledgements
AWS Machine Learning Blog https://aws.amazon.com/blogs/machine-learning/utilizing-xgboost-training-reports-to-improve-your-models/?nc1=b_rp
