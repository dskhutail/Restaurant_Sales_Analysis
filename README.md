# 🍽️ Restaurant Sales Analysis using Linear Regression

This project analyzes restaurant transaction data to uncover patterns in sales and customer behavior using **Linear Regression**. It walks through data exploration, visualization, modeling, and interpretation — making it ideal for beginners learning machine learning with real-world data.

---

## 🎯 Project Objectives

- Understand trends in product sales, payment methods, and transaction timings.
- Build and evaluate a **Linear Regression model** to predict transaction amounts.
- Derive business insights from customer behavior and sales patterns.
- Validate assumptions of the **Classical Linear Regression Model (CLRM)**.

---

## 📄 Dataset Overview

- **Observations:** 1000 rows  
- **Features:** 10 columns including `Product`, `Quantity`, `Payment Mode`, `Date`, and `Transaction Amount`
- **Missing Values:** 107 (handled during preprocessing)
- **Amount Range:** ₹20 to ₹900  
- **Average Quantity Sold:** ~8 units per transaction

---

## 🔍 Key Insights from EDA

- 🧊 **Cold Coffee** is the most popular item.  
- 🥪 **Sandwich** is the most expensive.  
- 🥙 **Vadapav** is the least sold and cheapest item.  
- 💳 **Online transactions** peak at night, while 💵 **cash payments** are common in the evening.  
- The distribution of sales is **right-skewed**.

---

## 🧰 Tools & Libraries Used

- **Python 3**  
- **Pandas**, **NumPy** – data handling  
- **Matplotlib**, **Seaborn** – visualization  
- **Scikit-learn** – linear regression modeling

---

## ⚙️ Model Summary

- **Model Used:** Simple Linear Regression  
- **Dependent Variable:** Transaction Amount  
- **Independent Variable:** Time of the Year

---

## 🔍 CLRM Assumption Check (Brief)

- **Linearity:** Reasonably met  
- **Normality of Residuals:** Slight skew observed  
- **Homoscedasticity:** Not fully satisfied  
- **Multicollinearity:** Not applicable (only one feature)

---

## 📌 Conclusion

- The linear model highlights basic sales trends but captures only a fraction of variance.
- Strong business insights can still be drawn regarding **product popularity** and **customer timing patterns**.


