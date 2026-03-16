#👩‍💼 Employee Retention Analytics Dashboard (Tableau)
##📌 Project Overview

This project presents an end-to-end Employee Retention Analytics Dashboard built using Tableau on an HR workforce dataset. The dashboard provides insights into workforce distribution, recruitment effectiveness, employee performance, and engagement trends to support data-driven HR decision-making.

The objective of this project is to help organizations:

Understand employee attrition patterns

Evaluate recruitment channel effectiveness

Monitor employee performance and productivity

Analyze engagement and satisfaction levels

📑 Table of Contents

Business Problem

Dataset

Tools & Techniques

Project Structure

Data Cleaning & Preparation

Research Questions & Key Findings

Dashboard

How to Run This Project

Final Recommendations

Author

🚨 Business Problem

Organizations often face challenges related to employee attrition, workforce productivity, and recruitment effectiveness. High employee turnover increases hiring costs, reduces operational efficiency, and negatively impacts organizational knowledge retention.

HR departments need data-driven insights to:

Identify departments with high attrition

Evaluate recruitment sources producing successful hires

Monitor employee engagement and satisfaction

Analyze performance and absenteeism patterns

This project develops an interactive HR analytics dashboard using Tableau to help HR leaders make data-driven workforce decisions.

📊 Dataset

Dataset Name: HR Workforce Dataset
Format: CSV

The dataset includes the following HR attributes:

Employee demographics
Department & job position
Recruitment source
Salary
Performance score
Employee engagement survey
Employee satisfaction score
Absences
Tenure (years)
Attrition indicator
State

Dataset Size

311 Employees
36 Columns
🛠 Tools & Techniques

Tools used in this project:

Tableau – Interactive dashboard development

Python (Pandas, NumPy) – Data cleaning and preprocessing

Jupyter Notebook – Exploratory Data Analysis

Git & GitHub – Version control and project hosting

📁 Project Structure
Employee-Retention-Analytics/
│
├── dashboard/
│   └── employee_retention_dashboard.png
│
├── notebooks/
│   └── hr_data_exploration.ipynb
│
├── scripts/
│   └── data_preprocessing.py
│
├── dataset/
│   └── hr_dataset.csv
│
├── tableau_dashboard/
│   └── employee_retention_dashboard.twbx
│
├── README.md
└── HR_Analytics_Report.pdf
🧹 Data Cleaning & Preparation

The dataset was preprocessed to ensure accuracy and usability.

Key preprocessing steps included:

Removed duplicate employee records

Handled missing values in manager and termination columns

Standardized date formats

Created calculated columns including:

Employee Age

Tenure Years

Attrition Indicator

Removed redundant employee ID fields

Prepared dataset for Tableau visualization

🔎 Research Questions & Key Findings

This project answers 22 key HR analytics business questions.

👥 Workforce Analytics

What is the total number of employees in the organization?

What is the overall employee attrition rate?

How are employees distributed across departments?

What is the gender distribution of employees?

Which positions have the highest number of employees?

How are employees distributed geographically by state?

📈 Recruitment Analytics

Which recruitment sources hire the most employees?

Which recruitment channels produce the best-performing employees?

Which recruitment sources lead to the highest attrition?

Does diversity job fair recruitment influence retention?

Which recruitment sources result in longer employee tenure?

📊 Performance Analytics

What is the distribution of employee performance scores?

Which departments have the highest performance ratings?

Does salary influence employee performance?

Do employees with more absences perform worse?

Does employee tenure influence performance ratings?

Which positions have the highest-performing employees?

💡 Engagement Analytics

Does employee satisfaction influence attrition?

Does engagement score correlate with employee retention?

Do employees with low engagement scores show higher absenteeism?

Which departments have the lowest employee satisfaction levels?

Is employee engagement related to performance scores?

📌 Key Findings

The dataset shows an employee attrition rate of approximately 33%

The Production department represents the largest workforce share

Indeed and LinkedIn are the most effective recruitment channels

Employees with higher engagement scores show stronger performance outcomes

Increased absenteeism is associated with lower performance scores

These insights help HR teams identify retention risks and improve workforce management strategies.

📊 Dashboard

This project includes four interactive HR analytics dashboards.

👥 Workforce Analytics

Total Employees

Attrition Rate

Employees by Department

Employees by Position

Gender Distribution

Employee Distribution by State

📈 Recruitment Analytics

Recruitment Source Distribution

Recruitment Source vs Performance

Recruitment Source vs Attrition

Diversity Job Fair Impact

📊 Performance Analytics

Performance Score Distribution

Salary vs Performance

Absences vs Performance

Tenure vs Performance

Top Performing Positions

💡 Engagement Analytics

Satisfaction vs Attrition

Engagement vs Retention

Engagement vs Absences

Satisfaction by Department

Engagement vs Performance

▶️ How to Run This Project

Clone the repository:

git clone https://github.com/yourusername/employee-retention-analytics.git

Steps:

Open Tableau Desktop

Load dataset from

dataset/hr_dataset.csv

Open the Tableau workbook

employee_retention_dashboard.twbx

Refresh data and explore the dashboards

📈 Final Recommendations
Workforce Optimization

Monitor departments with higher attrition trends

Develop targeted employee retention strategies

Recruitment Strategy

Prioritize high-performing recruitment channels such as LinkedIn and Indeed

Performance Management

Track absenteeism trends impacting productivity

Employee Engagement

Improve employee engagement through workplace satisfaction initiatives

👩‍💻 Author

Supriya Kusuma
Aspiring Data Analyst | Tableau | Power BI | SQL | Python | HR Analytics

GitHub
https://github.com/Supriya2098

LinkedIn
https://linkedin.com/in/supriya-kusuma09

Email
supriyakusuma0905@gmail.com
