# 📘 Power BI Tutorial – Slicers (Interactive Filtering)

---

# 🎯 Learning Objectives

By the end of this session, you will be able to:

* Understand what a slicer is
* Add and configure slicers
* Use single-select and multi-select slicers
* Convert slicers into dropdowns
* Format slicers professionally
* Understand how slicers differ from Filters

---

# 📊 Dataset Used

### `employee_performance.xlsx`

| EmployeeID | Employee Name | Department | City | Employment Type | Salary | Performance Rating |
| ---------- | ------------- | ---------- | ---- | --------------- | ------ | ------------------ |

(Use the same dataset from previous Filters session.)

---

# 🧠 What is a Slicer?

A **Slicer** is a visual filter that allows report users to filter data interactively.

> Filters are controlled by the report designer.
> Slicers are controlled by the report user.

---

# 📈 Step 1 – Create Base Visuals

Before adding slicers, create:

1️⃣ Column Chart – Average Salary by Department
2️⃣ Bar Chart – Employees by City
3️⃣ Pie Chart – Employment Type
4️⃣ Card – Total Employees

Now the report shows multiple visuals.

---

# 🟢 Step 2 – Add Your First Slicer

## Example: Department Slicer

### Steps:

1. Click on empty area
2. Select **Slicer visual**
3. Drag **Department** into the slicer field

You now see a list:

* IT
* HR
* Finance

---

## Test It:

Click “IT”

✔ All visuals update
✔ Card updates
✔ Charts change

Explain:

> Slicer affects all visuals on the page.

---

# 🟡 Step 3 – Convert to Dropdown Slicer

Sometimes list slicers take too much space.

### Steps:

1. Click slicer
2. Click dropdown arrow (top-right of slicer)
3. Select **Dropdown**

Now slicer becomes compact.

---

# 🔵 Step 4 – Enable Single Select

By default, slicers allow multiple selections.

### Steps:

1. Select slicer
2. Go to Format pane
3. Expand **Selection controls**
4. Turn ON:

   * Single select

Now only one department can be selected.

---

# 🟣 Step 5 – Multi-Select

Turn OFF Single select to allow:

* Ctrl + click multiple values

Demonstrate:
Select IT and HR together.

---

# 🟤 Step 6 – Add Multiple Slicers

Add slicers for:

* City
* Employment Type
* Performance Rating

Now demonstrate:

* City = Mumbai
* Department = IT

Show how filters combine.

Explain:

> Slicers work together (AND condition).

---

# 🟠 Step 7 – Clear Slicer Selection

Click the **eraser icon** in slicer to reset.

Teach students:
Always reset slicers before analysis.

---

# 🎨 Step 8 – Format Slicer Professionally

Select slicer → Format pane:

### Format Options:

* Title → ON
* Rename title to “Select Department”
* Change font size
* Adjust background color
* Border ON
* Increase spacing

Explain:

> Good formatting improves dashboard professionalism.

---

# 🧩 Step 9 – Numeric Slicer (Range Filter)

Add slicer for Salary.

It automatically becomes a **range slider**.

Demonstrate:

* Salary between 60,000 and 90,000

This is dynamic filtering.

---

# 🧠 Important Concepts to Explain

---

## 🔹 Slicer vs Filter

| Feature         | Filter Pane      | Slicer           |
| --------------- | ---------------- | ---------------- |
| Visible to user | No               | Yes              |
| Interactive     | Limited          | Yes              |
| Best for        | Designer control | User interaction |

---

## 🔹 Slicers Work at Page Level

Slicers affect:
✔ All visuals on that page
❌ Not other pages (unless synced)

---

# 🧪 Practice Task for Students

1. Add Department slicer
2. Convert to Dropdown
3. Enable Single Select
4. Add Salary range slicer
5. Add City slicer
6. Format slicers properly

---

# 🎯 Mini Dashboard Activity (10 Minutes)

Students create a clean layout:

Left panel:

* Department slicer
* City slicer

Right panel:

* Charts
* Card

---

# 🧠 Discussion Questions

1. When should we use slicer instead of filter?
2. What happens if multiple slicers conflict?
3. Can slicers slow down report performance?
