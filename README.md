# COFFE-ORDER-PROJECT
This project demonstrates how to build an interactive coffee sales dashboard in Excel, covering data gathering, transformation, pivot tables, pivot charts, dashboard design. It uses XLOOKUP, INDEX-MATCH, IF functions, formatting, with slicers and timelines for filtering by coffee type, country, and customer! 

# Interactive Coffee Sales Dashboard (Excel)

## Project Overview
This project is an end-to-end Excel data analysis project that demonstrates how to build a **dynamic and interactive coffee sales dashboard**. It covers the full workflow—from data gathering and transformation to visualization and dashboard design—using pivot tables, pivot charts, slicers, and timelines.

---

## Project Workflow

### 1. Data Gathering
**Problem:**  
The data required for analysis was distributed across multiple tables: **Orders**, **Customers**, and **Products**.

**Solution:**  
- Used **XLOOKUP** to retrieve customer details (Customer Name, Email, Country) from the *Customers* table into the *Orders* table. This function provides a simple and modern approach to value lookups.
- Used **INDEX-MATCH** to retrieve product details (Coffee Type, Roast Type, Size, Unit Price) from the *Products* table. INDEX-MATCH was chosen for its flexibility and ability to populate multiple columns when dragged.

**Business Insight:**  
Consolidating data from multiple sources provides a complete operational view and ensures accurate, reliable analysis.

---

### 2. Data Transformation and Preparation
**Problem:**  
Raw data required calculations, cleaning, and structural improvements before analysis.

**Solution:**  
- Calculated **Sales** by multiplying *Unit Price* by *Quantity*.
- Used **IF functions** to categorize data such as roast type based on unit price.
- Formatted dates and numeric values for readability and consistency.
- Identified and removed duplicate records to maintain data accuracy.
- Converted the dataset into an **Excel Table** to allow automatic expansion and seamless pivot table updates.

**Business Insight:**  
Clean, structured data is the foundation of reliable reporting. Excel Tables reduce errors and simplify future data updates.

---

### 3. Building Pivot Tables and Charts
**Problem:**  
Extracting insights and trends from large datasets.

**Solution:**  
- Created a **Total Sales Over Time** line chart to analyze trends by coffee type.
- Built a **Sales by Country** bar chart to identify top-performing regions.
- Developed a **Top 5 Customers** bar chart to highlight high-value customers.
- Applied formatting for clarity and visual appeal.

**Business Insight:**  
Visual analytics make trends, performance, and customer value easy to interpret and act upon.

---

### 4. Adding Interactivity with Timelines and Slicers
**Problem:**  
Static reports limit data exploration and decision-making.

**Solution:**  
- Added a **Timeline** linked to order dates for time-based filtering.
- Inserted **Slicers** for Roast Type, Size, and Loyalty Card status.
- Connected all slicers and the timeline to every pivot chart to ensure synchronized filtering.

**Business Insight:**  
Interactivity empowers users to explore data independently and gain insights without rebuilding reports.

---

### 5. Dashboard Assembly and Refinement
**Problem:**  
Multiple visuals needed to be organized into a cohesive dashboard.

**Solution:**  
- Created a dedicated worksheet named **Dashboard**.
- Adjusted layout, spacing, and alignment for usability.
- Added a dashboard title bar.
- Positioned all charts, slicers, and the timeline into a clean layout.
- Removed gridlines, headers, scroll bars, and the formula bar for a professional finish.

**Business Insight:**  
A well-designed dashboard centralizes KPIs and supports faster, more informed decision-making.

---

## Overall Business Value
This project demonstrates how raw sales data can be transformed into a powerful, interactive Excel dashboard that enables organizations to:

- Identify sales trends and seasonal patterns  
- Analyze geographical performance  
- Recognize and reward high-value customers  
- Explore data dynamically for faster decisions  

---

## Problem Solved
The dashboard addresses the lack of a **centralized, dynamic, and easy-to-understand sales reporting tool**. Instead of relying on static reports or manual analysis, stakeholders now have a real-time, interactive solution for monitoring and evaluating coffee sales performance.
