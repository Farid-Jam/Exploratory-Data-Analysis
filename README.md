# 📊 Internal Factors Influencing Student Performances
By Farid Jamshid

## 📘 Overview

This project explores how *internal factors*, or factors within a student's control, impact academic performance; specifically, exam scores. Unlike many analyses that focus 
on external contributors like parental involvement or socioeconomic status, this study hones in on variables students can actively influence. 

Key internal factors analyzed:
- 📚 **Hours Studied**
- 🏫 **Attendance**
- ⚽ **Participation in Extracurricular Activities**
- 💤 **Average Hours of Sleep per Night**
- 🔥 **Motivation Levels**

This analysis is based on a dataset from [Kaggle](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors?resource=download), cleaned to isolate internal factors, and 
visualized using Python libraries including, **pandas**, **matplotlib**, and **seaborn**.

## 🪜 Steps Performed

1. **Data Loading**: CSV file loaded using pandas.
2. **Data Cleaning**: Removed irrelevant columns, renamed headers, and checked for null values.
3. **Exploratory Data Analysis**:
    - Visualized distributions of exam scores.
    - Compared averages across grouped internal factor ranges (e.g., attendance brackets).
    - Bar graphs were used for clear, categorical comparison.

## 🔑 Key Findings

- **Attendance and Study Hours** had the **strongest positive correlation** with exam scores.
- **Motivation and Extracurricular Activities** showed **smaller, yet still positive influences**.
- **Sleep Hours** showed a **negligible negative relationship**, likely impacted by external confounding factors.

## 📌 Conclusion

Students have control over several factors that can influence their academic success. Improving class attendance and dedicating more 
time to study are the most effective ways to boost exam performance. While the impact of sleep and extracurricular activities is relatively minor, 
their role should not be completely dismissed. Motivation plays a moderate role in success and could be targeted in academic development strategies.

## 📚 References

- **Dataset**: [Kaggle - Student Performance Factors](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors?resource=download)
- **OUAC Educational Image**: [https://www.ouac.on.ca/guide/teas-guide/](https://www.ouac.on.ca/guide/teas-guide/)
- **Pandas**: [https://pandas.pydata.org/](https://pandas.pydata.org/)
- **Seaborn**: [https://seaborn.pydata.org/](https://seaborn.pydata.org/)
- **Matplotlib**: [https://matplotlib.org/](https://matplotlib.org/)
