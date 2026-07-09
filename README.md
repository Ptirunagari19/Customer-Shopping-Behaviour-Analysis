

<img width="1920" height="981" alt="Screenshot 2026-06-12 150747" src="https://github.com/user-attachments/assets/9b1ad7c1-df82-4172-8ffb-cc803c220e40" />


# 🛍️ Customer Shopping Behaviour Analysis

> An end-to-end analytics project — from raw data through Python EDA, SQL querying, and an interactive Power BI dashboard — built to surface actionable insights from retail customer transactions.

---

## 🔧 Tools & Technologies

| Tool | Role |
|---|---|
| Python (Pandas, NumPy) | Data cleaning and exploratory analysis |
| Matplotlib & Seaborn | Statistical visualizations |
| SQL | Business question analysis |
| Power BI Desktop | Interactive dashboard |
| Jupyter Notebook | Analysis environment |
| Git & GitHub | Version control |

---

## 🚀 End-to-End Pipeline

```
Raw CSV → Python EDA (Jupyter) → SQL Analysis → Power BI Dashboard
```

---

## 📦 About the Dataset

Retail transaction records across a diverse customer base, including:

| Field | Description |
|---|---|
| Customer ID | Unique identifier per shopper |
| Age & Gender | Demographic profile |
| Product Category | Type of item purchased |
| Purchase Amount | Transaction value |
| Payment Method | How the customer paid |
| Subscription Status | Whether the customer is subscribed |
| Rating | Customer satisfaction score |

---

## 🐍 Python Analysis (Jupyter Notebook)

### Data Cleaning
- Resolved missing values and removed duplicates
- Standardised categorical fields (gender, subscription status, shipping types)
- Corrected data types for reliable aggregation

### Exploratory Data Analysis (EDA)
- Spending distribution across age groups and gender
- Product category performance by revenue and volume
- Payment method preferences by demographic segment
- Subscription vs non-subscription spending comparison
- Correlation analysis across key variables

### Visualizations Built
- Bar and column charts for category and demographic comparisons
- Histograms for spend distribution
- Pie charts for category and subscription share
- Heatmaps for variable correlation

---

## 🔍 SQL Analysis

Business questions answered through SQL queries:

| # | Question |
|---|---|
| 1 | Total revenue breakdown by gender |
| 2 | High-spending customers who used discounts |
| 3 | Top products by average review rating |
| 4 | Spending comparison across shipping types |
| 5 | Subscribed vs non-subscribed customer behaviour |
| 6 | Products with highest discount usage |
| 7 | Revenue contribution by age group |

---

## 📊 Power BI Dashboard

### KPI Cards
- Total number of customers — **77**
- Average purchase amount — **$59.90**
- Average review rating — **3.74**

### Visualizations
- Donut chart — subscription status breakdown
- Bar charts — revenue and sales by product category
- Horizontal bar charts — revenue and sales by age group

### Interactive Slicers
- Subscription Status
- Gender
- Category
- Shipping Type

---

## 💡 Key Findings

- A small number of categories drive a disproportionate share of total revenue
- Subscribed customers show higher average spend and purchase frequency
- Age and gender are strong predictors of category preference and spend level
- Customers using discounts still complete high-value transactions
- Repeat customers account for the majority of overall sales

---

## 📁 Project Structure

```
Customer-Shopping-Behaviour-Analysis/
│
├── customer_shopping_behavior.csv
├── customer_shopping_behavior_Analysis.ipynb
├── Customer_bhevaior_SQL_script.sql
├── Customer_behavior_dashboard.pbix
├── README.md
└── .gitignore
```

---

## ▶️ Getting Started

**Clone the repo**
```bash
git clone https://github.com/Ptirunagari19/Customer-Shopping-Behaviour-Analysis.git
cd Customer-Shopping-Behaviour-Analysis
```

**Install Python dependencies**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**Run the notebook**
```bash
jupyter notebook customer_shopping_behavior_Analysis.ipynb
```

**Open the dashboard**

Open `Customer_behavior_dashboard.pbix` in Power BI Desktop.

---

## 🔭 What's Next

- Connect Power BI directly to a SQL database for live data refresh
- Apply K-Means clustering for customer segmentation
- Build a purchase prediction model using classification techniques
- Automate the pipeline using Azure Data Factory

---

## 🤝 Contributing

Open to feedback and collaboration. Fork the repo and raise a pull request with any improvements.

## 👩‍💻 Author

**Pranusha Tirunagari**  
Data Engineer | Azure | Databricks | PySpark | Power BI  
📍 [LinkedIn](https://www.linkedin.com/in/pranusha-tirunagari-a583a63a8/) | [GitHub](https://github.com/Ptirunagari19)
