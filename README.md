# A/B Testing Analysis: Evaluating Landing Page Performance

## Project Overview

This project analyzes the performance of a new website landing page using **A/B Testing**. The objective is to determine whether the new landing page leads to a higher conversion rate compared to the existing landing page.

The analysis includes data cleaning, exploratory data analysis (EDA), statistical hypothesis testing, confidence interval analysis and business recommendations.

---

## Business Objective

To determine whether the new landing page improves user conversion rates compared to the old landing page using statistical hypothesis testing.

---

## Dataset

The dataset contains user-level information from an A/B testing experiment.

**Features:**
- `user_id` – Unique user identifier
- `timestamp` – Time of user interaction
- `group` – Control or Treatment group
- `landing_page` – Old page or New page
- `converted` – Conversion status (0 = No, 1 = Yes)

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Jupyter Notebook

---

## Project Workflow

1. Importing Libraries 
2. Data Loading
3. Data Understanding
4. Data Cleaning
5. Exploratory Data Analysis (EDA)
6. Hypothesis Formulation
7. Statistical Hypothesis Testing
8. Confidence Interval Analysis
9. Experiment Summary
10. Business Recommendation
11. Final Conclusion
---

## Data Cleaning

- Checked for missing values
- Removed mismatched records where users were assigned the wrong landing page
- Removed duplicate user IDs
- Verified the cleaned dataset before analysis

---

## Exploratory Data Analysis

The following analyses were performed:

- Overall conversion rate
- Conversion rate by group
- Comparison of control and treatment groups
- Bar chart visualization of conversion rates

---

## Statistical Analysis

A **Two-Proportion Z-Test** was performed to compare the conversion rates of the control and treatment groups.

**Hypotheses**

**Null Hypothesis (H₀):**
The new landing page does not improve the conversion rate compared to the old landing page.

**Alternative Hypothesis (H₁):**
The new landing page has a higher conversion rate than the old landing page.

---

## Results

| Metric | Old Page (Control) | New Page (Treatment) |
|--------|-------------------:|---------------------:|
| Users | 145,274 | 145,310 |
| Conversions | 17,489 | 17,264 |
| Conversion Rate | 12.04% | 11.88% |

### Statistical Test Results

- Z-statistic: **1.3109**
- P-value: **0.9051**
- 95% Confidence Interval: **(-0.00394, 0.00078)**

---

## Key Findings

- The control group achieved a slightly higher conversion rate than the treatment group.
- The p-value (0.9051) was greater than the significance level (0.05).
- The 95% confidence interval included zero.
- There was no statistically significant difference between the two landing pages.

---

## Business Recommendation

Based on the statistical analysis, there is insufficient evidence to conclude that the new landing page performs better than the existing landing page.

It is recommended to continue using the current landing page or conduct additional A/B tests with new design variations before making a business decision.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- A/B Testing
- Hypothesis Testing
- Two-Proportion Z-Test
- Confidence Interval Analysis
- Statistical Inference
- Data Visualization
- Business Analytics
- Python (Pandas, NumPy, Matplotlib, Statsmodels)

---

## Author

**Geetha R. Iyer**
