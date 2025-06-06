# Automotive-Coupon-Recommendation-System

# 🚗 Automotive Coupon Recommendation System

This project is focused on developing a machine learning model to predict whether a customer will accept a specific automotive coupon offer based on their profile and behavioral data. The goal is to optimize coupon targeting strategies to improve acceptance rates and marketing efficiency.

## 📌 Table of Contents

- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Preprocessing](#preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [How to Run](#how-to-run)
- [Future Work](#future-work)
- [Contributors](#contributors)

---

## 🔍 Overview

The **Automotive Coupon Recommendation System** leverages customer and contextual data to recommend coupons for:

- Restaurant (20% off)
- Coffee House
- Carry-out & Take away
- Bar
- Restaurant (less than $20)

The model predicts whether a user will **accept or reject** the offered coupon using supervised learning techniques.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models
- **Jupyter Notebook** – Development environment

---

## 📂 Dataset

- Source: [UCI Machine Learning Repository - In-vehicle Coupon Recommendation](https://archive.ics.uci.edu/ml/datasets/In-Vehicle+Coupon+Recommendation)
- Records: ~5000
- Features:
  - User demographics (age, gender, income, etc.)
  - Time and location context
  - Type of coupon offered
  - Mode of transport, etc.
- Target:
  - Whether the user accepted the coupon (`Y/N`)

---

## 📊 Exploratory Data Analysis

Performed EDA to identify:

- Feature distributions and outliers
- Correlations between variables
- Class imbalance in the target variable
- Importance of features like time, income, destination, etc.

---

## 🧹 Preprocessing

- Handled missing/null values
- Label encoded categorical features
- Scaled numerical features using `StandardScaler`
- Train-test split (80-20)

---

## 🤖 Modeling

Implemented and compared the performance of various models:

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 76%     |
| Random Forest       | 81%     |
| Decision Tree       | 78%     |
| K-Nearest Neighbors | 74%     |

**Best performing model:** ✅ Random Forest

---

## 📈 Results

- **Accuracy:** 81% (Random Forest)
- **Precision & Recall:** Balanced across both classes
- **Confusion Matrix & ROC Curve:** Plotted for detailed evaluation

---

## 💻 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yashbhargavajuet/Automotive-Coupon-Recommendation-System.git
   cd Automotive-Coupon-Recommendation-System
