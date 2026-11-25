# excel-data-analysis-dashboard
Workforce and HR data analysis dashboard in Excel using PivotTables, interactive slicers, charts, and macros to explore people metrics.
📊 HR Analytics & Workforce Insights Dashboard

An interactive, macro-enabled Microsoft Excel dashboard built to explore employee demographics, department performance, regional distribution, and compensation insights across Indian office locations.

🔗 Quick Project Links

📂 Dataset & Macro Workbook: HR_Analytics_Dashboard_Dataset.xlsm

🖼️ Full Dashboard Preview: Screenshot (5).png

🌐 Repository: Destroyer-sword/excel-data-analysis-dashboard

📸 Dashboard Preview

🔍 Detailed Breakdown of the Dashboard (As Shown Above)

This dashboard is engineered for self-service workforce exploration using dynamic filtering, segmented PivotTables, macro-linked controls, and multi-chart visual storytelling:

1. Interactive Top Slicers (Multi-Dimensional Filtering)

Department Slicer (Top Row): Features 7 interactive buttons (Customer Support, Engineering, Finance, Human Resources, Marketing, Operations, and Sales). In the preview above, Sales is actively selected.

Location / City Slicer (Second Row): Filters employee records across 5 major Indian hubs (Bengaluru, Delhi NCR, Hyderabad, Kolkata, and Mumbai). In the preview above, Bengaluru is selected, dynamically updating all tables and charts below for Sales employees in Bengaluru.

2. Macro-Enabled View Controls (Dashboard 1 – Dashboard 4)

Positioned directly above each PivotTable are custom callout headers with interactive checkboxes (Dashboard 1, Dashboard 2, Dashboard 3, and Dashboard 4) powered by VBA (vbaProject.bin) to toggle and manage individual dashboard panels cleanly.

3. Segmented PivotTables (Employee-Level Metrics)

Four distinct PivotTables break down the filtered workforce into specific cohorts:

Dashboard 1 (Sum of Age): Displays age metrics for a 5-employee cohort (Aarav Chatterjee, Aditya Nair, Meera Joshi, Rahul Nair, Vikram Sharma) with a Grand Total of 235.

Dashboard 2 (Sum of Age): Tracks a younger 5-employee cohort (Divya Malhotra, Priya Bose, Rohan Sharma, Sneha Kumar, Vikram Ghosh) with a Grand Total of 118.

Dashboard 3 (Sum of Annual_Salary): Highlights higher compensation earners in INR (₹), led by Nikhil Ghosh (₹ 1,96,400.0) down to Divya Kumar (₹ 1,22,000.0), totaling ₹ 6,94,400.0.

Dashboard 4 (Sum of Annual_Salary): Tracks mid-tier compensation earners in INR (₹), led by Ananya Mukherjee (₹ 63,500.0) down to Riya Chatterjee (₹ 58,800.0), totaling ₹ 3,06,700.0.

4. Visual Analytics (Bottom Chart Suite)

Horizontal Bar Chart (Bottom Left): Compares employee ages from Dashboard 1, visually emphasizing age spread across the team (ranging from 42 to 54).

Pie Chart (Bottom Center): Illustrates percentage compensation share among the top earners in Dashboard 3, showing Nikhil Ghosh holding the largest share at 28%, while the remaining four employees each represent 18%.

Line Chart with Markers (Bottom Right): Plots the salary progression curve from Dashboard 4 (₹ 63,500.0 down to ₹ 58,800.0), making compensation drop-offs easy to spot at a glance.

🛠️ What I Built & Learned in This Project

Data Preparation & Structuring: Cleaned and structured raw employee records (Employee Name, Department, City/Location, Age, and Annual_Salary formatted in INR ₹).

PivotTable Architecture: Built 4 connected PivotTables to segment workforce cohorts by age and salary without duplicating raw data.

Interactive Slicer Styling: Customized horizontal button slicers with distinct active (gold/amber) and inactive (olive green) states for intuitive filtering.

Chart Design & Data Labels: Created complementary chart types (Bar, Pie, and Line) with clear percentage and currency labels tailored to each metric.

VBA & Form Controls: Embedded macro-enabled form checkboxes (vbaProject.bin) inside styled callout shapes to make the dashboard interactive.

🚀 How to Run This Workbook Locally

Download the Excel File:

Click on HR_Analytics_Dashboard_Dataset.xlsm in this repository and select Download raw file (or clone the repo using git clone https://github.com/Destroyer-sword/excel-data-analysis-dashboard.git).

Open in Microsoft Excel Desktop:

Open the .xlsm file in Microsoft Excel (Desktop app is required so Slicers and VBA macros work properly).

Enable Macros:

Click Enable Editing and Enable Content on the yellow security bar at the top of Excel.

Interact with the Dashboard:

Click any Department or City button on the top slicers to watch all 4 PivotTables and 3 charts update automatically!

📁 Repository Contents

File Name

Description

HR_Analytics_Dashboard_Dataset.xlsm

Main macro-enabled Excel workbook containing the dataset, 4 PivotTables, 2 Slicers, 3 Charts, and VBA code

Screenshot (5).png

Full-screen preview of the interactive dashboard filtered by Sales & Bengaluru

README.md

Complete project documentation and visual walkthrough

🔒 Data Disclaimer

All employee names, ages, and salary figures in this dataset are synthetic/sample records created solely for learning Excel data analysis and portfolio demonstration.