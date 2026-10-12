# 📊 Super Store Sales & Profit Dashboard | Power BI

An interactive Business Intelligence dashboard built with **Microsoft Power BI** to analyze sales performance, category profitability, customer segments, and quarterly trends. This project transforms raw Superstore data into actionable insights through KPI tracking and interactive data visualizations.

## 📌 Project Overview

The Super Store Sales & Profit Dashboard provides a consolidated view of business performance across sales, products, cities, and customer segments.

Designed to support data-driven decision-making, the dashboard helps identify high-performing markets, compare category-level profitability, and explore sales trends throughout the year.

## 🎯 Project Objectives

- Analyze overall sales, profit, and quantity sold.
- Evaluate profitability across product categories.
- Identify cities with the highest sales performance.
- Track quarterly sales trends and seasonal patterns.
- Compare performance across customer segments.
- Present business metrics through an interactive dashboard.
- Translate raw data into meaningful business insights.

## 📈 Key Performance Indicators

| KPI | Dashboard Value |
|---|---:|
| Total Sales | 175.23K |
| Maximum Profit | 8.40K |
| Total Quantity Sold | 22K |

> **Data validation note:** These figures reflect the values currently displayed in the dashboard. The profit KPI should be verified against the underlying dataset and the DAX measure definition before publication. Maximum profit should also be clearly distinguished from total profit.

## 🔍 Dashboard Features

### 1. 🏙️ Sales Analysis by City

- Compares sales across different cities.
- Highlights Newark as the highest-sales city in the displayed visualization.
- Helps identify strong-performing markets and potential regional opportunities.

### 2. 💰 Profitability Analysis by Category

The dashboard compares profit across three major product categories.

| Product Category | Profit | Contribution |
|---|---:|---:|
| Technology | 90.46K | 51.62% |
| Office Supplies | 74.80K | 42.68% |
| Furniture | 9.98K | 5.69% |

**Key observation:** Technology accounts for the largest share of reported category profit, followed by Office Supplies. Furniture contributes the smallest share and warrants further investigation into discounts, pricing, and operating costs.

*Note: Category profit figures and percentages should be reconciled with the underlying dataset before being treated as final results.*

### 3. 📅 Quarterly Sales Analysis

The dashboard visualizes sales performance across all four quarters.

| Quarter | Sales |
|---|---:|
| Q1 | 0.22M |
| Q2 | 0.27M |
| Q3 | 0.34M |
| Q4 | 0.52M |

**Key observation:** Displayed sales increase throughout the year, with Q4 recording the highest value. This trend provides a starting point for investigating seasonality, promotional activity, and changes in customer demand.

### 4. 👥 Customer Segment Analysis

Explore sales performance across three customer segments:

- **Consumer** — individual customer purchases.
- **Corporate** — business customer purchases.
- **Home Office** — purchases associated with home-office customers.

This analysis helps compare segment performance and identify opportunities for more targeted sales strategies.

### 5. 📦 Product-Level Analysis

The dashboard provides detailed product-level information, including:

- Product name
- City
- Average profit
- Percentage contribution to sales

These details enable users to investigate individual product performance, compare profitability, and identify products that may require further analysis.

## 💡 Key Business Insights

Based on the currently displayed dashboard values:

- **Technology leads category profitability:** It represents approximately 51.62% of the reported category profit.
- **Q4 is the strongest quarter:** Sales reach 0.52M in the displayed quarterly analysis.
- **Newark leads the displayed city comparison:** The city stands out as a potential focus for regional performance analysis.
- **Furniture has the smallest reported profit contribution:** Reviewing discounts, pricing, and costs could help explain its lower contribution.
- **Customer segments offer opportunities for targeted analysis:** Comparing purchasing patterns can help inform marketing and sales decisions.

These findings are preliminary observations from the dashboard. They should be validated against the source data before being used to make business decisions.

## 🛠️ Tools & Technologies

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Interactive dashboard development and reporting |
| Microsoft Excel | Data inspection and preparation |
| Data Cleaning | Improving data quality and consistency |
| Data Modeling | Organizing data for analytical reporting |
| Data Visualization | Communicating trends and comparisons |
| Business Intelligence | Converting business data into insights |

## 📂 Project Structure

```text
Super-Store-Sales-Dashboard/
│
├── README.md
├── dataset/
│   └── superstore_dataset.csv
├── dashboard/
│   └── superstore_dashboard.pbix
└── screenshots/
    └── dashboard.png
```

*The structure above is illustrative. Update the filenames and folders to match the actual contents of your repository.*

## 🚀 Getting Started

### Prerequisites

- Microsoft Power BI Desktop
- The source Superstore dataset, if required by the dashboard

### Steps to Explore

1. Clone or download this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. If prompted, configure the dataset source path.
4. Refresh the data if required.
5. Explore the KPI cards, charts, category comparisons, and customer segment analysis.
6. Use the dashboard's available filters and interactive visuals to investigate business performance.

## 🧠 Skills Demonstrated

- Data Cleaning and Preparation
- Exploratory Data Analysis (EDA)
- Data Modeling
- Data Visualization
- Dashboard Development
- Business Intelligence Reporting
- KPI Analysis
- Trend and Comparative Analysis
- Business Insight Generation

## 🔮 Future Enhancements

- Add month-over-month and year-over-year sales comparisons.
- Develop DAX measures for total profit, profit margin, average order value, and sales growth.
- Introduce drill-through pages for regional and category-level analysis.
- Analyze the relationship between discounts and profitability.
- Add dynamic KPI cards and conditional formatting.
- Improve data validation and consistency across dashboard metrics.
- Include additional insights into customer behavior and product performance.

## 👨‍💻 Author

**Rudraksh Bhatnagar**  
BCA Student • Data Science & AI

Interested in Data Analytics, Business Intelligence, Python, and data-driven problem-solving.

## ⭐ Support

If you find this project useful, consider giving the repository a star!

---

**Technologies:** Microsoft Power BI · Excel · Data Analytics · Business Intelligence

#PowerBI #DataAnalytics #BusinessIntelligence #DataVisualization #DashboardDevelopment
