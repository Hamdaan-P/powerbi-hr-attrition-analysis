HR Attrition Analysis Dashboard (Power BI)
Project Overview
This project utilizes human resources data to analyze and visualize the factors contributing to employee turnover (attrition). The goal is to provide data-driven insights to help the HR department develop targeted retention strategies, focusing on the most at-risk employee segments.

Dashboard Preview:

Technologies & Skills Demonstrated
Power BI Desktop (DAX/Power Query): Used for data cleaning, modeling, measure creation (KPIs), and visualization design.

Data Modeling (DAX): Creation of calculated columns (Attrition Value, Age Group, Income Group) and complex measures (Attrition Rate).

Data Visualization: Designing a cohesive, professional dark-themed dashboard using effective chart types (KPI Cards, Donut Charts, Stacked Bar Charts) and interactive Slicers.

Analytical Thinking: Identifying key drivers of attrition based on demographic and job-related factors.

Data Source
The analysis is based on the IBM HR Analytics Employee Attrition & Performance dataset, a publicly available dataset often used for educational and portfolio purposes.

Source File: WA_Fn-UseC_-HR-Employee-Attrition.csv (included in this repository)

Total Records: 1,470 employees

Key Performance Indicators (KPIs)
KPI	Value	Insight
Total Employees	1,470	The size of the dataset analyzed.
Total Attrition	237	The total number of employees who left the company.
Overall Attrition Rate	16.12%	This is the target metric for future reduction efforts.

Export to Sheets
Data-Driven Insights & Findings
The analysis revealed several critical areas where attrition is concentrated, providing clear priorities for retention efforts:

Income is the Primary Driver: Attrition is overwhelmingly highest in the "Under $5K" Income Group. This strongly suggests that low base pay is the most significant factor driving early turnover.

Concentration by Department: The Research & Development department accounts for the highest raw number of leavers, requiring a specific review of internal working conditions or salary competitiveness within that sector.

Job Role Risk: The Laboratory Technician job role shows the highest number of raw departures, indicating that roles with lower pay or high stress might be contributing to a concentrated attrition problem.

Demographic Vulnerability: The highest attrition risk is concentrated among Males in the 25-34 Age Group. Retention strategies should be specifically targeted at this demographic to mitigate future losses.

Next Steps
Root Cause Analysis: Further analysis could use the slicers to cross-reference the high-risk groups (e.g., Males 25-34 in R&D) with Job Satisfaction and Performance Ratings to identify specific retention gaps.

Time Series Analysis: If historical data were available, we would analyze attrition rate trends month-over-month to identify seasonal patterns or the impact of specific company events.

How to View the Dashboard
Download or clone this repository.

Install Power BI Desktop.

Open the file Attrition_Analysis_Dashboard.pbix in Power BI Desktop.

The visual dashboard will load, allowing for full interactivity using the slicers and visuals.


Thank you for reviewing my work!


## License
This project is licensed under the [MIT License](LICENSE).
