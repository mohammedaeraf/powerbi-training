
# 📊 **Power BI Hands-On Tutorial: Creating Your First Visuals**

## *(Bar Chart & Card using Sample Sales Data)*

---

## 🎯 **Learning Objectives**

By the end of this tutorial, learners will be able to:

* Import a simple dataset
* Create a **Bar / Column chart**
* Create a **Card (KPI) visual**
* Understand how Power BI aggregates data automatically

---

## 📂 **Step 1: Prepare Sample Sales Data**

Create an Excel file with the following data.

### **File Name:** `sales_visuals.xlsx`

### **Sheet Name:** `Sales`

| Category    | Sales |
| ----------- | ----- |
| Stationery  | 15000 |
| Accessories | 22000 |
| Electronics | 18000 |
| Furniture   | 12000 |
| Groceries   | 9000  |

Save the file.

---

## 📥 **Step 2: Import Data into Power BI**

1. Open **Power BI Desktop**
2. Click **Get Data → Excel**
3. Select `sales_visuals.xlsx`
4. Choose sheet **Sales**
5. Click **Load**

✔ Data appears in the **Fields** pane

---

## 📊 **Step 3: Create Bar (Column) Chart – Sales by Category**

1. Click on empty canvas
2. In **Visualizations**, select **Clustered Column Chart**
3. Drag:

   * `Category` → **X-Axis**
   * `Sales` → **Y-Axis / Values**

🎉 You have created your **first chart**

---

## 🧮 **Step 4: Create Card Visual – Total Sales**

1. Click on empty area
2. Select **Card** visual
3. Drag `Sales` into **Values**

✔ Power BI automatically shows **Sum of Sales**

---

## 🧠 **Important Concept: Automatic Aggregation**

* Power BI automatically applies **SUM**
* You can change aggregation:
  * Click dropdown on Sales → Sum / Average / Count

---

## 🎨 **Step 5: Simple Formatting (Optional)**

### For Bar Chart:

* Turn **Data labels → ON**
* Increase **Title font size**
* Rename title to: **Sales by Category**

### For Card:

* Increase font size
* Change title to: **Total Sales**

---

## 💾 **Step 6: Save Your Report**

* File → Save
* Name: **`Visuals_HandsOn.pbix`**

---

## 📌 **What You Have Learned**

✔ Imported Excel data
✔ Created a Bar chart
✔ Created a Card visual
✔ Understood aggregation
✔ Saved a Power BI report

---

## ❓ **Quick Practice Questions**

1. What happens if you remove Category from the chart?
2. Can a Card show Average Sales instead of Total?
3. Which pane shows available fields?
