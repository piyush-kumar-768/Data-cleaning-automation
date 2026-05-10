# 🧹 Data Cleaning & Reporting Automation

> Automated pipeline to detect, fix, and report data quality issues — missing values, duplicates, outliers, and inconsistencies.

🔗 **Live Demo:** [https://piyush-kumar-768.github.io/data-cleaning-automation](https://piyush-kumar-768.github.io/data-cleaning-automation)

---

## 📌 Project Overview

This project automates the full data preprocessing workflow — from raw messy data to a clean, analysis-ready dataset — with a detailed visual report generated automatically at every run. Upload any CSV or use the built-in 200-record sample dataset.

---

## ⚙️ Automated Pipeline Steps

| Step | Action | Technique |
|---|---|---|
| 1 | Load Data | CSV parsing, schema detection |
| 2 | Detect Issues | Missing, duplicates, outliers, format errors |
| 3 | Fix Missing Values | Mean imputation (numeric) · Mode imputation (categorical) |
| 4 | Remove Duplicates | Exact row match detection and removal |
| 5 | Fix Outliers | 3σ Winsorization (capping at boundary) |
| 6 | Standardize | Title case, whitespace trimming, date validation |
| 7 | Generate Report | Automated visual + text quality report |

---

## ✨ Key Features

- **Full Automated Pipeline** — 7-step cleaning workflow runs in one click
- **Issue Detection** — Missing values, duplicates, outliers, invalid formats, inconsistent text
- **Before / After View** — Side-by-side comparison of raw vs cleaned values
- **Column Profiler** — Data type, completeness %, unique values, min/max/mean per column
- **Visual Charts** — Issue distribution, quality score, missing values by column, completeness bars
- **Pipeline Log** — Real-time execution log with timestamps
- **Automated Report** — Full data quality report with techniques used and recommendations
- **CSV Upload** — Bring your own dataset
- **Export Report** — Download cleaning summary as text file

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| HTML / CSS / JavaScript | Frontend & UI |
| Chart.js | Visual summaries and charts |
| PapaParse | CSV file parsing |
| Python (pandas) | Referenced preprocessing methodology |
| Statistical Methods | Mean/mode imputation, 3σ outlier detection |

---

## 📊 Data Quality Issues Handled

| Issue | Detection Method | Fix Applied |
|---|---|---|
| Missing values | Null / empty cell check | Mean (numeric) / Mode (categorical) imputation |
| Duplicate rows | Exact row match | First occurrence kept, rest dropped |
| Outliers | 3 standard deviation rule | Winsorization (capped at 3σ boundary) |
| Inconsistent text | Case comparison | Standardized to Title Case |
| Invalid email | Regex validation | Flagged for manual review |
| Invalid dates | Format check | Flagged with error message |
| Whitespace | Strip check | Leading/trailing spaces removed |

---

## 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/piyush-kumar-768/data-cleaning-automation.git

cd data-cleaning-automation

# Open directly in browser — no installation needed
open index.html
```

---

## 📁 Project Structure

```
data-cleaning-automation/
│
├── index.html      # Full dashboard (self-contained)
└── README.md       # Project documentation
```

---

## 📈 Sample Results (Built-in Dataset)

- **200 records** processed across 10 columns
- **~40 issues** detected across 7 issue types
- **Quality score** improved from ~78% → ~96%
- **Pipeline runtime** < 2 seconds fully automated

---

## 👤 Author

**Piyush Kumar**
B.Tech CSE (AI & ML) — Guru Jambheshwar University of Science & Technology

- 📧 piyushkumar768x@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/piyush-kumar2908)
- 🐙 [GitHub](https://github.com/piyush-kumar-768)

---

## 🏆 Acknowledgements

- Built as part of a Data Analytics project submission
- Preprocessing methodology inspired by Python pandas and scikit-learn pipelines
- Outlier detection based on classical statistical 3σ rule
