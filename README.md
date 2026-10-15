# Adecco India: Data-Driven Retention Strategy and HR Analytics

Analyzing Employee Attrition and Enhancing Engagement for Junior Staff at Adecco India.

---

## Executive Summary and Diagnostics
A comprehensive empirical investigation across 4,410 staff records, highlighting key turnover drivers and actionable retention interventions for junior talent.

### Key Performance Benchmarks
- Total Headcount Analyzed: 4,410 employee records
- Overall Company Turnover: 16.1% (711 exits across the organization)
- Junior Staff Turnover Rate: 24.8% (Job Level 1 and staff under age 30)
- Operational Impact: Localized junior turnover disrupts software sprint delivery and increases replacement recruitment costs.

---

## Study Dataset and Methodology
- Merged Data Architecture: Unified demographic data, job survey results, manager feedback, and daily attendance logs across 4,410 employees.
- Multi-Department Scope: Evaluation across Engineering (Tech/R&D), Sales, Marketing, HR, and Customer Support divisions.
- Time-Log Analytics: Net working hours derived from daily in-time and out-time timestamps to accurately quantify overtime fatigue.

---

## Primary Drivers of Turnover

### 1. Overtime and Fatigue Burnout
- Employees averaging over 8.5 daily hours exhibit a 31.2% attrition rate, compared to 11.4% for those working standard hours.
- Junior developers average 8.6 daily working hours during sprint releases without compensatory recovery days.

### 2. Level 1 Career Growth Plateau
- Junior employees receiving low salary hikes (< 13%) leave at 22.5%.
- Staff spending 2 or more years in Job Level 1 without promotion show a 29.1% attrition rate due to role stagnation.

### 3. Manager Relationship and Commute Friction
- Attrition reaches 32.8% during the first 12 months under a direct manager, dropping to 11.2% once tenure exceeds 3 years.
- Frequent client travel triggers a 24.9% turnover rate, whereas non-traveling roles maintain an 8.0% baseline.

---

## Quantitative Risk Factors and Department Matrix

| Department Division | Attrition Rate | Primary Risk Factor | Risk Priority |
| :--- | :--- | :--- | :--- |
| Human Resources | 23.1% | Low Environment Satisfaction and Comp Hike | Critical |
| Junior Sales Staff | 21.4% | Frequent Travel (24.9%) and Incentive Gaps | Critical |
| Junior Tech / R&D | 17.8% | Sprint Crunch Overtime (>8.5 hrs/day) | High |
| Customer Support | 14.2% | Repetitive tasks and Level 1 stagnation | Moderate |

| Demographic / Operational Metric | High-Risk Cohort | Attrition Rate | Risk Level |
| :--- | :--- | :--- | :--- |
| Marital Status and Age | Single, Age < 30 Years | 34.2% | Critical |
| Work-Life Balance | Rating = 1 (Poor Balance) | 33.1% | Critical |
| Daily Work Hours | > 8.5 Hours per Day (Overtime) | 31.2% | Critical |
| Manager Relationship | <= 1 Year with Direct Manager | 32.8% | High |
| Role Progression | >= 2 Years in Job Level 1 | 29.1% | High |
| Work Environment | Environment Rating = 1 | 25.4% | High |

---

## Strategic Action Plan

- Q1 - Workload Caps: Institute 45-hour weekly overtime alarms and mandatory post-sprint rest days.
- Q2 - Career Tracks: Establish a transparent 18-month progression framework from Level 1 to Level 2.
- Q3 - Mentorship: Mandate structured 30-60-90 day skip-level reviews and manager alignment KPIs.
- Q4 - Hybrid Work: Offer 2-3 remote days for employees commuting over 10 km to reduce travel fatigue.

---

## Repository Structure
```text
├── data/
│   └── adecco_employee_attrition_dataset.csv
├── working_files/
│   └── Adecco_HR_Analytics_Working_File.xlsx
├── screenshots/
│   └── adecco_hr_dashboard_clean.png
├── presentation/
│   └── Adecco HR Analytics Case Study.pptx
└── README.md
