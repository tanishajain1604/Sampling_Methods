# Sampling Methods

## Overview
In this section, various approaches to balancing a dataset through undersampling and oversampling are discussed. It demonstrates how different sampling methods can be applied to draw samples from a balanced population, and the results are evaluated using five different machine learning models. These models classify the data into two classes: 0 or 1.

The dataset is provided along with the solution file.

## Sampling Techniques
- Simple Random Sampling
- Systematic Sampling
- Stratified Sampling
- Cluster Sampling

## Machine Learning Models
Five machine learning models were utilized for the assignment:
1. Logistic Regression (M1)
2. Decision Trees (M2)
3. Random Forest (M3)
4. Naive Bayes (M4)
5. K Nearest Neighbours (M5)

## Output Table

| Sample            | logistic_regression_on_sample | decision_tree_on_sample | gaussian_nb_on_sample | random_forest_on_sample | knn_on_sample |
|-------------------|------------------------------|-------------------------|-----------------------|-------------------------|---------------|
| simple_sample     | 0.964401                     | 0.993528                | 0.796117              | 1.0                     | 0.977346      |
| stratified_sample | 0.964401                     | 1.0                     | 0.796117              | 1.0                     | 0.977346      |
| systematic_sample | 0.964401                     | 0.996764                | 0.796117              | 1.0                     | 0.977346      |
| cluster_sample    | 0.964401                     | 1.0                     | 0.796117              | 1.0                     | 0.977346      |
