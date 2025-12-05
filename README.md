# retail-sales-eda
Exploratory Data Analysis on retail sales data using Python. Includes data cleaning, feature engineering, time series trends, category performance, customer insights and business recommendations supported by visualizations.


# Retail Sales and Customer Behavior Analysis using Python

This project performs end to end Exploratory Data Analysis (EDA) on a retail sales dataset. The goal is to understand sales performance, customer behavior, revenue patterns, product category trends and derive actionable business insights supported by visualizations.

---

## 📌 Project Objectives
- Clean and preprocess retail transaction data  
- Perform univariate and bivariate analysis  
- Analyze monthly revenue trends and seasonality  
- Study customer behavior and spending patterns  
- Identify top performing product categories  
- Visualize insights using Matplotlib and Seaborn  
- Provide business recommendations based on findings  

---

## 📁 Project Structure
├── retail_eda_notebook.ipynb # Full analysis code
├── retail_sales_cleaned.csv # Cleaned dataset (optional)
├── figures/ # Exported charts (optional)
├── README.md # Project documentation
└── requirements.txt # Python dependencies


---

## Tech Stack
- **Python**
- **Pandas** for data cleaning and manipulation  
- **NumPy** for numerical operations  
- **Matplotlib** & **Seaborn** for visualizations  
- **Google Colab / Jupyter Notebook** for execution  

---

## Key Analysis Performed

### ✔ Data Cleaning
- Handled date formats  
- Standardized column names  
- Validated numeric columns (quantity, price, total amount)  
- Extracted new features (year, month, weekday, order_month)

### ✔ Univariate Analysis
- Age distribution  
- Gender distribution  
- Product category frequency  
- Total amount distribution  

### ✔ Revenue Insights
- Revenue by product category  
- Monthly revenue trend  
- Revenue by weekday  

### ✔ Customer Behavior Insights
- Top 10 customers by total spending  
- Purchase amount patterns by age and gender  
- Quantity vs revenue relationships  

### ✔ Correlation Analysis
- Heatmap showing relationships among numeric variables  


---

## How to Run the Project

### **Option 1: Google Colab (Recommended)**  
1. Upload the dataset retail_sales_dataset.csv  
2. Open retail_eda_notebook.ipynb in Colab  
3. Run all cells

### **Option 2: Local Machine**
```bash
git clone https://github.com/YOUR_USERNAME/retail-sales-eda.git
cd retail-sales-eda
pip install -r requirements.txt
jupyter notebook

