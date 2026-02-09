# 📘 Power BI Advanced Slicer Control Tutorial

## (Edit Interactions & Sync Slicers)

---

# 🎯 Learning Objectives

By the end of this session, students will:

- Control how visuals interact with each other
- Modify default cross-filtering behavior
- Sync slicers across multiple pages
- Design more professional dashboards

---

# 📊 Dataset Used

Continue using:

`employee_performance.xlsx`

---

# 🟢 PART 1 – Edit Interactions

---

## 🧠 What is Edit Interactions?

By default:

- When you click a visual or slicer,
- It filters all other visuals on that page.

Sometimes you may want:

- One visual NOT to affect another
- More control over filtering behavior

That’s where **Edit Interactions** is used.

---

## 🧪 Step 1 – Create Base Visuals

Create:

1️⃣ Column Chart – Average Salary by Department
2️⃣ Bar Chart – Employees by City
3️⃣ Pie Chart – Employment Type
4️⃣ Department Slicer

---

## 🧪 Step 2 – Observe Default Interaction

Click:

- “IT” in Department slicer

Notice:
✔ All visuals update

---

## 🔧 Step 3 – Use Edit Interactions

### Steps:

1. Select the Column Chart
2. Go to **Format ribbon**
3. Click **Edit Interactions**

Icons appear above other visuals:

- 🔍 Filter
- ✨ Highlight
- 🚫 None

---

## 🧪 Step 4 – Disable Interaction

Example:
Prevent Column Chart from affecting Pie Chart.

1. Select Column Chart
2. On Pie Chart → Click 🚫 (None)

Now:

- Clicking a department in column chart
- Will NOT affect pie chart

---

## 🧠 Teaching Point

Edit Interactions allows:

- Selective filtering
- Better storytelling
- Cleaner dashboard logic

---

## 🔍 Highlight vs Filter

Explain difference:

- **Filter** → Removes other data completely
- **Highlight** → Shows selected portion but keeps others faded

---

# 🟡 PART 2 – Sync Slicers

---

## 🧠 What is Sync Slicers?

By default:

- A slicer affects only the current page.

Sync Slicers allows:

- Same slicer to work across multiple pages.

---

## 🧪 Step 1 – Add Second Page

Create Page 2:

- Add Table visual (all employees)

---

## 🧪 Step 2 – Add Department Slicer on Page 1

---

## 🔧 Step 3 – Open Sync Pane

1. Select Department slicer
2. Go to **View → Sync Slicers**

Sync pane appears on right.

---

## 🧪 Step 4 – Sync Across Pages

In Sync pane:

For Page 2:
✔ Check **Sync**
✔ Check **Visible** (optional)

Now:

- Selecting IT on Page 1
- Automatically filters Page 2

---

## 🧠 Sync vs Visible

| Option  | Meaning                     |
| ------- | --------------------------- |
| Sync    | Applies filter to that page |
| Visible | Shows slicer on that page   |

You can:

- Sync but hide slicer on Page 2
- Maintain consistent filtering

---

# 🎯 Real-World Use Case

Example:
Page 1 – Summary
Page 2 – Detailed View

User selects:
Department = IT

All pages reflect IT automatically.

Professional dashboards use this frequently.

---

# 🧩 Comparison Summary

| Feature           | Purpose                               |
| ----------------- | ------------------------------------- |
| Edit Interactions | Control how visuals affect each other |
| Sync Slicers      | Apply slicer filters across pages     |

---

# 💡 Imp Tip

> “Slicers control filtering. Edit Interactions controls relationships.”
