# 📌 What are KPIs?

**KPI = Key Performance Indicator**

A KPI is a measurable value used to evaluate how effectively a person, team, or organization is achieving key objectives.

Examples:

* Total Sales
* Profit Margin
* Revenue Growth %
* Employee Attrition Rate
* Customer Satisfaction Score
* Website Conversion Rate

---

# 🎯 Should KPIs Be Taught in a Power BI Course?

### ✅ Yes — Absolutely.

Here’s why:

Power BI is not just about:

* Charts
* Filters
* Drill Down

It is about:

> Turning data into decision-making tools.

And KPIs are at the center of business decision-making.

---

# 📚 When to Teach KPIs?

Teach KPIs:

✔ After DAX fundamentals
✔ After students understand Measures
✔ After they understand filter context

KPIs combine:

* DAX
* Visual design
* Business thinking

---

# 📘 Classroom-Ready Tutorial: KPIs in Power BI

---

# 🎯 Learning Objectives

Students will:

* Understand what KPIs are
* Create KPI measures
* Use Card & KPI visuals
* Compare actual vs target
* Use conditional formatting for performance

---

# 📊 Dataset

Use this dataset:

### File: `sales_kpi.xlsx`

| OrderID | Country       | OrderDate  | Sales  |
| ------- | ------------- | ---------- | ------ |
| 7001    | India         | 01-01-2024 | 75000  |
| 7002    | India         | 10-01-2024 | 65000  |
| 7003    | United States | 15-01-2024 | 120000 |
| 7004    | India         | 20-02-2024 | 80000  |
| 7005    | United States | 05-02-2024 | 95000  |
| 7006    | India         | 10-03-2024 | 70000  |
| 7007    | United States | 15-03-2024 | 110000 |

---

# 🟢 Step 1 – Create Basic Measures

---

## Total Sales

```DAX
Total Sales = SUM(Sales[Sales])
```

---

## Total Orders

```DAX
Total Orders = COUNT(Sales[OrderID])
```

---

# 🟡 Step 2 – Create Target Measure

Create a static target:

```DAX
Sales Target = 500000
```

---

# 🔵 Step 3 – Create KPI Variance Measure

```DAX
Sales Variance = [Total Sales] - [Sales Target]
```

---

# 🟣 Step 4 – Create KPI % Achievement

```DAX
Sales Achievement % = 
DIVIDE([Total Sales], [Sales Target])
```

Format as Percentage.

---

# 📊 Step 5 – Use Card Visual for KPI

Add:

1️⃣ Card → Total Sales
2️⃣ Card → Sales Target
3️⃣ Card → Sales Achievement %

---

# 🟠 Step 6 – Apply Conditional Formatting

For Sales Achievement %:

1. Select Card
2. Format → Callout value → Conditional formatting
3. Set rule:

* ≥ 100% → Green
* 80%–99% → Yellow
* < 80% → Red

Now it behaves like a real KPI indicator.

---

# 🟤 Step 7 – Use Built-in KPI Visual

Power BI has a **KPI visual**.

Steps:

1. Add KPI visual
2. Indicator → Total Sales
3. Target goals → Sales Target
4. Trend axis → OrderDate

This shows:

* Target line
* Trend
* Indicator status

---

# 🧠 What Students Learn Here

✔ Business thinking
✔ Measure comparison
✔ Target vs actual logic
✔ Conditional formatting
✔ Executive reporting

---

# 📊 KPI vs Normal Visual

| Normal Chart  | KPI               |
| ------------- | ----------------- |
| Shows numbers | Shows performance |
| Informational | Decision-focused  |
| Raw data      | Strategic insight |

---

# 🎓 Classroom Practice Task

1. Create Total Sales
2. Create Sales Target
3. Create Achievement %
4. Apply conditional formatting
5. Add slicer for Country

Observe KPI change by country.

---

# 🧠 Imp Tips

> A KPI must answer: Are we performing well or not?
> Reports show data. KPIs show performance.
