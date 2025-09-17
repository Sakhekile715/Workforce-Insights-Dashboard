# Workforce-Insights-Dashboard

This Power BI dashboard provides an analytical view of workforce data, enabling HR teams and business leaders to monitor employee trends, performance, and organizational health. It consolidates key HR metrics into an interactive platform for data-driven decision-making.

▶️ [Watch Project Walkthrough (Loom Video)]([https://www.loom.com/share/04bf95b322c64c1baf625f58f735e06b?sid=18a5c0a8-2887-47f4-9889-916966ef59b7])


---

## 📊 Project Overview
- **Focus**: Human Resources analytics (workforce, performance, attrition, demographics)  
- **Audience**: HR professionals, business managers, executives  
- **Goal**: Transform raw HRIS data into actionable insights to improve employee experience and organizational performance  

---

## 🗺️ Features
- Employee demographics (age, gender, location, department)  
- Headcount and leave tracking  
- Performance rating distribution and category analysis  
- Tenure analysis (years of service) to date. 
- Interactive drill-through to department- or employee-level data  
- KPI cards with total headcount, total amount spent on bonuses/allowance, and average tenure (Years).
---

## 🧮 Methodology
The dashboard integrates the raw HR dataset and applies transformations to ensure data quality and usability. Analysis includes:  
- **Categorization** of performance ratings into Low, Average, and High groups  
- **DAX calculations** for tenure, and performance categories   
- **Interactive filters and slicers** for performance category, region, and Work location
- **Calendar Table** for date columns using DAX to enable trend analysis. 

---

## 🛠️ Tools & Skills Used
- **Power BI** (DAX, Power Query, KPI cards, drill-throughs, conditional formatting)  
- **Data cleaning & transformation**  
- **Data visualization & storytelling**  

---

## 📑 Dashboard Pages
1. **Dashboard Overview** – High-level KPIs and demographic breakdowns  
2. **Average Performance Tooltip** – Average Performance Tooltip for category performance breakdown.  
3. **Gender vs. Salary** – Total Salary contributions towards employees (Gender Salary Distribution)
4. **Professional Development** – Drill through to specific details of employees' initiatives for professional development.  

---

## ⚠️ Limitations
- Dataset may be anonymized or simulated (not actual company data)  
- Analysis depends on available data fields (e.g., if absenteeism is not included, it won’t appear)  
- Limited predictive analytics; dashboard is primarily descriptive and diagnostic  

---

## 📂 Dataset 
- Transformation on fields and data type cleaning from the initial (e.g, handling data types).
- Tenure calculations derived using `DATEDIFF` in Power BI DAX  
- Age range grouped into categories for clearer insights  

---

## 🙌 Author
Built by **Sakhekile Jerry Mtyingizane**  



