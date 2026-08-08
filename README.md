# 📊 Sales Analysis using Python

## 📌 Project Overview

This project focuses on analyzing **12 months of sales data** from an electronics store using Python. The objective is to clean, explore, and analyze the sales data to uncover meaningful business insights and answer important questions related to sales performance, products, customers, cities, and advertising strategies.

The analysis was performed using **Pandas** for data manipulation and **Matplotlib** for data visualization.

---

## 🎯 Objectives

The main objectives of this project are to:

* Clean and prepare raw sales data for analysis
* Analyze monthly sales performance
* Identify the best-performing month
* Find the city with the highest number of sales
* Determine the best time to display advertisements
* Identify products that are frequently purchased together
* Find the best-selling products
* Understand factors that may influence product sales
* Visualize important findings using charts and graphs

---

## 🛠️ Technologies & Libraries

* **Python**
* **Pandas** – Data cleaning, manipulation, and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Jupyter Notebook** – Analysis and documentation

---

## 📂 Project Structure

```text
Sales-Analysis/
│
├── Sales Data/
│   ├── Sales data files
│
├── all_data.csv
├── sales analysis.ipynb
└── README.md
```

---

## 🧹 Data Cleaning

Before performing the analysis, the raw sales data was cleaned and prepared.

The data-cleaning process included:

* Removing missing values
* Removing rows based on specific conditions
* Converting columns to appropriate data types
* Converting date/time columns using `to_datetime`
* Converting numerical columns using `to_numeric`
* Combining multiple datasets into a single DataFrame
* Creating new columns from existing data

---

## 📈 Business Questions

The project answers the following key business questions:

### 1. What was the best month for sales?

Monthly sales were analyzed to identify the month with the highest revenue and understand sales trends throughout the year.

### 2. Which city sold the most products?

Sales were grouped by city to determine which location generated the highest number of sales.

### 3. What is the best time to display advertisements?

Order timestamps were analyzed to identify the hours when customers were most likely to make purchases. This can help the business optimize its advertising schedule.

### 4. What products are frequently sold together?

Order-level analysis was performed to identify products that customers commonly purchase together. These insights can be useful for product bundling and cross-selling strategies.

### 5. Which product sold the most?

Product-level sales were analyzed to identify the most popular products and investigate possible reasons behind their performance.

---

## 📊 Analysis & Visualization

The project uses different Pandas and Matplotlib techniques, including:

* `groupby()`
* `concat()`
* `apply()`
* String manipulation
* Date/time extraction
* Aggregation
* Bar charts
* Line charts
* Data filtering
* Feature creation

These techniques were used to transform raw sales data into meaningful business insights.

---

## 💡 Key Insights

The analysis helps identify:

* Monthly sales trends
* High-performing cities
* Peak purchasing hours
* Best-selling products
* Frequently purchased product combinations
* Potential opportunities for targeted advertising
* Opportunities for product bundling and cross-selling

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/akhilesh-kumawat/Sales-Analysis.git
```

### 2. Navigate to the project directory

```bash
cd Sales-Analysis
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib jupyter
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
sales analysis.ipynb
```

Run the cells sequentially to reproduce the analysis.

---

## 📌 Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Manipulation
* Data Aggregation
* Feature Engineering
* Data Visualization
* Business Problem Solving
* Python for Data Analysis
* Pandas
* Matplotlib
* Jupyter Notebook

---

## 📎 Dataset

The project uses sales data containing information about electronics store purchases, including details such as:

* Order date
* Product
* Quantity ordered
* Price
* Purchase address
* Sales information


