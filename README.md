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
```
## Usage

1. Clone this repository:

```bash
git clone <https://github.com/katr1nas/A-B-test>
cd <repository_folder>
```

2. Open A/B test.ipynb in Jupyter Notebook or Google Colab.

3. Run the notebook cells sequentially to generate data, clean it, visualize distributions, and perform statistical tests.

4. Check the printed summary for t-statistic, p-value, and bootstrap confidence intervals.

## Example Output

- **T-statistic, p-value, and 95% bootstrap confidence interval for the difference in session durations.**

- **Visualization of session duration distribution and conversion rates by group.**

Contributing

Contributions are welcome! Please create a pull request or open an issue for any improvements or suggestions.

License

This project is open-source and available under the MIT License.


I can also draft a **shorter, GitHub-friendly version with badges and a minimalistic style** if you want something more modern for your repo homepage.  

Do you want me to make that version too?
