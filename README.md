# 🍔 Foodpanda Data Analysis Project

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a Foodpanda-style food delivery dataset using **Python**. The objective is to clean, analyze, and visualize data to understand customer behavior, order patterns, ratings, and delivery performance.

The dataset contains **6,000+ records** with customer details, order information, food categories, payment methods, ratings, and delivery status.

---

## 🧩 Dataset Description

The dataset includes the following key features:

* Customer demographics (gender, age, city)
* Order details (restaurant, dish, category, price, quantity)
* Dates (signup date, order date, last order date, rating date)
* Order frequency and loyalty points
* Delivery status (Delivered, Cancelled, Delayed)
* Customer ratings (with missing values)

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 🔍 Key Analysis Steps

* Loaded and explored the dataset using Pandas
* Converted date columns to proper datetime format
* Identified and handled missing values in the `rating` column
* Imputed missing ratings logically based on order frequency
* Segmented data by delivery status: Delivered, Cancelled, and Delayed
* Performed customer and order behavior analysis
* Generated multiple visualizations for insights

---

## 📊 Visualizations Included

* Bar chart: Order frequency by dish
* Scatter plot: Dish preferences by age group
* Pie chart: Average ratings per dish
* Heatmaps: Loyalty points and payment methods vs gender
* Pair plots: Relationship between numerical variables
* Bar plots: Ratings by gender and food category

---

## 📈 Insights Gained

* Italian and Fast Food categories are the most popular
* Delivery performance is almost evenly split between Delivered, Delayed, and Cancelled
* Wallet, Cash, and Card payments are used nearly equally
* Higher order frequency customers tend to give better ratings
* Loyalty points vary significantly by restaurant and food type

---

## 🚀 Conclusion

This project demonstrates practical skills in **data cleaning, preprocessing, analysis, and visualization** using Python. It highlights the ability to transform raw data into meaningful insights, making it suitable for academic learning, internships, and entry-level data analyst roles.

---

## 📂 How to Run the Project

1. Clone this repository
2. Install required libraries

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the Jupyter Notebook and run all cells

---

## 📌 Author

**shirish**
Aspiring Data Analyst / Python Developer

