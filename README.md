# Credit Rating Model for Loan Lenders

This project aims to build a credit rating model using various machine learning algorithms to help loan lenders (banks) balance two conflicting goals:

→ Issuing as many loans as possible to generate revenue through fees and interest.

→ Minimising the issuance of loans to individuals who are unlikely to repay, thereby avoiding potential losses and collection costs.

# Project Overview

Using the Lending Club loan data, we developed a model to find an optimal tradeoff between maximising good loans and minimising bad loans.

# Data Preparation and Preprocessing 

→ Data Collection: Acquired Lending Club loan data.

→ Data Cleaning: Removed irrelevant or missing data.

→ Feature Engineering:

- Binary Target Creation: Created a binary target variable indicating loan repayment status.
- Label Encoding: Applied label encoding to categorical features.
- One-Hot Encoding: Applied one-hot encoding to nominal categorical features.
- Scaling: Scaled numerical features for model compatibility.

→ Train/Test Split: Split the data into training and testing sets to evaluate model performance.

# Model Training and Tuning

We trained and tuned the following models:

→ SGD Classifier: Stochastic Gradient Descent Classifier.

→ Random Forest Classifier: An ensemble learning method using multiple decision trees.

→ Gradient Booster Classifier: An ensemble technique that builds models sequentially to reduce errors.

# Model Evaluation

For each model, we calculated the following metrics to evaluate performance:

→ Accuracy: Proportion of correctly classified instances.

→ Precision: Proportion of true positive instances among the instances classified as positive.

→ Recall: Proportion of true positive instances among all actual positive instances.

→ F1-Score: Harmonic mean of precision and recall.

→ Area Under the ROC Curve (AUC): Measures the ability of the model to distinguish between classes.

→ Average Precision (AP): Precision averaged over all recall levels.

# Results

By comparing these metrics across models, we suggested the most useful credit rating model for banks to use, striking a balance between maximising good loans and minimising bad loans.

![Recall](https://github.com/Avinash3570/Credit-Rating-Project/assets/155007765/9355e710-7a1b-4f3e-8e57-f11ef1191992)
![Precision](https://github.com/Avinash3570/Credit-Rating-Project/assets/155007765/3fa28d65-6ac3-4348-b236-3b543d5eb916)
![F1-Score](https://github.com/Avinash3570/Credit-Rating-Project/assets/155007765/e266ca40-fbf2-40d0-a236-85e4719cdae4)
![AUC](https://github.com/Avinash3570/Credit-Rating-Project/assets/155007765/ede8200f-4840-423b-a6e4-ffe78635b942)
![AP](https://github.com/Avinash3570/Credit-Rating-Project/assets/155007765/c9c357c6-875e-4574-b9bc-3f32b943bfc5)
![Accuracy](https://github.com/Avinash3570/Credit-Rating-Project/assets/155007765/574dffaa-8698-43c7-9452-92abdfb986fe)
