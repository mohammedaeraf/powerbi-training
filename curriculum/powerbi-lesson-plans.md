# 🎓 **DETAILED MODULE-WISE LESSON PLAN (20 Sessions)**

Each session = **Objective → Explanation → Demo → Exercise → Quiz**

---

# **🌟 WEEK 1 — Foundations & Data Preparation (Sessions 1–5)**

---

## **Session 1: Introduction to Power BI**

**Objectives:**

* Understand Business Intelligence
* Explore Power BI Desktop UI
* Build first simple visual

**Topics:**

* What is BI?
* Power BI ecosystem
* Interface walkthrough

**Hands-on Exercise:**
Load an Excel file → create a bar chart → save PBIX.

**Quiz (3 Questions):**

1. Power BI Desktop is mainly used for?
2. What pane shows available data fields?
3. What is a *visual*?

---

## **Session 2: Importing Data**

**Topics:**

* Import from Excel, CSV
* Data types
* Auto date/time

**Hands-on:**
Import a sales CSV → verify data types → adjust wrongly detected types.

**Quiz:**

1. Name 2 formats supported by Power BI.
2. What happens if a column type is incorrect?
3. What is the difference between text and whole number?

---

## **Session 3: Power Query Basics**

**Topics:**

* What is ETL
* Remove rows/columns
* Replace values

**Hands-on:**
Open Power Query → clean dataset → remove blank rows → replace nulls.

**Quiz:**

1. Power Query is used for?
2. True/False: Transformations are saved as steps.
3. What is a query?

---

## **Session 4: Data Cleaning & Shaping**

**Topics:**

* Split column by delimiter
* Merge queries
* Append queries

**Hands-on:**
Split “FullName” → Merge “City” table with “State” table.

**Quiz:**

1. Difference between Merge and Append?
2. When do we use Split Columns?
3. What is a join type?

---

## **Session 5: Data Modelling**

**Topics:**

* Relationships
* Cardinality
* Star schema basics

**Hands-on:**
Create relationship between Sales (fact) and Products (dimension).

**Quiz:**

1. What is cardinality?
2. Why use a Date table?
3. One-to-many means?

---

---

# **🌟 WEEK 2 — Data Visualization (Sessions 6–10)**

---

## **Session 6: Basic Visuals**

**Topics:**

* Bar, Column, Pie
* KPIs, Cards

**Hands-on:**
Create sales by region bar chart. Add card for total sales.

**Quiz:**

1. Which visual is best for comparison?
2. Card visual shows what?
3. Is pie chart suitable for >5 categories?

---

## **Session 7: Tables & Slicers**

**Topics:**

* Tables vs Matrix
* Slicers
* Filtering vs Highlighting

**Hands-on:**
Add slicer for Year → Apply to page.

**Quiz:**

1. What is a Matrix visual?
2. Difference between filter and slicer?
3. What is conditional formatting?

---

## **Session 8: Formatting**

**Topics:**

* Themes
* Visual formatting
* Drill through
* Bookmarks

**Hands-on:**
Create a bookmark for “High Sales” view.

**Quiz:**

1. What are bookmarks?
2. What is drill-down used for?
3. Can themes be imported?

---

## **Session 9: Geo Visuals**

**Topics:**

* Filled map
* Shape map
* Data category settings

**Hands-on:**
Plot sales by state using Filled Map.

**Quiz:**

1. Which field type is required for maps?
2. What is geo-coding?
3. What causes map ambiguity?

---

## **Session 10: Dashboard Design**

**Topics:**

* Layout
* Best chart practices
* Choosing appropriate visuals

**Hands-on:**
Redesign an existing cluttered report.

**Quiz:**

1. Why avoid too many colors?
2. What makes a good dashboard?
3. What is visual hierarchy?

---

---

# **🌟 WEEK 3 — DAX & Calculations (Sessions 11–15)**

---

## **Session 11: Intro to DAX**

**Topics:**

* Calculated column vs measure
* SUM, AVERAGE, COUNT, DISTINCTCOUNT

**Hands-on:**
Create measures: `Total Sales`, `Total Units`.

**Quiz:**

1. DAX stands for?
2. Calculated column is stored where?
3. What function aggregates numbers?

---

## **Session 12: Time Intelligence (1)**

**Topics:**

* YTD, QTD, MTD
* SAMEPERIODLASTYEAR

**Hands-on:**
Calculate YTD Sales.

**Quiz:**

1. Why is date table required?
2. What is YTD?
3. What does SAMEPERIODLASTYEAR return?

---

## **Session 13: Time Intelligence (2)**

**Topics:**

* PREVIOUSMONTH
* DATESYTD
* Rolling totals

**Hands-on:**
Create Rolling 3-Month Sales measure.

**Quiz:**

1. Name one time intelligence function.
2. Why build rolling metrics?
3. What does PREVIOUSMONTH return?

---

## **Session 14: Advanced DAX**

**Topics:**

* CALCULATE
* ALL
* FILTER
* EARLIER basics

**Hands-on:**
Create measure: “Sales without filter”.

**Quiz:**

1. CALCULATE changes what?
2. ALL removes what?
3. FILTER is used for?

---

## **Session 15: Advanced Modelling**

**Topics:**

* Normalization
* Date table creation
* Row-level security

**Hands-on:**
Create RLS role: “Salesperson can see only their region”.

**Quiz:**

1. What is RLS used for?
2. What is a dimension table?
3. When is normalization needed?

---

---

# **🌟 WEEK 4 — Power BI Service & Final Project (Sessions 16–20)**

---

## **Session 16: Publishing**

**Topics:**

* Publish to Service
* Workspaces
* Version handling

**Hands-on:**
Publish first report to Power BI Service.

**Quiz:**

1. What is a workspace?
2. Who can view reports?
3. What is publishing?

---

## **Session 17: Dashboards in Power BI Service**

**Topics:**

* Creating dashboards
* Pinning visuals
* Alerts & subscriptions

**Hands-on:**
Create dashboard & set alert on KPI.

**Quiz:**

1. What is pinning?
2. Alerts work on which visual?
3. Are dashboards and reports same?

---

## **Session 18: Integrations**

**Topics:**

* Power Automate basics
* Excel integration
* Export-to-PDF/PPT

**Hands-on:**
Create simple Power Automate flow → email on data refresh.

**Quiz:**

1. Power Automate is used for?
2. What is Analyze in Excel?
3. Can Power BI export to PDF?

---

## **Session 19: Data Refresh & Gateways**

**Topics:**

* Scheduled refresh
* Gateway installation
* Troubleshooting

**Hands-on:**
Schedule daily refresh.

**Quiz:**

1. What is a gateway?
2. Why scheduled refresh?
3. How many refreshes allowed in free version?

---

## **Session 20: Final Mini-Project (Presentation Session)**

**Objective:**
Learners build a complete Power BI dashboard using all concepts.

**Requirements:**

* At least **3 tables**
* At least **6 visuals**
* At least **2 slicers**
* **3 DAX measures**
* Must include **Time Intelligence**
* Include **geo-visual**
* Publish to Power BI Service
* Create a dashboard and share link

**Project Ideas:**

* Retail Sales Dashboard
* Student Performance Dashboard
* HR Attrition Dashboard
* Hospital Patient Analysis
* E-commerce Sales Insights

**Evaluation Criteria:**

* Data modelling (20%)
* DAX usage (20%)
* Visualization quality (20%)
* Insights generated (20%)
* Presentation & explanation (20%)