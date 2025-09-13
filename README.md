** Customer Churn Data Analysis **
This project analyzes customer churn data from a telecommunications company, uncovering trends and insights that can help improve customer retention. The analysis uses Python and key libraries like Pandas, Matplotlib, Seaborn, and NumPy.

** Project Overview **
Goal: Identify key factors that affect customer churn

Data: customer churn.csv with 7,043 records and 21 columns including demographics, service usage, and payment details

Methods: Data cleaning, exploratory data analysis (EDA), visualization

Features
Data preprocessing: Handling blanks, converting types, and feature transformation (e.g., mapping SeniorCitizen to yes/no)

** EDA visualizations: **

Churn distribution counts and pie chart

Tenure distribution by churn status

Contract types vs. churn rates

Payment methods vs. likelihood of churn

Insights:

Shorter tenure customers are likely to churn

Month-to-month contract holders have far higher churn rates

Customers paying via electronic check are more likely to leave

How to Run
Clone or download this repository

Ensure customer churn.csv is in the working directory

Install the required libraries:

bash
pip install pandas matplotlib seaborn numpy
Run the analysis script:

bash
python churn_analysis.py
File Structure
churn_analysis.py — Main analysis script

customer churn.csv — Raw customer data

churnoutput.pdf — Output and analysis results

Visualization Samples
Churn count and percentage plot

Tenure histogram by churn status

Contract vs. churn countplot

Payment method vs. churn countplot

Key Columns in Data
Column	Description
customerID	Unique customer identifier
gender	Customer gender
SeniorCitizen	Senior status (mapped to yes/no)
tenure	Months the customer has stayed
Contract	Type of contract (month-to-month, 1/2 year)
PaymentMethod	Payment method (electronic check, etc.)
Churn	Whether the customer left (yes/no)
Insights & Recommendations
Target retention efforts at month-to-month contract holders and short-tenure users

Review processes for electronic check payments due to higher churn association

Senior citizens and dependents show distinct patterns worthy of further analysis

** License **
This project is for education or analysis purposes. Adapt or expand as needed.
