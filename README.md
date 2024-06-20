# Analysis of Customer Response to Fixed Term Savings Account Campaign Based on Personal Characteristics

This project involves analyzing data from an international bank's campaign to promote a fixed-term savings account. The goal is to identify potential customers who would respond positively to the campaign by examining campaign contact information and customers' personal characteristics.

## Table of Contents

1. [Introduction](#introduction)
2. [Pre-processing](#pre-processing)
   - [Missing values](#missing-values)
3. [Explanatory Data Analysis](#explanatory-data-analysis)
4. [Binning Variables](#binning-variables)
5. [Merging and Splitting of Dataset](#merging-and-splitting-of-dataset)
6. [Response Model](#response-model)
   - [Initial Model](#initial-model)
   - [Final Model](#final-model)
   - [Impact of Variables](#impact-of-variables)
   - [Performance Metrics](#performance-metrics)
7. [Marketing Campaign](#marketing-campaign)
   - [Target Customers](#target-customers)
   - [Communication Channels](#communication-channels)
   - [Strategies](#strategies)
8. [Conclusion](#conclusion)
9. [Appendix](#appendix)

## Introduction

This project aims to analyze the data from an international bank's campaign to promote a fixed-term savings account. The primary objective is to identify potential customers who would respond positively to the campaign. The analysis involves building a predictive model to understand the factors influencing customer responses and to improve the effectiveness of future campaigns.

## Pre-processing

### Missing values

The campaign dataset and the personal dataset were checked for missing values and outliers. The campaign dataset had outliers in the contact method variable, while the personal dataset had outliers in the age and region variables. There were no missing values in either dataset.

## Explanatory Data Analysis

Descriptive statistics and visualizations were created to understand the distribution of key variables and to identify any patterns or anomalies in the data.

## Binning Variables

Continuous variables were binned using equal percentile intervals to handle skewed data effectively. This approach ensured balanced data distribution across all bins.

## Merging and Splitting of Dataset

The campaign and personal datasets were merged into a single dataset and then split into training and testing sets (70% training, 30% testing) to build and validate the predictive model.

## Response Model

### Initial Model

A logistic regression model was initially built to identify significant variables influencing customer responses. Some variables were found to be insignificant and were removed for further refinement.

### Final Model

The final logistic regression model included only significant variables, such as contact method, job type, marital status, education level, loan status, call duration, and balance. This model demonstrated a high level of accuracy and reliability.

### Impact of Variables

Significant variables in the final model were found to increase the likelihood of a positive response. For instance, contacting customers via phone or mobile, certain job types (retired, student), higher education levels, and loan status were linked to higher response probabilities.

### Performance Metrics

The final model was evaluated using various performance metrics, including ROC curve, AUC, and Precision-Recall curve. The model achieved an AUC of 0.839, indicating effective distinction between positive and negative responses.

## Marketing Campaign

### Target Customers

Based on the model's findings, the following customer segments are recommended for targeted marketing:
- Customers with mobile and telephone contact information.
- Retired individuals and students.
- Married customers.
- Customers with tertiary education.
- Financially stable customers with higher balances and loans.

### Communication Channels

Effective communication channels identified include:
- Mobile and telephone calls.
- Personalized email campaigns.
- Social media engagement.

### Strategies

Personalized customer engagement, multi-channel outreach, real-time monitoring, and feedback loops are recommended to optimize the marketing campaign and improve response rates.

## Conclusion

The analysis identified key factors influencing customer responses to the bank's fixed-term savings account campaign. The findings were used to develop targeted marketing strategies aimed at improving the effectiveness of future campaigns.

## Appendix

Contains additional tables, figures, and code used in the analysis.

