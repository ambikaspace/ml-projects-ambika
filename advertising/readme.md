# 📈 Advertisement Sales Prediction

This project builds a regression model to **predict product sales** based on **advertising spend** across TV, Radio, and Newspaper platforms. The model helps in understanding which advertisement channels are most effective in influencing sales and provides data-driven support for marketing decisions.

---

## 🧠 Project Goal

To predict **sales figures** using ad spending data across multiple media channels, and identify how strongly each type of ad spend impacts the overall product sales.  
This can help **marketing teams** optimize their ad budgets and allocate resources more efficiently.

---

## 📊 Dataset Overview

- **Source:** Advertisement + Sales dataset  
- **Rows:** 200+ records  
- **Features:**  
  - `TV`: TV advertising budget  
  - `Radio`: Radio advertising budget  
  - `Newspaper`: Newspaper advertising budget  
- **Target:**  
  - `Sales`: Units sold (in thousands)

---

## 🧪 Model & Evaluation

- **Model Used:** Linear Regression  
- **Train-Test Split:** 80% training / 20% testing  
- **R² Score:** `0.8999`  
- **RMSE:** `1.77`  
- **Visualization:** Scatterplot of Actual vs Predicted Sales


---

## 🔍 Key Insights

- The model achieved a strong **R² score of 0.899**, explaining nearly **90% of the variation** in sales.  
- The **visualization** shows predictions closely follow actual values with no major outliers.
- This proves that **TV and Radio advertising** have a strong predictive influence on product sales.
- Even a simple Linear Regression model is effective when applied to **well-prepared, clean data**.

---

## 📁 Project Structure
advertising
├── advertisement.ipynb # Main notebook
├── README.md # Project summary

## ✅ Status

✔️ Completed  
✔️ Clean dataset  
✔️ Fully trained + evaluated  
✔️ GitHub-ready  