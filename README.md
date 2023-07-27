Overview:
In this project with the knowledge of Python and Supervised Machine learning techniques a model has been build to train and evaluate the loan risk. In order to identify the creditworthiness of borrowers a historical dataset from peer-to peer lending services company has been abstract. 

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

