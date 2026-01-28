# 📊 **Power BI Hands-On Session 03: Slicers, Tables & Formatting**

---

## 🎯 **Learning Objectives**

By the end of this session, learners will be able to:

- Add and use **Slicers**
- Create **Table visuals**
- Apply **basic formatting** for clean dashboards
- Understand how visuals interact with each other

---

## 📂 **Step 1: Sample Dataset**

Use the same Excel file to maintain continuity.

### **File Name:** `sales_interaction.xlsx`

### **Sheet Name:** `Sales`

| OrderID | Category    | Region | Sales |
| ------- | ----------- | ------ | ----- |
| 3001    | Stationery  | North  | 15000 |
| 3002    | Stationery  | South  | 12000 |
| 3003    | Accessories | North  | 18000 |
| 3004    | Accessories | West   | 22000 |
| 3005    | Electronics | East   | 25000 |
| 3006    | Electronics | South  | 20000 |
| 3007    | Furniture   | West   | 14000 |
| 3008    | Furniture   | North  | 16000 |

Save the file.

---

## 📥 **Step 2: Import Data**

1. Open **Power BI Desktop**
2. **Get Data → Excel**
3. Load `sales_interaction.xlsx`

---

## 📋 **Step 3: Create a Table Visual**

1. Click on empty canvas
2. Select **Table** visual
3. Drag the following fields:
   - OrderID
   - Category
   - Region
   - Sales

✔ Table displays detailed row-level data

---

## 🧩 **Step 4: Add a Slicer (Filter by Region)**

1. Click on empty canvas
2. Select **Slicer** visual
3. Drag `Region` into **Field**

✔ Slicer shows North, South, East, West

### 🧪 Test Interaction

- Click **North**
- Notice:
  - Table updates instantly
  - Other visuals respond automatically

---

## 📊 **Step 5: Create Bar Chart (Sales by Category)**

1. Add **Clustered Column Chart**
2. Axis → Category
3. Values → Sales

✔ Visual responds to slicer selections

---

## 🎨 **Step 6: Format Visuals Properly**

### 🖌️ Format Bar Chart

- Turn **Data labels → ON**
- Title → **Sales by Category**
- Align center
- Reduce gridlines

---

### 🖌️ Format Table

- Increase font size
- Turn **Gridlines OFF**
- Enable **Column headers**
- Adjust column width

---

### 🖌️ Format Slicer

- Change slicer orientation → Vertical
- Turn **Search ON**
- Rename title → **Select Region**

---

## 📐 **Step 7: Layout Best Practices**

- Align visuals properly
- Keep slicer on left/top
- Avoid overlapping visuals
- Maintain consistent spacing

---

## 💾 **Step 8: Save Report**

- File → Save
- Name: **`Session03_Slicers_Tables.pbix`**

---

## 📌 **What You Learned**

✔ Created Table visual
✔ Added Slicer
✔ Observed visual interaction
✔ Applied clean formatting
✔ Designed a simple layout

---

## 🧠 **Important Tip**

> “Slicers make reports feel alive”
