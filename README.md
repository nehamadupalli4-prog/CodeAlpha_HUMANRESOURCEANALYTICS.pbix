Human Resources Analytics Dashboard – Power BI
Overview

This project was developed as part of the CodeAlpha Power BI Internship. The Human Resources Analytics Dashboard provides insights into employee demographics, attrition trends, job satisfaction, performance ratings, and workforce forecasting. The dashboard helps HR teams make informed decisions related to employee retention, workforce planning, and organizational performance.

Objective

To create an interactive HR Analytics Dashboard that enables:

Employee attrition analysis
Workforce management
Employee satisfaction monitoring
Performance evaluation
Predictive workforce planning
Data-driven HR decision-making
Dataset

Dataset Used: IBM HR Analytics Employee Attrition Dataset

The dataset contains information related to:

Employee demographics
Job roles and departments
Attrition status
Performance ratings
Job satisfaction
Monthly income
Work experience
Education details
Work-life balance
Dashboard Features
Key Performance Indicators (KPIs)
Total Employees
Attrition Count
Attrition Rate (%)
Average Monthly Income
Average Job Satisfaction
Average Performance Rating
Employee Attrition Analysis
Attrition Distribution
Department-wise Attrition Analysis
Employee Turnover Insights
Employee Satisfaction Analysis
Job Satisfaction by Role
Employee Engagement Insights
Satisfaction Comparison Across Job Roles
Performance Analysis
Performance Rating by Department
Workforce Productivity Insights
Workforce Demographics
Gender Distribution
Employee Age Distribution
Department-wise Workforce Analysis
Predictive Analytics
Workforce Forecasting
Employee Trend Analysis
Future Workforce Planning Support
Interactive Filters
Gender
Department
Marital Status
Job Role
Tools & Technologies
Power BI Desktop
DAX (Data Analysis Expressions)
Data Modeling
HR Analytics
Data Visualization
Forecasting Analytics
DAX Measures Used
Attrition Count
Attrition Count =
CALCULATE(
COUNT(HR_Analytics[Attrition]),
HR_Analytics[Attrition] = "Yes"
)
Attrition Rate %
Attrition Rate % =
DIVIDE(
[Attrition Count],
COUNT(HR_Analytics[Attrition])
) * 100
Dashboard Insights
Identified employee attrition patterns across departments.
Analyzed employee satisfaction levels based on job roles.
Evaluated workforce performance using performance ratings.
Studied employee demographics including age and gender distribution.
Forecasted workforce trends to support future hiring and retention strategies.
Project Deliverables
Power BI Dashboard (.pbix)
Interactive HR Analytics Report
Workforce Forecasting Visualizations
Employee Attrition Analysis Dashboard
Learning Outcomes

Through this project, I gained hands-on experience in:

HR Data Analysis
Employee Attrition Analytics
Power BI Dashboard Development
DAX Measure Creation
Interactive Report Design
Workforce Forecasting
Business Intelligence Reporting
Dashboard Screenshots


Author

Neha Madupalli

Internship: CodeAlpha Power BI Internship

Repository Structure
CodeAlpha_HRAnalytics/
│
├── Human_Resources_Analytics.pbix
├── HR_Analytics.csv
├── README.md
├── screenshots/
│   ├── dashboard_overview.png
│   ├── attrition_analysis.png
│   ├── workforce_forecast.png
│   └── filters.png
