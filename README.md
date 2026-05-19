# Healthcare Power BI Projects

A collection of Power BI reports built on real healthcare datasets, covering patient analytics, operational performance, and clinical insights.

---

## 01 — Patient Analytics

**Dataset:** Hospital Emergency Department visits (9,216 patients, 2019–2020)

### Report Pages

#### Page 1 — Executive Summary
High-level KPIs and trends for hospital leadership.

![Executive Summary](01-Patient-Analytics/screenshots/Executive%20Summary.png)

| Visual | Description |
|---|---|
| KPI Card | Total Patients |
| KPI Card | Average Wait Time (mins) |
| KPI Card | Average Satisfaction Score |
| KPI Card | % Admitted |
| Line Chart | Patient visits over time |
| Donut Chart | Admitted vs Not Admitted |

#### Page 2 — Patient Demographics
Breakdown of the patient population by personal characteristics.

![Patient Demographics](01-Patient-Analytics/screenshots/patient%20demographics.png)

| Visual | Description |
|---|---|
| Bar Chart | Patients by Race |
| Bar Chart | Patients by Age |
| Donut Chart | Patients by Gender |
| Bar Chart | Average Wait Time by Department |

#### Page 3 — Operations & Performance
Operational metrics to identify bottlenecks and performance gaps.

![Operations & Performance](01-Patient-Analytics/screenshots/operation%20%26%20Performance.png)

| Visual | Description |
|---|---|
| Bar Chart | Average Wait Time by Department |
| Bar Chart | Average Satisfaction Score by Department |
| Column Chart | Patients by Visit Shift (AM / PM) |
| Bar Chart | Average Wait Time by Visit Shift |

---

### DAX Measures

| Measure | Description |
|---|---|
| `Total Patients` | Count of all patient visits |
| `Avg Wait Time` | Average wait time in minutes |
| `Avg Satisfaction Score` | Average score (excludes nulls — 73% of patients had no score) |
| `% Admitted` | Percentage of patients who were admitted |
| `Patients Rated` | Count of patients who submitted a satisfaction score |
| `Avg Patient Age` | Average age across all patients |

---

### Key Findings

- **9,216** total patient visits recorded
- **50%** of patients were admitted
- Average wait time: **35.3 minutes**
- Average satisfaction score: **5.0 / 10** (based on 2,517 rated patients)
- **73%** of patients did not submit a satisfaction score
- Average patient age: **39.9 years**

---

### Tools & Theme

- **Tool:** Power BI Desktop (PBIP format)
- **Theme:** Custom Dark Navy & Teal
- **Slicers:** Date range, Patient Gender, Department Referral

---

## Projects Roadmap

| # | Project | Status |
|---|---|---|
| 01 | Patient Analytics | Done |
| 02 | Hospital Finance | Coming soon |
| 03 | Clinical Operations | Coming soon |
| 04 | Staff Performance | Coming soon |
| 05 | Equipment Utilization | Coming soon |
