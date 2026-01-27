
# 🎓 **POWER BI COMPLETE COURSE – ALL 20 SESSIONS (MARKDOWN FORMAT)**

**(45-minute sessions × 20 days)**

---

# -----------------------------------------

# **SESSION 01 — Introduction to Power BI**

# -----------------------------------------

## **Objectives**

* Understand what Business Intelligence is
* Learn Power BI components
* Explore Power BI Desktop interface
* Build first simple chart

## **Topics Covered**

* BI Concepts
* Power BI Desktop vs Power BI Service
* Navigation: Ribbon, Views, Fields Pane
* Creating basic visual

## **Explanation**

Business Intelligence (BI) is the process of transforming raw data into useful insights. Power BI is Microsoft’s BI tool for building interactive dashboards.

Interface basics:

* **Report View** → Create visuals
* **Data View** → Inspect imported tables
* **Model View** → Manage relationships

## **Hands-on Exercise**

1. Open Power BI Desktop
2. Import a sample Excel/CSV file
3. Create a simple bar chart (Sales by Category)
4. Add a Card visual for Total Sales
5. Save file as `Lesson01.pbix`

## **Quiz**

1. Which view is used to create visuals?
2. What is Power BI?
3. What are the three main panes in Report View?

---

# -----------------------------------------

# **SESSION 02 — Importing Data**

# -----------------------------------------

## **Objectives**

* Import data from Excel, CSV
* Understand data types
* Explore auto-detected fields

## **Topics Covered**

* Get Data
* Data source types
* Data type conversion

## **Explanation**

Power BI accepts multiple formats: Excel, CSV, Web, Databases, JSON, etc.
Correct data types ensure accurate visuals and calculations.

## **Hands-on Exercise**

1. Import an Excel file with Sales data
2. Change data types for:

   * Date → Date
   * Price → Decimal Number
   * Quantity → Whole Number
3. Remove unnecessary columns

## **Quiz**

1. Name two supported file formats
2. What happens when a column has wrong data type?
3. Which icon represents Date type?

---

# -----------------------------------------

# **SESSION 03 — Power Query Basics**

# -----------------------------------------

## **Objectives**

* Work with Power Query Editor
* Clean and transform raw data

## **Topics Covered**

* ETL concept
* Removing rows
* Replacing values
* Applied Steps

## **Explanation**

Power Query is where data cleaning happens. Every transformation is recorded as a step, making changes traceable.

## **Hands-on Exercise**

1. Open Power Query
2. Remove blank rows
3. Replace null values in ‘City’ column with “Unknown”
4. Apply changes

## **Quiz**

1. Power Query is used for?
2. True/False: Transformations are saved as steps.
3. What does ETL stand for?

---

# -----------------------------------------

# **SESSION 04 — Data Cleaning & Shaping**

# -----------------------------------------

## **Objectives**

* Split, merge, append queries
* Handle missing/incomplete data

## **Topics Covered**

* Split Column
* Merge Queries
* Append Queries
* Data profiling

## **Explanation**

* **Split column** → when one column contains multiple fields
* **Merge queries** → join like SQL JOIN
* **Append** → stack datasets vertically

## **Hands-on Exercise**

1. Split FullName into FirstName + LastName
2. Merge Sales table with Product Details table
3. Append Sales_Q1 and Sales_Q2 tables

## **Quiz**

1. Difference between Merge and Append?
2. When do you use Split Columns?
3. What is a Join Kind?

---

# -----------------------------------------

# **SESSION 05 — Data Modelling (Basics)**

# -----------------------------------------

## **Objectives**

* Understand relationships
* Build a simple data model

## **Topics Covered**

* Star schema
* Cardinality
* Relationship directions

## **Explanation**

Fact tables contain numeric values.
Dimension tables describe facts.
Common cardinalities:

* One-to-Many
* Many-to-One

## **Hands-on Exercise**

1. Load Sales, Products, Customers tables
2. Create relationships using ProductID, CustomerID
3. Validate relationship directions

## **Quiz**

1. What is a Fact table?
2. Define Cardinality
3. Why do we create relationships?

---

# -----------------------------------------

# **SESSION 06 — Basic Visuals**

# -----------------------------------------

## **Objectives**

* Create foundational charts

## **Topics Covered**

* Bar/Column
* Pie/Donut
* Card/KPI

## **Explanation**

