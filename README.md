# 📖 Project Overview

This project showcases the end-to-end HR Analytics process using Microsoft Excel. The objective was to transform a raw Human Resources dataset into an interactive dashboard that provides meaningful insights for workforce management and strategic decision-making.

The project involved data cleaning, data transformation, column enrichment, pivot table analysis, and dashboard development. The final dashboard enables HR professionals to monitor key workforce metrics through interactive visualizations and slicers.


# 🎯 Business Problem

Managing employee data manually can make it difficult for HR professionals to identify workforce trends and make timely, data-driven decisions.

This project was designed to answer the following business questions:

- How many employees are currently in the organization?
- Which department has the highest number of employees?
- What is the average salary across the workforce?
- How is salary distributed across departments?
- What is the employee attrition rate?
- How are employees performing based on performance ratings?
- How can HR managers monitor workforce performance using an interactive dashboard?


# 📂 Dataset Information

The HR dataset contains employee records including:

- Employee ID
- Employee Name
- Gender
- Age
- Department
- Hire Date
- Salary
- Performance Rating
- Years of service
- Attrition rate
- Other employee-related information


# 🧹 Data Cleaning

Before performing any analysis, the raw dataset was cleaned to improve data quality and ensure reliable results.

The following cleaning processes were carried out:

### ✔ Missing Values

The raw dataset contained missing values in some records. These were identified and appropriately handled to improve data completeness.

### ✔ Duplicate Records

Duplicate employee records were identified and removed to maintain data accuracy.

### ✔ Hire Date Standardization

The **Hire Date** column contained inconsistent date formats. All dates were converted into a uniform format to ensure consistency during analysis and visualization.

### ✔ Text Cleaning

Several Excel functions were used to standardize text values across the dataset.

Functions used include:

- `TRIM()`
- `CLEAN()`
- `PROPER()`
- `UPPER()`

### ✔ Data Type Validation

Numeric, currency, percentage, and date fields were validated and formatted appropriately to support accurate calculations.

### ✔ Category Standardization

Categorical fields such as Department, Gender, Attrition Status, and Performance Ratings were standardized to eliminate inconsistencies.

# ✨ Column Enrichment

To improve analysis and dashboard reporting, additional calculated fields were created from the existing dataset.

These included:

- Performance Categories
- Employee Tenure Classification
- KPI calculations used for Pivot Tables and dashboard metrics

The enriched columns simplified reporting and enhanced dashboard interactivity.

# 📊 Data Analysis

After cleaning and transforming the dataset, Pivot Tables were created to summarize and analyze key HR metrics.

The analysis focused on:

- Total Employee
- Department 
- Salary Analysis
- Average Salary
- Performance score
- Attrition Analysis
- Years of Analysis

These summaries served as the foundation for building the interactive dashboard.

# 📈 Dashboard Development

An interactive HR dashboard was created in Microsoft Excel to provide a clear overview of key workforce metrics.

### Dashboard KPIs

- Total Employees
- Average Salary
- Employee Attrition Rate
- Average Performance Rating

### Dashboard Visualizations

- Department Distribution
- Salary Distribution
- Performance Rating Analysis
- Employee Attrition Analysis
- Years at Company Analysis

### Interactive Features

The dashboard includes slicers that allow users to dynamically filter data by:

- Department
- Gender
- Attrition Status

This enables users to explore workforce metrics efficiently and gain insights from different perspectives.


# 📌 Key Insights

Analysis of the HR dataset revealed several important findings:

### 1. Department Workforce Distribution

Some departments have significantly more employees than others, highlighting differences in workforce allocation across the organization.

### 2. Salary Distribution

Salary varies across departments, providing valuable information for compensation planning and budget allocation.

### 3. Employee Performance

Performance rating analysis helps identify high-performing employees while highlighting areas where additional training and development may be required.

### 4. Employee Attrition

Attrition analysis provides visibility into employee turnover trends, enabling HR teams to investigate underlying causes and improve retention strategies.

### 5. Workforce Monitoring

The interactive dashboard allows HR managers to monitor workforce performance quickly and make informed business decisions using real-time metrics.


# 💡 Recommendations

Based on the analysis, the following recommendations are proposed:

- Investigate departments with higher employee attrition to identify retention opportunities.
- Conduct periodic salary reviews to ensure equitable and competitive compensation.
- Strengthen employee performance management through regular appraisals and targeted development programs.
- Standardize future data entry procedures, especially for date fields, to improve data quality.
- Address missing values promptly to maintain accurate reporting.
- Continuously update the dashboard with new employee data to support ongoing HR decision-making.

# ⚠ Challenges Encountered

Several challenges were identified during the project:

- Missing values within the raw dataset.
- Inconsistent formatting of the Hire Date column.
- Duplicate employee records.
- Inconsistent text formatting across categorical fields.

# ✅ Resolution

The identified challenges were resolved through a structured data preparation process.

- Missing values were identified and appropriately handled.
- Duplicate records were removed.
- Hire Date values were standardized into a consistent date format.
- Text inconsistencies were corrected using Excel functions such as **TRIM(), CLEAN(), PROPER(), and UPPER()**.
- Data validation checks were performed before building Pivot Tables and the final dashboard.


# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Cleaning and preparing raw datasets for analysis.
- Transforming HR data into actionable insights.
- Building interactive Excel dashboards.
- Creating business-focused visualizations.
- Presenting data to support strategic decision-making.


T
