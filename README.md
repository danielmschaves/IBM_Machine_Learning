# About This Repository

In this repository, I have created a Jupyter Notebook where I implemented some of the popular classification algorithms that I learned during my data science course.

- Importing the Required Libraries
- Importing the Dataset
- Data Preprocessing
- Training Data and Test Data
- Linear Regression
- Decision Tree
- Logistic Regression
- SVM
- Report

## Phases
- Import the required libraries
- Importing the Dataset
- Data Preprocessing
- Linear Regression
    - Use the train_test_split function to split the features and Y dataframes with a test_size of 0.2 and the random_state set to 10.
    - Create and train a Linear Regression model called LinearReg using the training data (x_train, y_train).
    - Now use the predict method on the testing data (x_test) and save it to the array predictions.
    - Using the predictions and the y_test dataframe calculate the value for each metric using the appropriate function.
    - Show the MAE, MSE, and R2 in a tabular format using data frame for the linear model.
    
- KNN
    - Create and train a KNN model called KNN using the training data (x_train, y_train) with the n_neighbors parameter set to 4.
    - Now use the predict method on the testing data (x_test) and save it to the array predictions.
    - Using the predictions and the y_test dataframe calculate the value for each metric using the appropriate function.
    - 
- Decision Tree
    - Create and train a Decision Tree model called Tree using the training data (x_train, y_train).
    - Now use the predict method on the testing data (x_test) and save it to the array predictions.
    - Using the predictions and the y_test dataframe calculate the value for each metric using the appropriate function.
    
- Logistic Regression
    - Use the train_test_split function to split the features and Y dataframes with a test_size of 0.2 and the random_state set to 1.
    - Create and train a LogisticRegression model called LR using the training data (x_train, y_train) with the solver parameter set to liblinear.
    - Now, use the predict method on the testing data (x_test) and save it to the array predictions.
    - Using the predictions and the y_test dataframe calculate the value for each metric using the appropriate function.
    
- SVM
    - Create and train a SVM model called SVM using the training data (x_train, y_train).
    - Now use the predict method on the testing data (x_test) and save it to the array predictions.
    - Using the predictions and the y_test dataframe calculate the value for each metric using the appropriate function.
    
-Report
    - Show the Accuracy, Jaccard Index, F1-Score, and LogLoss in a tabular format using data frame for all of the above models.

## Conclusion

In this project, we explored various classification algorithms for predicting whether it will rain tomorrow based on the weather conditions of the current day. We used a dataset that contained observations of weather metrics for each day from 2008 to 2017. We performed one-hot encoding to convert categorical variables to binary variables and replaced the values of the 'RainTomorrow' column, changing them from a categorical column to a binary column.

We then used the following classification algorithms:

- Linear Regression
- K-Nearest Neighbors (KNN)
- Decision Trees
- Logistic Regression
- Support Vector Machines (SVM)

We evaluated the performance of each algorithm using the following metrics: Accuracy Score, Jaccard Index, F1-Score, and LogLoss (only for Logistic Regression).

Here is a summary of the results:

| Model	Accuracy | Score |	Jaccard Index	| F1-Score | Log-Loss |
| -------------- | ----- | ---------------| ---------| ---------|
| KNN	| 0.8183 |  0.4251	| 0.5966	| NaN |
| Decision Tree	| 0.7527	| 0.3955	| 0.5668	| NaN |
| Logistic Regression	| 0.8351	| 0.5046	| 0.6707	| 5.6950 |
| SVM |	0.8377	| 0.5012	| 0.6713	| NaN |

We can see that the SVM and Logistic Regression models had the best accuracy scores, with SVM having the highest Jaccard Index and Logistic Regression having the highest F1-Score. The Logistic Regression model also had the lowest Log-Loss score.

In conclusion, based on our evaluation metrics, the SVM and Logistic Regression models are the most effective in predicting whether it will rain tomorrow based on the weather conditions of the current day.
