# DATA VORTEX – AARUUSH'26

## Round 1 – Dataset 01 | Data Intake Restoration

### 📌 Overview

This project was developed for Round 1 of Data Vortex – Aaruush'26.

The objective was to recover Dataset 01 and rebuild the corrupted social-engine data through data cleaning, missing-value handling, anomaly detection, standardization, and exploratory data analysis (EDA).

---

## 📂 Dataset

Dataset 01 consists of two recovered datasets:

- `Social_Engine_Users_Cleaned.csv`
- `Social_Engine_Posts_Cleaned.csv`

The Posts dataset contained intentionally corrupted and inconsistent data that required preprocessing before analysis.

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing platform values
- Handled missing and `NULL` text content
- Decoded HTML entities
- Standardized timestamp formats
- Detected invalid negative engagement values
- Handled missing likes, shares, and comments
- Checked post-to-user referential integrity
- Standardized text and categorical values

### Anomaly Handling

Invalid negative engagement values were identified as anomalies and converted to missing values before appropriate imputation.

---

## 📊 Exploratory Data Analysis

The following analysis was performed:

- Platform-wise post distribution
- Average engagement by platform
- Monthly engagement trends
- Location-wise engagement
- Relationship between followers and likes
- Total engagement analysis

---

## 🔍 Key Insights

The EDA was used to identify:

- Differences in engagement across social platforms
- Platforms with higher average engagement
- Monthly engagement patterns
- Locations with higher average engagement
- Relationship between follower count and post likes

Detailed results and visualizations are available in:

`Data_Vortex_EDA_Report.pdf`

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- CSV
- GitHub

---

## 📓 Reproducibility

The complete cleaning and EDA workflow is available in:

`Data_Vortex_Round1_Cleaning_EDA.ipynb`

The notebook contains the preprocessing logic, anomaly handling, data validation, and EDA code required to reproduce the analysis.

---

## 📁 Repository Structure

```text
data-vortex-aaruush26-round1/
│
├── Social_Engine_Users_Cleaned.csv
├── Social_Engine_Posts_Cleaned.csv
├── Data_Vortex_Round1_Cleaning_EDA.ipynb
├── Data_Vortex_EDA_Report.pdf
└── README.md
