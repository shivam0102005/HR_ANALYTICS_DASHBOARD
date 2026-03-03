# 📊 HR Attrition Analysis Dashboard (Power BI)

## 🔍 Project Overview

This project is an interactive **HR Attrition Dashboard** built using **Power BI** to analyze employee attrition patterns and identify key factors affecting employee turnover.

The dashboard provides department-wise, age-wise, salary-wise, and education-wise attrition insights to help HR teams make data-driven decisions.

---

## 🎯 Business Objective

Employee attrition impacts productivity and increases hiring costs.
The objective of this project is to:

* Calculate overall attrition rate
* Identify high-risk age groups
* Analyze department-wise attrition
* Understand salary band impact on attrition
* Explore education background trends

---

## 📈 Key Insights

* 👥 Total Employees: 450
* ❌ Total Attrition: 93
* 📉 Attrition Rate: 20.7%
* 👤 Highest Attrition Age Group: 26–35
* 💼 Highest Attrition Department: Sales
* 💰 Majority Attrition in Salary Band: Up to 5K

---

## 🛠 Tools & Technologies Used

* Power BI
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Cleaning & Transformation
* Interactive Visualizations

---

## 📊 Dashboard Features

* KPI Cards (Total Employees, Attrition Count, Attrition Rate)
* Department Filter (HR, R&D, Sales)
* Attrition by Age Group
* Attrition by Education
* Attrition by Salary Band
* Job Role-wise Attrition
* Gender-based Attrition Distribution
* Interactive Filtering & Cross-Highlighting

---

## 🧮 DAX Calculations Used

### ✔ Attrition Count

```DAX
Attrition Count = 
CALCULATE(COUNT(Employee[Attrition]), Employee[Attrition] = "Yes")
```

### ✔ Attrition Rate

```DAX
Attrition Rate = 
DIVIDE(
    [Attrition Count],
    COUNT(Employee[EmployeeID])
)
```

---

## 📷 Dashboard Preview

(Add your dashboard screenshot here)

```markdown
<img width="1907" height="1008" alt="image" src="https://github.com/user-attachments/assets/bd7240c0-2af6-4537-92d1-bfcf3b3c737f" />

```

---

## 📁 Project Structure

```
HR-Attrition-Dashboard/
│
├── HR_Attrition_Dashboard.pbix
├── dataset.csv
├── screenshots/
│   └── dashboard.png
└── README.md
```

---

## 🚀 How to Use

1. Download the `.pbix` file.
2. Open in Power BI Desktop.
3. Interact with department filters and visuals.
4. Explore insights dynamically.

---

## 📌 Skills Demonstrated

* Data Analysis
* Business Intelligence Reporting
* Data Visualization
* DAX Calculations
* Dashboard Design
* Analytical Thinking

---



⭐ If you found this project useful, feel free to give it a star!
