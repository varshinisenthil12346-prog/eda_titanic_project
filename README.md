# eda_titanic_project
# Exploratory Data Analysis (EDA) - Titanic Dataset

## Overview
This project analyzes the Titanic passenger dataset (891 passengers) to uncover patterns and identify the factors that influenced survival. It uses statistical summaries, visualizations and correlation analysis, and presents the findings in a structured report.

## Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

## Workflow
1. Loaded the dataset and inspected its structure
2. Handled missing values (dropped `deck`, filled `age` with median, `embarked` with mode)
3. Generated statistical summaries
4. Univariate analysis (age, fare, passenger class, survival)
5. Bivariate analysis (survival vs gender, class, age group, port, family)
6. Correlation analysis
7. Wrote a structured report of the findings

## Key Insights
- Overall survival rate was **38.4%**
- Women survived at **74.2%** vs men at **18.9%** (gender was the strongest factor)
- 1st class survival was **63.0%**, 3rd class only **24.2%**
- Children had a survival rate of **58.0%**
- Passengers travelling with family survived at **50.6%** vs **30.4%** for those alone
- Fare is positively correlated with survival (**0.26**), class is negatively correlated (**-0.34**)

## Files
- `Untitled3.ipynb` - Complete code and outputs
- `eda_report.md` - Structured EDA report
- `summary_statistics.csv` - Statistical summary
- `1_univariate.png` - Univariate analysis
- `2_survival_factors.png` - Factors affecting survival
- `3_class_gender.png` - Survival by class and gender
- `4_correlation.png` - Correlation heatmap

## Conclusion
Gender, passenger class and age were the main factors influencing survival. Women, children and first-class passengers had the highest chances of survival.
