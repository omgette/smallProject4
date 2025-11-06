# Predicting Cardiovascular Disease Risk Using Spark-Based Classification
This project explores the use of distributed machine learning with Apache Spark to predict cardiovascular disease risk based on patient health metrics. Accurate prediction of cardiovascular outcomes is very important for early intervention, personalized treatment planning, and public health resource optimization.

I am using the publicly available Kaggle Dataset [Cardiovascular Disease Dataset]([url](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)), which contains 70,000 patient records. This project demonstrates the power of big data analytics and parallel computation in clinical classification tasks. PySpark is used across multiple virtual machines to enable scalable preprocessing and statistical ML analysis.

# Overview
Cardiovascular disease remains one of the leading causes of death worldwide. Early detection through predictive modeling can significantly improve patient outcomes and reduce healthcare costs.

This project implements a Spark-based classification pipeline to predict the presence of cardiovascular disease using patient features such as age, blood pressure, cholesterol levels, and lifestyle indicators. The pipeline leverages distributed computing across one master node and one worker node to efficiently handle large amounts of data.

# Key Features
## Data Preprocessing

## Model Approaches

# Results

# Distributed Cluster Setup
To handle the dataset’s scale, the project was deployed on two virtual machines (VMs):
- 1 Master Node and 1 Worker Node

# Dataset
I found a dataset on Kaggle with 70,000 records of patient data on cardiovascular disease. It has 11 features plus a target variable.

Source: [Cardiovascular Disease Dataset]([url](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset))

Reference: Kaggle. (2018). Cardiovascular Disease Dataset (70,000 records of patient data) [Dataset]. Retrieved from https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset. 

# Methods Summary
## Preprocessing

## Modeling

# How to Run Project
## Prereqs
- Python 3.x
- Apache Spark installed on all VMs (/opt/spark)
- PySpark, NumPy, Pandas, Matplotlib, Seaborn

# Team Members
- Olivia Gette
