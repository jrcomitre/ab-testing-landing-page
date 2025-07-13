# A/B Testing on Landing Page Conversion

This project demonstrates a full A/B testing workflow using Python, focused on analyzing conversion rates between two groups (control and treatment) in a marketing experiment.

## 📌 Purpose

The primary goal of this project is **learning and improving data analysis and statistics skills**, specifically in the area of A/B testing and hypothesis testing. This repository is part of my personal portfolio to showcase practical applications of data science techniques.

## 📊 Project Overview

- Two landing pages were tested:
  - **Old Page** (`control` group)
  - **New Page** (`treatment` group)
- The outcome of interest is whether the user **converted** or not.
- A **Z-test for proportions** was used to determine if the conversion rate difference is statistically significant.

## ✅ Main Features

- Data cleaning and exploratory analysis
- Conversion rate calculation per group
- Z-test implementation for hypothesis testing
- Data visualization using Seaborn and Matplotlib
- Automatic PDF report generation with test results (using FPDF)

## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Seaborn / Matplotlib
- Statsmodels
- FPDF

## 📈 Results Summary

- The control group had a slightly higher conversion rate than the treatment group.
- However, the difference was **not statistically significant (p > 0.05)**.
- Conclusion: There is no sufficient evidence to say the new landing page performs better or worse than the old one.

## 📚 Learning Outcomes

Through this project, I practiced:
- Statistical hypothesis testing
- Experimental design interpretation
- Data-driven decision making
- Automated result reporting

## 📁 Dataset