# 🎓 Codecademy Quiz Performance Analysis

This project explores how learners’ **prior progress** and **lesson type** relate to their quiz scores on Codecademy.  
It uses **linear regression modeling**, **diagnostic plots**, and **visual comparisons** to understand learning performance patterns.

---

## 📊 Features

- Reads and inspects data from `codecademy.csv`
- Visualizes relationships between:
  - `completed` (prior lessons completed) and `score`
  - `lesson` (lesson category) and `score`
- Fits **Ordinary Least Squares (OLS)** regression models:
  - Model 1: Predicts quiz `score` based on `completed` lessons
  - Model 2: Predicts quiz `score` based on `lesson` type
- Generates multiple plots:
  - Scatter plots with regression lines
  - Histogram of residuals (normality check)
  - Residuals vs fitted values (homoscedasticity check)
  - Boxplot comparing lessons
  - `sns.lmplot()` to show regression trends by lesson group
- Predicts expected quiz score for a learner with **20 completed lessons**
- Compares **mean scores** between Lesson A and Lesson B

---

## ⚙️ Requirements

Make sure these Python libraries are installed:

```bash
pip install pandas numpy matplotlib seaborn statsmodels
