# HR Employee Attrition Analytics 🧑‍🤝‍🧑

This project analyzes employee attrition using the IBM HR Analytics Dataset. It explores various employee demographics and builds predictive models to identify employees at risk of leaving the company. The models created achieve up to 98% accuracy.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Data Exploration](#data-exploration)
- [Modeling Techniques](#modeling-techniques)
- [Key Findings](#key-findings)
- [Installation](#installation)
- [Usage](#usage)
- [Libraries Used](#libraries-used)

## Overview

The aim of this project is to analyze various factors affecting employee attrition and build a robust predictive model to help companies identify employees who are likely to leave. Understanding these factors enables HR departments to take preventive measures to retain valuable employees.

## Features

- **Data Exploration**: Analysis of employee demographics such as gender, age, education level, and marital status.
- **Attrition Analysis**: Insightful visualizations of attrition rates by gender, department, salary, and more.
- **Predictive Modeling**: Development of a machine learning model with 98% accuracy to predict employees at risk of attrition.

## Data Exploration

The analysis explores various features of the dataset, such as:

- Attrition rates per gender, department, and salary.
- The impact of marital status on attrition.
- The correlation between job roles and attrition rates.

## Modeling Techniques

The following techniques were utilized to build the predictive model:

- Train-Test Split
- Random Forest
- Gradient Boosting

## Key Findings
- Attrition is highest among employees aged 18 to 35 and decreases with age.
- Attrition is highest among the Sales Department with Sales Representatives having an attrition rate of nearly 40%. 
- Employees with lower income levels have an attrition rate at nearly 15% higher than those with higher incomes.
- Women aged 18-29 are more likely to attrition across all age groups. 

## Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/HR-Employee-Attrition-Analytics.git
   ```
2. Navigate to the project directory:
   ```bash
   cd HR-Employee-Attrition-Analytics
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Load the dataset.
2. Run the data exploration notebooks to visualize and understand the data.
3. Use the modeling scripts to train and evaluate the predictive models.

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn
