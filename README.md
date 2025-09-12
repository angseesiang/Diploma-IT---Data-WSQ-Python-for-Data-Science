# Diploma (IT - Data) — WSQ Python for Data Science
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)](#) [![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](#) [![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-brightgreen)](https://colab.google.com)

This repository contains the **assignments** and **project milestones** I completed during my _Diploma in Information Technology (Data)_. The notebook names below follow the original course naming, including **Project_Milestone_1&2_Python_for_Data_Science** and **Project_Milestone_3&4_Python_for_Data_Science**.

## Contents
- [1. Assignment_01a_WSQ_Python_for_Data_Science_(SF)](#assignment-01a-wsq-python-for-data-science-sf)
- [2. Assignment_01b_WSQ_Python_for_Data_Science_(SF)](#assignment-01b-wsq-python-for-data-science-sf)
- [3. Assignment_02a_WSQ_Python_for_Data_Science_(SF)](#assignment-02a-wsq-python-for-data-science-sf)
- [4. Assignment_03_WSQ_Python_for_Data_Science_(SF)](#assignment-03-wsq-python-for-data-science-sf)
- [5. Project_Milestone_1&2_Python_for_Data_Science](#project-milestone-1-2-python-for-data-science)
- [6. Project_Milestone_3&4_Python_for_Data_Science](#project-milestone-3-4-python-for-data-science)

## Quick Start (Local)

1. **Clone** the repo and create a virtual environment
   ```bash
   git clone <your-repo-url>.git
   cd <your-repo-name>
   python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate
   ```

2. **Install packages** (example set below)
   ```bash
   pip install -U jupyter pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Launch Jupyter**
   ```bash
   jupyter notebook
   ```

4. **Open** the notebooks in the order shown in the table of contents.

## Open in Google Colab

You (and users) can open any of these `.ipynb` files directly in **Google Colab**:

- Go to **https://colab.google.com**.
- To open from **GitHub**: **File ▸ Open notebook ▸ GitHub** tab → paste your repository URL → pick a notebook.
- To open from your **local computer**: **File ▸ Upload notebook** and choose the `.ipynb` file you've saved locally.
- If a notebook needs data files (CSV/Excel), upload them in the Colab session (left sidebar ▸ Files ▸ Upload) or mount Google Drive and adjust the file paths.

## Environment & Libraries
- **Python**: 3.9 or newer recommended
- **Common libraries used across notebooks**:
  - Plotting: `matplotlib`
  - Numerical computing: `numpy`
  - Data wrangling: `pandas`
  - Statistical plotting: `seaborn`

## 1. Assignment_01a_WSQ_Python_for_Data_Science_(SF)

**File:** `Assignment_01a_WSQ_Python_for_Data_Science_(SF).ipynb`  
**Cells:** 8 code, 7 markdown

**Overview:** Task 1: Variable Manipulation  *  Create two variables named num1 and num2 and assign them integer values of your choice. *  Calculate the sum of num1 and num2 and store the result in a variable called sum_result. *  Print the value of sum_result.

---

## 2. Assignment_01b_WSQ_Python_for_Data_Science_(SF)

**File:** `Assignment_01b_WSQ_Python_for_Data_Science_(SF).ipynb`  
**Cells:** 7 code, 8 markdown

**Overview:** Task 1: Double the Number  *  Write a Python function named double_number that takes a number as input and returns the double of the number.

---

## 3. Assignment_02a_WSQ_Python_for_Data_Science_(SF)

**File:** `Assignment_02a_WSQ_Python_for_Data_Science_(SF).ipynb`  
**Cells:** 5 code, 5 markdown

**Overview:** Task 1: Convert Weights to Pounds  *  Create a Python list weight_kg with weight values *  Convert weight_kg to numpy array np_weight_kg *  Convert np_weight_kg to weight in Pounds np_weight_lbs  Hint: Use the conversion factor of 2.2 pounds per kilogram

**Libraries imported:** `numpy`

---

## 4. Assignment_03_WSQ_Python_for_Data_Science_(SF)

**File:** `Assignment_03_WSQ_Python_for_Data_Science_(SF).ipynb`  
**Cells:** 6 code, 7 markdown

**Overview:** Task 1: Load the Dataset and Explore  *  Download the Titanic dataset and assign it to a DataFrame. *  Display the first few rows to get an overview of the data.

**Libraries imported:** `matplotlib, pandas, seaborn`

---

## 5. Project_Milestone_1&2_Python_for_Data_Science

**File:** `Project_Milestone_1&2_Python_for_Data_Science.ipynb`  
**Cells:** 21 code, 16 markdown

**Overview:** 1. Load the COVID-19 dataset using pandas from the provided dataset.

**Main sections/headings:**
- Activity 2
- Activity 3

**Libraries imported:** `matplotlib, pandas, seaborn`

---

## 6. Project_Milestone_3&4_Python_for_Data_Science

**File:** `Project_Milestone_3&4_Python_for_Data_Science.ipynb`  
**Cells:** 17 code, 23 markdown

**Overview:** 1. Create a grouped bar chart to visualize new cases by continent and month.

**Main sections/headings:**
- Project Milestone 3
- Activity 4: Regional Analysis Unveiling regional nuances in COVID-19 dynamics and identifying patterns in case distribution and fatality across time and continents.
- Activity 5: Time Series Analysis Capturing the daily dynamics of COVID-19, assessing the impact of vaccination, and monitoring testing metrics for a comprehensive global overview.
- Project Milestone-04
- Activity 6: In-Depth Country Analysis Conducting an in-depth examination of specific countries, understanding the correlation between cases and deaths globally, and exploring continental variations in case distribution.
- Activity 7: Additional Insights Extracting additional insights, examining the influence of external factors, and evaluating regional disparities for a holistic understanding of the COVID-19 landscape.

**Libraries imported:** `matplotlib, pandas, seaborn`

---

## Data Notes
If a notebook references external data files (e.g., via `pandas.read_csv`), ensure the files exist at the expected paths. For portability, store datasets under a `data/` folder and update notebook paths accordingly.

## Learning Outcomes
Across these assignments and milestones, I practiced:
- Python basics (variables, control flow, functions, data structures)
- Data wrangling with pandas (loading, cleaning, transforming, grouping, merging)
- Exploratory data analysis (descriptive statistics, handling missing values, outliers)
- Visualization with matplotlib/seaborn (distributions, relationships, time series)
- Introductory machine learning with scikit‑learn (train/test split, basic models)

## Repository Structure
```
.
├─ Assignment_01a_WSQ_Python_for_Data_Science_(SF).ipynb
├─ Assignment_01b_WSQ_Python_for_Data_Science_(SF).ipynb
├─ Assignment_02a_WSQ_Python_for_Data_Science_(SF).ipynb
├─ Assignment_03_WSQ_Python_for_Data_Science_(SF).ipynb
├─ Project_Milestone_1&2_Python_for_Data_Science.ipynb
├─ Project_Milestone_3&4_Python_for_Data_Science.ipynb
└─ data/                     # (optional) datasets used by notebooks
```

## Acknowledgements
Coursework prepared as part of **WSQ Python for Data Science (SF)** in my Diploma (Information Technology - Data). This repository is shared for educational purposes.
