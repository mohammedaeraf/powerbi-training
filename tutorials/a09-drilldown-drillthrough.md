# 📘 Drill Down & Drill Through in Power BI

## 📊 Dataset – Retail Store Sales

### File Name: `retail_sales.xlsx`

### Sheet Name: `Sales`

| OrderID | Country | State       | City       | Category    | Product | Sales |
| ------- | ------- | ----------- | ---------- | ----------- | ------- | ----- |
| 1001    | India   | Karnataka   | Bengaluru  | Electronics | Laptop  | 75000 |
| 1002    | India   | Karnataka   | Mysuru     | Electronics | Mobile  | 30000 |
| 1003    | India   | Maharashtra | Mumbai     | Furniture   | Chair   | 15000 |
| 1004    | India   | Maharashtra | Pune       | Furniture   | Table   | 22000 |
| 1005    | India   | Tamil Nadu  | Chennai    | Electronics | Laptop  | 80000 |
| 1006    | India   | Tamil Nadu  | Coimbatore | Clothing    | Shirt   | 2000  |
| 1007    | India   | Karnataka   | Bengaluru  | Clothing    | Jeans   | 3500  |
| 1008    | India   | Maharashtra | Mumbai     | Electronics | Mobile  | 28000 |
| 1009    | India   | Tamil Nadu  | Chennai    | Furniture   | Sofa    | 45000 |
| 1010    | India   | Karnataka   | Mysuru     | Clothing    | Jacket  | 4000  |

---

# 🎯 Learning Objectives

You will learn:

- What is Drill Down
- How to create hierarchy
- How Drill Down works within a visual
- What is Drill Through
- How to create a Drill Through page
- When to use each feature

---

# 🟢 PART 1 – Drill Down

---

## 🧠 What is Drill Down?

Drill Down allows users to:

- Navigate through hierarchical levels
- Stay within the same visual

Example:
Country → State → City

---

## 🔧 Step 1 – Create a Hierarchy

In Fields pane:

1. Right-click **Country**
2. Select **Create hierarchy**
3. Drag **State** into that hierarchy
4. Drag **City** into that hierarchy

Now hierarchy looks like:

Country
→ State
→ City

---

## 📊 Step 2 – Create Column Chart

- Axis → Country hierarchy
- Values → Sales (Sum)

You now see Country-level data.

---

## 🔽 Step 3 – Use Drill Down Buttons

On the visual (top left icons):

- Drill Down (single arrow)
- Expand All Down One Level (double arrow)
- Drill Up

---

## 🧪 Demo

Click:

- Drill Down mode ON
- Click India

Now you see States under India.

Click Karnataka → See Cities.

---

## 🔼 Drill Up

Click Drill Up arrow to return to previous level.

---

## 🧠 Teaching Points

Drill Down:

- Works inside same visual
- Uses hierarchy
- Good for geographic or product breakdown

---

# 🔵 PART 2 – Drill Through

---

## 🧠 What is Drill Through?

Drill Through allows:

- Navigate to a different page
- See detailed data related to selected value

Example:
Click State → Go to detail page

---

## 🔧 Step 1 – Create Drill Through Page

Add new page
Rename it:

**State Details**

---

## 🔧 Step 2 – Enable Drill Through

On Page 2:

1. Drag **State** into Drill-through filter area (right pane)
2. Add Table visual:
   - OrderID
   - City
   - Category
   - Product
   - Sales

---

## 🔙 Step 3 – Add Back Button

Insert → Buttons → Back

Allows return to main page.

---

## 🧪 Step 4 – Use Drill Through

Go back to main page.

Right-click:

- Karnataka

Select:
Drill Through → State Details

Now only Karnataka data appears.

---

## 🧠 Imp Points

Drill Through:

- Opens new page
- Shows detailed records
- Keeps filter context

---

# 🔎 Drill Down vs Drill Through

| Feature            | Drill Down         | Drill Through         |
| ------------------ | ------------------ | --------------------- |
| Navigation         | Same visual        | Different page        |
| Requires hierarchy | Yes                | No                    |
| Used for           | Aggregation levels | Detailed view         |
| Example            | Country → State    | State → Order details |

---

# 🎯 Practice Task for Students

1. Create Category → Product hierarchy
2. Drill down to see product sales
3. Create Drill Through page for Category
4. Show detailed orders

---

# 💡 Strong Teaching Line

> Drill Down explores levels.
> Drill Through explores details.
