# 🎓 Student Performance Predictor (Machine Learning)

## 📌 Project Overview
This project predicts **student final exam performance (G3)** using Machine Learning.

The goal is to understand how **study habits, lifestyle, and social factors** influence academic performance and to build a complete end-to-end ML pipeline.

---

## 🧠 Problem Statement
Can we predict a student’s final grade **without using previous exam marks**?

To make the problem realistic, the previous grades **G1 and G2 were removed**, forcing the model to learn from real-life factors such as:
- Study time
- Past failures
- Internet access
- Family and social background

---

## 📂 Dataset
**Student Performance Dataset (UCI / Kaggle)**  
Contains demographic, social and academic information of students.

Target variable:

---

## ⚙️ Machine Learning Pipeline

1. Data Loading & Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Data Visualization  
4. Feature Encoding (One-Hot Encoding)  
5. Train-Test Split (80/20)  
6. Model Training  
7. Model Evaluation  
8. Feature Importance Analysis  

---

## 📊 Exploratory Data Analysis

Key visualizations performed:
- Distribution of final grades
- Study time vs final grade
- Past failures vs final grade

### Key Observations
- Most students score between **8–15 marks**
- A noticeable number of students scored **0**, indicating failure group
- More study time → higher grades
- More past failures → lower grades

---

## 🤖 Models Used

| Model | Purpose |
|---|---|
| Linear Regression | Baseline model |
| Ridge Regression | Reduce overfitting |
| Lasso Regression | Feature selection |

---

## 📈 Model Performance

| Model | MSE | R² Score |
|---|---|---|
| Linear Regression | 17.60 | 0.14 |
| Ridge Regression | **17.55** | **0.14 (Best)** |
| Lasso Regression | 19.94 | 0.02 |

👉 **Ridge Regression performed best**

---

## 🔍 Feature Importance (Key Insights)

### 📉 Negative Impact on Grades
- Past failures (strongest negative factor)
- Romantic relationship (slight negative effect)
- Need for school support

### 📈 Positive Impact on Grades
- Desire for higher education (strongest positive factor)
- Study time
- Internet access
- Paid classes

---

## 🎯 Final Conclusion
Predicting student performance using lifestyle factors alone is challenging.

However:
- Academic history and motivation play major roles.
- Students with goals for higher education perform better.
- Past academic failures strongly affect future performance.

This project demonstrates a complete real-world **ML workflow** from data analysis to model comparison.

---

## 🛠️ Tech Stack
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🚀 Future Improvements
- Include G1 & G2 for improved accuracy
- Try advanced models (Random Forest, XGBoost)
- Deploy as a web app using Streamlit or Flask

---

## 👨‍💻 Author
**Anurag Kar**  
BCA Student | Aspiring Machine Learning Engineer