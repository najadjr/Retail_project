# 📊 Retail Sales Dashboard using Python & Streamlit

## Overview

This project focuses on analyzing retail sales data to uncover valuable business insights through data processing, visualization, and interactive reporting. Using Python and Streamlit, I developed a dashboard that allows users to explore sales performance, monitor key business metrics, and analyze customer and product trends.

The project follows a complete data analytics workflow—from cleaning raw data to presenting results in an easy-to-use dashboard.

---

## live streamlit dashboard
https://retailproject-ln5grxw7cmvmt3huskq7xu.streamlit.app/

## Project Goals

The main objectives of this project were to:

- Prepare and clean a raw retail dataset.
- Explore sales data to identify business trends.
- Calculate important business performance metrics.
- Build an interactive dashboard for data visualization.
- Practice real-world data analytics techniques using Python.

---

## Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Data analysis and dashboard development |
| Pandas | Data cleaning and manipulation |
| Plotly | Interactive visualizations |
| Streamlit | Dashboard development |
| Jupyter Notebook | Data exploration |
| VS Code | Project development |
| Git & GitHub | Version control |

---

## Dataset Description

The project uses a retail sales dataset containing around **80,000 transactions** with **33 different attributes**.

The dataset includes information such as:

- Customer details
- Order information
- Product categories
- Sales and profit values
- Regional data
- Payment methods
- Return information

---

## Data Preparation Process

Before beginning the analysis, the dataset was cleaned to improve its quality and reliability.

The preprocessing included:

- Removing duplicate records
- Correcting inconsistent values
- Formatting date columns
- Handling missing information
- Verifying quantity values
- Standardizing return status
- Creating a cleaned dataset for analysis

---

## Business Analysis Performed

Several analyses were carried out to understand business performance, including:

- Sales performance over time
- Regional revenue comparison
- Profit analysis
- Category-wise sales distribution
- Customer contribution analysis
- Year-over-year sales comparison

---

## Dashboard Features

The Streamlit application provides an interactive interface where users can:

- View important KPIs
- Filter data by region, category, and customer segment
- Analyze monthly sales trends
- Compare regional performance
- Identify top-performing customers
- Explore the cleaned dataset interactively

---

## Key Metrics Displayed

The dashboard highlights several business indicators:

- Total Revenue
- Total Profit
- Total Orders
- Profit Margin
- Average Order Value
- Return Rate
- Repeat Customer Rate
- Top 10 Customers

---

## Project Structure

```
Retail_Project/
│
├── analysis.ipynb
├── dashboard.py
├── retail_sales.csv
├── retail_sales_clean.csv
├── README.md
```

---

## Running the Project

### Clone the repository

```bash
git clone https://github.com/najadjr/Retail_project.git
```

### Open the project

```bash
cd Retail_Project
```

### Install the required packages

```bash
pip install pandas plotly streamlit
```

### Launch the dashboard

```bash
streamlit run dashboard.py
```

---

## Major Findings

After analyzing the data, several important observations were made:

- Sales fluctuate across different months.
- Certain regions consistently generate higher profits.
- Some product categories contribute more revenue than others.
- A relatively small group of customers accounts for a significant portion of total sales.
- Business performance shows positive growth across multiple years.

---

## Skills Demonstrated

This project helped strengthen my understanding of:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- KPI Reporting
- Dashboard Development
- Python Programming
- Business Data Analysis
- Git & GitHub Workflow

---

## Future Enhancements

Possible improvements for future versions include:

- Sales forecasting using machine learning
- Customer segmentation analysis
- Inventory performance dashboard
- Export reports to PDF or Excel
- User authentication
- Mobile-friendly dashboard

---

## Conclusion
This project demonstrates practical skills in data cleaning, data analysis, KPI reporting, and dashboard development. It highlights how raw business data can be transformed into meaningful insights that support better decision-making.

---

## 📷 Dashboard Preview

### 🏠 Dashboard Home

This is the main dashboard displaying key business metrics such as Revenue, Profit, Orders, and Average Order Value (AOV), along with the monthly sales trend.

![Dashboard Home](screenshots/dashboard_home.png)

---

### 📊 Sales and Profit by Region

This visualization compares total sales and profit across different regions, helping identify the highest-performing markets.

![Sales and Profit by Region](screenshots/sales_profit_region.png)

---

### 🥧 Category-wise Sales Distribution

This pie chart illustrates the contribution of each product category to overall sales.

![Category Distribution](screenshots/category_distribution.png)

---

### 👥 Top 10 Customers

This chart highlights the top ten customers based on total sales, allowing businesses to identify their most valuable customers.

![Top Customers](screenshots/top_customers.png)

---

### 🎯 Interactive Dashboard Filters

The dashboard provides dynamic filters for Region, Category, and Customer Segment, enabling users to analyze specific business scenarios in real time.

![Interactive Filters](screenshots/filtered_dashboard.png)

## Author

**Najad K Sabeen**

B.Sc. Computer Science

MES Kalladi College, Kerala

GitHub: https://github.com/najadjr

---

Thank you for visiting this project. Feedback and suggestions are always welcome!
