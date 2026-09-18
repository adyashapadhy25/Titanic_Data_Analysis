# Titanic Dataset — Data Cleaning & Exploratory Analysis

## Overview
This project involves cleaning the Titanic dataset and performing exploratory 
data analysis (EDA) to understand survival patterns based on gender, passenger 
class, and age.

## Dataset
The dataset contains information about 891 passengers aboard the Titanic, 
including their age, gender, ticket class, and survival status.
Source: Kaggle Titanic Dataset

## Steps Performed
1. **Data Loading** — Loaded the dataset using pandas
2. **Data Exploration** — Checked dataset structure and identified missing values
3. **Data Cleaning**
   - Filled missing 'Age' values with the mean age
   - Filled missing 'Embarked' values with the mode
   - Dropped the 'Cabin' column due to excessive missing data (77%)
4. **Exploratory Data Analysis**
   - Analyzed survival rate by gender
   - Analyzed survival rate by passenger class
   - Visualized age distribution of passengers

## Key Insights
- Female passengers had a significantly higher survival rate (74%) compared to 
  male passengers (19%)
- First-class passengers had a higher survival rate (63%) compared to third-class 
  passengers (24%)
- Majority of passengers were between 20-40 years old

## Tools Used
- Python
- Pandas
- Matplotlib

## How to Run
1. Clone this repository
2. Open the notebook in Google Colab or Jupyter
3. Run all cells sequentially
