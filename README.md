# 📊 Educational Challenges — SAP Analytics Cloud Project

An end-to-end analytics project built on **SAP Analytics Cloud (SAC)** that explores the educational challenges affecting student performance, attendance, and dropout risk using a structured student dataset and an interactive story dashboard.

---

## 📌 Project Title
**"Educational Challenges You Aim to Address"**

## 👤 Author
- **Submitted by:** Meesala Triveni
- **Guide:** Mr. Raghavendra Rao
- **Track:** Analytics Track
- **Platform:** SAP Analytics Cloud (SAC)

---

## 📝 Overview

Educational institutions often struggle to identify at-risk students until it's too late to intervene. This project uses SAP Analytics Cloud to analyze a 100-record student dataset and uncover how factors such as **attendance, department, internet access, and family income** influence academic performance and dropout risk.

The full write-up — including methodology, dataset details, dashboard screenshots, insights, and recommendations — is available in the project report:

📄 **[Educational_Challenges_SAC_Project_Report.docx](./Educational_Challenges_SAC_Project_Report.docx)**

---

## 🎯 Objectives

- Analyze student attendance and marks across different departments
- Identify the distribution of dropout risk (High, Medium, Low) among students
- Study the impact of family income on student performance
- Build interactive dashboards in SAC for data-driven decision-making
- Help institutions identify at-risk students early for timely intervention

---

## 🗂️ Dataset

**Educational_Challenges_SAC_Dataset** — 100 rows, 8 columns

| Type | Columns |
|---|---|
| **Measures (2)** | Attendance (SUM), Marks (SUM) |
| **Dimensions (6)** | Student_ID, Gender, Department, Internet, Family Income, Dropout Risk |

---

## 🛠️ Tools & Technology

| Component | Details |
|---|---|
| Platform | SAP Analytics Cloud (SAC) |
| Modules Used | Datasets, Data Modeler, Stories (Dashboards) |
| Data Format | Structured tabular dataset (student records) |
| Chart Types | Bar Chart, Pie Chart, Donut Chart |

---

## 📈 Dashboard / Story

The SAC Story combines four visualizations into a single dashboard:

1. **Attendance per Department** (Bar Chart)
2. **Attendance per Dropout Risk** (Pie Chart)
3. **Marks per Department** (Bar Chart)
4. **Marks per Family Income** (Donut Chart)

Screenshots of the dataset preparation, home page, and final dashboard are included in [`/screenshots`](./screenshots) and embedded in the project report.

---

## 🔍 Key Insights

- **MECH** and **EEE** departments recorded the highest overall attendance.
- Dropout risk is fairly evenly distributed across High, Medium, and Low categories — no single group dominates.
- **EEE** and **ECE** show the strongest academic performance in total marks.
- Students from **low-income families** account for the largest share (40.04%) of recorded marks, highlighting the need for continued support.

## ✅ Recommendations

- Set up automated attendance-tracking dashboards with minimum-threshold alerts
- Introduce targeted academic support for lower-performing departments/income groups
- Proactively counsel and monitor students flagged as "High" dropout risk
- Prioritize financial aid/scholarships for low-income students
- Review SAC dashboards periodically (e.g., monthly) for up-to-date intervention decisions

---

## 📁 Repository Structure

```
├── Educational_Challenges_SAC_Project_Report.docx   # Full project report
├── screenshots/                                      # SAC platform screenshots
│   ├── home_page.png
│   ├── dataset_preparation.png
│   ├── dataset_saved.png
│   └── story_dashboard.png
└── README.md
```

---

## 📚 References

- [SAP Analytics Cloud Trial](https://www.sap.com/products/data-cloud/cloud-analytics/trial.html)
- SAP Analytics Cloud Help Documentation (in-app)
