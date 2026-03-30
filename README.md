# 🧬 Cancer Patient Analytics

A complete end-to-end data analytics project on a large-scale clinical dataset of **890,000 cancer patients** across multiple countries. The workflow begins with **Exploratory Data Analysis (EDA) in a Jupyter Notebook** — covering data cleaning, feature engineering, and statistical analysis — and culminates in an **interactive 3-page Power BI Dashboard** that visualizes all insights.

---


---

## Dataset Overview

| Attribute       | Details |
|-----------------|--------|
| **Records**     | 890,000 cancer patients |
| **Format**      | Structured CSV (`dataset_med`) |
| **Coverage**    | Multiple countries |
| **Domain**      | Oncology, epidemiology, predictive modeling, health policy |

### Columns in the Dataset

| Column | Type | Description |
|--------|------|------------|
| `id` | Integer | Unique patient identifier |
| `age` | Integer | Patient age at diagnosis |
| `gender` | Categorical | Male / Female |
| `country` | Categorical | Country of residence |
| `cancer_stage` | Categorical | Stage I, II, III, or IV |
| `family_history` | Binary | Family history of cancer (0/1) |
| `smoking_status` | Categorical | Never / Former / Current |
| `bmi` | Float | Body Mass Index |
| `cholesterol_level` | Float | Cholesterol level |
| `hypertension` | Binary | Presence of hypertension (0/1) |
| `asthma` | Binary | Presence of asthma (0/1) |
| `cirrhosis` | Binary | Presence of liver cirrhosis (0/1) |
| `other_cancer` | Binary | Presence of additional cancers (0/1) |
| `treatment_type` | Categorical | Chemotherapy / Surgery / Radiation / Combined |
| `diagnosis_date` | Date | Date of cancer diagnosis |
| `end_treatment_date` | Date | Date treatment was completed |
| `survived` | Binary | Survival outcome post-treatment (0/1) |
| `Treatment Duration` | Computed | Days from diagnosis to treatment completion |
| `Age Group` | Computed | Age buckets derived from `age` |
| `Total Patients` | Measure | Count of patient records |
| `Male patients` | Measure | Count filtered by gender = Male |
| `Female patients` | Measure | Count filtered by gender = Female |

---

## EDA & Analysis Workflow

- Step 1 — Data Loading & Initial Inspection
- Step 2 — Data Cleaning & Preprocessing
- Step 3 — Feature Engineering
- Step 4 — Exploratory Data Analysis (EDA):  Demographics, Cancer Stage, Treatment Analysis, Lifestyle Factors, Comorbidities, Family History, Multiple Cancers, Time Trends, Completion Analysis
- Power BI Dashboard


---

##  Pipeline
- Raw CSV -> Jupyter Notebook -> Cleaned & Enriched Dataset -> Power BI Dashboard
---

##  Getting Started

### Prerequisites
- Python 3.8+
- pandas, numpy, matplotlib, seaborn
- Power BI Desktop

### Install Dependencies
pip install pandas numpy matplotlib seaborn jupyter

### Run Notebook
cd notebook
jupyter notebook cancer_analysis.ipynb

---
### Open Power BI

- Open `proj_report.pbix`
- Update dataset path if needed

---

## Tech Stack

| Tool | Purpose |
|------|--------|
| Python | Data processing |
| Pandas | Data analysis |
| NumPy | Computation |
| Matplotlib / Seaborn | Visualization |
| Jupyter | Notebook |
| Power BI | Dashboard |
| DAX | Measures |

---
## 📄 License

Educational use only. Ensure compliance with data privacy laws.
