# Exploring Salary Trends in the Technology Sector 💼📊

## Overview 🌟
This project investigates salary trends within the technology and information sectors, analyzing distinctions between remote and in-person job modes and exploring the impact of education levels on income. By leveraging statistical tests, bootstrapping, and data visualization, this analysis reveals insights into compensation disparities and provides actionable knowledge for professionals and educators in the field.

---

## Problem Statement 🧩
**What are the key differences in salaries for remote versus in-person jobs in the tech industry, and how does education level influence compensation?**

As remote work continues to redefine job markets and education becomes increasingly tied to earning potential, understanding these dynamics is crucial for professionals, organizations, and policymakers.

---

## Objectives 🎯
1. Examine differences in salary distribution between remote and in-person work modes.
2. Quantify the impact of educational attainment on income using statistical and computational techniques.
3. Employ robust methods like t-tests, ANOVA, and bootstrapping to ensure reliable conclusions.

---

## Methodology 🚀

### 1. Exploratory Data Analysis (EDA)
- **Visualization**: Created insightful plots (e.g., salary distribution by education, salary trends across job modes) to uncover data patterns.
- **Descriptive Statistics**: Summarized key statistics for salary groups, identifying trends and outliers.

### 2. Hypothesis Testing for Job Modes
- **Two-Sample T-Test**: Compared average salaries for remote and in-person workers:
  - **Manual Calculation**: Step-by-step computation of t-statistic and pooled standard deviation.
  - **Python Functionality**: Validated results using Python's built-in statistical libraries.
- **Bootstrapping**: Simulated distributions with 10,000 replications to estimate differences in mean salaries, visualizing bootstrapped distributions.

### 3. Impact of Education on Income
- **ANOVA**: Conducted an analysis of variance to assess salary differences among three education groups:
  - Bachelor's Degree
  - Master's Degree
  - Professional Degree
- **Bootstrapping for ANOVA**: Visualized distributions of differences in means to ensure consistency.

---

## Key Findings 🎯
1. **Remote vs. In-Person Jobs**:
   - Salaries for remote workers were significantly higher than their in-person counterparts.
   - Bootstrap distributions confirmed this trend, with minimal discrepancies from t-test results.
2. **Education and Income**:
   - Salaries varied significantly across education levels, with Professional Degrees showing the highest average compensation.
   - Bootstrapping reinforced the validity of the ANOVA results.

---

## Tools & Techniques 🛠️
- **Programming**: Python (Jupyter Notebook)
- **Libraries**:
  - NumPy, Pandas, Matplotlib, Seaborn, Scipy, Statsmodels
- **Statistical Methods**:
  - Two-Sample T-Test
  - Welch's T-Test
  - ANOVA
  - Bootstrapping
- **Visualization**:
  - Bar plots, histograms, scatter plots, and distribution plots for deeper insights.

---

## Deliverables 📦
- **Visualizations**:
  - Salary distributions and comparisons by job mode and education level.
  - Bootstrapped distributions and their differences.
- **Statistical Summaries**:
  - T-test and ANOVA results.
  - P-values and confidence intervals.
- **Notebook**:
  - Organized analysis with clear markdown explanations and annotated code.

---

## Repository Structure 📂
```plaintext
├── salary_analysis.ipynb         # Notebook containing the analysis and visualizations
├── clean_kaggle_data_2024.csv    # Cleaned dataset used for the analysis
├── README.md                     # Project overview and details
```
---

## Next Steps 🧭
- Expand the dataset to explore additional demographic and geographic trends.
- Incorporate machine learning models to predict salaries based on education and job modes.
- Investigate longitudinal trends in remote work adoption and its impact on compensation.

---

Feel free to explore, collaborate, and contribute to this project! 🚀✨
