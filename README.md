# Lasso-Ridge-and-Logistic-Regression

# Overview

This project focuses on analyzing the crime rate in the Boston dataset by building a binary response variable and applying logistic regression. The binary variable indicates whether the crime rate is above or below the median. Key perfromance metrics such as precision, recall, F1-score, and accuracy are calculated to evaluate the model's performance.

# Dataset

The dataset usedd in this analysis is the Boston dataset. It contains various features related to the housing and neighborhood characteristics in Boston, including crime rate, housing prices, and socioeconomic information.

<ins> Key Features </ins>

1. crime_above_median: A binary variable created to indicate if the crime rate is above the median (1) or below the median (0).

2. Other Features: Various other features from the Boston dataset that are used as predictors.

# Steps Performed

<ins> Data Loading and Preprocessing </ins>

1. The Boston dataset is loaded using Pandas

2. A new binary response variable crime_above_median is created.

<ins> Logistic Regression </ins>

1. A logistic regression model is trained to predict crime_above_median based on the features inthe dataset.

2. Pefromance metrics are calculated for both classes.

<ins> Performance Evaluation </ins>

1. Precision  (Class 0) : 0.78

2. Recall (Class 0) : 0.95

3. F1-Score (Class 0) : 0.86

4. Precision (Class 1) : 0.93

5. Recall (Class 1) : 0.74

6. F1-Score (Class 1) : 0.82

7. Overall Accuracy : 0.8421

# Results and Discussion

The logistic regression model performed well, achieving an accuracy of 84.21%. However, there is a slight imbalance in the precision and recall scores for both classes, which could be addressed in future iterations.

# Conclusion

This assignment demonstrates how logistic regression can be applied to classify crime rates based on neighborhood data.
