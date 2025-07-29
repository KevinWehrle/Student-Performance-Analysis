# Student Performance Analysis

This project analyzes student achievement data from two Portuguese secondary schools, using visualizations and machine learning to explore factors that influence final grades.

## Objective

The primary goal was to identify which features have the greatest influence on students' final grades (G3), and to use this insight to support struggling students. This analysis combines data visualization with a predictive linear regression model.

## Dataset

- **Source**: [UCI Machine Learning Repository](https://doi.org/10.24432/C5TG7T)
- **Features**: 30 attributes (demographics, family background, study time, etc.)
- **Target**: Final grade (G3)

## Methods

- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `ucimlrepo`
- **Steps**:
  - Data preprocessing and encoding
  - Exploratory Data Analysis (EDA)
    - Heatmaps, barplots, and boxplots to identify trends
  - Feature selection
  - Linear regression model
  - Model evaluation using RMSE, MAPE, and R² metrics

## Key Insights

- **Free time** had a slightly negative correlation with final grades.
- **Study time**, **mother’s/father’s education**, and **fewer past failures** correlated with better performance.
- Students with internet access and those who participated in activities performed slightly better.
- **Linear regression model** achieved:
  - RMSE: ~1.17
  - MAPE: ~5.8%
  - R² Score: 0.86

## Model Performance

The regression model performed strongly, suggesting that prior grades (G1, G2), study habits, and certain lifestyle factors have predictive value in academic outcomes.

## Societal Impact

This analysis could help educators and students better understand which lifestyle and educational factors most strongly influence academic performance, potentially guiding students toward better habits.

## Citation

Cortez, P. (2008). *Student Performance [Dataset]*. UCI Machine Learning Repository. [https://doi.org/10.24432/C5TG7T](https://doi.org/10.24432/C5TG7T)

---

## 📁 Files

- `student_performance_analysis.ipynb` – Jupyter notebook with full code
- `plots/` – Folder containing visualizations (optional)
- `README.md` – Project summary
