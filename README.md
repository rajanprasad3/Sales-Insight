# 📈 Sales Insight – AtliQ Hardware Power BI Dashboard

---

## 📊 Live Dashboard

> 🔗 **[Click here to view the Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNGRmNDBmNTItN2YwMi00Y2FjLTgxYmMtYWQxMGY1MDRjMDYyIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

---

## 📌 Project Overview

AtliQ Hardware, a company that supplies computer hardware and peripherals across India, was struggling to track its sales performance dynamically. The Sales Director had difficulty getting clear insights from regional managers and needed a data-driven solution to understand declining sales trends.

This project involved designing an end-to-end **Power BI Sales Dashboard** that analyzes **4 years of sales data**, helping the leadership team make informed decisions and strategize for revenue recovery.

> 📊 The dashboard is projected to **increase revenue by at least 7%** in the next quarter by enabling faster, data-driven decisions.

---

## 🎯 Objective

- Visualize 4 years of AtliQ Hardware's sales trends in one unified dashboard
- Track revenue, sales quantity, and profit margins across regions and markets
- Identify top and bottom performing customers, products, and regions
- Enable the Sales Director to monitor performance without depending on manual reports
- Support strategic decisions to recover declining revenue

---

## 🗂️ Dataset Description

| File | Description |
|------|-------------|
| `db_dump.sql` | MySQL database dump containing all transactional sales data |
| `Sales_Insight.pdf` | Full dashboard snapshot and project report |

---

## 📐 Key Metrics (KPIs)

| Metric | Description |
|--------|-------------|
| **Total Revenue** | Overall revenue generated across all markets and years |
| **Total Sales Quantity** | Total number of units sold |
| **Revenue by Market** | City-wise revenue breakdown |
| **Sales Quantity by Market** | City-wise units sold comparison |
| **Top 5 Customers** | Highest revenue-contributing customers |
| **Top 5 Products** | Best performing products by revenue |
| **Revenue Trend** | Month-over-month and year-over-year revenue trend |
| **Profit Margin %** | Profitability across regions and customers |

---

## 🔍 Key Insights

- 📉 Revenue showed a consistent declining trend over the last 2 years
- 🏙️ Delhi NCR is the highest revenue-generating market, contributing the largest share
- 🏆 Electricalsara Stores is the top customer by revenue
- 📦 Prod318 is the top-selling product by revenue
- 📅 Revenue peaks were observed during Q1 and Q4 each year
- ⚠️ Several markets operate at negative profit margins, requiring strategic review
- 🔄 Sales quantity does not always correlate with revenue — some markets sell more but earn less

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Dashboard design and interactive visualization
- **MySQL** – Data storage, querying, and extraction via `db_dump.sql`
- **Power Query** – Data transformation and cleaning inside Power BI
- **DAX (Data Analysis Expressions)** – Custom KPI and measure calculations

---

## 📁 Project Structure

```
Sales-Insight/
│
├── 📄 README.md
├── 📊 Sales_Insight.pdf
└── 🗃️ db_dump.sql
```

---

## 🚀 How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/rajanprasad3/Sales-Insight.git
   ```

2. Import the database into MySQL:
   ```sql
   SOURCE db_dump.sql;
   ```

3. Connect Power BI Desktop to your local MySQL database

4. Load the data and refresh the dashboard to explore insights

5. Refer to `Sales_Insight.pdf` for a full snapshot of the dashboard

---

## 👤 Author

**Rajan Prasad**
📧 [GitHub Profile](https://github.com/rajanprasad3)

---

## 📃 License

This project is for **educational and portfolio purposes** only.

---

> ⭐ If you found this project helpful, consider giving it a star on GitHub!
