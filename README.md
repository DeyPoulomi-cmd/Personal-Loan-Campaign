
AllLife Bank - Personal Loan Prediction

Project Overview

This project focuses on building a predictive model for AllLife Bank, a US-based bank aiming to expand its customer base for personal loans. The goal is to identify liability customers (depositors) with a high probability of purchasing personal loans, enabling better-targeted marketing campaigns.

Problem Statement

AllLife Bank wants to increase its asset customer base by converting liability customers into personal loan customers while retaining them as depositors. The marketing team seeks a machine learning model to:

Predict whether a customer will accept a personal loan offer.

Identify the key attributes influencing customer decisions.

Determine the most lucrative customer segments for targeted campaigns.


##Key Steps

####Data Exploration and Preparation

Loaded and inspected the dataset to ensure completeness and correctness.

Performed sanity checks to identify missing or inconsistent values.

Examined data distribution, summary statistics, and data types.

####Feature Engineering

Identified relationships and patterns in data to create meaningful features.

Checked the importance of each feature in influencing the target variable (Personal_Loan).

##Model Development

Used a Decision Tree Classifier to build the prediction model.

Split the data into training and testing sets for evaluation.

####Evaluated model performance using key metrics such as:

Accuracy

Precision

Recall

F1 Score

##Confusion Matrix

Insights and Recommendations

Derived actionable insights from the model.

Recommended strategies to target high-potential customers effectively.

##Installation

To run this notebook, you need the following dependencies:

Python 3.7+

Jupyter Notebook or Google Colab

##Libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn

##How to Use

Clone or download this repository.

Open the notebook AIML_ML_Project_full_code_PD_notebook.ipynb.

Run the cells sequentially to:

Load the dataset.

Explore and preprocess data.

Train the machine learning model.

Evaluate the results.

Interpret the outputs and visualizations to understand key findings.

##Results and Observations

The model accurately identifies high-potential customers for personal loans.

Features such as Income, Education, and Credit Card Usage play significant roles in determining customer behavior.

Targeting customers with high credit card spending and advanced education can yield better conversion rates.

##Future Scope

Experiment with other algorithms like Random Forest and Logistic Regression for better accuracy.

Perform hyperparameter tuning to optimize the Decision Tree model.

Extend the model to include time-based campaign performance tracking.

##Author: Poulomi DeyInstitution: UT AUSTIN, mentored by Great learningPurpose: Final Machine Learning Project
