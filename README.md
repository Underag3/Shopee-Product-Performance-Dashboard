# 🛒 Shopee Product Performance Dashboard

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Looker Studio](https://img.shields.io/badge/Looker_Studio-Dashboard-4285F4.svg)](https://lookerstudio.google.com/)

**[View Live Dashboard Here](https://datastudio.google.com/reporting/526c8331-9037-49aa-9a81-361d86d54bc2)**

## 📌 Overview Project
This project aims to analyze and visualize product performance on the Shopee e-commerce platform. Through an interactive dashboard built using Google Data Studio (Looker Studio), users can monitor various key business metrics such as [name key metric, e.g., total sales, best-selling products, or revenue trends].

The data preparation process (cleaning and transformation) was performed entirely in Python before being imported into the visualization tool.

## 🛠️ Tools and Technologies
* **Programming Language:** Python (via Jupyter Notebook)
* **Data Processing Library:** [Specify library, e.g., Pandas, NumPy]
* **Visualization & Dashboard:** Google Data Studio / Looker Studio
* **Data Source:** [Specify data source, e.g., web scraping, Kaggle, or internal dataset]

## 📂 Repository Structure
* `Data Cleaning.ipynb`: A notebook containing steps for cleaning raw data, handling missing values, and formatting the data to prepare it for analysis.
* `[Dataset_Clean_File_Name.csv]`: *(Optional - If you uploaded the data)* The cleaned dataset used in the dashboard.

## 💡 Key Insights
1. **Impulse Buying & Repeat Order Phenomenon:** The Sales-to-Favorite ratio reached 1.27 (127%), indicating that consumers often make purchases immediately without first 'bookmarking/favoriting' or making repeat purchases.
2. **Home Appliances Category as the Main Revenue Driver:** Contributed the highest revenue of IDR 242.2 million despite lower sales volume, indicating a high average product price (AOV) but requiring strict evaluation of quality due to its lowest rating (4.41).
3. **High Window Shopping Behavior in Women's Fashion:** The women's clothing and handbags category had a high volume of interest (Favorites), but had the lowest conversion ratio (<0.75), indicating that consumers needed additional incentives (such as vouchers or free shipping) to checkout.
4. **Groceries & Pets Has the Highest Loyalty:** Recording the highest Sales/Favorite ratio of 2.76, making it the most potential category for subscription-based marketing.

## 🚀 How to Run a Local Project (Data Preparation Stage)
If you want to view or modify the data cleaning process:

1. Clone this repository:
```bash
git clone [https://github.com/Underag3/Shopee-Product-Performance-Dashboard.git](https://github.com/Underag3/Shopee-Product-Performance-Dashboard.git)

2. Make sure you have the required libraries installed. You can install them via pip:

```bash
pip install pandas numpy jupyter
```
3. Run Jupyter Notebook:

```
jupyter notebook
```
4. Open the Data Cleaning.ipynb file and run the cells in it.

## 👤 Author
Mohammad Tyas Subianto
