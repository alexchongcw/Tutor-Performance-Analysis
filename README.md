# 📊 Tutor Performance Analysis Dashboard

A full end-to-end Business Intelligence solution using Microsoft Fabric and Power BI to evaluate tutor and training program effectiveness. 
This dashboard enables decision-makers to explore Net Promoter Score (NPS), average ratings, and performance trends across tutors, intakes, and programs—powered by a live Google Sheets data source and a robust Lakehouse architecture.

---

## 🛠 Project Name Convention
**LH_PowerBI_TutorPerformanceDashboard202403**

---

## 🎯 Objectives
- Analyze tutor-level performance: total responses, average scores, and NPS indicators
- Evaluate training delivery across intakes and programs
- Visualize NPS breakdown: promoter, passive, and detractor counts with NPS percentages
- Enable drill-through to individual score and comment responses
- Compare performance across intake/program/tutor combinations
- Incorporate custom insights to support actionable strategy

---

## 🧠 Key Insights
- **Tutor A achieved the highest NPS (+60)** and maintained strong ratings across three cohorts
- **Training for Program Y improved significantly** between Intakes March and June, showing a 12% NPS gain
- **Detractor rates spiked** in a specific program, suggesting targeted intervention needed
- **Drill-through comments reveal students value interactive delivery and clarity**
- **NPS trends correlate with tutor consistency**, particularly in smaller learning groups

---

## 💡 Value-Added Analysis
- Time-based trend visuals: tutor rating vs. NPS progression
- Word cloud from qualitative comments to highlight recurring student feedback
- Conditional formatting to spotlight underperforming training sessions or tutors

---

## 📌 Features
- Cross-filtered views by intake, program, and tutor
- Fully interactive Power BI visuals and slicers
- Drill-through to row-level feedback and score distributions
- NPS scoring logic with customizable thresholds
- Power BI UX follows best practices for clarity and accessibility

---

## 🚀 Technologies Used
- **Google Sheets:** Live-connected as the dynamic weekly-updated data source  
- **Microsoft Fabric – Data Factory:** Data pipeline orchestration and transformation  
- **Lakehouse Storage:** Unified data layer for storing structured feedback data  
- **Microsoft Fabric Data Warehouse (DataGen2):** Data modeling and measure calculations  
- **Microsoft Fabric Notebooks:** Python-based transformations and exploratory insights  
- **Power BI Desktop:** Visualization, dashboard design, and report delivery  
- **GitHub:** Version control, documentation, and project sharing

---

## 🧪 NPS Scoring Logic
- **Promoters:** 9–10  
- **Passives:** 7–8  
- **Detractors:** 1–6  
- **NPS Formula:** (% Promoters - % Detractors)

---

> This project showcases a scalable BI solution—designed to surface impactful educational insights through structured pipelines, semantic modeling, and intuitive reporting.
