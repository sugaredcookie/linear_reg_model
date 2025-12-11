# 📏 Height–Weight Linear Regression Project

A small machine learning project that predicts a person's weight based on their height using simple linear regression. The goal is to understand how the model works mathematically, not just how to run the code. 🤖📚

---

## 📌 Overview
This project uses a height–weight dataset to:
- 📊 Split the data into training and testing sets  
- 🔧 Scale the height values using StandardScaler  
- 🧠 Train a Linear Regression model  
- 📈 Evaluate performance using the R² score  
- 🔮 Predict weight for new height values  

Everything here revolves around finding the best straight line that describes the relationship between height and weight.

---

## 🖥️ How to Run This on Your PC
1. 📁 Clone or download the project folder  
2. 🧪 Create and activate a virtual environment  
3. 📦 Install dependencies using:  (requirements.txt)

---

## 📚 The Math Behind It
Linear regression fits a straight line of the form:

**weight = m * height + b**

Where:  
- 📐 **m** = slope  
- 🎯 **b** = intercept  

The model finds the best values of m and b by minimizing the **SSE (Sum of Squared Errors):**

SSE = Σ (y_actual - y_predicted)²,
 To measure how well the model fits the data, we use the **R² score**:

R² = 1 - (SSE / SST),
 Where **SST** is the total variation in actual weight values.

- ⭐ R² close to 1 → model explains most of the variation  
- ⚠️ R² near 0 → model is barely better than guessing the mean  

In this project, the model achieves about **0.73**, meaning it explains roughly 73% of the relationship between height and weight.

---

A simple project, but perfect for understanding how machine learning models actually work under the hood. 🚀
