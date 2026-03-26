# 🧬 Cancer Data Analysis & Survival Insights

## 📖 Overview
This project performs an in-depth analysis of a cancer patient dataset to uncover patterns related to:

- Patient demographics  
- Cancer stages  
- Treatment effectiveness  
- Lifestyle factors  
- Comorbidities  
- Genetic influences  
- Survival outcomes  

The analysis focuses on identifying **key factors influencing survival rates and treatment success** using **data analysis and visualization techniques**.

---

## 🎯 Objectives
- Analyze patient demographics and geographic distribution  
- Study survival rates across cancer stages  
- Evaluate treatment effectiveness and duration  
- Examine the impact of lifestyle factors (smoking, BMI)  
- Assess the influence of comorbidities and family history  
- Understand how multiple cancer conditions affect survival  
- Perform time-based analysis on treatment duration  

---

## 📂 Dataset Description
The dataset (`cancer_dataset1.csv`) contains detailed patient-level information, including:

### 👤 Patient Information
- `id` – Patient ID  
- `age` – Age of patient  
- `gender` – Male/Female  
- `country` – Patient location  

### 🧬 Medical Details
- `cancer_stage` – Stage I to IV  
- `survived` – Survival status (1 = Yes, 0 = No)  
- `treatment_type` – Chemotherapy, Surgery, Radiation, Combined  
- `diagnosis_date`, `end_treatment_date`  

### ⚕️ Health & Lifestyle
- `smoking_status`  
- `bmi`  
- `cholesterol_level`  

### 🏥 Comorbidities
- `asthma`  
- `hypertension`  
- `cirrhosis`  

### 🧬 Genetic & History
- `family_history`  
- `other_cancer`  

---

## 🧹 Data Preprocessing
- Converted date columns to datetime format  
- Created **treatment_duration** (days between diagnosis and treatment completion)  
- Converted age to integer format  
- Created **age groups**:
  - 0–20, 20–40, 40–60, 60–80, 80–110  

---

## 📊 Analysis Performed

### 1️⃣ Patient Demographics & Geographic Analysis
- Age distribution across cancer stages  
- Gender distribution and average age  
- Gender-based differences in survival and treatment  
- Country-wise patient count and survival rates  
- Age variation across countries and stages  

---

### 2️⃣ Cancer Stage & Survival Analysis
- Survival rates across stages (Stage I–IV)  
- Identification of stage with highest death rate  
- Survival probability across age groups  
- Comparison of **early-stage vs late-stage survival**  
- Distribution of cancer stages at diagnosis  

---

### 3️⃣ Treatment Effectiveness & Patterns
- Survival rates by treatment type  
- Most commonly used treatments  
- Treatment variation across stages  
- Comparison: **Combined vs Single treatments**  
- Relationship between:
  - Treatment duration  
  - Survival rate  

---

### 4️⃣ Lifestyle Factors & Risk Assessment
- Impact of **smoking** on survival and cancer severity  
- Effect of **BMI categories**:
  - Underweight  
  - Normal  
  - Overweight  
  - Obese  

---

### 5️⃣ Comorbidities & Health Conditions
- Impact of:
  - Asthma  
  - Hypertension  
  - Liver cirrhosis  
- Comparison of survival:
  - Single comorbidity  
  - Multiple comorbidities  

---

### 6️⃣ Family History & Genetic Factors
- Effect of family history on:
  - Age of diagnosis  
  - Cancer stage  
- Comparison of stage distribution with/without family history  

---

### 7️⃣ Multiple Cancer Cases
- Impact of additional cancers on survival  
- Comparison between:
  - Single cancer  
  - Multiple cancers  

---

### 8️⃣ Time-Based Analysis
- Validation of diagnosis and treatment dates  
- Statistical summary of treatment duration  
- Relationship between:
  - Treatment duration  
  - Survival outcomes  

---

## 📈 Visualizations
The project includes extensive visualizations using:

- Count plots  
- Bar charts  
- Scatter plots  
- Strip plots  
- Heatmaps (crosstab-based insights)  
- Box plots  

---

## 🛠️ Technologies Used
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  
- Power BI (for dashboard visualization `.pbix` file)

---

## 🔍 Key Insights
- Early-stage diagnosis significantly improves survival rates  
- Treatment effectiveness varies by type and duration  
- Lifestyle factors like smoking and BMI influence outcomes  
- Multiple comorbidities reduce survival probability  
- Family history impacts diagnosis patterns  
- Longer or optimized treatment duration can correlate with survival  
