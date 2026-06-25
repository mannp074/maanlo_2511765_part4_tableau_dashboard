# Chart Selection Justification

## 1. Monthly Sales Trend

### Business Question
How are sales changing over time?

### Chart Type
Line Chart

### Why This Chart?
A line chart is the most appropriate visualization for displaying trends over time because it clearly shows increases, decreases, and seasonal fluctuations.

### Fields Used
- X-Axis: Order Date (Month)
- Y-Axis: Sales
- Filter: Region, Category, Customer Segment

### Design Principles Applied
- Chronological ordering
- Simple color palette
- Clear axis labels
- Minimal clutter

### Mistake Avoided
Avoided using bar charts for time-series analysis, which would make trends harder to interpret.

---

## 2. Regional Sales Performance

### Business Question
Which regions generate the highest sales?

### Chart Type
Horizontal Bar Chart

### Why This Chart?
Bar charts allow quick comparison between independent categories and make ranking regions straightforward.

### Fields Used
- Rows: Region
- Columns: Sales
- Color: Sales intensity
- Filters: Region, Category, Customer Segment

### Design Principles Applied
- Descending sorting
- Consistent color scheme
- Easy comparison of values

### Mistake Avoided
Avoided pie charts, which are less effective for comparing multiple categories.

---

## 3. Category & Sub-Category Profitability

### Business Question
Which product categories and sub-categories contribute the most profit?

### Chart Type
Horizontal Bar Chart

### Why This Chart?
The chart clearly ranks profitable sub-categories while maintaining readability for long category names.

### Fields Used
- Rows: Sub-Category
- Columns: Profit
- Color: Category
- Labels: Profit values

### Design Principles Applied
- Ranking from highest to lowest
- Consistent category colors
- Direct value labels

### Mistake Avoided
Avoided stacked charts that would reduce comparison accuracy.

---

## 4. Discount vs Profit Analysis

### Business Question
How do discounts affect profitability?

### Chart Type
Scatter Plot with Trend Line

### Why This Chart?
Scatter plots are ideal for identifying relationships between two continuous numerical variables.

### Fields Used
- X-Axis: Discount
- Y-Axis: Profit
- Color: Category
- Detail: Order ID
- Trend Line: Linear regression

### Design Principles Applied
- Trend line for interpretation
- Category differentiation using color
- Reduced clutter by avoiding unnecessary labels

### Mistake Avoided
Avoided aggregating all orders into a single point, which would hide the true relationship.

---

## 5. Return Analysis

### Business Question
Which product categories have the highest return rates?

### Chart Type
Horizontal Bar Chart

### Why This Chart?
Bar charts provide an intuitive comparison of return percentages across categories.

### Fields Used
- Rows: Category
- Columns: Return Rate
- Labels: Return Rate (%)
- Color: Return Rate

### Design Principles Applied
- Percentage formatting
- Ranking by return rate
- Consistent visual hierarchy

### Mistake Avoided
Avoided tables, which are less effective for quickly identifying high-return categories.

---

# Dashboard Design Principles

The dashboard was designed for executive decision-making by following key visualization best practices:

- A clear visual hierarchy with KPI cards positioned at the top.
- Consistent color usage across all visualizations.
- Minimal clutter with sufficient spacing between components.
- Interactive filters for Region, Category, and Customer Segment.
- Dashboard actions enabling interactive exploration.
- Appropriate chart selection based on the business question.
- Readable fonts, labels, and titles.
- Business-focused formatting to support rapid interpretation.