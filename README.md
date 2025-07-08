
# 📌 Customer Churn Prediction (Jupyter, Python, Scikit-learn)

This project predicts **customer churn** for a telecom company using real-world-style data and classic machine learning.

---

## 🗂️ Overview

- **Goal:** Identify key factors that drive customer churn and build models to predict who is likely to leave.
- **Tech:** Python, pandas, matplotlib, seaborn, scikit-learn (Logistic Regression & Decision Tree)
- **Notebook:** Fully commented and organized in clear sections (Data Cleaning, EDA, Modeling, Evaluation).

---

## 🧹 Steps

1️⃣ **Data Cleaning:**  
- Handled missing values with vectorized `.loc`  
- Converted Yes/No and gender columns to binary using `.map()` with a loop  
- Used `get_dummies` for multi-category columns to avoid the dummy variable trap

2️⃣ **EDA:**  
- Created visualizations (countplots, boxplots) with seaborn & matplotlib  
- Found trends between contract types, internet service, monthly charges, and churn

3️⃣ **Modeling:**  
- Trained a Logistic Regression model with ~80% accuracy on test data  
- Built a Decision Tree to compare recall and feature impact  
- Evaluated with confusion matrix and classification report

---

## 🔑 Key Insights

✔️ Customers with **month-to-month contracts**, **fiber optic internet**, **no tech support**, and **higher monthly charges** are more likely to churn.  
✔️ Logistic Regression had higher overall accuracy, but the Decision Tree caught more churners (higher recall).  
✔️ Shows how model choice affects predictions!

---

## ⚙️ Next Steps

- Try **Random Forest** or **SMOTE** to improve churner recall  
- Experiment with hyperparameter tuning for tree depth  
- Deploy as a simple API or dashboard

---

## ✅ What I Learned

This project shows my end-to-end data pipeline skills:
- Cleaning messy data
- Vectorized operations and loops in pandas
- Visual EDA
- Building & comparing ML models
- Explaining results clearly

---

**🔗 Always open to feedback and new ideas!**  
