# Power-BI-Reports
# Adventure Works Sales & Returns Analysis Dashboard

## Project Overview

This project presents a comprehensive Business Intelligence solution for **"Adventure Works Cycles,"** a fictitious global manufacturing company specializing in cycling equipment.  
The primary goal was to transform raw sales and returns data into actionable insights—empowering management to make data-driven decisions regarding **sales performance, product profitability,** and **customer behavior**.

This project was undertaken as part of the **Maven Analytics Power BI Desktop course**, significantly deepening my expertise gained from the course.

---

## Business Questions Addressed

- What are the key sales, revenue, profit, and return rate KPIs?  
- How has revenue trended over time, and what seasonal patterns exist?  
- Which product categories and sub-categories are the most profitable, and which are most returned?  
- How does sales performance vary across different geographical regions?  
- Who are the high-value customers, and what are their demographic characteristics?  
- What insights can be derived to optimize sales strategies and reduce returns?

---

## Tools & Technologies

- **Microsoft Power BI Desktop:** For data modeling, DAX calculations, and interactive dashboard design  
- **Power Query (M Language):** For data extraction, cleaning, transformation, and loading (ETL)  
- **DAX (Data Analysis Expressions):** For creating complex measures and calculated columns  
- **Microsoft Excel / CSV:** Source data files

---

## Project Phases & Key Learnings

### 1. Data Acquisition & Transformation

- **Process:**  
  Connected to multiple CSV files representing sales, returns, products, customers, and calendar data.  
  Utilized Power Query for extensive data cleaning (handling missing values, correcting data types, splitting columns) and transformation.

- **Learning:**  
  Deepened understanding of advanced Power Query functionalities, efficient ETL processes, and ensuring data quality for robust analysis.

---

### 2. Data Modeling

- **Process:**  
  Built a robust star schema data model, establishing one-to-many relationships between fact tables (Sales, Returns) and dimension tables (Customer, Product, Calendar, Territory).  
  Optimized for performance and intuitive filtering.

- **Learning:**  
  Mastered best practices for relational data modeling, understanding cardinality, and filter context to create a scalable and efficient data structure.

---

### 3. DAX Calculations

- **Process:**  
  Developed a suite of complex DAX measures and calculated columns to derive key performance indicators (KPIs) such as `Total Revenue`, `Total Profit`, `Return Rate`, `Year-over-Year Growth (YoY)`, `Profit Margin`, and more.

- **Learning:**  
  Enhanced proficiency in DAX, including time-intelligence functions and iterative functions, to create dynamic and insightful metrics.

---

### 4. Interactive Dashboard Design

- **Process:**  
  Designed a multi-page, interactive Power BI dashboard with an executive summary, product detail, geographical analysis, and customer insights pages.  
  Utilized various visualizations (card visuals, line charts, bar charts, maps, tables) and interactive elements (slicers, drill-throughs).

- **Learning:**  
  Gained expertise in creating user-friendly, visually appealing, and highly interactive dashboards that effectively communicate complex data stories to diverse stakeholders.

---

## Key Insights & Findings

- **Product Performance:**  
  Bikes consistently drove the highest revenue and profit, while Accessories—despite lower individual value—often led in order volume, suggesting different market approaches.

- **Regional Sales Dynamics:**  
  The United States was the leading market in terms of total sales, but Australia showed a higher average revenue per customer, indicating distinct purchasing behaviors.

- **Seasonal Trends:**  
  Analysis revealed clear seasonal spikes in sales, particularly in December, aligning with holiday shopping patterns. Noticeable fluctuations were also observed in mid-2020, likely reflecting broader market influences.

- **Customer Segmentation:**  
  Identified high-value customer segments based on demographics like education level and occupation, providing actionable insights for targeted marketing and customer retention strategies.

- **Return Rate Analysis:**  
  Specific product types, such as *Shorts*, showed higher return rates, indicating potential areas for product quality review or improved product descriptions.

---

## Repository Contents

- `AdventureWorks Report PBIX.pdf`: The main Power BI project report exported as a PDF file.
- `AdventureWorksRawData.zip`: Contains the raw datasets used for analysis.

