# 📊 Business KPI Dashboard | Power BI

An interactive Business Intelligence dashboard developed using **Power BI** to analyze retail business performance, monitor key performance indicators (KPIs), and generate actionable insights from Superstore sales data.

The project combines data analysis, KPI calculations, and interactive visualizations to provide a comprehensive view of sales, profitability, customer orders, and product category performance.

---

## 📌 Project Overview

Businesses generate large amounts of transactional data, but extracting meaningful insights requires effective analysis and visualization.

This project transforms processed retail sales data into an interactive Power BI dashboard that helps monitor business performance, identify trends, and understand differences across product categories and geographical regions.

**Primary Objective:**  
To develop an interactive business intelligence dashboard that presents key performance indicators and supports data-driven decision-making through visual analytics.

---

## 🎯 Project Objectives

- Analyze retail business performance using transactional data.
- Calculate and monitor important business KPIs.
- Identify monthly sales trends and variations.
- Compare sales performance across product categories.
- Examine the relationship between sales and profitability.
- Analyze regional business performance.
- Develop an interactive dashboard with dynamic filtering.

---

## 📂 Dataset Description

**Dataset:** Superstore Sales Dataset (Processed)

**Dataset File:**

```text
data/cleaned_superstore.csv
```

The dataset contains information related to:

- Sales transactions
- Profit and revenue
- Customer information
- Product categories
- Regional performance
- Order dates and transaction details

The processed dataset is used as the primary data source for KPI calculations and dashboard visualizations.

---

## 📊 Key Performance Indicators (KPIs)

The dashboard focuses on four primary business performance indicators.

| KPI | Description |
|---|---|
| Total Sales | Overall revenue generated from sales transactions |
| Total Profit | Total profit earned from business transactions |
| Order Count | Number of orders placed |
| Average Order Value (AOV) | Average revenue generated per order |

### KPI Calculation Logic

**1. Total Sales**

```text
Total Sales = SUM(Sales)
```

**2. Total Profit**

```text
Total Profit = SUM(Profit)
```

**3. Order Count**

```text
Order Count = DISTINCTCOUNT(Order ID)
```

**4. Average Order Value**

```text
AOV = Total Sales / Order Count
```

These KPIs provide a high-level overview of business performance.

---

## 🔍 Analysis Performed

### 1. Sales Trend Analysis

Monthly sales trends are analyzed to identify changes in revenue over time.

- Monthly sales aggregation.
- Identification of sales fluctuations.
- Observation of time-based patterns.
- Comparison of sales performance across periods.

### 2. Category-wise Performance Analysis

Sales performance is compared across different product categories.

- Category-level sales comparison.
- Identification of high-performing categories.
- Revenue contribution analysis.
- Comparison of category performance.

### 3. Sales vs Profit Analysis

The relationship between sales and profitability is examined to understand business performance.

- Comparison of sales and profit.
- Identification of differences in profitability.
- Examination of revenue and profit patterns.

### 4. Regional Performance Analysis

Business performance is explored across different geographical regions.

- Regional sales comparison.
- Identification of regional variations.
- Analysis of geographical performance differences.

---

## 📈 Dashboard Features

The Power BI dashboard includes the following components:

### KPI Summary Cards

- Total Sales
- Total Profit
- Order Count
- Average Order Value

### Interactive Visualizations

- Monthly sales trend using a line chart.
- Category-wise sales comparison using a bar chart.
- Sales and profitability analysis.
- Regional performance analysis.

### Interactive Filters

Users can explore business performance through filters for:

- Region
- Product Category
- Order Date

These filters allow users to investigate specific business segments and time periods.

---

## 🌐 Live Power BI Dashboard

Explore the interactive dashboard:

<p align="center">
  <a href="https://app.powerbi.com/groups/me/reports/476a8ae9-4be3-4b6a-8779-7daa45c7740b?ctid=1490b17d-5dc9-4cbf-aeba-a2e854f521b8&pbi_source=linkShare">
    <img src="https://img.shields.io/badge/OPEN%20POWER%20BI%20DASHBOARD-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Open Power BI Dashboard"/>
  </a>
</p>

---

## 🖼️ Dashboard Preview

Add your actual Power BI dashboard screenshots here.

For example:

```markdown
![Dashboard Overview](images/dashboard-overview.png)

![Sales Trend Analysis](images/sales-trend.png)
```

Recommended screenshots:

1. Complete dashboard overview.
2. KPI summary cards.
3. Monthly sales trend.
4. Category-wise sales comparison.

---

## 🛠️ Tools & Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Power BI | Interactive dashboard development |
| Jupyter Notebook | Exploratory analysis and KPI calculations |

---

## 📁 Project Structure

```text
business-kpi-dashboard-powerbi/
│
├── data/
│   └── cleaned_superstore.csv
│
├── notebooks/
│   └── KPI_Dashboard.ipynb
│
├── images/
│   ├── dashboard-overview.png
│   ├── sales-trend.png
│   └── category-performance.png
│
├── README.md
└── requirements.txt
```

*Note: The images directory and requirements file are suggested additions. Adjust the structure to match the actual repository.*

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Satyam1245/business-kpi-dashboard-powerbi.git
```

### 2. Navigate to the Project Directory

```bash
cd business-kpi-dashboard-powerbi
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate on Windows:

```bash
venv\Scripts\activate
```

Activate on Linux/macOS:

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 5. Run the Analysis Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/KPI_Dashboard.ipynb
```

Execute the notebook cells to explore the analytical workflow and KPI calculations.

### 6. Open the Power BI Dashboard

Open the published dashboard using the Power BI link above.

For local dashboard development, use Power BI Desktop and the corresponding project source file if available.

---

## 💡 Key Business Insights

The analysis focuses on identifying the following business patterns:

- Sales performance varies across different months.
- Product categories contribute differently to total revenue.
- Higher sales do not necessarily translate into proportionally higher profits.
- Regional differences influence overall business performance.
- KPI monitoring provides a consolidated view of business performance.

*Specific numerical findings should be added after verifying the dashboard and notebook results.*

---

## 🔗 Connection With Other Analytics Projects

This project is part of a broader retail analytics workflow:

| Project | Purpose |
|---|---|
| Retail Data Preprocessing Pipeline | Data cleaning and preparation |
| Retail Sales EDA Analysis | Exploratory analysis and trend discovery |
| Business KPI Dashboard | Business intelligence and performance monitoring |

Together, these projects demonstrate the progression from raw data preparation to analytical exploration and interactive business reporting.

---

## 🚀 Future Improvements

- Add year-over-year and month-over-month comparisons.
- Introduce additional profitability KPIs.
- Implement customer segmentation.
- Add product-level performance analysis.
- Develop sales forecasting capabilities.
- Introduce more advanced drill-through reports.
- Automate data refresh and reporting workflows.

---

## 🎓 Key Learning Outcomes

This project demonstrates practical experience in:

- Business Intelligence and dashboard development.
- KPI identification and calculation.
- Retail sales performance analysis.
- Data visualization and reporting.
- Interactive filtering and data exploration.
- Translating analytical findings into business insights.

---

## 👨‍💻 Author

**Satyam Chaudhary**

- GitHub: https://github.com/Satyam1245
- Project: https://github.com/Satyam1245/business-kpi-dashboard-powerbi

---

*Transforming business data into meaningful insights through analytics and visualization.*
