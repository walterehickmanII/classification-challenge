# classification-challenge
# Module 13
Spam Detection Classification Challenge
Background
You work at an Internet Service Provider (ISP) and have been tasked with improving the email filtering system for its customers. The goal is to develop a supervised machine learning (ML) model that accurately detects spam emails using a provided dataset. The dataset contains information about emails classified as either spam or not spam. You will create two classification models, logistic regression and random forest, and evaluate their accuracy in detecting spam.

# Files
Download the following files to get started:

### Module 13 Challenge files
# Before You Begin
Create a new repository for this project called classification-challenge. Do not add this assignment to an existing repository.
Clone the new repository to your computer.
Inside your local Git repository, add the starter file spam_detector.ipynb from your file downloads.
Push these changes to GitHub or GitLab.
# Instructions
This challenge consists of the following subsections:

Split the data into training and testing sets.
Scale the features.
Create a logistic regression model.
Create a random forest model.
# Evaluate the models.
1. Split the Data into Training and Testing Sets
Open the starter code notebook and follow these steps:

Read the data from spam-data.csv into a Pandas DataFrame.
In the appropriate markdown cell, make a prediction as to which model you expect to do better.
Create the labels set (y) from the “spam” column, and then create the features (X) DataFrame from the remaining columns.
Note: A value of 0 in the “spam” column means that the message is legitimate. A value of 1 means that the message has been classified as spam.
Check the balance of the labels variable (y) by using the value_counts function.
Split the data into training and testing datasets using train_test_split.

2. Scale the Features
Create an instance of StandardScaler.
Fit the StandardScaler with the training data.
Scale the training and testing features DataFrames using the transform function.

3. Create a Logistic Regression Model Fit a logistic regression model using the scaled training data (X_train_scaled and y_train). Set the random_state argument to 1.
Save the predictions on the testing data labels using the testing feature data (X_test_scaled) and the fitted model.
Evaluate the model’s performance by calculating the accuracy score of the model.

4. Create a Random Forest Model Fit a random forest classifier model using the scaled training data (X_train_scaled and y_train).
Save the predictions on the testing data labels using the testing feature data (X_test_scaled) and the fitted model.
Evaluate the model’s performance by calculating the accuracy score of the model.

5. Evaluate the Models In the appropriate markdown cell, answer the following questions:

Which model performed better? How does that compare to your prediction?
# Conclusion
By following the above steps, you will develop two classification models to detect spam emails and evaluate their performance. This project will help improve the email filtering system for the ISP's customers, ensuring that their inboxes remain free of spam.
