# AIA-Capstone-2024
Hello and welcome to the Capstone project for AI Academy bootcamp by Group 8. Our goal with this project was to create a predictive model that can be acccuratly used by credit servicers to detect if a credit acrd transaction is fraudulant or not using a Kaggle dataset. We tested variouse analytical techniques including Principle Component Analysis(PCA). Linear Regression, and a couple different Decision Tree Regression models. We settled on a Decision tree Regression model optimized using SMOTE to handle our imbalanced dataset.

# Project Objective
- Build a predictive model to detect the likelihood of a transaction being fraudulent
- Experiment with various machine learning techniques to classify fraudulent and nonfraudulent transactions
- Test different ways to handle the imbalanced dataset

### Project Approach

1. **Find a dataset**: We used Kaggle to find a dataset that fit the problem we wanted to solve.
2. **Exploratory Data Analysis**: Combed through the dataset to get an understading of the data we were working with and how to best go about creating a model.
3. **Data Preparation**:
 - Clean the data
 - Normalize and Standardize the dataset
 - Add a unique ID in the form of transaction numbers to each of the records

1. **Model Selection**: Various machine learning models are defined including:
   - Logistic Regression
   - Decision Trees
   - Principal Component Analysis (PCA)
  
2. **Handling Imbalance using Oversampling Techniques**: Used SMOTE to handle class imbalance within our dataset
3. **Model Training**: The models were trained using cross-validation both with and without SMOTE
3. **Prediction**: The models were introduced to testing data which were transactions different from the ones they were tested on.
4. **Model Tuning**: After we analyzed the predictions given by each model we tuned the model to better fit our objective. for the decision tree we pruned the leaves of the tree in an attempt to give us a more accurate result. 
