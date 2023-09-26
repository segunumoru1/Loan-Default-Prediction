# Exploratory Data Analysis on Loan Default Prediction

## Introduction

Financial inclusion has expanded access to banking services. The main function of banks is to lend money to borrowers using money saved by depositors. In deciding who to lend to, banks need to assess these borrowers based on traits and historical performance of their previous borrowings. This type of assessment is captured in the C's of credit. This project aims to perform an exploratory data analysis on the Loan Default Prediction dataset to gain insights into factors that contribute to loan default.

## Dataset

The Loan Default Prediction dataset is a public dataset that contains information on loan applicants and whether they defaulted on their loans or not. The dataset contains 10,000 observations and 14 variables, including the target variable 'Loan_Status', which indicates whether a loan was approved or not.

## Methodology

The following methodology was used in this project:

1. Importing Libraries: Libraries such as Pandas, Numpy, Matplotlib, and Seaborn were imported for data manipulation and visualization.

2. Loading the Dataset: The dataset was loaded using pd.read_csv() from the local computer.

3. Exploratory Data Analysis: The dataset was explored to identify columns, unique values, missing values, shape of the entire dataset, info of the columns and data types, and statistical analysis of the data. Outliers were also identified in the dataset.

4. Relationship, Insights, and Visualizations: Univariate, bivariate, and multivariate analysis techniques were used to visualize the data and identify patterns and trends. Relationships between variables were explored using scatterplots, boxplots, and heatmaps.

5. Feature Engineering: Categorical variables were encoded to convert them into numerical values so that they can be featured or implemented in the machine learning model.

6. Model Preparation and Deployment: The dataset was split into training and testing sets for use in machine learning models. Several machine learning models were trained and evaluated, including Logistic Regression, Random Forest Classifier, and XGBoost Classifier.

7. Model Evaluation: The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The best performing model was selected based on these metrics.

## Results

The exploratory data analysis and machine learning models revealed several insights into factors that contribute to loan default:

- Applicants with higher credit scores were less likely to default on their loans.
- Applicants with higher income levels were less likely to default on their loans.
- Applicants with higher loan amounts were more likely to default on their loans.
- Applicants with longer loan terms were more likely to default on their loans.
- Applicants who had previously defaulted on loans were more likely to default on their current loans.

These insights can help banks develop strategies to reduce loan defaults and improve their lending practices.

## Conclusion

Through exploratory data analysis on the Loan Default Prediction dataset, we gained insights into factors that contribute to loan default. By understanding these factors, banks can develop strategies to reduce loan defaults and improve their lending practices.