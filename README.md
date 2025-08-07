# Employee Analysis Dashboard

An interactive Power BI dashboard to analyze employees' headcount and salary distribution across departments, with dynamic filters and KPI cards for quick insights.

---

## 📊 Visuals Included
1. Employees per Department – Ribbon chart  
2. Average Monthly Income per Department – Pie chart  
3. HR Employees Monthly Income by Gender – Donut chart  
4. R&D Employees Monthly Income by Gender – Donut chart  
5. Sales Employees Monthly Income by Gender – Donut chart  

---

## 🔍 Interactivity
- Department Slicer filters all visuals instantly.  
- Two KPI Cards dynamically display:  
  - Total number of employees in the selected department  
  - Average monthly income for the selected department  
- Summary text updates based on slicer selection to provide context for decision-making.  

---

## 📂 Files in This Repository
- employee_analysis.pbix — Power BI dashboard file (sample data).  
- employees_sample.csv — anonymized dataset for demonstration.  
- media/ — contains images and a short demo video of the dashboard in action.  

---

## 📄 Dataset Overview
The dataset includes the following columns:  

| Column Name     | Description |
|-----------------|-------------|
| EmployeeID      | Unique employee identifier |
| Name            | Employee's name (anonymized) |
| Department      | Department name (e.g., HR, R&D, Sales) |
| Gender          | Employee gender (M/F) |
| MonthlyIncome   | Monthly salary amount |
| HireDate        | Date of joining |
| Age             | Employee's age |

---

## 🛠 Steps to Recreate the Dashboard
1. Load Data  
   - Open Power BI Desktop.  
   - Import employees_sample.csv.  
   - Set data types correctly (e.g., MonthlyIncome → Decimal Number, HireDate → Date).  

2. Create Visuals  
   - Ribbon Chart: Department on Axis, EmployeeID (Count) as Value.  
   - Pie Chart: Department vs Monthly Income (Average aggregation).  
   - Donut Charts: Filter each chart to a specific department, show MonthlyIncome by Gender.  
   - Slicer: Add Department.  
   - KPI Cards: Show Count of Employees and Average Monthly Income.  
   - Summary: Add a text box to describe the insights based on slicer selection.  

3. Formatting  
   - Apply thousands separators to numbers.  
   - Use a consistent color theme.  

---
## Preview & Files

### Overview screenshot
[![Dashboard Overview](https://raw.githubusercontent.com/MostafaHussien997/Employee-Analysis-Dashboard/main/Images/1.jpg))
> Click the image to view full-size screenshot.

### Power BI file (.pbix)
- Download the Power BI file: (https://raw.githubusercontent.com/MostafaHussien997/Employee-Analysis-Dashboard/main/Employee%20Dashboard.pbix)

### Demo video
- Watch the demo: (https://raw.githubusercontent.com/MostafaHussien997/Employee-Analysis-Dashboard/main/Demo/Demo%20Video.mp4)
---

## 📌 Key Insights
- Compare headcount across departments.
- Identify salary distribution patterns by department and gender.
- Quickly view KPIs for any department using the slicer.

---
## 📬 Contact

Feel free to connect with me:  
🔗 [LinkedIn](https://www.linkedin.com/in/mostafa-hussien-khalil-302a25177)

---
## 📜 License
This project uses the [MIT License](LICENSE).

---
📊 Numbers are just numbers, until you connect the dots.
