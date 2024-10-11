# Inferential Analysis of Company Attitude Dataset

## Overview
This repository contains an inferential analysis of a dataset focused on company attitudes using R. The analysis aims to explore how various factors, such as employee demographics and job satisfaction, influence overall attitudes towards the company.

## Dataset
The company attitude dataset includes survey responses from employees about their feelings towards the company. Key columns in the dataset include:

- **employee_id**: Unique identifier for each employee.
- **age**: Age of the employee.
- **gender**: Gender of the employee (e.g., Male, Female, Other).
- **job_satisfaction**: Rating of job satisfaction on a scale (e.g., 1 to 5).
- **company_attitude**: Overall attitude toward the company (e.g., Positive, Neutral, Negative).
- **department**: Department in which the employee works.

## Objectives
The main objectives of this analysis are:
- To investigate the relationship between job satisfaction and company attitude.
- To examine if demographic factors (age, gender) influence attitudes towards the company.
- To perform hypothesis testing to determine if observed differences in attitudes are statistically significant.

## Methodology
1. **Data Preparation**: The dataset is loaded, cleaned, and transformed for analysis, addressing any missing or inconsistent values.
2. **Exploratory Data Analysis (EDA)**: Initial exploration through summary statistics and visualizations to understand distributions and patterns.
3. **Inferential Statistics**:
   - Conduct hypothesis tests (e.g., chi-square tests, t-tests) to analyze relationships and differences.
   - Calculate confidence intervals for mean job satisfaction ratings across different attitude groups.
4. **Visualizations**: Generate plots (e.g., bar charts, boxplots) to illustrate the analysis results.

## Results
The analysis will provide insights into:
- The impact of job satisfaction on overall company attitude.
- Statistical significance of demographic factors affecting employee perceptions.
- Recommendations based on the findings for improving employee attitudes.

## Installation
To run the analysis, ensure you have R and the required packages installed. You can install the necessary packages using the following commands:

```R
install.packages(c("ggplot2"))
