## Credit-risk-classification

for this task I trained and assessed a loan risk-based model for this task using a variety of methodologies. I developed a model to determine the creditworthiness of borrowers using past lending data from a peer-to-peer lending services company.


## Split the Data into Training and Testing Sets

From the "loan status" column, I made a y label, and from the remaining columns in the DataFrame, I made a features X label.

## Create a Logistic Regression Model with the Original Data

I fitted the logistic regression model using the training data and my understanding of logistic regression. Using the testing feature data and the fitted model, I then recorded the predictions for the testing data labels.

I then calculated the model's accuracy score, produced a confusion matrix, and printed the classification report as seen below to assess the model's performance.

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%201.PNG)

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%202.PNG)

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%203.PNG)

## Predict a Logistic Regression Model with Resampled Training Data

In order to review the initial model for this section, I used RandomOverSampler to resample the training data. I then fitted the model and made predictions using the LogisticRegression and resampled data.

following with calculation of the model's accuracy score, produced a confusion matrix, and printed the classification report as seen below to assess the model's performance.

![]( https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%204.PNG)

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%205.PNG)

![](https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Images/Capture%206.PNG)


The Credit Risk Analysis Report 

Can be found on the link below

* [https://github.com/Gilaine-UOT/Credit-risk-classification/blob/main/Credit_Risk/Risk_Analysis_Report.md]


## References 

The purpose of the dataset is solely for educational reasons.



