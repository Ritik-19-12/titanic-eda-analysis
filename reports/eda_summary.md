# Titanic EDA – Summary Report 📊

## 1. Objective

Perform in-depth exploratory data analysis on the Titanic dataset to understand patterns, distributions, and relationships that impact survival.

---

## 2. Key Findings

### ✅ Data Distribution

- **Age**: Most passengers were between 20–40 years old.
- **Fare**: Highly skewed; a few very high fares.
- **Pclass**: Majority in 3rd class.

### ✅ Missing Values

- **Age** had 177 missing values.
- **Cabin** was missing for over 75% of rows — dropped from analysis.
- **Embarked** had 2 missing rows — filled with most frequent value (`S`).

### ✅ Outliers

- **Fare** had outliers above 300, verified by IQR and Z-score.
- **Age** had a few outliers over 70–80.

### ✅ Relationships

- **Gender**: Female survival rate much higher than male.
- **Pclass**: Higher class → higher survival.
- **Fare & Age** had weak positive correlation with survival.
- **Heatmap** showed minor correlation between Fare, Pclass, and Survival.

---

## 3. Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Git & GitHub

---

## 4. Conclusion

The analysis uncovered strong patterns that could be useful for predictive modeling — notably, the impact of gender, class, and fare on survival.

