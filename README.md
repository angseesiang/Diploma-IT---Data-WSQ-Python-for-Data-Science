# Diploma (IT - Data) — WSQ Python for Data Science
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)](#) [![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](#) [![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-brightgreen)](https://colab.google.com)

This repository contains the **assignments** and **project milestones** I completed during my _Diploma in Information Technology (Data)_. 

## Contents
- [1. Assignment_01a_WSQ_Python_for_Data_Science_(SF)](#assignment-01a-wsq-python-for-data-science-sf)
- [2. Assignment_01b_WSQ_Python_for_Data_Science_(SF)](#assignment-01b-wsq-python-for-data-science-sf)
- [3. Assignment_02a_WSQ_Python_for_Data_Science_(SF)](#assignment-02a-wsq-python-for-data-science-sf)
- [4. Assignment_02b_WSQ_Python_for_Data_Science_(SF)](#assignment-02b-wsq-python-for-data-science-sf)
- [5. Assignment_03_WSQ_Python_for_Data_Science_(SF)](#assignment-03-wsq-python-for-data-science-sf)
- [6. Project_Milestone_1&2_Python_for_Data_Science](#project-milestone-1-2-python-for-data-science)
- [7. Project_Milestone_3&4_Python_for_Data_Science](#project-milestone-3-4-python-for-data-science)

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

You can open any of these `.ipynb` files directly in **Google Colab**:

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

<a id="assignment-01a-wsq-python-for-data-science-sf"></a>
## 1. Assignment_01a_WSQ_Python_for_Data_Science_(SF)

**File:** `Assignment_01a_WSQ_Python_for_Data_Science_(SF).ipynb`  
**Cells:** 8 code, 7 markdown

**Overview:** Task 1: Variable Manipulation  * Create two variables named num1 and num2, sum them, and print the result.

---

<a id="assignment-01b-wsq-python-for-data-science-sf"></a>
## 2. Assignment_01b_WSQ_Python_for_Data_Science_(SF)

**File:** `Assignment_01b_WSQ_Python_for_Data_Science_(SF).ipynb`  
**Cells:** 7 code, 8 markdown

**Overview:** Task 1: Double the Number  * Write a Python function that doubles an input number.

---

<a id="assignment-02a-wsq-python-for-data-science-sf"></a>
## 3. Assignment_02a_WSQ_Python_for_Data_Science_(SF)

**File:** `Assignment_02a_WSQ_Python_for_Data_Science_(SF).ipynb`  
**Cells:** 5 code, 5 markdown

**Overview:** Task 1: Convert Weights to Pounds  * Convert a Python list of weights in kg to numpy array and then to pounds.

**Libraries imported:** `numpy`

---
<a id="assignment-02b-wsq-python-for-data-science-sf"></a>
## 4. Assignment_02b_WSQ_Python_for_Data_Science_(SF)

**File:** `Assignment_02b_WSQ_Python_for_Data_Science_(SF).ipynb`  
**Cells:** 8 code, 10 markdown

**Overview:** Task 1: Loading the Data:  *  Load the Titanic dataset into a Pandas DataFrame.

**Libraries imported:** `pandas`

---

<a id="assignment-02b-wsq-python-for-data-science-sf"></a>
## 4. Assignment_02b_WSQ_Python_for_Data_Science_(SF)

**File:** `Assignment_02b_WSQ_Python_for_Data_Science_(SF).ipynb`  
**Cells:** 8 code, 10 markdown

**Overview:** Tasks: Practice with lists, tuples, and dictionaries; apply iteration and conditionals in Python.

**Libraries imported:** `pandas`

---

<a id="assignment-03-wsq-python-for-data-science-sf"></a>
## 5. Assignment_03_WSQ_Python_for_Data_Science_(SF)

**File:** `Assignment_03_WSQ_Python_for_Data_Science_(SF).ipynb`  
**Cells:** 6 code, 7 markdown

**Overview:** Task 1: Load the Titanic dataset with pandas and perform basic exploration and visualization.

**Libraries imported:** `matplotlib, pandas, seaborn`

---

<a id="project-milestone-1-2-python-for-data-science"></a>
## 6. Project_Milestone_1&2_Python_for_Data_Science

**File:** `Project_Milestone_1&2_Python_for_Data_Science.ipynb`  
**Cells:** 21 code, 16 markdown

**Overview:** Milestones 1 & 2: Work with COVID-19 dataset, perform data wrangling, and visualize trends.

**Libraries imported:** `matplotlib, pandas, seaborn`

---

<a id="project-milestone-3-4-python-for-data-science"></a>
## 7. Project_Milestone_3&4_Python_for_Data_Science

**File:** `Project_Milestone_3&4_Python_for_Data_Science.ipynb`  
**Cells:** 17 code, 23 markdown

**Overview:** Milestones 3 & 4: Extended COVID-19 analysis including regional, time series, and country-level insights.

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
- Introductory machine learning with scikit-learn (train/test split, basic models)

## Repository Structure
```
.
├─ Assignment_01a_WSQ_Python_for_Data_Science_(SF).ipynb
├─ Assignment_01b_WSQ_Python_for_Data_Science_(SF).ipynb
├─ Assignment_02a_WSQ_Python_for_Data_Science_(SF).ipynb
├─ Assignment_02b_WSQ_Python_for_Data_Science_(SF).ipynb
├─ Assignment_03_WSQ_Python_for_Data_Science_(SF).ipynb
├─ Project_Milestone_1&2_Python_for_Data_Science.ipynb
├─ Project_Milestone_3&4_Python_for_Data_Science.ipynb
└─ data/                     # (optional) datasets used by notebooks
```

## Acknowledgements
Coursework prepared as part of **WSQ Python for Data Science (SF)** in my Diploma (Information Technology - Data). This repository is shared for educational purposes.
