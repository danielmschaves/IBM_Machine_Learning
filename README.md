# About This Repository

In this repository, I have created a Jupyter Notebook where I implemented some of the popular classification algorithms that I learned during my data science course.

- Steps Included
- Importing the Required Libraries
- Importing the Dataset
- Data Preprocessing
- Training Data and Test Data
- Linear Regression
- Decision Tree
- Logistic Regression
- SVM
- Report

## Let's dive into each step in detail:

1. Importing the Required Libraries:
In this step, I have imported the necessary libraries required to implement the classification algorithms.

2. Importing the Dataset:
In this step, I have imported the weatherAUS.csv dataset that contains the observations of weather metrics for each day from 2008 to 2017. The dataset has additional columns like 'RainToday' and the target variable is 'RainTomorrow'.

3. Data Preprocessing:
In this step, I have performed data preprocessing tasks such as checking for missing values, handling categorical variables, feature scaling, etc.

4. Training Data and Test Data:
In this step, I have split the dataset into training data and testing data using the train_test_split function from Scikit-learn. I have used 70% of the data for training and 30% of the data for testing.

5. Linear Regression:
In this step, I have implemented the Linear Regression algorithm to predict whether it will rain tomorrow or not. I have evaluated the model using various evaluation metrics such as Accuracy Score, Jaccard Index, F1-Score, LogLoss, Mean Absolute Error, Mean Squared Error, and R2-Score.

6. Decision Tree:
In this step, I have implemented the Decision Tree algorithm to predict whether it will rain tomorrow or not. I have evaluated the model using various evaluation metrics such as Accuracy Score, Jaccard Index, F1-Score, LogLoss, Mean Absolute Error, Mean Squared Error, and R2-Score.

7. Logistic Regression:
In this step, I have implemented the Logistic Regression algorithm to predict whether it will rain tomorrow or not. I have evaluated the model using various evaluation metrics such as Accuracy Score, Jaccard Index, F1-Score, LogLoss, Mean Absolute Error, Mean Squared Error, and R2-Score.

8. SVM:
In this step, I have implemented the SVM algorithm to predict whether it will rain tomorrow or not. I have evaluated the model using various evaluation metrics such as Accuracy Score, Jaccard Index, F1-Score, LogLoss, Mean Absolute Error, Mean Squared Error, and R2-Score.

9. Report:
In this step, I have generated a report using the models that we created in the previous steps. The report includes various evaluation metrics for each model and the comparison of their performance.

Conclusion

In this project, we explored various classification algorithms for predicting whether it will rain tomorrow based on the weather conditions of the current day. We used a dataset that contained observations of weather metrics for each day from 2008 to 2017. We performed one-hot encoding to convert categorical variables to binary variables and replaced the values of the 'RainTomorrow' column, changing them from a categorical column to a binary column.

We then used the following classification algorithms:

Linear Regression
K-Nearest Neighbors (KNN)
Decision Trees
Logistic Regression
Support Vector Machines (SVM)
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
