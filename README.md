# Riverside General Hospital — Clinical & Operations Dashboard

In this project, I developed a comprehensive healthcare analytics dashboard in Power BI for a simulated hospital, Riverside General Hospital. My objective was to transform clinical and operational data into an executive-level dashboard that supports hospital leadership in improving patient flow, quality outcomes, and operational efficiency.

I focused on analyzing admissions trends, average length of stay (ALOS), readmission rates, ER performance metrics, bed utilization, payer mix, and discharge patterns. Through structured data modeling and DAX-driven KPIs, I built an interactive dashboard designed to surface bottlenecks and identify opportunities to optimize throughput and care delivery.

---

## Project Objectives
In this analysis, I aimed to answer the following business questions:
1. What is the total patient volume and how is it distributed by department/service line?  
2. What are the trends in **admissions**, **discharges**, and **average length of stay (ALOS)** over time?  
3. What is the **30-day readmission rate** and which diagnosis groups contribute most?  
4. How are **ER arrivals**, **wait times**, and **left-without-being-seen (LWBS)** trending?  
5. What is the current **bed occupancy** and **capacity utilization** across units?  
6. How do **payer mix** and **discharge disposition** influence operational performance?  
7. Which actionable levers (throughput, staffing, discharge timing) can reduce bottlenecks and improve quality metrics?

---

##  Dashboard Preview

![Riverside General Hospital Dashboard](Riverside%20Dashboard.png)

---

## Tools & Technical Approach
In this project, I used:
- Power BI Desktop
- Structured data modeling across patient encounters, units, and payer data
- DAX measures to calculate KPIs such as:
- Average Length of Stay (ALOS)
- 30-day Readmission Rate
- Bed Occupancy %
- ER Median Wait Time
- Line and area charts for trend analysis
- Bar and column charts for department and diagnosis group performance
- Donut/Pie visuals for payer mix and discharge disposition
- Slicers for dynamic filtering (date range, department, admission type, payer)
- Drillthrough pages and tooltip detail for deeper patient pathway insights
- Healthcare-focused UI/UX layout to prioritize clarity and executive readability

I structured the dashboard to surface high-impact KPIs first, followed by operational breakdowns that support root-cause analysis.

---

## Key Insights / Results
Through this dashboard, I identified:
- Total patient volume across the selected period, with measurable trends in admissions and discharges.
- Variability in average length of stay by department, indicating opportunities for throughput optimization.
- Concentrated 30-day readmissions within specific diagnosis groups, highlighting quality improvement targets.
- ER performance bottlenecks during peak census periods, with elevated wait times and LWBS rates.
- High bed occupancy in select units during peak days, suggesting staffing and discharge coordination opportunities.
- Payer mix distribution influencing reimbursement dynamics and patient flow strategy.
- Discharge timing patterns that impact early bed availability and daily capacity turnover.

This analysis demonstrates how healthcare operational data can be leveraged to improve patient outcomes, reduce avoidable readmissions, optimize staffing, and increase capacity efficiency.

---

## What I Learned
Through this project, I strengthened my ability to:
- Build healthcare-focused dashboards with complex operational KPIs
- Write advanced DAX measures for clinical quality indicators
- Analyze patient flow and capacity utilization trends
- Translate healthcare metrics into actionable leadership insights
- Design dashboards that balance clinical relevance with operational strategy

Given my background in nursing, this project also deepened my understanding of how frontline clinical metrics translate into executive-level performance indicators.

---

## Challenges I Encountered
One challenge I faced was accurately calculating 30-day readmission rates while avoiding double counting across encounter records. I addressed this by structuring DAX measures carefully and validating time-based logic.

Another challenge involved modeling time-based trends (admissions vs. discharges) while ensuring correct date hierarchies and filtering behavior.

Additionally, presenting complex healthcare metrics in a clear, executive-friendly layout required thoughtful prioritization of KPIs and reduction of visual clutter.

---

## Dataset Overview
The dataset included:
- Encounter ID and de-identified patient ID
- Admission and discharge timestamps
- Admission type (Emergency, Inpatient, Elective)
- Department and service line
- Diagnosis group categories (DRG/ICD groupings)
- Length of stay and 30-day readmission flag
- ER metrics (triage level, door-to-provider time, wait time, LWBS indicator)
- Bed capacity and occupancy metrics by unit
- Payer group and discharge disposition






