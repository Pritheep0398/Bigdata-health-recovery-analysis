
# Predictive Analysis of Post-Surgical Recovery Using PySpark in Big Data Healthcare

This project focuses on analyzing patient recovery times after surgery using large-scale healthcare data. The goal is to understand how different factors such as age, diabetes status, surgery details, and lifestyle choices affect recovery time. The analysis is performed using **PySpark RDDs** on **Google Colab**.
---
## Project Objectives

- Identify how patient **demographics** (like age and diabetes) affect recovery time.
- Analyze the **impact of surgery type, duration, and anesthesia** on recovery.
- Study how **lifestyle choices** such as smoking and alcohol use influence recovery.

---
## Dataset Description

The dataset contains synthetic healthcare records of 100,000 patients with the following features:

- **Demographics:** Age Group, Gender, Diabetes, BMI
- **Lifestyle:** Smoking Status, Alcohol Use, Exercise Level
- **Surgery Details:** Type of Surgery, Duration, Anesthesia Type
- **Post-Surgery:** Recovery Time, Hospital Stay, Pain Level, Infection Occurrence

Stored in: `data/ExportCSV.csv`

---

## Analytical Tasks

### Task 1: Demographics (Age + Diabetes)
- Calculates average recovery time by grouping patients based on age group and diabetes status.

### Task 2: Surgery Details
- Identifies the combination of surgery type, duration, and anesthesia that causes the **maximum recovery time**.

### Task 3: Lifestyle (Smoking + Alcohol)
- Compares average recovery time across different lifestyle combinations.

---

## Tools and Technologies Used

- Apache Spark 3.0.1
- PySpark (RDDs)
- Google Colab
- findspark
- Python 3.x
- CSV File Input

---
## How to Run

1. Clone this repository:
```bash
git clone https://github.com/Pritheep0398/BigData-HealthRecovery-Analysis.git
```

2. Open each `.ipynb` notebook in Google Colab or Jupyter.

3. Make sure the dataset is available at:  
```python
file_path = "data/ExportCSV.csv"

4. Run the cells in order.

---
## Project Report

A full PDF report of the project is available in the [`docs/`](docs/) folder:  
👉 [Click to view](docs/BigData_Healthcare_Analysis_Report.pdf)

---

## Conclusion

This project shows how PySpark can be used to analyze large healthcare datasets and find patterns in patient recovery after surgery. We studied how different factors like age, diabetes, surgery type, smoking, and alcohol use affect recovery time. Even though the data was synthetic, the analysis helped us understand how real hospitals could use similar methods to plan better care. PySpark’s RDDs allowed us to process and group the data efficiently, and using Google Colab made it easy to run the project without setting up a big system. Overall, this project proves that big data tools can be very helpful in improving healthcare decisions and outcomes.

---