Use bar charts for comparison, pie charts for composition, and cards/KPIs for single-number summaries.

## **Hands-on Exercise**

1. Bar chart: Sales by Region
2. Card visual: Total Sales
3. KPI: Actual vs Target

## **Quiz**

1. Which visual compares categories?
2. What is a KPI?
3. Should pie charts have many slices?

---

# -----------------------------------------

# **SESSION 07 — Tables, Matrix & Slicers**

# -----------------------------------------

## **Objectives**

* Build tables & matrix
* Use slicers effectively

## **Topics Covered**

* Table vs Matrix
* Slicers
* Visual-level filters

## **Explanation**

Tables show row-level data.
Matrix provides pivot-table style summary.
Slicers help filter reports interactively.

## **Hands-on Exercise**

1. Create Matrix for Category → Year → Sales
2. Add slicer: Filter by Region
3. Apply visual-level filter: Sales > 10,000

## **Quiz**

1. What is a Matrix?
2. What is a slicer?
3. What is conditional formatting?

---

# -----------------------------------------

# **SESSION 08 — Formatting & Interactivity**

# -----------------------------------------

## **Objectives**

* Format visuals
* Use bookmarks
* Apply drill-through

## **Topics Covered**

* Themes
* Visual formatting
* Drill-down
* Bookmarks

## **Explanation**

Formatting improves readability.
Bookmarks help create guided storytelling and custom navigation.

## **Hands-on Exercise**

1. Import a theme
2. Create bookmark “High Sales View”
3. Add button to navigate

## **Quiz**

1. What is a bookmark?
2. What does drill-down do?
3. Can themes be imported?

---

# -----------------------------------------

# **SESSION 09 — Geo Visuals**

# -----------------------------------------

## **Objectives**

* Plot geographical data

## **Topics Covered**

* Filled Map
* Shape Map
* Data Category settings

## **Explanation**

Geo visuals require proper data categories like Country, State, City.

## **Hands-on Exercise**

1. Create Filled Map: Sales by State
2. Set correct Data Category: State → State or Province

## **Quiz**

1. What data category enables maps?
2. What is geo-coding?
3. Why do map visuals show warnings?

---

# -----------------------------------------

# **SESSION 10 — Dashboard Design Principles**

# -----------------------------------------

## **Objectives**

* Learn layout fundamentals
* Avoid common mistakes

## **Topics Covered**

* Spacing
* Color palette
* Chart selection
* Visual hierarchy

## **Explanation**

Good dashboards are clean, minimal, and visually balanced.

## **Hands-on Exercise**

Redesign a cluttered dashboard using:

* Consistent colors
* Proper spacing
* Appropriate visuals

## **Quiz**

1. Why avoid too many colors?
2. What is visual hierarchy?
3. Which chart is best for trends?

---

# -----------------------------------------

# **SESSION 11 — Introduction to DAX**

# -----------------------------------------

## **Objectives**

* Learn DAX basics
* Understand measures vs calculated columns

## **Topics Covered**

* SUM, COUNT, DISTINCTCOUNT
* Calculated columns
* Measures

## **Explanation**

DAX is formula language for Power BI calculations.

## **Hands-on Exercise**

Create the following measures:

* Total Sales
* Total Units
* Unique Customers

## **Quiz**

1. What is DAX?
2. Difference between measure and calculated column?
3. Which function adds numbers?

---

# -----------------------------------------

# **SESSION 12 — Time Intelligence (Part 1)**

# -----------------------------------------

## **Objectives**

* Work with date-based DAX

## **Topics Covered**

* YTD, QTD, MTD
* SAMEPERIODLASTYEAR

## **Explanation**

Time intelligence functions require a proper Date table with continuous dates.

## **Hands-on Exercise**

1. Create Date Table
2. Create: Sales YTD
3. Create: Sales Last Year

## **Quiz**

1. Why do we need a Date table?
2. What is YTD?
3. SAMEPERIODLASTYEAR returns what?

---

# -----------------------------------------

# **SESSION 13 — Time Intelligence (Part 2)**

# -----------------------------------------

## **Objectives**

* Build advanced date-based calculations

## **Topics Covered**

* PREVIOUSMONTH
* DATESYTD
* Rolling metrics

## **Explanation**

Rolling metrics are moving windows that smooth trends.

## **Hands-on Exercise**

Create a Rolling 3-month Sales measure.

