# Assignment_2_Sampling
Submitted by: Sanjana Sinha  
Roll No: 102103040  
Group: 3COE2

## Dataset
The dataset comprises 31 columns and 772 entries, with a target variable labeled 'Class'. This variable is binary, taking on values of '0' or '1'. The dataset is imbalanced, with 763 entries classified as Class '0' and only 9 entries as Class '1'.

## Balancing the Dataset
The RandomOverSampler approach is used to balance this dataset. RandomOverSampler works by generating new samples by randomly sampling with replacement the current available samples. The synthetic points are added between the chosen point and its neighbors. After balancing the dataset, there are 763 entries each of Class '0' and '1'.

## Creating 5 Samples
The Simple Random, Systematic, Stratified, Cluster and Bootstrap Sampling Techniques are used.

## Models Used
 
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Support Vector Classifier
5. Gradient Boosting Classifier.

## Table

<img width="359" alt="image" src="https://github.com/SanjanaSinha1/Assignment_Sampling/assets/100065115/dcc3c13b-9f89-47ab-9733-37054597b089">

## Result  

Systematic Sampling Technique and Random Forest Classifier had the best accuracy.

## Graph 

![image](https://github.com/SanjanaSinha1/Assignment_Sampling/assets/100065115/cc4211f2-b0e3-4b12-8cac-5359b4f175e6)


