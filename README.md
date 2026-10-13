# Olist E-Commerce Store Analysis

## Project Overview
This project analyzes the Olist e-commerce marketplace to understand sales performance, customer behavior, product and seller performance, delivery operations, and customer satisfaction. The goal is to turn transaction data into actionable business insights using **Excel, SQL, Power BI, and Tableau**.

## Business Objectives
- Analyze order and payment trends over time.
- Identify key customer regions and geographic growth opportunities.
- Examine delivery performance and its relationship with customer reviews.
- Explore payment methods and customer experience patterns.
- Recommend actions to improve sales, logistics, and customer satisfaction.

## Tools & Technologies
- **Microsoft Excel:** Data cleaning, preparation, pivot tables, and exploratory analysis
- **SQL (MySQL):** Data extraction, aggregations, KPI calculations, and business queries
- **Power BI:** Data modeling, DAX measures, KPI cards, and interactive dashboards
- **Tableau:** Interactive visualizations, trend analysis, and geographic analysis

## Dataset at a Glance
The project presentation reports the following marketplace figures:

| Metric | Reported value |
|---|---:|
| Orders | 99,441 |
| Customers | 96,096 |
| Sellers | 3,095 |
| Order items | 112,650 |
| Total payment value | Approximately R$16.01 million |

*Note: These figures are reported in the project presentation. Individual dashboard totals may differ depending on the table, measure, or filters used.*

## Key Findings
- **Sales performance:** November 2017 was identified as the peak sales period, with approximately **R$1.18 million** in revenue and around **7,544 orders**, coinciding with the Black Friday period.
- **Customer geography:** São Paulo had the highest customer concentration, with **41,746 customers** (about 42% of the customer base) and approximately **R$5.77 million** in revenue.
- **Regional opportunities:** Rio de Janeiro and Minas Gerais were identified as important secondary markets.
- **Delivery operations:** The presentation reports an average delivery time of **11.37 days** and a late-delivery rate of **8.11%**.
- **Customer satisfaction:** The reported average review score was **4.09/5**. The dashboard analysis showed lower review scores for longer delivery-time categories.
- **Payment behavior:** Credit card was the most frequently used payment method in the project analysis.

## Dashboards & Analysis
The project includes dashboard and query work across four tools:

### Excel
- Pivot-table analysis
- Weekday versus weekend payment value
- Review-score analysis by shipping-duration group
- Average price, payment value, and delivery-day analysis

### SQL
- Business queries using `SELECT`, `CASE`, aggregate functions, `GROUP BY`, and filtering
- Weekday/weekend payment analysis
- Review-score and payment-method analysis
- Average delivery-time calculations
- Average price and payment-value analysis for São Paulo

### Power BI
- KPI cards for payment value and selected business measures
- Weekday versus weekend payment comparison
- Review scores by delivery-duration category
- Payment value by payment type
- Delivery and customer-experience analysis

### Tableau
- Weekday versus weekend payment comparison
- Five-star review analysis
- Average price and payment-value views
- Delivery-day analysis
- Shipping duration versus review-score analysis

## Recommendations
1. **Plan for seasonal demand:** Align marketing, inventory, and promotions with high-performing periods such as Black Friday.
2. **Improve delivery performance:** Investigate regions and categories with longer delivery times and late orders.
3. **Use regional insights:** Consider targeted marketing and operational planning in high-demand states and secondary growth markets.
4. **Support strong performers:** Identify successful product categories and sellers and learn from their practices.
5. **Improve customer experience:** Investigate delivery and product issues associated with lower review scores.

## Project Workflow
1. Prepare and explore the data in Excel.
2. Query and aggregate the data using SQL.
3. Build data models, measures, and interactive dashboards in Power BI.
4. Create additional visual analyses in Tableau.
5. Summarize findings and translate them into business recommendations.

## Repository Structure
A suggested repository structure is:

```text
olist-ecommerce-store-analysis/
├── README.md
├── data/
│   └── (add dataset files here, if permitted)
├── excel/
│   └── (add Excel analysis/workbook)
├── sql/
│   └── (add SQL query files)
├── power-bi/
│   └── (add Power BI .pbix file and dashboard screenshots)
├── tableau/
│   └── (add Tableau workbook or screenshots)
└── presentation/
    └── (add project presentation)
```

*This is a suggested structure. Keep only folders and files you actually upload.*

## Project Deliverables
- Excel analysis and dashboard
- SQL queries for business KPIs
- Power BI dashboard
- Tableau dashboard
- Project presentation

## Conclusion
This project demonstrates an end-to-end data analytics workflow: preparing data, querying business information, creating dashboards, interpreting trends, and recommending data-informed actions to improve marketplace performance and customer experience.

---

**Project type:** Data Analytics  
**Tools:** Excel | SQL | Power BI | Tableau
