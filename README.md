# AltSchool Africa — 3rd Semester Machine Learning Portfolio

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-150458.svg)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-0.12%2B-3776AB.svg)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)]()

> **Tracking Machine Learning Workflows, Data Science Experiments, and Portfolio Projects for AltSchool Africa (3rd Semester — 2026).**

---

> [!IMPORTANT]
> **Educational Disclaimer & Caveat**  
> *The datasets and statistical analyses included in this repository are generated strictly for educational, learning, and coursework purposes within the AltSchool Africa Data Science / ML track. The data is synthetic/simulated and **does not represent actual figures of the U.S. Educational System** or official institutional metrics.*

---

## 📌 Repository Overview

This repository serves as a professional portfolio documenting end-to-end Machine Learning (ML) workflows, Exploratory Data Analysis (EDA), feature engineering pipelines, model training, and evaluation techniques developed during the 3rd Semester at AltSchool Africa.

The core objective is to move beyond superficial charting and establish a rigorous, production-minded visualization and analytical pipeline to understand complex multi-dimensional datasets.

---

## 📅 Semester Curriculum & Activity Tracker

| Week / Module | Focus Area & Key Topics | Status | Main Deliverables |
| :--- | :--- | :---: | :--- |
| **Week 1** | **ML Visualization & Exploratory Data Analysis (EDA)**<br>• Visualization Pipeline Setup (Matplotlib & Seaborn)<br>• Univariate & Multivariate Distribution Analysis<br>• Socioeconomic & Academic Feature Interaction | `COMPLETED` | [`third_Semester_Wk1.ipynb`](file:///c:/Users/hp/OneDrive/Desktop/ecob%20data%20notes/completed%20projects/anti%20pip/third%20semester/Third_semester_Baraka_Altschool_2026/third_Semester_Wk1.ipynb)<br>[`us_education_system_dataset.csv`](file:///c:/Users/hp/OneDrive/Desktop/ecob%20data%20notes/completed%20projects/anti%20pip/third%20semester/Third_semester_Baraka_Altschool_2026/us_education_system_dataset.csv) |
| **Week 2** | **Data Cleaning & Feature Engineering**<br>• Missing Value Imputation & Outlier Handling<br>• Categorical Encoding & Numerical Scaling | `PLANNED` | *Upcoming* |
| **Week 3** | **Supervised Learning — Regression & Classification**<br>• Baseline Model Implementation<br>• Decision Boundaries & Confusion Matrices | `PLANNED` | *Upcoming* |
| **Week 4** | **Model Diagnostics & Optimization**<br>• Bias vs. Variance Trade-off Analysis<br>• Hyperparameter Tuning (GridSearch / RandomSearch) | `PLANNED` | *Upcoming* |
| **Week 5** | **Advanced Machine Learning & Capstone Project**<br>• Model Deployment & End-to-End Pipeline Packaging | `PLANNED` | *Upcoming* |

---

## 📊 Week 1 Activity Deep-Dive: Exploratory Data Analysis & Visualization Pipeline

In Week 1, we implemented an exploratory pipeline analyzing institution-level academic and socioeconomic data.

### 1. Dataset Overview
- **Records**: 5,000 Academic Institutions
- **Attributes**: 35 Features categorized into:
  - **Institutional Context**: `level`, `control` (Public, Private Religious, Private For-Profit), `title_i_status`, location features (`state_code`, `county`).
  - **Resources & Expenditures**: `per_pupil_expenditure_usd`, `total_enrollment`, `student_teacher_ratio`, `broadband_access_pct`.
  - **Demographics & Student Needs**: `percent_free_reduced_lunch`, `special_education_pct`, `english_learner_pct`, racial distribution percentages.
  - **Academic Outcomes**: `math_proficiency_pct`, `reading_proficiency_pct`, `graduation_rate_pct`, `avg_sat_score`, `avg_act_score`.

### 2. Analytical & Visualization Highlights
- **Univariate Distribution & Skewness Analysis**:
  - Kernel Density Estimation (KDE) and Histograms were generated to examine per-pupil expenditure distributions across institutions.
  - Box plot comparisons of `math_proficiency_pct` across different `title_i_status` levels to evaluate baseline academic disparity.
- **Multivariate Socioeconomic Interactions**:
  - Multi-axis scatter plots mapping socioeconomic challenge (`percent_free_reduced_lunch`) against academic output (`math_proficiency_pct`), hue-encoded by institutional control type (`control`) and scaled by per-pupil expenditure (`per_pupil_expenditure_usd`).

---

## 📁 Repository Directory Structure

```
Third_semester_Baraka_Altschool_2026/
├── README.md                      # Professional portfolio overview & activity tracker
├── third_Semester_Wk1.ipynb       # Week 1 EDA & Visualization Pipeline Notebook
└── us_education_system_dataset.csv # Educational dataset (5,000 records, 35 features)
```

---

## 🛠️ Tech Stack & Dependencies

- **Language**: Python 3.8+
- **Environment**: Jupyter Notebook / Google Colab
- **Data Manipulation**: `pandas`, `numpy`
- **Data Visualization**: `seaborn`, `matplotlib`

---

## 🚀 How to Run the Notebooks

### 1. Clone the Repository
```bash
git clone https://github.com/Ecoplex82/Third_semester_Baraka_Altschool_2026.git
cd Third_semester_Baraka_Altschool_2026
```

### 2. Set Up Virtual Environment & Install Dependencies
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook third_Semester_Wk1.ipynb
```

---

## 👤 Author & Acknowledgments

- **Author**: Emmanuel Bright Chetachi ([@Ecoplex82](https://github.com/Ecoplex82))
- **Program**: AltSchool Africa — Data Science / Machine Learning Track (3rd Semester)
- **Year**: 2026
