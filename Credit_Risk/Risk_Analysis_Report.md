
# Credit Risk Analysis Report

## Analysis Overview

The goal of this study is to utilize machine learning to forecast the creditworthiness of a prospective borrower by predicting whether they are healthy (low-risk) or unhealthy (high-risk) when granted a loan. The analysis employs a dataset of past lending activity from a peer-to-peer lending services company. The researcher's objective was to estimate the number of low-risk and high-risk loans anticipated and actualized by creating a confusion matrix based on various variables. Additionally, the accuracy scores and recall were used to assess the ability of the models to differentiate between low-risk and high-risk borrowers.

## Results

## Machine Learning Model 1

Balanced Accuracy Score

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%201.PNG)

Confusion Matrix

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%202.PNG)

Classification Report

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%203.PNG)

The initial model exhibits a balanced accuracy score of nearly 95%, but it is more proficient in forecasting low-risk loans rather than high-risk loans. The model's recall value for healthy loans is 0.99, indicating that it accurately predicts 99% of healthy loans. On the other hand, the recall value for unhealthy loans is 0.91, indicating that it accurately predicts 91% of unhealthy loans. When analyzing the confusion matrix, it is evident that there were 56 false positives and 102 false negatives.


## Machine Learning Model 2

Balanced Accuracy Score

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%204.PNG)

Confusion Matrix

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%205.PNG)

Classification Report

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%206.PNG)

The second model has a balanced accuracy score of around 99%, which is also reflected in the recall score of 0.99 for both low-risk and high-risk loans. The second model performs better than the first model in predicting high-risk loans. However, the confusion matrix shows that there were 4 cases of false positives and 116 cases of false negatives.

## Summary 

The second model is the most suitable for predicting high-risk loans based on its balanced accuracy score and recall, while both the first and second models perform similarly for predicting low-risk loans. Even though the second model has a slightly higher number of false negatives according to the confusion matrix, it has significantly fewer false positives. Hence, I would suggest utilizing Model 2, which is the logistic regression model developed using oversampled data.


