# 📘 Assignment: Employee Performance KPI Dashboard

*(Correct Time-Based Version)*

---

# 📂 Dataset

### File Name: `employee_performance_kpi_updated.xlsx`

| EmployeeID | EmployeeName | Department | ReviewDate | PerformanceRating |
| ---------- | ------------ | ---------- | ---------- | ----------------- |
| E001       | Aarav        | IT         | 01-01-2024 | 4                 |
| E002       | Priya        | IT         | 01-01-2024 | 3                 |
| E003       | Rahul        | HR         | 01-01-2024 | 5                 |
| E004       | Sneha        | Finance    | 01-01-2024 | 4                 |
| E005       | Karan        | IT         | 01-01-2024 | 2                 |
| E006       | Meera        | HR         | 10-04-2024 | 4                 |
| E007       | Vikram       | Finance    | 10-04-2024 | 5                 |
| E008       | Ananya       | IT         | 10-04-2024 | 3                 |
| E009       | Rohan        | HR         | 10-04-2024 | 2                 |
| E010       | Kavya        | Finance    | 10-04-2024 | 4                 |

---

# 🎯 What This Dataset Represents

* January Review (5 employees)
* April Review (5 employees)
* Department-wise performance
* Time-based comparison possible

Now KPI will compare:

👉 Average rating in April
vs
Target rating

And show trend from January → April.

---

# 📝 Part A – Create Measures

---

## 1️⃣ Average Rating

```DAX
Average Rating = 
AVERAGE(Employees[PerformanceRating])
```

---

## 2️⃣ Target Rating

```DAX
Target Rating = 4
```

---

## 3️⃣ Achievement %

```DAX
Achievement % = 
DIVIDE([Average Rating], [Target Rating])
```

Format as Percentage.

---

## 4️⃣ High Performers

```DAX
High Performers =
CALCULATE(
    COUNT(Employees[EmployeeID]),
    Employees[PerformanceRating] >= 4
)
```

---

# 📊 Part B – Create KPI Visual

Add KPI visual:

* Indicator → Average Rating
* Target Goals → Target Rating
* Trend Axis → ReviewDate

---

# 🧠 What KPI Will Show Now

First it calculates:

January Avg = (4+3+5+4+2)/5 = 3.6
April Avg = (4+5+3+2+4)/5 = 3.6

Latest Date = April

So KPI shows:

Average Rating = 3.6
Target = 4
Achievement % = 90%

Trend Line:

Jan (3.6) → April (3.6)

Now this is correct business behavior.

---

# 📈 Part C – Supporting Visuals

Create:

1️⃣ Line Chart → Average Rating by ReviewDate
2️⃣ Column Chart → Average Rating by Department
3️⃣ Card → Achievement %
4️⃣ Card → High Performers

---

# 🎛 Part D – Add Department Slicer

Add slicer:
Department

Test:

Select IT
Now KPI recalculates for IT only.

This demonstrates filter context clearly.

---

# 🧠 Imp Tips

> KPI is comparing the latest review cycle’s performance, not individual employees.
> KPI tracks performance by period, not by person.
