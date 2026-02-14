# 📘 Power BI Tutorial – DAX Fundamentals

---

# 🎯 Learning Objectives

By the end of this session, students will:

* Understand what DAX is
* Create Measures
* Understand Calculated Columns
* Understand Filter Context
* Use basic DAX functions
* Create simple KPIs

---

# 🧠 What is DAX?

**DAX (Data Analysis Expressions)** is a formula language used in Power BI to create:

* Measures
* Calculated Columns
* Calculated Tables

It is used for:

* Calculations
* Aggregations
* Logical conditions
* Advanced analytics

---

# 🟢 Step 1 – Dataset

Use a simple dataset:

### File: `sales_dax.xlsx`

| OrderID | Country       | Category    | Quantity | UnitPrice |
| ------- | ------------- | ----------- | -------- | --------- |
| 6001    | India         | Electronics | 2        | 25000     |
| 6002    | India         | Furniture   | 1        | 15000     |
| 6003    | United States | Electronics | 3        | 30000     |
| 6004    | United States | Clothing    | 4        | 2000      |
| 6005    | India         | Clothing    | 5        | 1800      |

---

# 🟡 PART 1 – Measures

---

## 🧠 What is a Measure?

A Measure:

* Is calculated dynamically
* Responds to filters
* Is not stored row-by-row

Think of it as:

> A smart calculator.

---

## 🧮 Create Your First Measure

### Total Sales

Go to:
Modeling → New Measure

```DAX
Total Sales = SUMX(Sales, Sales[Quantity] * Sales[UnitPrice])
```

---

### Explanation:

SUMX:

* Iterates row-by-row
* Multiplies Quantity × UnitPrice
* Then sums the results

---

Add Card visual:
→ Drag Total Sales

Now apply slicer → Notice it changes dynamically.

---

## 🧮 Create Simple Measure (Alternative)

If Total column exists:

```DAX
Total Quantity = SUM(Sales[Quantity])
```

```DAX
Average Price = AVERAGE(Sales[UnitPrice])
```

---

# 🔵 PART 2 – Calculated Columns

---

## 🧠 What is a Calculated Column?

* Calculated for each row
* Stored in table
* Does NOT change with slicers

---

## Create Sales Amount Column

Modeling → New Column

```DAX
Sales Amount = Sales[Quantity] * Sales[UnitPrice]
```

Now it appears as a normal column.

---

## Measure vs Column Difference

| Feature              | Measure        | Calculated Column |
| -------------------- | -------------- | ----------------- |
| Calculated when?     | At report time | At data load      |
| Affected by filters? | Yes            | No                |
| Stored in model?     | No             | Yes               |

---

# 🟣 PART 3 – Filter Context (Most Important Concept)

---

## 🧠 What is Filter Context?

Filter context is:

> The environment in which a measure is calculated.

Example:
If slicer selects India:

Total Sales measure only calculates India rows.

---

## Demonstration

Create:

```DAX
Total Orders = COUNT(Sales[OrderID])
```

Add slicer:
Country

Select:
India

Watch Total Orders change.

This is filter context.

---

# 🟠 PART 4 – CALCULATE Function

---

## 🧠 What is CALCULATE?

CALCULATE modifies filter context.

---

### Example:

Sales Only for India

```DAX
India Sales = 
CALCULATE(
    [Total Sales],
    Sales[Country] = "India"
)
```

This measure ignores slicer and always calculates India sales.

---

# 🟤 PART 5 – Logical Functions

---

## IF Function

```DAX
High Sales Flag = 
IF([Total Sales] > 100000, "High", "Low")
```

---

## DIVIDE Function (Safer than /)

```DAX
Average Revenue = 
DIVIDE([Total Sales], [Total Orders])
```

---

# 📊 Suggested Visual Practice

Create:

* Card → Total Sales
* Card → Total Orders
* Column Chart → Sales by Country
* Slicer → Country

Watch dynamic behavior.

---

# 🎓 Classroom Practice Task

1. Create Total Sales measure
2. Create Total Quantity measure
3. Create Sales Amount column
4. Apply slicer and observe changes
5. Create IF condition measure

---

# 🧠 Key Concepts Summary

✔ Measures are dynamic
✔ Columns are static
✔ Filter context controls calculation
✔ CALCULATE changes context

---

# 💡 Imp Tip

> “DAX makes your visuals intelligent.”

