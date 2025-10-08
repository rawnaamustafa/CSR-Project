# CSR-Project

## Overview
This project focuses on analyzing **CRS** data, the dataset used isn't real and created for educational purpose.
The goal was to create a data model and making template using **Figma** then visualizing using **Power BI**.

## Data Modeling Steps

### Fact Tables 
- **Fact_Expenditures** – created from Expenditures table.

- **Fact_Impacts** – created from Impacts table.

- **Fact_Stakeholders** – created from Stakeholders table.

### Dimension Tables
- **Dim_Projects** – created from Projects table.

- **Dim_ExpenseCategory** – normalized from Expenditures.

- **Dim_ImpactMetric** – normalized from Impacts.

- **Dim_StakeholderType** – normalized from Stakeholders.

### Calendar Table
A Calendar dimension was generated using the CALENDAR() function, covering all dates between the earliest StartDate and the latest EndDate, enabling time-based analysis.

<img width="940" height="771" alt="image" src="https://github.com/user-attachments/assets/7d696a85-062e-4be6-ae55-04041ebe42c1" />

## Key measures and KPIs
- No. of Active Projects
- Average Project Duration (Days)
- Average Stakeholder Satisfaction Rate
- Budget Utilization = Total Expenses / Total Budget
- Impact per Dollar = Total Impact Value / Total Amount
- Projects Within Budget = (Projects with Expenses ≤ Budget) / Total Projects
- Satisfied Stakeholders % = Stakeholders with Rating > 3
- Total Budget by Category
- Stakeholder Type Distribution
- Utilization & Impact by Region

## Tools Used
- Figma (Making a mockup dashboard)
- Power Query (Data Transformation)
- Power BI (Data Modeling & Visualization)
- DAX (Measures Calculation)

## Final Dashboards
<img width="923" height="820" alt="dashboard1" src="https://github.com/user-attachments/assets/14c84270-88c4-4248-97a4-a2216145fd0a" />
<img width="917" height="602" alt="dashboard2" src="https://github.com/user-attachments/assets/00779a68-3e32-42e3-801f-557357c3bb6a" />


