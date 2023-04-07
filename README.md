# Fraud-Detection-Analysis-for-Banking-Transactions
This Python script aims to predict fraudulent activity in banking transactions using a dataset of credit card transactions. It uses a logistic regression model to identify the fraudulent transactions.
This Python script aims to predict fraudulent activity in banking transactions using a dataset of credit card transactions. It uses a logistic regression model to identify the fraudulent transactions.

The process can be explained as follows:

Import the necessary libraries, including pandas, numpy, seaborn, matplotlib.pyplot, and scikit-learn.

Load the credit card transaction dataset into a pandas DataFrame.

Explore the dataset by printing the first few rows of the data, obtaining summary statistics with the describe() method, and checking for any missing values in the dataset.

Visualize the distribution of the classes (fraudulent vs. non-fraudulent transactions) using a count plot.

Create a correlation matrix to determine any correlation between the features of the dataset. This is achieved by using a heatmap plot.

Use box plots to compare the distribution of amounts for fraudulent and non-fraudulent transactions.

Visualize the distribution of time by plotting a histogram.

Use histograms to plot the distribution of each feature in the dataset.

Split the dataset into training and testing sets.

Create a logistic regression model.

Train the model on the training data.

Predict the classes of the test data using the trained model.

Evaluate the accuracy of the model by calculating the accuracy score, the confusion matrix, and the classification report.

The final result of this process is a logistic regression model that can be used to detect fraudulent activity in banking transactions with high accuracy. By using this model, banks can reduce their losses from fraudulent activities and increase overall fraud prevention.
