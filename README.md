# 🍽️ Zomato Data Analysis (EDA Project)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-orange)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-yellow)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-green)
![Jupyter Notebook](https://img.shields.io/badge/Tool-Jupyter%20Notebook-red)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## 📘 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of the **Zomato Restaurants Dataset** to uncover insights about restaurant ratings, cuisines, locations, and user preferences across different countries.  a

The goal is to analyze and visualize restaurant-related data to understand key trends that impact restaurant performance and customer satisfaction.

---

## 🎯 Objectives

- Clean and preprocess raw restaurant data  
- Explore relationships between **ratings**, **price range**, **votes**, and **location**
- Identify top cuisines and countries with the most listings  
- Visualize patterns using Python libraries  
- Prepare insights that could be used for **business strategy** or **machine learning modeling**

---

## 📊 Dataset Information

**Dataset Source:** Zomato Restaurants Dataset (public dataset, Kaggle / sample data)

| Column Name | Description |
|--------------|-------------|
| Restaurant Name | Name of the restaurant |
| Country Code | Code representing the country |
| City | City where the restaurant is located |
| Cuisines | Type(s) of food served |
| Aggregate Rating | Average customer rating |
| Votes | Number of user votes received |
| Price Range | Price category (1–4) |
| Currency | Currency used in that country |

---

## 🧹 Data Cleaning Steps

- Handled missing values using imputation or removal  
- Merged country data using `Country-Code.xlsx`  
- Removed irrelevant columns (Email, Address, Avatar, etc.)  
- Detected and capped outliers in numeric variables  
- Converted categorical data into suitable formats  
- Checked correlations and feature relationships

---

## 📈 Exploratory Data Analysis

Key visualizations and statistical analysis performed:

- **Distribution of Ratings**  
- **Most Popular Cuisines**  
- **Restaurants by Country and City**  
- **Price Range vs. Ratings**  
- **Correlation Heatmap**  
- **Top 10 Rated Restaurants**  

## 🧰 Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| **Python** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical plotting |
| **Jupyter Notebook** | Development environment |

---

## 💡 Key Insights

- 🇮🇳 **India** has the maximum number of restaurants on the platform.  
- 🍴 Higher-rated restaurants tend to have a **mid-range price level**.  
- 🍜 **North Indian**, **Chinese**, and **Fast Food** cuisines are the most popular globally.  
- 👍 **Votes** have a positive correlation with **Aggregate Rating**.
## 🔍 Exploratory Questions

- Which country has the most Zomato listings?  
- What cuisines are most common across top-rated restaurants?  
- How does price range affect customer ratings?  
- Are more votes always associated with higher ratings?  
- What are the most popular cuisines by region?

---

## 📈 Top Visualizations

- 🌍 Country-wise restaurant distribution (**Bar Chart**)  
- 🍽️ Top cuisines by average rating (**Horizontal Bar Chart**)  
- 💰 Price Range vs Aggregate Rating (**Boxplot**)  
- 🔥 Correlation Heatmap  
- 👍 Votes vs Ratings (**Scatter Plot**)

---

## 🧾 Acknowledgements

- [Kaggle Zomato Dataset](https://www.kaggle.com/datasets)  
- Zomato API documentation for reference  
- Open-source Python community for inspiration  

---

## 👨‍💻 Author

**Sanjay Merugu**  
📧 [sanjaymerugu@gmail.com](mailto:sanjaymerugu@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/sanjaymerugu)  
📊 Data Science Enthusiast | Power BI | Python | SQL | Machine Learning
