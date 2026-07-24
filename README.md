# Predicting Income Levels Using Census Data

## 1. Project Title
This project analyzes factors associated with whether individuals earn above or below $50K per year. It uses demographic, education, and employment information from the UCI Adult Census Income dataset to explore patterns in income outcomes.

## 2. One-Sentence Summary
We analyzed Census data to understand how factors such as education, age, occupation, and work hours relate to income levels. We also built machine learning models to predict whether an individual earns above or below $50K.

## 3. The Problem
Income inequality affects individuals’ access to financial security, career opportunities, and quality of life. Understanding which factors are associated with higher income can help identify patterns in economic opportunity and areas where support may be needed.

## 4. The Data
This project used the UCI Adult Census Income dataset from the 1994 U.S. Census, which contains information about adults including age, education, occupation, hours worked per week, and income. After cleaning the dataset by handling missing values, removing duplicates, and removing unnecessary variables, 26,904 records remained. Exploratory analysis showed that education level and work hours were strongly related to income differences.

## 5. What We Did
We cleaned and prepared the dataset by removing missing values, correcting formatting issues, dropping the sampling weight variable, and converting income into a binary target for machine learning. We performed exploratory data analysis through visualizations and tested multiple machine learning models, including Gradient Boosting, Logistic Regression, Random Forest, Decision Tree, and Neural Network models. These models were evaluated using accuracy, precision, recall, and F1 score to compare their performance.

## 6. What We Found
The Gradient Boosting model achieved the highest accuracy with **83.66%** and the highest F1 score among the tested models. The analysis showed that individuals with higher education levels were more likely to earn above $50K, although income cannot be explained by one factor alone.

## 7. Fairness Check
The model was evaluated across male and female groups to determine whether performance differed between groups. Male accuracy was 80.3% and female accuracy was 90.4%, showing that model performance was not identical across groups and should be carefully considered before real-world use.

## 8. Limits and What's Next
This dataset is based on the 1994 U.S. Census, meaning it does not capture modern changes such as remote work, technology-driven careers, and changes in the economy. Future improvements could include using newer data, adding more relevant variables, and testing additional methods to improve fairness.

## 9. How to Run It
This project can be run using the Google Colab notebook, which contains the full process from data cleaning to machine learning evaluation. The notebook requires the dataset and Python libraries included in the notebook setup, and the full analysis can be completed within a few minutes.

## 10. Team and Roles
This project was completed by Misheeta, Sarakshi, Nisha, and Simran. Each team member contributed to different parts of the data investigation process, including data cleaning, exploratory analysis, visualization, machine learning, and documentation.
