# TelecomChurn
Telecom Churn Case Study

Problem Statement:  
  * The telecommunications industry experiences an average of 15-25% annual churn rate 
  * Customer retention has now become even more important than customer acquisition
  * For many incumbent operators, retaining high profitable customers is the number one business goal.
  * To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.
  * Analyse customer-level data of a churning telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.
 
 Objective:
 
  * To build Classification model to select the churns that are most likely to convert into paying customers
  * Model to be flexible in order to adjust to if the company's requirement changes in the future 
  * The business objective is to predict the churn in the last (i.e. the ninth) month using the data (features) from the first three months.

The following are team members who worked on this project:

  * Anil Thakre
  * Avishi Sinha


Solution Approach:

We used classification models such as logistic regression, Decision Tree & Random Forest. Based on business case we selected Logitic regression as Recall was better for this model. As we do not want to lose customers we would be offering some extra benefits, wrongly identifying non-churner as churner won't hurt the business as much as missing a churner, hence Recall is more important. 

The steps involved for this case study are mentioned below:

  * Data Loading
  * Exploratory Data Analysis
  * Data Preparation (* Missing value handling * Feature engineering * Standardization)
  * Model Building - Logistic Regression, Decision Tree & Random Forest
  * Model Performance Evaluation using Probability Calibration, ROC Curve, Precision-Recall Curve
  * Conclusion


Files Submitted:

  * README file
  * Python commented file: Juputer Notebook.
  * Presentation in PDF format
