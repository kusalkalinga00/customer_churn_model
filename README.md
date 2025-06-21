# Customer Churn Prediction Model

This project provides an exploratory and visual analysis of customer churn data, aimed at predicting which customers are likely to leave a bank. The workflow is implemented in a Jupyter Notebook and covers data exploration, visualization, and preparation for modeling.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Features](#features)
- [Visualizations](#visualizations)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)

## Overview

Customer churn is when customers stop using a company's service. Predicting churn helps banks identify at-risk customers and take action to retain them.  
This project analyzes a bank's customer dataset, performing data exploration and visualization to understand the drivers of churn.

## Dataset

The dataset used is `Customer_Churn_Modelling.csv`, which contains the following columns:

- **RowNumber**
- **CustomerId**
- **Surname**
- **CreditScore**
- **Geography**
- **Gender**
- **Age**
- **Tenure**
- **Balance**
- **NumOfProducts**
- **HasCrCard**
- **IsActiveMember**
- **EstimatedSalary**
- **Exited** (Target: 1 if the customer left, 0 otherwise)

## Exploratory Data Analysis

The notebook performs:
- Loading and displaying the dataset
- Checking the distribution of the target variable (`Exited`)
- Analyzing feature distributions and their relation to churn

## Features

The following features are used for analysis:

- `CreditScore`: Customer’s credit score
- `Geography`: Country of the customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Tenure`: Years the customer has been with the bank
- `Balance`: Account balance
- `NumOfProducts`: Number of bank products the customer uses
- `HasCrCard`: Whether the customer has a credit card (1 = Yes, 0 = No)
- `IsActiveMember`: Whether the customer is an active member (1 = Yes, 0 = No)
- `EstimatedSalary`: Estimated annual salary

## Visualizations

The notebook includes visualizations such as:
- Churn distribution
- Categorical feature counts vs churn (Geography, Gender, NumOfProducts, HasCrCard, IsActiveMember, Tenure)
- Pairwise relationships between features and churn

## Requirements

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib

Install dependencies with:

```bash
pip install pandas numpy seaborn matplotlib
