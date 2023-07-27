Overview:
The main purpose of this analysis is to build the model to predict creditworthiness of the browers. In order to conduct annalysis we have used the dataset form peer-to-peer lending service company which includes various featues such as; 	loan size,	interest rate,	borrower income,	debt_to_income,	num_of_accounts,	derogatory_marks,	total_debt based on which loan status is identified. The intregated algorithm is logistic regression has the purpose of the model is to determine whether a loan to the borrower in the testing set would be low or high risk.  

Scope: 
While building the model we have used panda to scale/preprocessing,  manipulation and analysis the data, pathlib from Python to create the path to resources, numpy form Python to create array, Sklearn metrics from Python to annalyse model performance by producing confusion metrix and classification report .

Tasks Performed:
Create the label set y (dependent variable) from loan_status columns and then the x (features/ independent variable) from the remaining columns of the DataFrame.
Y = loan status
X = remaining features in the data frame that impact on y. 

Split the data into training and testing the datasets by using train test and split function. 
By importing the train_test_split function from sklearn model selection, the data has been split to train and test sets. 

Creating the Logistic Regression Model with the Original data 
Logistic Regression algorithm is used to train the model with hyper parameter. Then train dataset has been fit into the model. 

The predictions are tested using the train set and saved in the variable named prediction. 

Evaluating the Model’s Performance by:
Confusion Matrix:


Classification Report: 

Confusion Matrix:
https://github.com/Bar89bas/Credit-risk-classification/issues/2

Classification Report:
https://github.com/Bar89bas/Credit-risk-classification/issues/1

The classification report for Machine Learning means:

Precision: 
For class 0: Precision is 1.00, which means that out of all the samples predicted as class 0, all of them are true positives. The model has a perfect precision for class 0.
For class 1: Precision is 0.85, which means that out of all the samples predicted as class 1, 85% of them are true positives, while 15% are false positives.

Recall:
For class 0: Recall is 0.99, which means that out of all the actual samples that belong to class 0, the model correctly identifies 99% of them as true positives, while 1% of class 0 samples are incorrectly predicted as class 1 (false negatives).
For class 1: Recall is 0.91, which means that out of all the actual samples that belong to class 1, the model correctly identifies 91% of them as true positives, while 9% of class 1 samples are incorrectly predicted as class 0 (false negatives).

F1-Score: 
For class 0: The F1-score is 1.00, which is the harmonic mean of precision and recall for class 0. Since precision and recall are both very high (close to 1), the F1-score is also very high.
For class 1: The F1-score is 0.88, which indicates a good balance between precision and recall for class 1.

Support:
For class 0: The support is 18765, which means there are 18765 samples in the dataset that belong to class 0.
For class 1: The support is 619, indicating there are 619 samples in the dataset that belong to class 1.

Accuracy:
The overall accuracy of the model is 0.99, which means that it correctly classifies 99% of all samples in the dataset.

Summary
Based on the confusion matrix, the regression model is able to perform well, especially for class healthy loan, where it achieves almost perfect precision, recall, and F1-score. For class high-risk loan, the performance is also quite good, with a lower F1-score compared to class healthy loan but still showing a reasonably balance trade-off between precision and recall. 
