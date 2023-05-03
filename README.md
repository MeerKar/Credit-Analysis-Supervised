# Credit-Analysis-Supervised

# Background

In this Project, various techniques is used  to train and evaluate a model based on loan risk. 
A dataset of historical lending activity from a peer-to-peer lending services company is used ,to build a model that can 
identify the creditworthiness of borrowers.

The  project is divided into the following subsections:

. Split the Data into Training and Testing Sets

. Create a Logistic Regression Model with the Original Data

. Predict a Logistic Regression Model with Resampled Training Data

. Write a Credit Risk Analysis Report

## Split the Data into Training and Testing Sets

Using the  starter code notebook  to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

<img width="776" alt="image" src="https://user-images.githubusercontent.com/116701851/235831039-5f51b773-2783-41a1-a2d4-e13784555090.png">

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

<img width="773" alt="image" src="https://user-images.githubusercontent.com/116701851/235831220-6ad85ae9-2e21-4922-ab5d-e116cc7da332.png">


Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Calculate the accuracy score of the model.

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

Write a Credit Risk Analysis Report
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

An overview of the analysis: Explain the purpose of this analysis.

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
