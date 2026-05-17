Derivable Judgement: A Statistical Decision-Making Model
Project Overview

This project focuses on applying inferential statistics and hypothesis testing techniques on a healthcare dataset using Python in Google Colab. The project analyzes different health-related factors such as age, BMI, smoking habits, blood pressure, diabetes, and hypertension to derive meaningful statistical conclusions.

The main objective of this project is to understand how statistical methods help in decision-making and data interpretation in real-world healthcare scenarios.

Objectives
Apply inferential statistics on real-world health data
Perform hypothesis testing
Calculate confidence intervals
Analyze relationships between variables
Perform statistical tests such as:
Chi-Square Test
T-Test
ANOVA
Correlation
Covariance
Technologies Used
Python
Google Colab
Pandas
NumPy
SciPy
Matplotlib
Dataset Information

The dataset contains healthcare-related records with the following attributes:

Column Name	Description
record_id	Unique ID of patient
age_group	Age category
age	Age of individual
weight	Weight of individual
gender	Gender of individual
region	Region of individual
smoking_status	Smoking habit
exercise_frequency	Exercise frequency
bmi	Body Mass Index
blood_pressure	Blood pressure value
diabetes	Diabetes status
hypertension	Hypertension status
cholesterol_level	Cholesterol level
glucose_level	Glucose level
visit_date	Date of visit
Statistical Techniques Used
1. Chi-Square Test

Used to determine whether smoking status affects diabetes prevalence.

2. Confidence Interval

Calculated confidence interval for age data.

3. T-Test

Compared BMI between male and female individuals.

4. ANOVA Test

Compared blood pressure across different age groups.

5. Correlation

Measured relationship between Age and BMI.

6. Covariance

Measured directional relationship between Age and BMI.

Project Workflow
Import dataset
Data preprocessing
Statistical summary
Hypothesis formulation
Apply statistical tests
Interpret results
Visualize data
Generate conclusions
Visualizations Included
Histogram
Scatter Plot
Bar Chart
How to Run the Project
Step 1

Open Google Colab

Step 2

Upload:

health_dataset.csv
maths_project_3.ipynb
Step 3

Run all notebook cells sequentially

Sample Hypothesis
Null Hypothesis (H₀)

Smoking has no effect on diabetes prevalence.

Alternative Hypothesis (H₁)

Smoking affects diabetes prevalence.

Results
Statistical tests were successfully applied
P-values were interpreted for decision-making
Correlation and covariance analysis were performed
Data visualizations provided insights into health patterns
Conclusion

This project demonstrates the practical implementation of inferential statistics and hypothesis testing using Python. It helps in understanding how statistical methods can be used to analyze healthcare data and derive meaningful conclusions for decision-making.

Future Improvements
Add machine learning models
Create interactive dashboards
Use larger real-world datasets
Deploy project using Streamlit or Flask
Author

Yagna Patel
