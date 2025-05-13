# 📊 Sales Data Analysis

A data analysis project focused on understanding key trends and business insights from retail sales data. This project combines data cleaning, transformation, and exploratory data analysis using Python and its powerful libraries.

---

## 🚀 Objective

To explore and analyze monthly sales data from 2019 to answer business-critical questions such as:

- Which month had the highest sales?
- Which cities generated the most revenue?
- Which products are frequently bought together?
- What is the relationship between product price and quantity sold?

---

## 🧾 Dataset Description

The dataset comprises multiple `.csv` files—each representing sales data for a month in 2019. These files contain:

- `Order ID`
- `Product`
- `Quantity Ordered`
- `Price Each`
- `Order Date`
- `Purchase Address`

> 📁 All files are stored in the `Sales_Data/` folder.

---

## 🛠️ Tools & Technologies

- **Language:** Python 3
- **Notebook:** Jupyter
- **Libraries:**
  - `pandas` – data manipulation
  - `numpy` – numerical operations
  - `matplotlib` & `seaborn` – data visualization
  - `os`, `glob` – file handling utilities

---

## 🔍 Key Insights

- 📅 **December** was the best month for sales, likely due to holiday shopping.
- 🏙️ **San Francisco** topped the list for city-wise revenue, followed by Los Angeles and New York City.
- 🔗 **Frequently Bought Together:** Items like *iPhone* and *Lightning Charging Cable* were commonly sold in pairs.
- 💰 **Price vs Quantity:** Lower-priced products had higher sales volumes, but premium products contributed significantly to revenue.

---

## 📂 Project Structure

Sales_Data_Analysis
```├── Sales_Data/```                 # CSV files
```├──Sales_Data_Analysis.ipynb```    # Jupyter notebook with analysis
```└── README.md```                   # Documentation file
