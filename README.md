# ISM Store Data Analysis 📊

This project analyzes raw transactional data from **ISM Store** for the year 2025. The dataset captures each order with details such as date, category, gender, state, quantity, and amount, enabling a variety of business insights.

---

## 📁 Dataset Overview

The **`ISM Store`** sheet contains the following columns:

- **Order Date** – The date when the order was placed.
- **Category** – Product category (e.g., Clothing, Footwear, Accessories).
- **Gender** – Gender of the customer.
- **State** – Customer’s state.
- **Quantity** – Number of units purchased.
- **Amount** – Total amount for the order.
- **Age Group** – Customer’s age group (e.g., Teen, Adult, Senior).
- **Order Status** – Whether the order was delivered, canceled, or pending.

---

## 🔍 Example Insights

From the dataset, you can analyze:

- **Top-Selling Categories** – Identify the highest-revenue product types.
- **Gender-Based Purchases** – Compare male vs female buying patterns.
- **State Performance** – Determine high-performing and low-performing states.
- **Seasonal Trends** – Discover peak months or festive spikes in sales.
- **Order Fulfillment** – Track delivery vs cancellation rates.

---

## 🛠️ Tools for Analysis

You can work with this dataset in:

- **Excel** – For pivot tables, charts, and quick summaries.
- **Python** – For deeper analysis:
  - `pandas` – Data manipulation
  - `matplotlib` / `seaborn` – Visualizations

---

## 🚀 How to Use

1. Download the file **`ISM Store Data Analysis.xlsx`**.
2. Open the **`ISM Store`** sheet.
3. Perform analysis using Excel or run the sample Python script below:

```python
import pandas as pd

df = pd.read_excel("ISM Store Data Analysis.xlsx", sheet_name="ISM Store")
print(df.head())
