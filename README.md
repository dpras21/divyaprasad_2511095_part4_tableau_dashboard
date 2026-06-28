# Executive Sales Dashboard using Tableau

## 1. Business Problem Summary

The objective of this project is to analyze sales performance and provide business insights using an interactive Tableau dashboard. The dashboard helps management understand sales trends, profitability, customer behavior, regional performance, shipping efficiency, discount impact, and return patterns to support data-driven decision-making.

---

## 2. Dataset Description

The dataset contains transactional sales data for an e-commerce business.

### Key fields included:
- Order ID
- Order Date
- Product Name
- Category
- Sub-Category
- Region
- Customer Segment
- Sales
- Profit
- Quantity
- Discount
- Ship Mode
- Delivery Days
- Return Flag
- Customer Rating

The dataset contains information related to sales, profitability, customers, shipping, and returns.

---

## 3. Tableau Workbook Description

The Tableau workbook consists of multiple worksheets and one executive dashboard.

### Worksheets Created:
1. Sales Trend View
2. Regional Performance View
3. Category Profitability View
4. Customer Segment View
5. Shipping Performance View
6. Discount vs Profit View
7. Return Analysis View
8. KPI Sheets (Total Sales, Total Profit, Total Orders)

### Dashboard:
- Executive Dashboard containing all charts, KPIs, filters, and interactions.

---

## 4. Calculated Fields Created

The following calculated fields were created:

### Return Rate
```tableau
SUM([Return Flag]) / COUNT([Order ID])
```

### Total Orders KPI
```tableau
COUNTD([Order ID])
```

Additional calculated fields may include:
- Delivery Days
- Average Order Value
- Shipping Delay Bucket

---

## 5. Dashboard Components

The dashboard includes:

### KPI Cards
- Total Sales
- Total Profit
- Total Orders

### Charts
- Sales Trend Line Chart
- Regional Performance Bar Chart
- Category Profitability Bar Chart
- Customer Segment Bar Chart
- Shipping Performance Bar Chart
- Discount vs Profit Scatter Plot
- Return Analysis Chart

---

## 6. Filters and Interactions Used

### Interactive Filters:
- Region
- Category
- Customer Segment

### Dashboard Interactions:
Filter actions were configured so that selecting values in one visualization updates related charts across the dashboard.

---

## 7. Key Business Insights

- Technology category generates the highest profit.
- Sales show fluctuations over time indicating seasonality.
- Regional performance varies significantly across regions.
- Higher discounts generally reduce profitability.
- Standard Class shipping contributes the highest delivery days.
- Customer segments contribute differently to overall sales.
- Return rates differ across product categories.
- Some regions and categories present opportunities for growth.

---

## 8. Dashboard Story Summary

The executive dashboard provides a comprehensive overview of business performance. It highlights sales trends, profitability drivers, customer behavior, operational efficiency, and business risks. The dashboard enables leadership teams to identify high-performing areas, monitor underperforming segments, and take corrective actions for improved business outcomes.

---

## 9. Assumptions and Limitations

### Assumptions
- Dataset values are accurate and complete.
- Delivery days correctly represent shipping performance.
- Return flags accurately indicate product returns.

### Limitations
- Analysis is limited to available historical data.
- External factors such as market conditions are not considered.
- Customer demographics are not available for deeper analysis.

---

## 10. Screenshots Included

The project includes screenshots of:
- Executive Dashboard
- Individual Worksheets
- KPI Cards
- Interactive Filters


