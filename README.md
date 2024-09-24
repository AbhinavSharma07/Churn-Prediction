# Telecom Churn Prediction 

## Overview
This project focuses on predicting customer churn for a telecom company using data from four consecutive months. The goal is to predict churn in the last month (September) using data from the first three months (June, July, August).

## Problem Definition
Churn is defined as customers who have stopped using the service (no calls, no internet usage) in the last month. The objective is to predict churn for **high-value customers** who generate the most revenue.

## Approach
1. **Data Preparation**: 
   - Derive new features using domain knowledge.
   - Filter **high-value customers** (top 30% based on recharge amounts in the first two months).
   - Tag churners based on the last month's activity.

2. **Modeling**: 
   - Preprocess data, reduce dimensionality (e.g., PCA), handle class imbalance, and train classification models.
   - Focus on identifying churners using metrics like precision-recall and F1 score.

## Dataset
- Download the dataset [here](https://drive.google.com/file/d/1SWnADIda31mVFevFcfkGtcgBHTKKI94J/view?usp=sharing).
- The dataset contains customer data for four months with attributes for usage, recharge, calls, and data.

## Business Impact
Predicting churn will help telecom companies reduce churn and retain high-value customers through preventive actions like special offers or discounts.

