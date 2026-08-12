# Student-Performance-Academic-Analytics-Dashboard-Using-Excel
A dynamic, multi-subject student analytics system built in Excel to consolidate exam results, evaluate strengths and weaknesses, and benchmark individual student performance against cohort averages for study time, attendance, and GPA.

📌 Project Overview
Educational institutions often store academic results across isolated subject logs, making it difficult for advisors to evaluate a student's holistic performance. This project integrates multi-subject exam records with student demographic and behavioral data to build an interactive individual student scorecard. By typing a student's name into the primary dashboard, the report dynamically extracts exam scores, subject-level mastery, study habits, and attendance variances.

🛠️ Key Technical Features & Formulas
Multi-Sheet Data Integration: Normalized subject data across 6 core academic disciplines (Biology, Chemistry, Mathematics, Philosophy, Physics, Sociology) and merged demographic/behavioral metrics from Additional Details.

Dynamic Lookups (XLOOKUP): Automated retrieval of scores, evaluation indicators, weekly study hours, and absences without relying on legacy VLOOKUP limitations.

Cohort Variance Analysis (AVERAGE & Arithmetic Functions): Evaluates individual study time and attendance against class averages to highlight engagement risks.

Automated Score Aggregation (SUM): Automatically computes cumulative exam points across all evaluated subjects.

Subject Mastery Classification: Binary tagging (1 = Strength, 0 = Weakness) per subject to quickly target academic intervention.

<img width="930" height="607" alt="image" src="https://github.com/user-attachments/assets/e7ef42f8-6496-4d0d-a14d-f019f06c3411" />

## 📊 Dashboard Preview & Interactive Student Report

<img width="1344" height="618" alt="image" src="https://github.com/user-attachments/assets/089883a9-522f-4f0a-805f-174faea1ce16" />


💡 Key Business & Academic Insights
Study Hours vs. Performance Correlation: Students averaging above the cohort mean (~9.95 hrs/week) consistently show higher GPA metrics and fewer flagged subject weaknesses.

Attendance Impact: Class attendance averages ~14.62 absent days. Students exceeding 20 absent days display marked point drops across quantitative subjects like Mathematics and Physics.

Subject-Specific Bottlenecks: Cross-subject comparison reveals distinct mastery gaps in Chemistry and Physics, allowing academic counselors to assign targeted tutoring.

🚀 How to Use the Dashboard
Download Excel_project_File.xlsx from this repository.

Open the file in Microsoft Excel 2021 or Excel for Microsoft 365 (required for XLOOKUP support).

Navigate to the Report of Students sheet.

In cell E5, enter any valid student name (e.g., James Walker or Velma Clemons).

The report will instantly update all scores, strengths/weaknesses, study time metrics, and attendance comparisons.
