# Hospital Emergency Room Operational Analytics & Dashboard

An end-to-end Excel analytical model designed to evaluate emergency room operational performance, patient throughput, wait times, and satisfaction metrics across multi-year data (2023–2024).

---

## 📌 Executive Summary

Emergency departments frequently face bottlenecking, unpredictable patient volumes, and service delays. This project transforms raw clinical visit logs into an interactive, visual decision-support tool. By modeling throughput dynamics, demographic distributions, and referral bottlenecks, this dashboard provides actionable insights to optimize ER staffing and patient admission workflows.

---

## 📊 Key Metrics Tracked

* **Total Patient Volume:** 9,216 recorded visits across the reporting period.
* **Average Wait Time:** ~35.26 minutes per patient across departments.
* **Patient Satisfaction Score:** 4.99 / 10 average rating.
* **Admission Conversion:** ~50.04% admitted vs. 49.96% discharged directly from ER.
* **On-Time Service Performance:** 59% of patients attended within target SLA window vs. 41% operational delay.

---

## 🔍 Key Findings & Operational Insights

* **Departmental Concentration:** The Emergency Unit absorbs the vast majority of volume (5,400+ visits), followed by General Practice (1,840 visits) and Orthopedics (995 visits).
* **Demographic Breakdown:** Patient volume is evenly distributed across age brackets (0–69) with a sharp drop-off only in the 70–79 age group. Gender ratio is nearly equal (51% Male, 49% Female).
* **Throughput Delays:** Over 40% of patients experience delays relative to standard triage response windows, driving a clear correlation with lower patient satisfaction scores.

---

## ⚙️ Dashboard & Workbook Structure

The workbook contains structured reporting tabs and dedicated trend analysis sheets:

1. **`Hospital Emergency Room Data`**: Cleaned base dataset tracking patient IDs, demographics, referral departments, admission status, wait times, and satisfaction scores.
   <a href="https://github.com/Zero4247/Excel-Dashboards/blob/main/Hospital%20Patient/Data%20after%20cleaning.png">
   <img src="Data after cleaning.png"></a>
3. **`DASHBOARD`**: Executive view equipped with dynamic KPI cards, year/month slicers, admission status bars, and department breakdown charts.
   <a href="https://github.com/Zero4247/Excel-Dashboards/blob/main/Hospital%20Patient/Hospital%20Dashboard.png">
   <img src="Hospital Dashboard.png"></a>
5. **`Daily Emergency Room Attendance`**: Detailed timeline analysis tracking daily visit fluctuations throughout the year.
    <a href="https://github.com/Zero4247/Excel-Dashboards/blob/main/Hospital%20Patient/Hospital%20Dashboard.png">
   <img src="KPI(Daily attendance).png"></a>
7. **`AVERAGE WAIT TIME CHART`**: Dedicated trend sheet isolating daily wait times to highlight peak operational congestion.
    <a href="https://github.com/Zero4247/Excel-Dashboards/blob/main/Hospital%20Patient/Hospital%20Dashboard.png">
   <img src="KPI(Avg. wait time).png"></a>
9. **`AVERAGE PATIENT SATISFACTION SCORE`**: Detailed time-series tracking of patient feedback ratings.
     <a href="https://github.com/Zero4247/Excel-Dashboards/blob/main/Hospital%20Patient/KPI(Avg.%20Patient%20satisfaction%20score).png">
   <img src="KPI(Avg. Patient satisfaction score).png"></a>

---

## 🛠️ Tools & Technical Features

* **Application:** Microsoft Excel
* **Data Modeling & Calculations:** Excel Formulas (`SUMIFS`, `AVERAGEIFS`, `COUNTIFS`, Date/Time functions)
* **Visualization:** Custom Combo Charts, Donut Charts, Horizontal Bar Charts, Area/Line Trendlines
* **Interactivity:** Dynamic Slicers (Year/Month filtering) and cross-sheet navigation links


