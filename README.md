# 🌸 Task 1 — Iris Dataset: Data Exploration & Visualization

## 🎯 Aim of the Task
This task focuses on performing **exploratory data analysis (EDA)** on the well-known Iris dataset.  
The goal is to examine the structure of the data, summarize key statistics, and create visualizations that reveal relationships, trends, and unusual values.

---

## 📊 Dataset Overview
- **Dataset:** Iris flower measurements  
- **Source:**  
  - Direct import from Seaborn: `sns.load_dataset("iris")`  
  - Or downloadable CSV from public repositories  
- **Features:**
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
  - `species` (categorical label)
- **Size:** 150 samples × 5 columns

---

## 🛠 Steps Completed
1. **Data Import:** Loaded dataset using **pandas**.
2. **Initial Inspection:** Viewed shape, column headers, and top rows.
3. **Data Summary:** Applied `.info()` and `.describe()` for an overview of datatypes and statistics.
4. **Visualization:**
   - Scatter plots to compare feature pairs.
   - Histograms to see how values are distributed.
   - Box plots to highlight potential outliers.

---

## 📚 Skills Applied
- Data handling with **pandas**
- Descriptive statistical analysis
- Visual data exploration using **matplotlib** and **seaborn**

---

## 🔍 Observations
- **No Missing Data:** All entries are complete.
- **Clear Clusters:** Petal measurements separate species distinctly.
- **Distribution Patterns:** Some attributes show skewness; others are more balanced.
- **Outliers:** Slight anomalies in `sepal_width` values.

---

## 📁 Repository Contents
- `iris_exploration.ipynb` — Notebook with all code, output, and commentary.
- `README.md` — Overview of the task and insights gained.

---

## 📎 Resources
- [Seaborn Dataset Reference](https://seaborn.pydata.org/data.html)
- [UCI Iris Dataset Information](https://archive.ics.uci.edu/ml/datasets/iris)

---

**Status:** ✅ Completed
