<div align="center">

# 📱 Mobile Sales Analysis Dashboard

### An Interactive Power BI Business Intelligence Project

**Turning mobile sales data into actionable business insights**

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analytics](https://img.shields.io/badge/Domain-Data%20Analytics-2563EB?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Portfolio%20Project-198754?style=for-the-badge)

</div>

---

## 📌 Project Overview

The **Mobile Sales Analysis Dashboard** is an interactive Power BI project designed to explore sales performance, transaction volume, mobile model performance, payment preferences, customer ratings, and sales trends over time.

The report brings key performance indicators and detailed visuals into one place, helping business stakeholders monitor performance and identify areas that may need further investigation.

## 🎯 Business Objectives

- Monitor overall sales, quantity sold, transaction count, and average price.
- Compare yearly sales with the same period in the previous year.
- Track month-to-date (MTD) sales progress.
- Compare sales by mobile brand and model.
- Understand transaction patterns across payment methods and customer-rating categories.
- Explore sales and quantity trends by month, weekday, and location.

## 🖥️ Dashboard Preview

### 1. Main Sales Dashboard

The overview page highlights key sales KPIs and compares yearly performance with the previous year. Filters allow users to explore the report by mobile model, payment method, and date hierarchy.

![Dashboard.png](https://github.com/Tinku679/Power-BI-Data-Analytics-Projects/blob/main/Dashboard.png)

### 2. Same Period Last Year Analysis

This page focuses on year-to-date/month-to-date style comparisons and shows the selected year's daily sales progression. In the example shown, **2022** is selected and the cumulative chart reaches approximately **22.8M**.

![Same Period Last Year Report](images/Same%20period%20Last%20year.png)

### 3. MID Report — Sales and Customer Insights

This page provides a more detailed view of monthly quantity, customer-rating categories, payment-method transactions, brand performance, mobile-model sales, and weekday sales patterns.

![Mobile Sales MID Report](images/MID%20report.png)

## 📊 Key Metrics Shown

The dashboard screenshots show the following overall figures:

| KPI | Value shown | What it helps monitor |
|---|---:|---|
| Total Sales | **68.28M** | Overall sales value |
| Total Quantity | **~2K** | Total units/quantity recorded |
| Transactions | **331** | Number of transactions |
| Average Price | **~41K** | Average price KPI displayed in the report |

> **Note:** Values are based on the supplied dashboard screenshots. Confirm the dataset's currency, units, and exact measure definitions before presenting them as final business results.

## 🔎 Insights to Explore

- **Yearly performance:** The report compares sales for 2022, 2023, and 2024 and displays a same-period-last-year comparison.
- **Brand comparison:** The visible brand table allows comparison of total sales and transaction counts for Apple, Samsung, OnePlus, Vivo, and Xiaomi.
- **Model performance:** The model chart highlights the top displayed mobile models by sales, including iPhone SE, OnePlus Nord, and Galaxy S21.
- **Payment behavior:** The payment-method visual compares transactions across UPI, credit card, debit card, and cash.
- **Customer feedback:** The rating visual groups customer ratings into Good, Average, and Poor categories.
- **Time patterns:** Monthly and weekday visuals help identify when sales or quantities are comparatively higher or lower.
- **Geographic distribution:** The map displays sales-related locations included in the report.

These are patterns surfaced by the visuals, not proof of the causes behind them. Further analysis would be needed before making causal claims.

## 🧰 Tools & Skills Demonstrated

- **Power BI Desktop** — report design and interactive dashboarding
- **Data visualization** — KPI cards, clustered column charts, line charts, bar charts, pie chart, table, and map
- **Interactive filtering** — slicers for mobile model, payment method, date, and brand
- **Time-based analysis** — year, quarter, month, day, and same-period-last-year comparison
- **Business analysis** — comparing sales, quantity, transactions, price, customer ratings, and product performance

*Add Power Query, DAX, data modeling, or specific DAX measure names here only if you used them in this project and can explain them in an interview.*

## 💡 Business Recommendations

Based on the patterns identified after validating the underlying data, a business team could:

1. **Review high-performing models** and check whether stock availability can support demand.
2. **Compare brand performance** using both sales value and transaction count, rather than sales alone.
3. **Monitor payment-method usage** to make checkout options convenient for customers.
4. **Investigate low-rating categories** to understand possible product, delivery, or service issues.
5. **Compare weekday and monthly trends** when planning promotions and inventory.
6. **Track year-over-year performance** to identify periods that need closer investigation.

These are recommended follow-up actions; they should be validated against the source data and business context before implementation.

## 🚀 How to Use This Project

1. Download or clone this repository.
2. Open the `.pbix` file in **Microsoft Power BI Desktop**, if included in the repository.
3. If Power BI asks for the source data, update the data source path to your local dataset.
4. Refresh the data and explore the report using the slicers and visuals.

> The screenshots are included for preview. The interactive report requires the original `.pbix` file and any source dataset or connections it depends on.

## 📁 Suggested Repository Structure

```text
mobile-sales-analysis/
├── README.md
├── Mobile_Sales_Dashboard.pbix
├── data/
│   └── source_data.csv
└── images/
    ├── Dashboard.png
    ├── Same period Last year.png
    └── MID report.png
```

Rename files or folders to match the actual files you upload. Do not upload confidential or restricted source data.

## 📌 Future Improvements

- Add a dedicated executive summary with the most important validated findings.
- Add drill-through pages for brand and mobile-model details.
- Include a data dictionary defining each KPI and its unit.
- Add checks for missing values, duplicates, and inconsistent date or price fields.
- Document the exact DAX measures and data model used.
- Publish a view-only Power BI report link if sharing permissions and data privacy allow it.

## 👤 About This Project

This project demonstrates practical use of **Power BI for sales reporting and business analysis**. It is intended as a portfolio project to showcase dashboard design, KPI reporting, time-based comparison, and insight communication.

---

<div align="center">

**If you find this project useful, feel free to ⭐ the repository.**

</div>

