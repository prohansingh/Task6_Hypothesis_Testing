# Task6_Hypothesis_Testing
Happie Loop Technologies

Task 6 – Hypothesis Testing using Amazon Sales Dataset
**Project Overview**

This project focuses on performing hypothesis testing using the Amazon Sales dataset with the help of Python and statistical analysis techniques. The purpose of this task is to make data-driven decisions by analyzing whether significant differences exist between different groups within the dataset.

Hypothesis testing is an important statistical method used in data analytics to validate assumptions and support decision-making based on data rather than intuition.

In this project, a statistical t-test was performed to compare sales behavior between different product categories in the Amazon Sales dataset.

**Objectives of the Project**

The main objectives of this project are:

To formulate a research question and hypotheses
To clean and prepare the dataset for testing
To apply an appropriate statistical test
To calculate the p-value and test statistic
To interpret the statistical results
To make conclusions based on data analysis
Tools and Technologies Used
Tool / Library	Purpose
Python	Programming Language
Pandas	Data Analysis and Manipulation
NumPy	Numerical Operations
Matplotlib	Data Visualization
SciPy	Statistical Testing

**Dataset Description**

The dataset used in this project is the Amazon Sales dataset stored in CSV format. The dataset contains sales-related information including product categories, quantities, and total sales values.

The dataset was used to analyze whether significant differences exist between the sales performance of different product groups.

**Research Question**

Is there a significant difference in average sales between two product categories in the Amazon Sales dataset?

**Hypotheses Formulation**
Null Hypothesis (H₀)

There is no significant difference in average sales between the selected product categories.

Alternative Hypothesis (H₁)

There is a significant difference in average sales between the selected product categories.

**Steps Performed in the Project**
1. Importing Required Libraries

Necessary Python libraries were imported for data preprocessing and statistical testing.

2. Loading the Dataset

The dataset was loaded into Python using pandas for further analysis.

3. Data Cleaning

Basic preprocessing techniques were applied including:

Handling missing values
Removing duplicate records
Selecting relevant columns

These steps ensured the dataset was suitable for hypothesis testing.

4. Selecting Product Categories

Two product categories were selected from the dataset for comparison based on total sales values.

The sales data from these categories was extracted for statistical analysis.

5. Applying Statistical Test

An Independent T-Test was performed to compare the average sales values between the selected categories.

The test generated:

T-statistic
P-value

These values helped determine whether the difference between categories was statistically significant.

**Interpretation of Results**

The p-value obtained from the t-test was compared with the significance level of 0.05.

Decision Rule
If p-value < 0.05:
Reject the Null Hypothesis
If p-value > 0.05:
Fail to Reject the Null Hypothesis

Based on the calculated p-value, conclusions were drawn regarding whether significant differences existed between the selected product categories.

**Key Observations**
Statistical testing helped compare category sales performance.
The analysis provided evidence-based conclusions.
Hypothesis testing reduced decision-making based on assumptions.
The t-test provided insights into category-level sales behavior.

**Challenges Faced**

Some challenges encountered during the project included:

Handling missing values
Selecting suitable categories for comparison
Understanding statistical test assumptions
Interpreting p-values correctly

These challenges were resolved through proper preprocessing and statistical analysis techniques.

**Conclusion**

This project successfully demonstrated hypothesis testing using the Amazon Sales dataset. Statistical analysis helped determine whether significant differences existed between product category sales.

The project improved practical understanding of statistical testing, p-values, hypothesis formulation, and data-driven decision-making techniques.

**Project Structure**

Task6_Hypothesis_Testing/

│

├── amazon_sales_data_2025.csv

├── hypothesis_testing.py

├── README.md

│

└── images/

└── category_comparison.png

**Output Generated**

The project generated:

T-test results
P-value interpretation
Statistical conclusions
Category comparison visualization

These outputs helped in making data-driven decisions from the dataset.

**Learning Outcomes**

Through this project, the following skills were improved:

Statistical hypothesis testing
T-Test implementation
Data preprocessing
P-value interpretation
Research question formulation
Data-driven analysis

**Final Result**

The hypothesis testing task was completed successfully using Python and statistical analysis libraries. The project demonstrated how statistical methods can be applied to real-world sales data for meaningful decision-making and business analysis.
