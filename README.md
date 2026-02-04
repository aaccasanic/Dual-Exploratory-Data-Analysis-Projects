# Data Analytics Portfolio — Dual Exploratory Data Analysis Projects

This repository contains two complete Exploratory Data Analysis (EDA) projects focused on health, lifestyle, and cost-related patterns. Both analyses apply rigorous data-cleaning workflows, statistical exploration, and visualization techniques commonly used in real-world data analytics roles.

The projects included are:

- EDA – Medical Insurance Cost

- EDA – Lifestyle and Sleep Patterns

These notebooks demonstrate a structured analytical approach, clear reasoning behind visualization choices, and the ability to extract actionable insights from structured datasets.

## 📁 Project Structure

``` powershell

/
├── EDA - MEDICAL INSURANCE COST.ipynb
├── EDA - LIFESTYLE AND SLEEP PATTERNS.ipynb
└── README.md

```

## 📌 1. Medical Insurance Cost — EDA

**Dataset Overview**

Extracted from Kaggle, the dataset contains 1,338 medical insurance records, including:

- Age

- Sex

- Region

- BMI

- Smoking status

- Number of children

- Annual medical charges

**Analytical Approach**

This EDA focuses on identifying key cost drivers and understanding how demographic and lifestyle variables affect medical charges.

**Why These Visuals?**

- Histograms + KDE: To assess feature distributions and detect skewness (e.g., charges are right-skewed).

- Boxplots: To compare cost variability across gender or smoker status.

- Scatterplots with regression lines: To inspect linear or nonlinear relationships (e.g., BMI vs. charges).

- Correlation heatmap: To identify high-strength predictors before modeling.

These choices reflect standard workflows in cost analytics and actuarial pre-modeling assessment.

**Key Insights**

- Smoking status is the most influential predictor of high medical charges.

- BMI and age show positive trends with increasing costs.

- Gender and region have limited predictive power.

- Costs cluster below $10,000, with long-tail behavior.

## 📌 2. Lifestyle & Sleep Patterns — EDA

**Dataset Overview**

This dataset (374 records, 13 variables) includes:

- Demographics: Gender, Age

- Lifestyle: Physical Activity, Daily Steps

- Health metrics: Heart Rate, Blood Pressure, BMI Category

- Sleep metrics: Sleep Duration, Sleep Quality, Sleep Disorder

**Why These Visuals?**

- Histograms: To examine data quality, detect skew, and evaluate distribution patterns.

- Boxplots: To compare sleep-related metrics across categorical variables such as gender or stress levels.

- Regression plots: To validate behavioral correlations, such as physical activity vs. sleep duration.

- Violin plots: To visualize distribution density and inter-category variation (e.g., sleep disorder impact).

- Grouped barplots (mean/median): To summarize central tendencies across age or occupation groups.

- Dashboard layout: To consolidate multi-dimensional insights in a single visual block.

These visual decisions reflect a structured data exploration framework commonly used in health analytics.

**Key Insights**

- Average sleep duration is around 7.1 hours (healthy range).

- Higher physical activity correlates with longer sleep duration.

- Stress level is strongly associated with lower sleep quality.

- Sleep duration increases slightly with age.

- The strongest correlations:

  - Sleep Quality (0.88)
  - Stress Level (0.81)

 ## 🔍 Analytical Methodology Across Both Projects

 Both EDAs follow a professional analysis pipeline:

**1. Data Cleaning**

- Casting identifiers (e.g., Person ID) to string to avoid unwanted numerical treatment.

- Handling null values using semantic imputation (e.g., “No Disorder” for missing sleep disorder entries).

- Validating ranges and searching for outliers in cost, BMI, steps, and vitals.

**2. Descriptive Exploration**

- Univariate analysis to understand baseline feature behavior.

- Categorical frequency analysis to inspect population structure.

**3. Bivariate Analysis**

- Cost/lifestyle vs. demographic variables.

- Continuous vs. continuous relationships using regression plots.

**4. Correlation Analysis**

- Heatmaps to identify feature interactions and model-worthy predictors.

**5. Insight Synthesis**

- Extracting actionable, business-facing interpretations from the statistical patterns.

## 👨‍💻 Tools & Technologies

- Python

- pandas

- numpy

- matplotlib

- seaborn

- Jupyter Notebook

## 📊 Summary

Both exploratory studies apply a structured analytical workflow, combining:

- Rigorous data cleaning practices

- Consistent statistical exploration

- Visualization-driven pattern detection

- Interpretation of health, lifestyle, and cost-related trends

These notebooks reflect a clear methodology for transforming raw datasets into meaningful insights, using reproducible analysis and industry-standard Python tools.

