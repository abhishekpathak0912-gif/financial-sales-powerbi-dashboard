# 📊 Financial Sales Dashboard — Power BI

An interactive **Financial Sales Dashboard** built using **Microsoft Power BI** to analyze sales, profit, profit margins, products, countries, and monthly performance.

The dashboard converts raw financial data into an interactive business intelligence report that helps identify sales trends, profitable products, and geographical performance.

## 🚀 Dashboard Overview

The dashboard provides an executive-level view of financial performance through:

- Total Sales
- Total Profit
- Total Units Sold
- Profit Margin %
- Sales by Product
- Profit by Product
- Profit Margin by Product
- Sales by Country
- Monthly Sales Trends
- Interactive Country and Year filters

## 📌 Key KPIs

| KPI | Description |
|---|---|
| **Total Sales** | Overall revenue generated |
| **Total Profit** | Overall profit generated |
| **Total Units Sold** | Total quantity of products sold |
| **Profit Margin %** | Profit as a percentage of total sales |

## 📈 Dashboard Visualizations

### Sales Trend
A line chart showing how sales change throughout the year, allowing identification of:

- High-performing months
- Low-performing months
- Seasonal trends
- Major changes in sales performance

### Sales by Product
A horizontal bar chart comparing total sales across products such as:

- Paseo
- VTT
- Velo
- Amarilla
- Montana
- Carretera

### Profit by Product
Shows which products generate the highest overall profit.

### Profit Margin by Product
Compares the profitability efficiency of individual products.

### Sales by Country
Compares sales performance across different countries, including:

- Canada
- France
- Germany
- Mexico
- United States of America

### Interactive Filters

The dashboard includes slicers for:

- **Country**
- **Year**

These filters dynamically update the dashboard visuals.

## 🧮 DAX Measures

The project uses DAX measures to calculate important business metrics.

### Total Sales

```DAX
Total Sales = SUM('Financial Sample'[Sales])
```

### Total Profit

```DAX
Total Profit = SUM('Financial Sample'[Profit])
```

### Total Units Sold

```DAX
Total Units Sold = SUM('Financial Sample'[Units Sold])
```

### Profit Margin %

```DAX
Profit Margin % =
DIVIDE(
    [Total Profit],
    [Total Sales],
    0
)
```

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop**
- **Power Query**
- **DAX**
- **Data Visualization**
- **Data Modeling**
- **Financial Analysis**

## 📂 Project Structure

```text
Financial-Sales-Dashboard/
│
├── README.md
├── Financial_Sales_Dashboard.pbix
└── screenshots/
    └── dashboard.png
```

## 🎯 Business Questions Answered

This dashboard helps answer questions such as:

1. What are the total sales and profit?
2. Which products generate the most sales?
3. Which products generate the most profit?
4. Which products have the highest profit margins?
5. Which countries generate the most sales?
6. Which months have the highest sales?
7. How does performance change when filtering by country?
8. How does performance change across different years?

## 📊 Key Insights

From the dashboard:

- **Paseo** is the strongest product by total sales and total profit.
- **Amarilla** has the highest profit margin among the displayed products.
- **October** represents the strongest month in the sales trend.
- Sales performance varies considerably across products and countries.
- The dashboard allows these results to be explored dynamically using filters.

## 🖼️ Dashboard Preview

Add your dashboard screenshot here:

```markdown
![Financial Sales Dashboard](screenshots/dashboard.png)
```

## ▶️ How to Use

1. Download or clone this repository.
2. Install **Power BI Desktop**.
3. Open the `.pbix` file.
4. Use the Country and Year slicers to interact with the dashboard.
5. Select different visual elements to cross-filter the report.

## 📚 What I Learned

Through this project, I practiced:

- Creating interactive Power BI dashboards
- Building DAX measures
- Creating KPI cards
- Designing business-focused visualizations
- Working with categorical and time-series data
- Using slicers and cross-filtering
- Comparing sales, profit, and profitability
- Building an executive-style BI report

## 👤 Author

**Abhishek Pathak**

GitHub: [Add your GitHub profile here]

LinkedIn: [Add your LinkedIn profile here]

---

⭐ If you found this project useful, consider giving the repository a star.