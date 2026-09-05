# Amazon-Product-Customer-Review-Analysis-Using-Python
Performed exploratory data analysis on 1,465 Amazon products to analyze pricing, discounts, customer ratings, product categories, and review engagement. Used Pandas, NumPy, Matplotlib, and Seaborn for data cleaning, analysis, visualization, and business insight generation.

# Amazon Product & Customer Review Analysis Using Python

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on an Amazon product dataset to analyze product pricing, discount strategies, customer ratings, review activity, and category-level performance.

The analysis focuses on identifying patterns in **product prices, discounts, customer ratings, product categories, and customer engagement** to generate meaningful business insights.

---

## 🎯 Project Objectives

The key objectives of this analysis are:

* Analyze product distribution across different categories
* Understand product pricing patterns
* Analyze discount percentages and monetary savings
* Explore customer rating distribution
* Identify highly rated products
* Examine the relationship between price, discount, and rating
* Analyze customer review and rating engagement
* Generate actionable business insights from the data

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook**

---

## 📊 Dataset

The dataset contains **1,465 product records and 16 original columns** related to Amazon products and customer reviews.

### Key Features

| Column                | Description                     |
| --------------------- | ------------------------------- |
| `product_id`          | Unique product identifier       |
| `product_name`        | Product name                    |
| `category`            | Product category/sub-category   |
| `discounted_price`    | Product price after discount    |
| `actual_price`        | Original product price          |
| `discount_percentage` | Discount offered on the product |
| `rating`              | Customer rating                 |
| `rating_count`        | Number of ratings               |
| `about_product`       | Product description             |
| `user_id`             | Customer identifier             |
| `user_name`           | Customer name                   |
| `review_id`           | Review identifier               |
| `review_title`        | Review title                    |
| `review_content`      | Customer review                 |
| `img_link`            | Product image URL               |
| `product_link`        | Product page URL                |

---

## 🧹 Data Cleaning

The dataset required several preprocessing steps before performing the analysis.

### Cleaning activities performed:

* Checked dataset structure and data types
* Checked missing values
* Checked duplicate records
* Removed currency symbols from price columns
* Converted price columns to numeric format
* Converted discount percentage to numeric format
* Converted ratings to numeric format
* Cleaned rating count values
* Removed unnecessary leading/trailing spaces
* Created a `Main_category` column by extracting the primary category from the hierarchical category field

The dataset initially contained **2 missing values in `rating_count`** and no duplicate records.

---

## 🔍 Exploratory Data Analysis

### 1. Category Analysis

The project analyzes:

* Number of products by category
* Average product price
* Average customer rating
* Average discount

The major categories in the dataset include:

* Electronics
* Computers & Accessories
* Home & Kitchen
* Office Products
* Home Improvement
* Musical Instruments
* Car & Motorbike
* Health & Personal Care
* Toys & Games

Electronics contains the largest number of products in the dataset, followed by Computers & Accessories and Home & Kitchen.

---

### 2. Rating Analysis

The project examines customer rating distribution and identifies highly rated products.

Key findings:

* Average customer rating is approximately **4.09**
* Most products have ratings between **4.0 and 4.5**
* **104 products** have a rating of 4.5 or higher
* Very few products have ratings below 3.5

---

### 3. Price Analysis

The project analyzes the distribution of discounted product prices.

The discounted price ranges from approximately **₹39 to ₹77,990**, with a median price of approximately **₹799**.

The analysis also identifies products providing the highest monetary savings through discounts.

---

### 4. Discount Analysis

Discount percentages are analyzed to understand pricing strategies and their relationship with customer ratings.

The project investigates whether higher discounts are associated with better customer ratings and finds that **higher discounts do not necessarily result in higher ratings**.

---

### 5. Product & Customer Engagement Analysis

The analysis explores rating counts and review activity to identify products receiving higher levels of customer engagement.

The results indicate that customer engagement is concentrated among a relatively small number of products.

---

## 💡 Key Business Insights

The analysis produced the following major insights:

1. **Electronics has the largest product assortment** in the dataset.
2. Most products have ratings above 4, indicating generally positive customer feedback.
3. Electronics has the highest average listed price among the major categories.
4. Electronics also provides the highest average monetary savings.
5. Product price has a **weak relationship with customer rating**.
6. Higher discounts do not necessarily lead to higher customer ratings.
7. Customer engagement is concentrated among a relatively small number of products.

---

## 📈 Business Recommendations

Based on the analysis:

* Focus on high-engagement products to understand what drives customer interest.
* Use category-level pricing analysis to optimize product positioning.
* Avoid relying solely on high discounts to improve customer satisfaction.
* Monitor highly rated products and their characteristics for potential cross-selling or promotional opportunities.
* Use customer ratings and engagement metrics alongside pricing information when evaluating product performance.

---

## 📁 Project Structure

```text
Amazon-Product-Customer-Review-Analysis/
│
├── Amazon Product & Customer Review Analysis using Python.ipynb
├── README.md
└── dataset/
    └── amazon.csv
```

> **Note:** If the dataset is not included in the repository, provide the original dataset source/link in this section instead.

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
```

### 2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Open the notebook

```bash
jupyter notebook
```

Open:

```text
Amazon Product & Customer Review Analysis using Python.ipynb
```

### 4. Update the dataset path

Before running the notebook, update the dataset path according to your local environment.

---

## 📌 Skills Demonstrated

This project demonstrates practical Data Analyst skills including:

* Exploratory Data Analysis (EDA)
* Data Cleaning & Preprocessing
* Data Transformation
* Data Aggregation
* GroupBy Analysis
* Statistical Analysis
* Data Visualization
* Business Insight Generation
* Python-based Data Analysis

---

## 👩‍💻 Author

**Sweta Sharma**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

---

⭐ If you found this project useful, feel free to explore the repository and provide feedback.

