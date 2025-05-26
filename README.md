# Plotting-data-and-finding-cut-offs-on-a-global-level

Here's a short and efficient **README** for your project:

---

## 👓 Specs Prediction - Exploratory Data Analysis (EDA)

This project analyzes a dataset containing demographic, lifestyle, and health features to identify patterns associated with wearing spectacles.

### 🔍 Key Tasks

* Cleaned and preprocessed raw data
* Calculated correlation of features with the target variable `wears_specs`
* Dropped low-correlation features (|corr| < 0.1)
* Identified cut-off thresholds where 70%+ individuals wear specs
* Analyzed binary features for high-impact groups
* Visualized patterns using histograms, box plots, and scatter plots

### 📁 Files

* `specs_data.csv` – Raw dataset
* `eda_visualization.py` – Python script for full analysis
* `correlation_summary.csv` – Feature-target correlation report
* `cleaned_specs_data.csv` – Processed dataset for further use

### 📊 Libraries Used

* `pandas`, `numpy`, `matplotlib`, `seaborn`

### ▶️ How to Run

```bash
python eda_visualization.py
```

### ✅ Output

* Visual insights on which factors are linked to wearing specs
* Cleaned dataset for modeling or dashboard use

---
