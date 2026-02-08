# 📘 Power BI Tutorial – Understanding Filters

---

# 🎯 Learning Objectives

By the end of this session, students will be able to:

- Understand what Filters are
- Apply Visual-level filters
- Apply Page-level filters
- Apply Report-level (All Pages) filters
- Understand the difference between them

---

# 📊 Step 1 – Load the Dataset

### File: `employee_performance.xlsx`

Import the dataset into Power BI.

---

# 📈 Step 2 – Create Base Visuals

Before applying filters, create these visuals:

---

## 1️⃣ Column Chart – Average Salary by Department

- Axis → Department
- Values → Salary (Average)

---

## 2️⃣ Bar Chart – Employees by City

- Axis → City
- Values → EmployeeID (Count)

---

## 3️⃣ Pie Chart – Employment Type

- Legend → Employment Type
- Values → EmployeeID (Count)

---

## 4️⃣ Card – Total Employees

- Field → EmployeeID (Count)

---

Now the page shows multiple visuals.

---

# 🔎 What is a Filter?

A filter limits the data shown in visuals.

Filters can be applied at three levels:

1. Visual Level
2. Page Level
3. Report Level

---

# 🟢 Visual-Level Filter

## Definition:

Affects only the selected visual.

---

## Demo Example:

Filter the **Column Chart** to show only the IT department.

### Steps:

1. Click the Column Chart
2. Open the **Filters pane**
3. Under **Filters on this visual**
4. Drag “Department”
5. Select only **IT**

---

### Result:

- Column chart changes
- Other visuals remain unchanged

---

## Teaching Point:

Visual filter applies to only one visual.

---

# 🟡 Page-Level Filter

## Definition:

Affects all visuals on the current page.

---

## Demo Example:

Filter the page to show only employees in Mumbai.

### Steps:

1. Drag “City” into **Filters on this page**
2. Select **Mumbai**

---

### Result:

- All visuals update
- Card value changes
- Pie chart updates
- Bar chart updates

---

## Teaching Point:

Page filter affects all visuals on one page only.

---

# 🔵 Report-Level Filter (All Pages)

## Definition:

Affects all pages in the report.

---

## Step 1 – Add a Second Page

Create Page 2 and add:

- Table visual (all employees)

---

## Demo Example:

Filter Employment Type = Full-time.

### Steps:

1. Drag “Employment Type” into **Filters on all pages**
2. Select **Full-time**

---

### Result:

- Page 1 visuals update
- Page 2 visuals update

---

## Teaching Point:

Report-level filter affects the entire report.

---

# 📊 Filter Comparison

| Filter Type | Affects                     |
| ----------- | --------------------------- |
| Visual      | Only selected visual        |
| Page        | All visuals on current page |
| Report      | All pages in report         |

---

# 🔧 Advanced Filter Examples (Optional)

You can also demonstrate:

### Salary Greater Than 80,000

1. Add Salary to filter pane
2. Choose Advanced filtering
3. Set condition → is greater than 80000

---

### Top N Filter

1. Select Bar chart
2. Add Department to Visual filter
3. Choose Top N
4. Top 2 by Salary

---

# 🧠 Important Concepts

- Filters reduce visible data
- Multiple filters can be applied
- Filters work together
- Filters affect aggregation

---

# 📝 Quick Classroom Questions

1. Which filter affects only one visual?
2. What happens if Page and Visual filters conflict?
3. When should Report-level filters be used?

---

# 💡 Imp Tip

> “Filters control what data your report shows.”

---

# 🎓 Mini Practice Task

1. Apply Visual filter → Department = HR
2. Apply Page filter → City = Delhi
3. Apply Report filter → Employment Type = Full-time
