# 🏥 ClinicalPulse Analytics

An interactive hospital admissions analytics dashboard built with **Power BI**, analysing admissions, patient outcomes, length of stay, and discharge performance across multiple hospitals and wards between **2020 and 2024**.

---

## 📊 Live Dashboard

👉 **[View the Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGRlMWI3ZmQtM2IzOC00N2MyLTliNTYtZTE0NTUyYzBkNzQxIiwidCI6IjA3M2U1ODhkLTI4NmMtNDAwNS04ZmYwLWYyYWMzYzhlYTRkMyJ9)**

---

## 📁 Project Structure

```
ClinicalPulse-Analytics/
│
├── 02_Hospital_Admissions.xlsx           # Source dataset (3,000 admissions)
├── Hospital admissions.pbit              # Power BI template file
├── Hospital admissions.jpg               # Dashboard preview image
└── README.md
```

---

## 🗂️ Dataset Overview

**Source file:** `02_Hospital_Admissions.xlsx` — 3,000 hospital admission records covering 5 hospitals and 7 clinical wards (2020–2024).

| Column | Type | Description |
|---|---|---|
| Admission ID | Integer | Unique admission identifier |
| Admission Date | Date | Date of patient admission |
| Hospital | String | Hospital where the patient was admitted |
| Ward | String | Clinical ward |
| Admission Type | String | Emergency, Elective, or Referral |
| Length of Stay | Integer | Number of days admitted |
| Outcome | String | Recovered, Transferred, DAMA, or Deceased |
| Year | Integer | Admission year |

---

## 📈 Dashboard Features

### KPI Cards

- **Total Admissions** — 3,000
- **Average Length of Stay** — 15.1 days
- **Emergency Admissions** — 1,530
- **Mortality Rate** — 0.1%
- **Recovery Rate** — 74.5%

### Visuals

| Visual | Insight |
|---|---|
| Annual Admission Trend | Tracks yearly hospital admissions between 2020–2024 |
| Admissions by Hospital | Compares patient volume across all hospitals |
| Length of Stay Distribution | Groups admissions by duration of hospitalization |
| Admissions by Ward | Compares ward activity based on selected discharge outcome |
| Discharge Rate by Ward | Evaluates discharge performance across hospital wards |
| Admission Type Distribution | Shows Emergency, Elective, and Referral admissions |
| Discharge Outcomes | Visualizes recovery, transfer, DAMA, and mortality outcomes |

### Filters / Slicers

- **Year** — 2020–2024
- **Hospital**
- **Ward**
- **Admission Type**
- **Discharge Outcome** (Recovered, Transferred, DAMA, Deceased)

---

## 🔑 Key Insights

1. **Emergency admissions account for over half of all hospital admissions**, highlighting the demand for emergency healthcare services.
2. **Nearly three-quarters of admitted patients recovered successfully**, indicating a strong overall recovery rate.
3. **The average hospital stay is approximately 15 days**, with longer stays concentrated in the 15–21 day and 22+ day categories.
4. **Admission volumes remain relatively stable across the five-year period**, with only minor annual fluctuations.
5. **Hospital and ward comparisons help identify areas with higher patient volumes and varying discharge outcomes**, supporting operational planning and resource allocation.

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development and visualization |
| DAX | KPI calculations and measures |
| Power Query (M) | Data cleaning and transformation |
| Microsoft Excel | Source dataset |

---

## 🚀 How to Use

1. **Clone this repository**

```bash
https://github.com/Lawal-Jnr-Analyst/Hospital-Admissions.git
```

2. **Open the template in Power BI Desktop**

- Open `hospital admissions.pbit`
- When prompted, connect the template to `02_Hospital_Admissions.xlsx`

3. **Or explore the published dashboard online**

👉 **[Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOGRlMWI3ZmQtM2IzOC00N2MyLTliNTYtZTE0NTUyYzBkNzQxIiwidCI6IjA3M2U1ODhkLTI4NmMtNDAwNS04ZmYwLWYyYWMzYzhlYTRkMyJ9)**

---

## 📷 Preview

![Hospital Admissions Dashboard](https://github.com/Lawal-Jnr-Analyst/ClinicalPulse-Analytics/blob/main/ClinicalPulse_Analytics.jpg)

---

## 📄 Licence

This project was developed for **portfolio and educational purposes**. The dataset is a simulated hospital admissions dataset created for healthcare analytics and dashboard development.

---

## 👤 Author

**Lawal Jamiu**

**Data Analyst | Power BI · SQL · Python**

- 🔗 [LinkedIn](https://linkedin.com/in/lawal-jnr-analyst)
- 🐙 [Lawal-Jnr-Analyst](https://github.com/Lawal-Jnr-Analyst)
