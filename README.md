# Student Performance Prediction

**Predict final exam scores using study habits, attendance, and more!**

---

## Dataset
- **Source:** [Kaggle - Student Performance Factors](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)
- **Rows:** 6,607 students
- **Target:** `Exam_Score` 

---

## Key Findings
- **Hours Studied** and **Attendance** are the **strongest predictors**
- **Polynomial Regression (deg 2)** beats Linear:
  - **R² = 93.71%**
  - **Linear Regression**: R² = 91.48%

---

## Results

| Model                  | MSE   | RMSE  | R²       |
|------------------------|-------|-------|----------|
| Linear Regression      | 0.960 | 0.980 | **91.48%** |
| Polynomial (deg 2)     | 0.710 | 0.842 | **93.71%** |

---
