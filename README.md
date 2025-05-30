🏥 Hospital Patient Data Dashboard (Excel Project)
This Excel dashboard project analyzes hospital patient data to provide insights into patient satisfaction, length of stay, age distribution, and treatment costs.

📌 Objectives
Clean and prepare hospital patient data

Perform data transformation and categorization

Build pivot tables for analysis

Create an interactive Excel dashboard with slicers and charts

Share a professional, well-structured project on GitHub

🧹 Data Cleaning & Transformation
The original data was duplicated into a separate sheet to preserve the raw data. I performed the following cleaning and transformation steps:

✅ Removed duplicate rows

✅ Created an Age Label column using IF statements to group patients by age range

✅ Formatted the Treatment Cost column with comma separators (e.g., 100000 → 100,000)

✅ Renamed the Length of Stay column to show units clearly (e.g., 5 → 5 days)

Used the formula: =B2 & " " & IF(B2=1, "day", "days")

✅ Mapped the numerical Satisfaction values (2–5) to categories:

2 → Poor

3 → Okay

4 → Good

5 → Excellent

📊 Dashboard Features
The dashboard includes:

Bar chart showing satisfaction levels

Pie chart showing patient age group distribution

Slicer for gender and satisfaction level

KPIs for average length of stay and total treatment cost

Everything was built with Excel pivot tables and charts, then organized into a final dashboard sheet.

📁 Folder Structure

📂 data
   └── cleaned_hospital_data.xlsx

📂 dashboard
   └── hospital_analysis_dashboard.xlsx

📂 screenshots
   └── dashboard_preview.png

🔗 Tools Used
Microsoft Excel

Data cleaning

IF statements

Pivot Tables

Charts & Slicers

Dashboard design

📤 How to Use
Download the cleaned data file from the data folder.

Open the dashboard file in the dashboard folder to explore the visualizations.

 View a screenshot of the final dashboard in the screenshots folder.

