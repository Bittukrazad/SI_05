# SI_05
Student Grades Analysis

This project performs an Exploratory Data Analysis (EDA) and predictive modeling to analyze student performance based on various factors. The dataset includes information on student demographics, academic performance, and socio-economic factors. The project aims to uncover patterns that influence student grades and build models to predict academic outcomes.

Key Features:

Exploratory Data Analysis (EDA):

In-depth exploration of the dataset to identify key patterns, trends, and relationships.
Visualizations like histograms, scatter plots, and correlation heatmaps provide insights into factors affecting student performance.

Data Preprocessing:

Handling missing values, encoding categorical variables, and scaling features using StandardScaler.
Label encoding of categorical data for modeling purposes.

Regression Analysis:

A multiple linear regression model is built to predict students' final grades (G3).
The model achieves a Root Mean Square Error (RMSE) of approximately 2.12 and an R² score of 0.79, indicating a good fit.

Classification Model:

Logistic regression is used to classify students' final grades into categories (pass/fail).
The logistic regression model, after scaling features and tuning hyperparameters, achieves an accuracy of 92.4%.

Technologies Used:

Python (pandas, NumPy, scikit-learn)
Data visualization libraries (matplotlib, seaborn)

Installation:

To run this project locally:

Clone the repository.

Install the required libraries using pip install -r requirements.txt.
Run the Jupyter Notebook to execute the analysis.

Dataset:
The dataset used in this project is a public dataset of student performance from UCI Machine Learning Repository.


