## CapstoneWork
Rowan Zinn WGU Capstone
## Project Description
# Research Question
Is a college education necessary to earn a good salary and secure a high-level job title in the workforce?

# Scope
This project analyzes employee data from the IT department at OU Health to investigate the relationship between education level, salary, and job title. The focus is on comparing high school, bachelor’s, and master’s degrees. Data cleaning, visualization, and statistical analysis are performed using Python and JupyterLab. The project excludes years of experience and does not consider associate’s degrees.

# Solution Overview
Tools: Python (≥3.8), pandas, matplotlib, seaborn, JupyterLab

# Methods: 
Data cleaning (handling NaNs/nulls), feature engineering (adding columns for education years and job title grouping), statistical analysis (correlations, max/min values), and visualization (scatter plots, pie charts)

# Environment: 
Local Python environment with a private GitHub repository for code version control

## Project Execution
Plan vs. Execution
Plan: Follow SEMMA methodology—Sample, Explore, Modify, Model, Assess

# Execution: 
Data imported and cleaned (no nulls or NaNs found), two new columns added for analysis, visualizations created (scatter plots and pie chart), and statistical measures computed to evaluate relationships

Timeline: Data import and cleaning on April 4, 2024; analysis and visuals created April 5-6; presentation on April 12, 2024

# Methodology
Data Sampling: Focus on OU Health IT department employees

Exploration: Used .describe(), .info(), and .head() to understand dataset characteristics

Modification: Added columns Education_Years and Title_Grouped to support modeling

Modeling: Created visual graphs and calculated correlations

Assessment: Verified model findings with statistics and visual inspection

## Data Selection and Preparation
Data provided as a CSV file from OU Health—no collection obstacles or governance issues

Dataset advantages: detailed education and salary information for IT employees

Limitations: limited to one company and one state (Oklahoma), no associate degrees, no experience data

Preparation steps: loaded data with pandas, replaced employee IDs for privacy, checked for nulls, and added derived columns

## Data Analysis Process
Organized via SEMMA framework

Generated statistics on education level distribution (e.g., 32.88% high school, 59.01% bachelor’s, 8.12% master’s)

Created a pie chart for education breakdown and scatter plots for education vs salary and education vs job title

Calculated max, min, and average salaries per education level

Computed correlation coefficient between salary and education level (~0.474)

## Results
Employees without college degrees can still earn livable salaries and hold meaningful job titles

Bachelor’s degree holders make up the majority and have access to all job title groups

The CIO with a master’s degree has the highest salary; the lowest-paid employee has a high school degree

Average salaries by education: High School — $79,987; Bachelor’s — $107,845; Master’s — $182,785

Positive correlation between education and salary confirms higher education generally leads to higher pay

## Project Evaluation
The project effectively answered the research question with clear visuals and statistics

Tools and techniques were appropriate and efficient for the dataset and project scope

Limitations include lack of experience data and restricted geographic scope

Findings help inform hiring practices and career planning at OU Health and similar organizations

## Key Takeaways
A college degree is not strictly necessary for a good salary or job title, but higher education generally improves opportunities

Scatter plots and pie charts clearly communicate the distribution and relationships in the data

## Recommendations:

Continue considering applicants with high school or bachelor’s degrees, as they represent the majority of successful employees

Emphasize experience and skills alongside education in hiring and career development decisions


