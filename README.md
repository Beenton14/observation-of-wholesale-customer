# 📊 Wholesale Customer Behavior Analysis

This project analyzes wholesale customer annual spending using exploratory data analysis (EDA) and supervised machine learning models. The goal is to understand customer purchasing patterns across different product categories and predict customer regions.

## ✅ Project Objectives
- Perform **Data Cleaning** and **Exploratory Data Analysis (EDA)**.
- Visualize **spending distributions** and **feature correlations**.
- Build and evaluate **classification models** using:
  - K-Nearest Neighbors (KNN)
  - Decision Tree
- Compare model performance using **accuracy**, **precision**, **recall**, and **F1-score**.

## 📁 Dataset Description
The dataset contains **439 customer records** with the following features:
- Annual spending on: Fresh, Milk, Grocery, Frozen, Detergents/Paper, Delicatessen
- Categorical features: Channel (Retail/Horeca), Region (Lisbon, Oporto, Other)

## 🛠️ Tools & Libraries
- **Python**, **Pandas**, **Matplotlib**, **Seaborn**
- **Scikit-learn** for machine learning models and evaluation metrics

## 📌 Key Findings
- EDA reveals spending patterns vary significantly by **channel** and **region**.
- **KNN** showed better generalization across test sets, while **Decision Tree** tended to **overfit**.
- Performance metrics highlight trade-offs between accuracy and precision across models.

## 💻 How to Run
1. Clone the repository
```bash
git clone https://github.com/yourname/observation-of-wholesale-customer.git
