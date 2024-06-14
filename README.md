# AIA-Capstone-2024
Capstone project for AI bootcamp Group 8 

# Purpose
The project will review the data: https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud

Using the given variables, we will be able to help Discover discover patterns in credit card fraud. 

# Choosing the Data
This data was chosen for its size, recentness, and variable interpretability. 
The columns/variables are labeled in a manner that would be understood as to what it represented. There were many other data sets but they unfortunately did not have labeled columns and thus would have made it difficult to interpret and present as a solution to a hypothetical problem. 

# Notebook
Unfortunately, due to an error in creating the GitHub, all files used are located in the main branch. The important file with code that we would like to present is labeled as "Group 8 Final Code". 

In this code, you see that a basic EDA was ran to get initial thoughts on the data. 

Afterwards, it is clear that there is a clear class imbalance so SMOTE is the first step. 

The idea of using the PCA is that with 6 variables, two new variables "PC1" and "PC2" could be created to be used in future models. Unfortunately due to an error in interpretation and time, PCA was found to be useful but not used to run logistical regression and the decision tree. 

The next step was to run a logistical regression which did indeed produce nice metrics (accuracy, precision, recall, and F1), but the decision tree was decided given that recall was prioritized. 

Our reason for prioritizing recall was because given the nature of the probelem (finding positive cases), our model needed to be able to find true positives out of the true positives. It would be better to have the model mark a non-fraudulent case as fraudelent, rather than not flagging a fraudulent case as non- fraudulent. 
