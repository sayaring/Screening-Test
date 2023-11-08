# Screening-Test
The repository consists of the solutions of two ML problem statements for the screening test

## Problem 1: Review Sentiment Analysis

An online fashion retailer wants to develop a machine learning model that can classify
customer reviews into different sentiment categories. The model will take as input a
customer review and output a prediction of the review's sentiment, such as positive,
negative, or neutral. Develop a ML model for aforesaid classification with an example
Dataset.

### Dataset: Women's E-Commerce Clothing Reviews

Kaggle link: https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews/data

Description: The dataset used for this analysis is the "Women's Clothing E-Commerce Reviews" dataset. This dataset contains information about clothing reviews, including the text of the review and the associated rating. The dataset is used to train and evaluate the sentiment analysis model.

This dataset includes 23486 rows and 10 feature variables. Each row corresponds to a customer review, and includes the variables:
Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.
Age: Positive Integer variable of the reviewers age.
Title: String variable for the title of the review.
Review Text: String variable for the review body.
Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.
Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.
Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.
Division Name: Categorical name of the product high level division.
Department Name: Categorical name of the product department name.
Class Name: Categorical name of the product class name.

Code: https://github.com/sayaring/Screening-Test/blob/main/Medical_Readmission.ipynb

## Problem 2: Medical Readmission

A hospital has a large dataset of patient records, including information on demographics,
medical history, diagnoses, treatments, and outcomes. The hospital wants to use this data
to develop a machine learning model that can predict the risk of readmission for patients
after they are discharged from the hospital. Develop a ML solution for the aforesaid
prediction with an example Dataset.

### Dataset: Predicting the Readmission of Diabetic Patient's

Dataset link: https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008

Description : "The data set represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. Information was extracted from the database for encounters that satisfied the following criteria.
It is an inpatient encounter (a hospital admission).It is a diabetic encounter, that is, one during which any kind of diabetes was entered to the system as a diagnosis.The length of stay was at least 1 day and at most 14 days.Laboratory tests were performed during the encounter.Medications were administered during the encounter.The data contains such attributes as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c test result, diagnosis, number of medication, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc."


