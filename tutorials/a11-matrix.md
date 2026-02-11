# 📘 Power BI Tutorial – Matrix Visual

---

# 🎯 Learning Objectives

By the end of this session, students will:

* Understand what a Matrix visual is
* Create row & column grouping
* Add hierarchical levels
* Use expand/collapse
* Show subtotals and grand totals
* Format matrix professionally

---

# 📊 Dataset Used

`regional_sales.xlsx`

| OrderID | Country | State | City | Category | Sales |

---

# 🧠 What is a Matrix Visual?

A **Matrix** is an advanced version of a Table.

It allows:

✔ Row grouping
✔ Column grouping
✔ Hierarchical drill
✔ Subtotals
✔ Grand totals

Think of it as a **Pivot Table inside Power BI**.

---

# 🟢 Step 1 – Create a Basic Matrix

### Steps:

1. Click **Matrix visual**
2. Drag fields:

* Rows → Country
* Columns → Category
* Values → Sales (Sum)

---

### Result:

| Country       | Electronics | Furniture | Clothing |
| ------------- | ----------- | --------- | -------- |
| India         | 285000      | 45000     | 27000    |
| United States | 395000      | 95000     | 58000    |

✔ You now have grouped rows & columns.

---

# 🟡 Step 2 – Add Hierarchy to Rows

Drag into Rows:

Country
→ State
→ City

Now rows have hierarchy.

---

# 🔽 Step 3 – Expand and Collapse

You will see:

▶ Expand (+) icon
▼ Collapse (-) icon

Click:

* Expand Country → See States
* Expand State → See Cities

---

## Teaching Point:

Matrix supports hierarchy navigation without using Drill Down buttons.

---

# 🔵 Step 4 – Add Subtotals

### Steps:

1. Select Matrix
2. Go to **Format pane**
3. Expand **Subtotals**
4. Turn ON:

   * Row subtotals
   * Column subtotals

Now:

* State totals appear
* Country totals appear

---

# 🟣 Step 5 – Add Grand Total

Format pane → Grand Total → ON

You now see overall total.

---

# 🟤 Step 6 – Format Matrix Professionally

Format options:

✔ Increase font size
✔ Bold row headers
✔ Turn off gridlines
✔ Add background color
✔ Adjust column width
✔ Align values right

---

# 🟠 Step 7 – Multiple Measures in Matrix

Add:

Values:

* Sales (Sum)
* OrderID (Count)

Now matrix shows:

Sales + Order Count together.

Very powerful for dashboards.

---

# 🧩 Step 8 – Conditional Formatting

### Example:

Highlight high sales.

Steps:

1. Select Sales field in Values
2. Click dropdown
3. Conditional formatting → Background color
4. Set rules (e.g., > 100000 = Green)

Great for executive dashboards.

---

# 📊 Advanced Example – Sales Breakdown

Rows:
Country → State

Columns:
Category

Values:
Sales (Sum)

This shows:

* Country total
* State breakdown
* Category breakdown

---

# 🔎 Matrix vs Table

| Feature         | Table | Matrix |
| --------------- | ----- | ------ |
| Row grouping    | ❌     | ✅      |
| Column grouping | ❌     | ✅      |
| Subtotals       | ❌     | ✅      |
| Hierarchy       | ❌     | ✅      |
| Pivot style     | ❌     | ✅      |

---

# 🎯 When to Use Matrix

✔ Financial reports
✔ Regional breakdown
✔ Performance summary
✔ Category comparison
✔ Pivot-style reporting

---

# 🎓 Classroom Practice Task

1. Create matrix with:

   * Rows → Country → State
   * Columns → Category
   * Values → Sales

2. Turn on subtotals

3. Add conditional formatting

4. Add Order Count

---

# 🧠 Imp Tip

> Matrix is Power BI’s Pivot Table.
