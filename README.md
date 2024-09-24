# Lead-Scoring

This repository presents the Lead Scoring Case Study, an academic project aimed at enhancing the lead conversion process for X Education, an online course provider. The project focuses on building a logistic regression model to score leads, helping the sales team target high-potential leads more effectively.

## Project Deliverables:
* Logistic Regression Model: Predicts the likelihood of lead conversion.
* Data Analysis: Employs statistical and machine learning techniques to analyze lead data.
* Business Insights: Provides actionable recommendations based on model outcomes.

## Problem Statement:
X Education generates leads through online platforms but struggles with a low conversion rate of 30%. The project’s goal is to create a model to identify "Hot Leads," aiming to increase the conversion rate to 80%.

## Goals:
* Logistic Regression Model: Develop a model to assign a lead score (0-100) that predicts conversion probability.
* Data Insights: Analyze the dataset to identify factors driving lead conversion and prioritize leads.
* Business Impact: Offer insights to improve sales focus and strategy.

## Dataset Description:
The dataset consists of around 9000 leads with features like:

* Lead Source: Origin of the lead (Google, referrals, etc.).
* Time on Website: Duration a lead spent on the site.
* Total Visits: Number of website visits.
* Last Activity: The most recent interaction by the lead.
* Converted: The target variable (1 for conversion, 0 for no conversion).
* Special handling is required for missing data, such as treating categorical entries like 'Select' as missing values.

## Repository Files:
* Lead_Scoring_Logistic_Regression_Assignment.ipynb: Contains the complete project code for data processing, model building, and evaluation.
* Leads.csv: The dataset.
* Lead Scoring Case Study PPT.pdf: Presentation of key results and insights.
* Lead Scoring Case Study Q&A.pdf: Answers to company-specific questions.
* Summary Report.pdf: A 500-word summary of the project's approach and results.
* README.md: Overview of the project and repository contents.

## Project Workflow:
* Data Preprocessing: Handle missing values, categorical encoding, and normalize numerical features.
* Exploratory Data Analysis (EDA): Visualize trends, correlations, and identify factors affecting conversion.
* Model Building: Build and optimize a logistic regression model to predict lead conversion, assigning scores based on predicted probabilities.
* Model Evaluation: Use accuracy, precision, recall, F1-Score, and ROC-AUC to assess performance. Visualize results using confusion matrices and ROC curves.
* Business Insights: Highlight key conversion factors and offer strategies for prioritizing high-potential leads.

## Running the Project:
* Clone the repository:

bash
Copy code
git clone https://github.com/ManjitSingh2003/Lead-Scoring.git

* Run the Jupyter notebook to preprocess the data, build the model, and evaluate results. Review the accompanying analysis, presentation, and report for business insights.

## Key Learnings:
* Data Preprocessing: Managing missing values and categorical encoding.
* EDA: Understanding variables that influence lead conversion.
* Modeling & Evaluation: Logistic regression modeling and performance metrics.
* Business Strategy: Translating model results into actionable sales strategies for higher lead conversion.
