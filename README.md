  # Retail Executive Sales Performance Dashboard

## Business Problem Summary

This project was developed as part of the Business Analytics Assignment (Part 4: Data Storytelling). The objective was to design an executive Tableau dashboard that enables retail leadership to monitor business performance, identify trends, evaluate profitability, and support data-driven decision-making.

The dashboard combines sales, profitability, customer segmentation, regional performance, shipping efficiency, discount analysis, and return patterns into a single interactive reporting solution.

---

# Dataset Description

The project uses the provided retail sales dataset:

- **File:** `dashboard_sales_data.xlsx`
- Order-level transactional retail data
- Includes customer, product, geographic, shipping, sales, profit, discount, and return information

Major fields include:

- Order Date
- Region
- State
- Customer Segment
- Category
- Sub-Category
- Sales
- Profit
- Discount
- Delivery Days
- Ship Mode
- Return Flag

---

# Tableau Workbook

Workbook File:

```text
tableau/executive_dashboard.twbx
```

The workbook contains:

- Executive Dashboard
- Sales Trend
- Regional Performance
- Category & Sub-Category Profitability
- Customer Segment Performance
- Shipping Performance
- Discount vs Profit Analysis
- Return Analysis
- KPI Worksheets

---

# Calculated Fields Created

The following calculated fields were created in Tableau:

| Calculated Field | Description |
|------------------|-------------|
| Profit Margin | Profit ÷ Sales |
| Cost | Sales − Profit |
| Average Order Value | Sales ÷ Number of Orders |
| Return Rate | Returned Orders ÷ Total Orders |
| Shipping Delay Bucket | Categorizes delivery time into Fast, Standard, and Delayed |

---

# Dashboard Components

The executive dashboard contains:

- 3 KPI Cards
  - Total Sales
  - Total Profit
  - Profit Margin

- Interactive Charts
  - Monthly Sales Trend
  - Regional Sales Performance
  - Category & Sub-Category Profitability
  - Discount vs Profit Analysis
  - Return Analysis

---

# Filters and Interactions

Interactive Filters:

- Region
- Category
- Customer Segment

Dashboard Interaction:

- Dashboard Filter Action enabling users to filter all visualizations by selecting values.

---

# Key Business Insights

Major findings include:

- Sales remain relatively stable throughout the year with seasonal peaks.
- South region contributes the highest sales.
- Technology products generate the highest profits.
- Higher discounts generally reduce profitability.
- Return rates vary across product categories.
- Delivery performance differs significantly by shipping mode.

Detailed insights are available in:

```text
outputs/business_insights.md
```

---

# Dashboard Story

The dashboard supports executive decision-making by combining multiple business perspectives into one integrated view.

It highlights:

- Overall business performance
- Regional strengths
- Product profitability
- Pricing effectiveness
- Return risks
- Opportunities for operational improvement

Complete business story:

```text
outputs/dashboard_story.md
```

---

# Assumptions

- Profit Margin calculated as Profit ÷ Sales.
- Average Order Value calculated using total sales divided by number of orders.
- Return Rate calculated using returned orders divided by total orders.
- Delivery performance measured using average delivery days.
- Filters affect all dashboard visualizations.

---

# Limitations

- Analysis is based only on the provided historical dataset.
- External factors such as promotions, competitor activity, inflation, and customer satisfaction are not included.
- The dashboard is descriptive rather than predictive.

---

# Repository Structure

```text
part4_tableau_dashboard/
│
├── data/
│   └── dashboard_sales_data.xlsx
│
├── tableau/
│   └── executive_dashboard.twbx
│
├── outputs/
│   ├── business_insights.md
│   ├── dashboard_story.md
│   └── chart_selection_justification.md
│
├── screenshots/
│   ├── full_dashboard.png
│   ├── sales_trend_view.png
│   ├── regional_performance_view.png
│   ├── category_profitability_view.png
│   └── filter_interaction_view.png
│
└── README.md
```

---

# Screenshots Included

The repository includes:

- Full Executive Dashboard
- Sales Trend View
- Regional Performance View
- Category Profitability View
- Filter Interaction Demonstration

---

# Technologies Used

- Tableau Public
- Microsoft Excel
- GitHub

---

