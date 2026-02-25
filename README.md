Healthcare Analytics Dashboard


📌 Overview
The Healthcare Analytics Dashboard is an interactive data visualization project developed using Python and Streamlit.
This project transforms raw hospital data into meaningful insights through visual analytics, enabling better operational and strategic decision-making in healthcare management.
The dashboard focuses on analyzing patient trends, disease distribution, departmental performance, and surgery patterns using real-world data analysis techniques.

🎯 Problem Statement
Hospitals generate large amounts of patient data daily. However, raw tabular data makes it difficult for management to identify trends, peak loads, and critical performance indicators.
This project solves that problem by:
Converting raw healthcare datasets into clear visual insights
Identifying high-impact diseases and busiest departments
Tracking disease trends over time
Supporting data-driven resource planning

📊 Dashboard Modules
1️⃣ Overview Dashboard
Total Patients (KPI)
Total Departments
Total Surgeries
Total Revenue (if applicable)

2️⃣ Disease Intelligence
Top 10 Diagnoses (Bar Chart)
Disease Trend Over Time (Line Chart)
Monthly Admission Analysis

3️⃣ Department Analysis
Department-wise Patient Count
Workload Distribution
Comparative Analysis

4️⃣ Surgery Analysis
Most Performed Surgeries
Surgery Frequency Trends

📂 Dataset Information
The dataset consists of structured healthcare records including:
Patient ID
Age
Gender
Diagnosis
Department
Admission Date
Discharge Date
Surgery Type
Treatment Cost

Data Preprocessing Steps:
Removed duplicate records
Handled missing values using appropriate strategies
Converted date columns into datetime format
Aggregated data using groupby()
Created calculated metrics for trend analysis

🛠️ Technology Stack
Tool / Library
Purpose
Python
Programming Language
Pandas
Data Cleaning & Analysis
Matplotlib
Visualization
Seaborn
Advanced Visualization
Streamlit
Interactive Dashboard Development

📈 Key Insights Derived
Identified most frequent diseases treated
Determined busiest hospital departments
Observed seasonal disease patterns
Tracked monthly admission trends
Analyzed surgery volume patterns

These insights help in:
Resource allocation
Staff planning
Operational optimization
Strategic decision-making

💡 Business Impact
This dashboard enables hospital administrators to:
✔ Monitor performance in real-time
✔ Identify trends instantly
✔ Reduce manual reporting effort
✔ Make faster, data-backed decisions
