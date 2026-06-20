# HR-Analytics-Employee-Insights-Dashboard
# HR Analytics: Employee Performance & Payroll Dashboard 📊

## 🎓 About the Project
As a student at **FAST NUCES** and having recently completed my **Power BI Certification from SimpliLearn**, I developed this project to demonstrate end-to-end data analytics capabilities. This dashboard is the result of intensive practice and represents the "Best-of-Four" projects I developed during my learning journey.

## 🚀 Key Features
* **Workforce Demographics:** Analysis of 680+ employees across 5 countries and multiple departments.
* **Salary Analytics:** Evaluation of Annual Payroll vs. Average Job Rates.
* **Interactive Filtering:** Dynamic slicing by Country, Gender, and Center.
* **Modern Developer Workflow:** Implementation of **TMDL** for version control and clean model definition.

## 🛠️ Technical Stack
* **Tool:** Power BI Desktop
* **Data Transformation:** Power Query (M)
* **Modeling:** DAX (Data Analysis Expressions) for explicit measures
* **Version Control:** TMDL (Tabular Model Definition Language)
* **UI/UX:** Neumorphic design with shadows and rounded corners for a 3D effect.

## 📈 Featured DAX Measures
```dax
Total Employees = COUNTROWS('EmpTable')

Salary Efficiency = DIVIDE(SUM('EmpTable'[Annual Salary]), SUM('EmpTable'[Job Rate]), 0)

Leave Intensity = AVERAGE('EmpTable'[Sick Leaves]) + AVERAGE('EmpTable'[Unpaid Leaves])

##🔗 How to View

Download the .pbix file.

Open in Power BI Desktop
