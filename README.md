# 🏥 Riverside General Hospital — Clinical & Operations Dashboard

This project presents a dynamic healthcare analytics dashboard built in Power BI for **Riverside General Hospital**, offering a comprehensive overview of patient flow and operational performance. The dashboard highlights key data such as admissions and discharges, average length of stay, readmission rates, ER wait times, bed occupancy, and service-line performance — empowering hospital leaders to make strategic, data-informed decisions that improve outcomes and efficiency.

---

## 🧠 Key Business Questions

1. What is the total patient volume and how is it distributed by department/service line?  
2. What are the trends in **admissions**, **discharges**, and **average length of stay (ALOS)** over time?  
3. What is the **30-day readmission rate** and which diagnosis groups contribute most?  
4. How are **ER arrivals**, **wait times**, and **left-without-being-seen (LWBS)** trending?  
5. What is the current **bed occupancy** and **capacity utilization** across units?  
6. How do **payer mix** and **discharge disposition** influence operational performance?  
7. Which actionable levers (throughput, staffing, discharge timing) can reduce bottlenecks and improve quality metrics?

---

## 📊 Dashboard Preview

![Riverside General Hospital Dashboard](Riverside%20Hospital.png)

---

## 📊 Tools Used

- **Power BI**  
- **Data Modeling with DAX Measures**  
- **KPI Cards for Volume, ALOS, Readmissions, and Occupancy**  
- **Line & Area Charts for Trend Analysis**  
- **Bar/Column Charts for Department & Diagnosis Group Performance**  
- **Donut/Pie for Payer Mix & Discharge Disposition**  
- **Slicers for Date Range, Department, Payer, and Admission Type**  
- **Tooltip Pages & Drillthrough for Patient Pathway Details**  
- **Professional layout and healthcare UI/UX design principles**

---

## 📌 Key Insights

- **[Total Patients]** across the selected period with **[ALOS] days** average length of stay.  
- **Readmission rate:** **[Readmission %]**, concentrated in **[Top Diagnosis Groups]**.  
- **ER performance:** median wait time **[ER Wait (min)]** with **[LWBS %]** left without being seen.  
- **Bed utilization:** average occupancy **[Occupancy %]**, with peak load in **[Peak Units]** during **[Peak Hours/Days]**.  
- **Payer mix:** **[Top Payer Group]** represents **[Payer %]**, influencing reimbursement and throughput planning.  
- **Discharge efficiency:** **[On-time Discharge %]** indicates opportunities to reduce length of stay and free capacity earlier in the day.  
- Dashboard supports targeted actions: streamline ER triage, expedite diagnostics, optimize staffing by census patterns, and improve discharge coordination.

---

## 📂 Dataset Overview

The dataset used in this dashboard includes:

- Encounter ID, patient (de-identified) ID, admission & discharge timestamps  
- Admission type (Emergency, Inpatient, Elective), department/service line  
- Diagnosis group categories (e.g., DRG/ICD groupings)  
- Length of stay (days/hours) and 30-day readmission flag  
- ER arrival mode, triage level, door-to-provider time, wait time, LWBS indicator  
- Bed capacity, unit, and occupancy metrics  
- Payer group/insurance category and discharge disposition

> **Source:** Simulated, de-identified hospital operations dataset for analytics training and visualization purposes.
