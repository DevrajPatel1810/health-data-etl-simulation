# 🩺 Public Health ETL Pipeline – Nova Scotia Notifiable Diseases

This project simulates a real-world ETL (Extract, Transform, Load) pipeline using intentionally corrupted healthcare datasets from Nova Scotia's Open Data Portal. The datasets represent notifiable disease reports categorized by region and sex between 2014 and 2017.

The project focuses on cleaning, validating, transforming, and visualizing public health data to mirror real-world data preprocessing challenges.

---

## 🧰 Technologies Used

- **Python 3.9**
- **Pandas** – data manipulation
- **NumPy** – numerical computations
- **Matplotlib** / **Seaborn** – data visualization
- **Jupyter Notebook** – interactive development

---

## 📂 Dataset Sources

- [Nova Scotia Open Data Portal](https://data.novascotia.ca/)
- Datasets:
  - *Notifiable Diseases by Sex (2014–2017)*
  - *Notifiable Diseases by Zone (2014–2017)*

The datasets have been manually corrupted to simulate real-world cleaning needs, including:
- Missing values
- Duplicated rows
- Negative or unrealistic values
- Shuffled and inconsistent summaries

---

## 📊 Project Tasks

### Section 1 – ETL and Data Cleaning
- Load CSV files into Pandas DataFrames
- Sort data by year and disease
- Detect and remove duplicate entries
- Identify and impute missing data (`np.nan`)
- Detect out-of-bounds values (e.g., negative case counts)
- Perform internal consistency checks within datasets
- Validate external consistency across datasets
- Generate a scatter plot of disease counts over time

> Example Plot: *Acquired Immune Deficiency Syndrome* cases by year (2014–2017)

---

## ✅ Key Learning Outcomes

- Developed data cleaning workflows following ETL best practices
- Validated public health datasets using rule-based logic
- Built robust scripts that can generalize to unseen corruptions
- Simulated end-to-end data pipeline components for healthcare reporting

---
