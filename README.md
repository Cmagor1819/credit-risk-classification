# credit-risk-classification

# Objective:

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

# Part 1:

To setup and start the code, we must import all of the necessary dependencies to work with the models and functions.

# Part 2:

This sections purpose is to read in the CSV file and transform into a pandas DataFrame and review it.

# Part 3: 

In this section, we start by seperating the labels (y variable) and the features (X variable) from the DataFrame so we can review them and work with them.

# Part 4: 

For the next section, we import the train_test_split module from sklearn, then we split the data into training and testing data, and assign a random_state variable of 1 to the function.

# Part 5:

Here we import the LogisticRegression module so we can instantiate the model and assign a random_state of 1 to the model as well. Next, we make predictions using the testing data and review the DataFrame and finally generate a confusion matrix for the model to evaluate the performance and a classification report to see what is happening.

# Part 6:

For the final section, we answer the analysis question of 'How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?'

# I got/referenced the following lines of code from Xpert Learning Assistant/GitHub:

* y = lending_df['loan_status'].ravel()

* matrix_confusion = confusion_matrix(y_test, predictions)
confusion_df = pd.DataFrame(matrix_confusion, index=['Actual 0', 'Actual 1'], columns=['Predicted 0', 'Predicted 1'])
