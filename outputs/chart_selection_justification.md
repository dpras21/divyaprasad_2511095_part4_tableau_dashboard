# Chart Selection Justification

## 1. Sales Trend View

### Question Answered
How are sales changing over time?

### Why the Chart Type is Appropriate
A line chart is the most suitable chart for showing trends and patterns over time.

### Fields Used
- X-axis: Order Date (Month)
- Y-axis: Sum of Sales
- Filters: Region, Category, Customer Segment

### Design Principle Applied
Used a continuous time axis with clear labels to highlight sales trends and seasonality.

### Mistake Avoided
Avoided using a bar chart, which would make long-term trends difficult to identify.

---

## 2. Regional Performance View

### Question Answered
Which region performs best in terms of sales?

### Why the Chart Type is Appropriate
A bar chart allows easy comparison between regions.

### Fields Used
- X-axis: Region
- Y-axis: Sum of Sales
- Color: Consistent dashboard color palette
- Filters: Region, Category, Customer Segment

### Design Principle Applied
Used consistent colors and clear axis labels for easy comparison.

### Mistake Avoided
Avoided using pie charts because comparing values across multiple regions is difficult.

---

## 3. Category Profitability View

### Question Answered
Which product categories generate the highest profit?

### Why the Chart Type is Appropriate
Bar charts effectively compare profits across categories.

### Fields Used
- X-axis: Category
- Y-axis: Sum of Profit
- Filters: Region, Category, Customer Segment

### Design Principle Applied
Applied minimal clutter and proper labels to improve readability.

### Mistake Avoided
Avoided using excessive colors or 3D charts that could distort interpretation.

---

## 4. Customer Segment View

### Question Answered
Which customer segment contributes the most sales?

### Why the Chart Type is Appropriate
A bar chart provides clear comparison among customer segments.

### Fields Used
- X-axis: Customer Segment
- Y-axis: Sum of Sales
- Filters: Region, Category, Customer Segment

### Design Principle Applied
Maintained consistent color usage across all comparison charts.

### Mistake Avoided
Avoided using stacked charts that could make comparisons difficult.

---

## 5. Shipping Performance View

### Question Answered
Which shipping mode contributes the highest delivery days?

### Why the Chart Type is Appropriate
Bar charts allow easy comparison of delivery performance across shipping modes.

### Fields Used
- X-axis: Ship Mode
- Y-axis: Sum of Delivery Days
- Filters: Region, Category, Customer Segment

### Design Principle Applied
Used clear titles and labels for quick business understanding.

### Mistake Avoided
Avoided using line charts because shipping modes are categorical variables.

---

## 6. Discount vs Profit View

### Question Answered
How does discount impact profit?

### Why the Chart Type is Appropriate
A scatter plot is ideal for identifying relationships and correlations between two numerical variables.

### Fields Used
- X-axis: Discount
- Y-axis: Profit
- Filters: Region, Category, Customer Segment

### Design Principle Applied
Used a scatter plot with minimal formatting to focus attention on the relationship between variables.

### Mistake Avoided
Avoided aggregating all values into a single point, which would hide important patterns.

---

## Overall Dashboard Design Principles

- Correct chart selection based on business questions.
- Consistent color palette across all charts.
- Clear titles and labels for readability.
- Interactive filters for better exploration.
- Minimal clutter and unnecessary visual elements.
- Business-focused layout with KPI cards placed at the top.
