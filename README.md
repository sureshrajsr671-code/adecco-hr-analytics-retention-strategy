# Adecco India: Data-Driven Retention Strategy & HR Analytics

Analyzing Employee Attrition & Enhancing Engagement for Junior Staff at Adecco India.

---

## 📌 Executive Summary & Problem Diagnostic
Adecco India ke **4,410 employee records** ka empirical data analysis kiya gaya hai taaki high-risk departments aur entry-level roles me badhte turnover ko diagnose karke retention safeguard kiya ja sake[cite: 10].

### Key Performance Metrics:
- **Total Headcount Analyzed:** 4,410 staff records[cite: 10]
- **Overall Company Turnover:** 16.1% (711 exits across the organization)[cite: 10]
- **Junior Staff Attrition Rate:** **24.8%** (Job Level 1 & age < 30 staff)[cite: 10]
- **Turnover Disruption:** Localized junior attrition software sprint delivery ko disrupt karti hai aur recruitment & onboarding costs ko escalate karti hai[cite: 10].

---

## 📊 Study Dataset & Analytics Architecture
- **Integrated Data Architecture:** Unified demographic profiles, job survey responses, manager feedback ratings, aur daily time-logs across 4,410 employees[cite: 10].
- **Departmental Coverage:** Engineering (Tech / R&D), Sales, Marketing, HR, aur Customer Support[cite: 10].
- **Time-Log Analytics:** In-time aur out-time attendance logs se calculated net daily work hours, jisse overtime fatigue quantify ki gayi[cite: 10].

---

## 🔍 Primary Drivers of Turnover & Bottlenecks

### 1. Overtime & Fatigue Burnout (31.2% Attrition)
- Daily working hours > 8.5 hours wale employees me **31.2% attrition** darj hui (standard hours walo ke **11.4%** ke mukable)[cite: 10].
- Tech developers sprint crunches me average **8.6 hours/day** log karte hain bina mandatory recovery days ke[cite: 10].

### 2. Level 1 Growth Plateau & Compensation Stagnation
- **Promotion Delays:** Job Level 1 me ≥ 2 saal bitane wale junior staff me **29.1% attrition** dekhi gayi[cite: 10].
- **Low Salary Hikes:** Sub-13% annual hike pane wale junior employees **22.5%** rate par exit karte hain[cite: 10].

### 3. Manager Relationship Friction (32.8% Attrition)
- Naye direct manager ke sath shuruati **12 months** me attrition **32.8%** tak pahunch jati hai, jo tenure > 3 years hone par ghat kar **11.2%** reh jati hai[cite: 10].

### 4. Commute Stress & Client Travel
- Frequent client travel karne wale roles me turnover **24.9%** hai (non-traveling roles ke baseline **8.0%** ke mukable)[cite: 10].
- Low Environment Satisfaction (Score = 1) pane wale staff me **25.4% attrition** darj hui[cite: 10].

---

## 📈 Quantitative Risk Factors & Department Matrix

### Department Attrition Breakdown:
| Department Division | Attrition Rate | Primary Risk Driver | Risk Level |
| :--- | :--- | :--- | :--- |
| **Human Resources** | 23.1% | Low Environment Satisfaction & Comp Hike | Critical |
| **Junior Sales Staff** | 21.4% | Frequent Travel (24.9%) & Incentive Gaps | Critical |
| **Junior Tech / R&D** | 17.8% | Sprint Crunch Overtime (>8.5 hrs/day) | High |
| **Customer Support** | 14.2% | Repetitive tasks & Level 1 stagnation | Moderate |

### Cohort Risk Factors Comparison:
| Demographic / Operational Metric | High-Risk Cohort | Attrition Rate | Risk Priority |
| :--- | :--- | :--- | :--- |
| **Marital Status & Age** | Single, Age < 30 Years | 34.2% | Critical |
| **Work-Life Balance** | Rating = 1 (Poor Balance) | 33.1% | Critical |
| **Daily Work Hours** | > 8.5 Hours per Day (Overtime) | 31.2% | Critical |
| **Manager Relationship** | ≤ 1 Year with Direct Manager | 32.8% | High |
| **Role Progression** | ≥ 2 Years in Job Level 1 | 29.1% | High |
| **Work Environment** | Environment Rating = 1 | 25.4% | High |
| **Client Travel** | Frequent Travel | 24.9% | High |
| **Compensation Hike** | < 13% Annual Salary Hike | 22.5% | Medium |

---

## 🛠️ Strategic Action Plan & Core Pillars

- **Q1 - Workload Caps (Burnout Control):** 45-hour weekly overtime alarms implement karna aur sprint release ke baad mandatory rest days ensure karna[cite: 10].
- **Q2 - Career Tracks (Level 1 Growth):** Level 1 se Level 2 promotion ke liye transparent 18-month career progression framework establish karna[cite: 10].
- **Q3 - Mentorship & Manager Alignment:** 30-60-90 day skip-level reviews mandate karna aur managers ke performance KPIs me team retention score link karna[cite: 10].
- **Q4 - Hybrid Flexibility (Commute Relief):** 10 km se zyada daily commute wale employees ke liye 2-3 weekly remote hybrid days offer karna[cite: 10].

---

## 📂 Repository Contents
- `/data`: 4,410 employee records dataset.
- `/working_files`: `Adecco_HR_Analytics_Working_File.xlsx` with complete KPI sheets, risk matrix, cohort calculations, and embedded charts.
- `/screenshots`: `adecco_hr_dashboard_screenshot.png` dashboard preview.
- `/presentation`: Complete executive slide deck (`Adecco HR Analytics Case Study.pptx`)[cite: 10, 11].
