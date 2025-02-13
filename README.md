# Credit Score Analysis and Prediction

## Overview
This project analyzes and predicts credit scores using a dataset of financial attributes. It utilizes Python with Pandas for data processing, Plotly for visualization, and Scikit-learn for model training.

## Features
- **Data Exploration**: Reads and displays initial insights from `train.csv`.
- **Data Cleaning**: Identifies missing values and maps categorical variables.
- **Visualization**: Generates various box plots to understand relationships between credit scores and financial factors.
- **Machine Learning Model**: Trains a `RandomForestClassifier` to predict credit scores based on financial attributes.
- **User Input Prediction**: Allows users to input financial details and predicts their credit score.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy plotly scikit-learn
```

## How to Run
1. Place `train.csv` in the working directory.
2. Run the script to explore and visualize data.
3. Enter financial details when prompted to get a predicted credit score.

## Data Attributes
The dataset includes:
- `Annual_Income`, `Monthly_Inhand_Salary`, `Num_Bank_Accounts`, `Num_Credit_Card`, `Interest_Rate`, `Num_of_Loan`
- `Delay_from_due_date`, `Num_of_Delayed_Payment`, `Credit_Mix`, `Outstanding_Debt`, `Credit_History_Age`, `Monthly_Balance`

## Visualization Insights
Box plots are generated to analyze how financial factors impact credit scores:
- **Occupation**, **Annual Income**, **Monthly Salary**, **Number of Bank Accounts/Credit Cards**
- **Interest Rate**, **Number of Loans**, **Delayed Payments**, **Outstanding Debt**
- **Credit Utilization Ratio**, **Credit History Age**, **EMI per Month**, **Monthly Balance**

## Machine Learning Model
- Uses `RandomForestClassifier` from Scikit-learn.
- Splits data into training and testing sets (67%-33%).
- Takes user input for financial details and predicts the credit score.

## Example Usage
```bash
python credit_score_analysis.py
```
When prompted, enter financial details to receive a credit score prediction.

## Future Enhancements
- Improve feature engineering.
- Implement additional ML models for comparison.
- Enhance data preprocessing for better accuracy.
