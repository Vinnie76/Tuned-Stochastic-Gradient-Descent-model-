# Tuned-Stochastic-Gradient-Descent-model
## Description
The repository hosts the tuned Stochastic Gradient Descent model and its comparison with the Random Forest model. 
### 1. Data Preparation 

#### 1.1 Read Data 

To train the model, you must first load the entire data. 

Remember to split the data before cleaning and pre-processing to avoid leakages. 

#### 1.2 Clean Data 

Clean the training set by handling missing/incorrect values. 

#### 1.3 Feature Engineering 

Create new features to help improve model performance. 

#### 1.4 Feature Scaling 

Scale features to similar scales to make it easier for the model to understand/interpret and handle the data. 

### 2. Model Training 

Here you test the performance on a Stochastic Gradient Descent model compare its performance with the Random Forest model from the previous sections. 

**Import the model from the sci-kit (sklearn) library** and build and evaluate your initial model on your training set. 

Use the cross-validation method to ensure that your initial evaluation results aren’t from an overfit model. 

### 3. Model Tuning 

Tune your model by specifying parameters with Grid Search or a range of values with Randomised Search. 

### 4. Model Testing 

At last! You are now ready to test your model. 

Note: Before you use your model ensure that your data is in the right shape (i.e., Properly split into features and labels with the same number of feature columns) 

#### 4.1 Load Model 

Load the best estimator from the tuning step and evaluate that model. 

#### 4.2 Predict Values 

Make predictions with your model based on your test dataset. 

#### 4.3 Evaluate Model 

Check the RMSE based on the values your model predicted and the actual values from the test dataset. 

### 5. Compare Models 

Compare the results from the Stochastic Gradient Descent model with the results from the Random Forest model.  