## **Quiz**

1. What does PREVIOUSMONTH return?
2. What is DATESYTD used for?
3. Why use rolling metrics?

---

# -----------------------------------------

# **SESSION 14 — Advanced DAX**

# -----------------------------------------

## **Objectives**

* Use CALCULATE
* Use ALL to remove filters
* Use FILTER for row-level logic

## **Topics Covered**

* CALCULATE
* ALL
* FILTER
* EARLIER basics

## **Explanation**

CALCULATE modifies filter context.
ALL removes filters.
FILTER creates table expressions for DAX calculations.

## **Hands-on Exercise**

1. Sales_without_filters = CALCULATE([Total Sales], ALL(Sales))

## **Quiz**

1. What does CALCULATE do?
2. What does ALL remove?
3. FILTER is used for?

---

# -----------------------------------------

# **SESSION 15 — Advanced Modelling**

# -----------------------------------------

## **Objectives**

* Learn RLS
* Build Date Table
* Understand normalization

## **Topics Covered**

* Star schema
* RLS
* Table roles

## **Explanation**

RLS restricts data visibility based on user roles.

## **Hands-on Exercise**

1. Create RLS role: Region Manager sees only their region

## **Quiz**

1. What is RLS?
2. What is a dimension table?
3. Why normalize data?

---

# -----------------------------------------

# **SESSION 16 — Publishing to Power BI Service**

# -----------------------------------------

## **Objectives**

* Publish reports
* Work with Workspaces

## **Topics Covered**

* Publishing
* Version control basics
* Sharing

## **Explanation**

Power BI Service is the cloud platform for dashboards and collaboration.

## **Hands-on Exercise**

Publish report → Add to Workspace.

## **Quiz**

1. What is a workspace?
2. Can reports be shared publicly?
3. What is publishing?

---

# -----------------------------------------

# **SESSION 17 — Dashboards in Power BI Service**

# -----------------------------------------

## **Objectives**

* Build dashboards
* Pin visuals
* Create alerts

## **Topics Covered**

* Dashboards vs Reports
* Alerts
* Subscriptions

## **Explanation**

Dashboards are a collection of pinned visuals from different reports.

## **Hands-on Exercise**

1. Pin KPIs to Dashboard
2. Create an alert: Sales < Target

## **Quiz**

1. What does “Pin” do?
2. Can dashboards have multiple pages?
3. Alerts work on which visual type?

---

# -----------------------------------------

# **SESSION 18 — Power Automate & Integrations**

# -----------------------------------------

## **Objectives**

* Use Power Automate with BI
* Export & share data

## **Topics Covered**

* Power Automate flows
* Analyze in Excel
* Export to PDF/PPT

## **Explanation**

Power Automate helps create automated workflows like sending emails on refresh.

## **Hands-on Exercise**

Create a flow: Email notification when dataset refreshes.

## **Quiz**

1. What is Power Automate for?
2. What is “Analyze in Excel”?
3. Can Power BI export to PDF?

---

# -----------------------------------------

# **SESSION 19 — Data Refresh & Gateways**

# -----------------------------------------

## **Objectives**

* Set up scheduled refresh
* Use On-Premises Gateway

## **Topics Covered**

* Gateway types
* Refresh frequency
* Troubleshooting errors

## **Explanation**

Refresh keeps reports updated with latest data.

## **Hands-on Exercise**

1. Install Gateway (personal mode)
2. Schedule Daily refresh at 8 AM

## **Quiz**

1. What is a Gateway?
2. Why schedule refresh?
3. How many refreshes allowed in free version?

---

# -----------------------------------------

# **SESSION 20 — Final Project**

# -----------------------------------------

## **Objective**

Build a complete Power BI dashboard using all concepts.

## **Project Requirements**

* Minimum **3 tables**
* Minimum **6 visuals**
* **2 slicers**
* **3 DAX measures**
* Include **Time Intelligence**
* Include **Geo visual**
* Publish to Power BI Service
* Create dashboard and share link

## **Project Ideas**

* Retail Sales Dashboard
* Student Performance Analysis
* HR Analytics Dashboard
* Hospital Patient Analytics
* E-commerce KPI Dashboard

## **Evaluation Criteria**

* Data Modelling — 20%
* DAX Usage — 20%
* Visual Design — 20%
* Insights — 20%
* Presentation — 20%