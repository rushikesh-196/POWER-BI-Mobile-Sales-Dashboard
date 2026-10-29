# 📱 Power BI Mobile Sales Dashboard

An interactive **Power BI dashboard for mobile sales analytics** that helps explore sales performance, transaction activity, quantities sold, customer ratings, payment methods, brands, mobile models, and city-level performance.

## 📊 Dashboard Preview

> Add a screenshot of your dashboard to the repository and update the path below.

![Power BI Mobile Sales Dashboard](images/mobile-sales-dashboard.png)

## 🎯 Project Objective

The objective of this project is to turn mobile-sales data into clear, interactive business insights. The dashboard allows users to filter results and compare sales performance across different dimensions to support data-driven decisions.

## ✨ Key Features

- **KPI cards** for total sales, total quantity, transactions, and average rating.
- **Month-wise quantity trend** to compare sales quantity throughout the year.
- **City-wise sales map** to explore geographic performance.
- **Rating-status analysis** for Good, Average, and Poor ratings.
- **Payment-method analysis** across UPI, Debit Card, Cash, and Credit Card.
- **Brand and mobile-model comparisons** to identify leading products.
- **Day-wise sales analysis** to explore sales by day of the week.
- **Interactive slicers** for mobile model, payment method, and brand.
- **Day selection** to filter the report by weekday.
- **MTD Report** and **Same Period Last Year** report navigation/buttons for period-based analysis.

## 📌 Dashboard KPIs

The screenshot displays the following headline metrics. These are the values visible in the supplied dashboard image and may change when filters are applied.

| KPI | Value shown |
|---|---:|
| Total Sales | 112M (rounded display) |
| Total Quantity | 3K (rounded display) |
| Transactions | 550 |
| Average Rating | 39.82K appears in the screenshot, but its label/format should be verified in Power BI |

**Important:** Verify the KPI card titles, measures, number formats, and units in the `.pbix` file before publishing. In particular, the visible `39.82K` value is unusual for an average rating and may represent a formatting or label issue.

## 📈 Visualizations

| Visualization | Purpose |
|---|---|
| Total Sales by City | Compare sales geographically across cities |
| Total Quantity by Month | Understand monthly quantity trends |
| Ratings by Rating Status | Compare customer rating categories |
| Transactions by Payment Method | Understand payment-method distribution |
| Total Sales by Mobile Model | Compare revenue across mobile models |
| Total Sales by Day Name | Explore sales performance by weekday |
| Brand / Sales / Transactions table | Review brand-level performance in tabular form |

## 🧰 Tools & Technologies

- **Microsoft Power BI Desktop** — report creation and interactive visualizations
- **Power Query** — data import and transformation, if used in the report
- **DAX** — measures and calculations, if implemented in the report
- **Data modeling** — organizing relationships and analytical fields, if applicable

*Only retain the Power Query, DAX, or data-modeling descriptions that match what you actually implemented.*

## 🗂️ Repository Structure

```text
POWER-BI-Mobile-Sales-Dashboard/
├── README.md
├── Power-bi-mobile-sales-demo (1).pbix
├── [source-data-file]
└── [additional-project-files]
```

The file names above are based on the visible repository screenshot. Replace the bracketed entries with the exact source-data and supporting-file names in your repository. If your `.pbix` file has a different name, update the structure accordingly.

## 🚀 How to View the Dashboard

1. Clone or download this repository.
2. Install **Microsoft Power BI Desktop**.
3. Open the `.pbix` report file included in the repository.
4. If Power BI asks for the source data, update the data-source path to the location on your computer.
5. Select **Refresh** if the source data is available and refresh is required.
6. Use the slicers, buttons, and charts to explore the report.

> The report may require the original dataset and compatible data-source paths to refresh successfully.

## 🔍 Example Business Questions

- Which cities generate the highest mobile sales?
- How does quantity sold change from month to month?
- Which mobile models contribute the most revenue?
- Which payment methods are used most often?
- How are customer ratings distributed?
- Which brands lead in sales and transactions?
- Which day of the week has the highest sales?

## 💡 Business Value

This dashboard can help business users:

- Monitor key sales indicators in one place.
- Compare product, brand, and geographic performance.
- Identify trends and areas that may need further investigation.
- Explore customer ratings and payment preferences.
- Support reporting and sales-planning discussions with interactive visuals.

## ⚠️ Notes & Limitations

- The values displayed in the README are taken from the provided screenshot, not independently recalculated from the dataset.
- Results depend on the underlying dataset, data model, measures, and active filters.
- The dashboard is an analytical reporting project; it does not by itself establish causes for sales changes.
- Verify all KPI labels and formats in Power BI before using the dashboard for business decisions.

## 👤 Author

**Rushikesh Barate**

- GitHub: [@rushikesh-196](https://github.com/rushikesh-196)
- Project Repository: [POWER-BI-Mobile-Sales-Dashboard](https://github.com/rushikesh-196/POWER-BI-Mobile-Sales-Dashboard)

---

⭐ If you find this project useful, consider starring the repository.
