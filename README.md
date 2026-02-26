# A/B Testing Analysis with Python

This project demonstrates a complete workflow for performing A/B testing and statistical analysis using Python. It includes data simulation, exploratory data analysis (EDA), hypothesis testing, and visualization.

## Features

- **Synthetic Dataset Generation**  
  Creates a realistic business dataset with user IDs, session durations, conversion outcomes, and demographic features. Handles missing values and outliers.

- **Data Wrangling & EDA**  
  - Cleans missing and extreme values.  
  - Visualizes session duration distributions by group.  
  - Compares conversion rates with 95% confidence intervals.

- **Hypothesis Testing**  
  - Independent two-sample t-test to compare session durations between Control and Test groups.  
  - Bootstrap estimation of mean differences for robust confidence intervals.

- **Visualization**  
  - KDE plots for session duration distributions.  
  - Bar plots for conversion rates with 95% confidence intervals.

## Installation

Ensure you have Python 3.x installed along with the required packages:

```bash
pip install pandas numpy matplotlib seaborn scipy
