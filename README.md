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

1. Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

<img width="776" alt="image" src="https://user-images.githubusercontent.com/116701851/235831039-5f51b773-2783-41a1-a2d4-e13784555090.png">

2. Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

<img width="773" alt="image" src="https://user-images.githubusercontent.com/116701851/235831220-6ad85ae9-2e21-4922-ab5d-e116cc7da332.png">


3. Split the data into training and testing datasets by using train_test_split.

<img width="690" alt="image" src="https://user-images.githubusercontent.com/116701851/235831767-8b21ee6b-d065-4b49-bb6c-a017a2c3abfc.png">

## Create a Logistic Regression Model with the Original Data

By using logistic regression to complete the following steps:

1. Fit a logistic regression model by using the training data (X_train and y_train).

<img width="458" alt="image" src="https://user-images.githubusercontent.com/116701851/235832139-889b101b-c616-47d0-8266-025b70dd7e88.png">

2. Saved the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

<img width="391" alt="image" src="https://user-images.githubusercontent.com/116701851/235832195-54c0efa7-8458-47b8-9902-b8d4fd84946e.png">

3. Evaluated the model’s performance by doing the following:

. Calculate the accuracy score of the model.

. Generate a confusion matrix.

. Print the classification report.

<img width="391" alt="image" src="https://user-images.githubusercontent.com/116701851/235832541-4c28e05d-cf91-40b4-ba2c-452c1d11500f.png">

<img width="213" alt="image" src="https://user-images.githubusercontent.com/116701851/235832582-8f5eb336-e32b-45b2-9aa1-97658fcad4b0.png">

<img width="574" alt="image" src="https://user-images.githubusercontent.com/116701851/235832647-fc5a3d61-9507-4aff-b6c5-3ce6fe8ecae3.png">


Answer the following question: 

How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?
Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

<img width="807" alt="image" src="https://user-images.githubusercontent.com/116701851/235832736-b075cb06-7ca3-44e5-a3bf-470506af6147.png">

## Predicted a Logistic Regression Model with Resampled Training Data¶

Step 1: Using the RandomOverSampler module from the imbalanced-learn library to resample the data. Be sure to confirm that the labels have an equal number of data points.¶

<img width="344" alt="image" src="https://user-images.githubusercontent.com/116701851/235833162-6ea47a76-ea7e-4a69-ae7f-e7fce2273a60.png">

Step 2: Using the LogisticRegression classifier and the resampled data to fit the model and make predictions.¶

Step 3: Evaluated the model’s performance by doing the following:

. Calculate the accuracy score of the model.

<img width="389" alt="image" src="https://user-images.githubusercontent.com/116701851/235833383-163f3a07-647e-4a4b-98fb-8bf7edd86d13.png">


. Generate a confusion matrix.

<img width="172" alt="image" src="https://user-images.githubusercontent.com/116701851/235833501-e88f803d-5999-4a9b-b9d3-31ce5c747557.png">

. Print the classification report.

<img width="591" alt="image" src="https://user-images.githubusercontent.com/116701851/235833549-ddab225e-4d48-42c3-8187-5f8797d4f63e.png">


<img width="824" alt="image" src="https://user-images.githubusercontent.com/116701851/235833627-4bb7f3dd-65f4-427c-8e14-bc152a41b925.png">







