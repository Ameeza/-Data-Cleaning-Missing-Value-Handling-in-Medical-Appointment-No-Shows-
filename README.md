# -Data-Cleaning-Missing-Value-Handling-in-Medical-Appointment-No-Shows-
Data Cleaning &amp; Missing Value Handling is done here. The duplicate row and columns are deleted here. Along with that the missing values are also handelled here.
# Medical Appointment No-Show Dataset – Data Preprocessing

## 📌 Objective
The goal of this task is to understand, clean, and prepare the **Medical Appointment No-Show dataset** for machine learning by identifying missing values, handling data quality issues, and validating the dataset after preprocessing.

This task helps in gaining **hands-on experience with real-world data preprocessing** using Python and Pandas.

---

## 📂 Dataset Description
The dataset contains information about medical appointments and whether patients showed up or missed their appointments.

Key features include:
- Patient details (Age, Gender)
- Health conditions (Hypertension, Diabetes, Alcoholism)
- Appointment details (ScheduledDay, AppointmentDay)
- Target variable: **No-show** (Yes / No)

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 🧪 Tasks Performed

### 1️⃣ Load Dataset & Inspect Structure
- Loaded the dataset using `pandas.read_csv()`
- Displayed first and last few rows
- Used `df.info()` and `df.describe()` to understand:
  - Data types
  - Missing values
  - Statistical summary

---

### 2️⃣ Identify Missing Values
- Used `.isnull().sum()` to identify missing values per column
- Calculated total missing values in the dataset

---

### 3️⃣ Visualize Missing Data
- Plotted a bar chart showing missing values **across the entire dataset**
- Helped visually understand missing data distribution

---

### 4️⃣ Handle Missing Values
- **Numerical columns**: Filled missing values using **median imputation**
- **Categorical columns**: Filled missing values using **mode imputation**

---

### 5️⃣ Handle Redundant Columns
- Identified duplicate columns (e.g., multiple `Hypertension` columns)
- Removed redundant/incorrect columns to improve data quality

---

### 6️⃣ Remove Duplicate Rows
- Checked for duplicate rows using `.duplicated()`
- Removed duplicates using `.drop_duplicates()`

---

### 7️⃣ Column Removal Based on Missing Values
- Checked percentage of missing values per column
- No column exceeded the defined missing value threshold  
  ➜ Hence, **no columns were removed**
- This indicates **good dataset quality**

---

### 8️⃣ Dataset Validation After Cleaning
- Verified:
  - No missing values remain
  - No duplicate rows remain
- Confirmed dataset is **ready for machine learning**

---

### 9️⃣ Before vs After Data Quality Comparison
Compared:
- Total missing values
- Duplicate rows
- Dataset shape and size

---

## ✅ Final Outcome
✔ Intern understands:
- Dataset structure and feature types  
- Handling missing values correctly  
- Difference between duplicate rows and duplicate columns  
- How to validate dataset quality  
- ML readiness of real-world healthcare datasets  

✔ Dataset is clean, consistent, and suitable for machine learning tasks.

---

## 📁 Repository Contents
- `Medical_App_Data_Cleaning.ipynb` – Jupyter Notebook with all code
- `Medical App.csv` – Dataset used
- `README.md` – Task explanation and outcomes

---

## 📌 Conclusion
This task demonstrates a complete **data preprocessing pipeline**, which is a critical step before applying any machine learning model. The dataset was found to be of high quality with minimal missing values and no severe data issues.

---

👩‍💻 *Prepared as part of internship / learning task*
