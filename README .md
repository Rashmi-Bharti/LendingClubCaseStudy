**EDA Case Study**

You work for a consumer finance company specializing in various types of loans for urban customers. The company must decide whether to approve or reject loan applications based on the applicant’s profile. There are two primary risks associated with these decisions:

Loss of Business: If the applicant is likely to repay the loan but the application is not approved, the company loses a potential business opportunity.
Financial Loss: If the applicant is likely to default on the loan but the application is approved, the company incurs a financial loss.


**Objectives**

The main objective is to use Exploratory Data Analysis (EDA) to identify patterns that indicate whether a person is likely to default on a loan. This information will help the company make better decisions, such as:

- Denying the loan
- Reducing the loan amount
- Lending to risky applicants at a higher interest rate

**Business Objectives**

The company is the largest online loan marketplace, facilitating personal loans, business loans, and financing for medical procedures. The primary objectives are to:

Minimize Credit Loss: Identify risky applicants to reduce the number of loans given to those likely to default.
Maximize Business Opportunities: Ensure that loans are not unnecessarily rejected for applicants likely to repay.
Improve Portfolio and Risk Assessment: Understand the variables that indicate a high risk of default to enhance risk assessment models.

## Table of Contents

**Step 1:** Loading the Data related to Loans

- Loaded the data related to loan
- Printed the column names, head and shape

**Step 2:** Data Cleaning: Handle missing values, outliers, and inconsistent data entries.

- Filled the Null Values
- Detected And Removed the Outliers
   - Finding the IQR
   - Finding the upper limit and lower limit
   - Removing the outliers and comparing

**Step 3:** Data Exploration: Analyze demographic information, loan attributes, and repayment status.

- Created Univariate , Bivariate , Multivariate Analysis using the graphs
- Univariate- Histogram , Boxplot , Countplot
- Bivariate- Scatter plot, Barchart, Boxplot
- Mutivariate- Heatmap

**Step 4:** Data Visualization: Use visualizations to identify trends and patterns.

- Using Countplot and Histplot to analyse the data

**Step 5:** Correlation Analysis: Identify relationships between different variables and the default status.

- Created a Correlation Heatmap to observe the relation between columns


## Conclusions

- It indicates that 'Not Verified' loans are more likely to be 'Charged Off'. While a lack of verification might be a red flag for potential issues¶
- Annual_income and loan_amount: A moderate positive correlation might indicate that individuals with higher incomes tend to take larger loans.
- Higher interest rates are associated with a higher likelihood of default.

## Technologies Used

- Python - version 3.11.2
- Jupyter Notebook - version 7.1.2

## Acknowledgements

- The project was based on Exploratory Data Analysis (EDA) to identify patterns that indicate whether a person is likely to default on a loan. This information will help the company make better decisions
- In this we have performed the EDA on the complete loan data for all loans issued through the time period 2007 t0 2011.

## Contact

Created by [@Rashmi-Bharti] - feel free to contact me!
