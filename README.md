# Activity Quantification and Glucose Dynamics (AQGD)

This repository contains the data and code for the study titled **"Activity Quantification and Glucose Dynamics (AQGD): A Predictive Model for Type 1 Diabetes in Free-Living."** The research presents a personalized, predictive model for understanding how varying levels of physical activity (PA) influence blood glucose (BG) in individuals with Type 1 Diabetes Mellitus (T1DM) under real-world, free-living conditions.

---

## 🔍 Key Highlights

### 🧠 Study Summary
The model quantifies the relationship between PA intensity and subsequent BG changes by analyzing participant data collected via Garmin wearable devices and continuous glucose monitors (CGMs). BG changes are predicted at 15-minute intervals based on PA levels categorized into Low, Medium, High, and Very High intensities.

- 14 participants with T1DM were studied in naturalistic conditions.
- The model achieved prediction accuracies up to **99.72%** across all PA levels.
- Bland–Altman analysis showed strong agreement between predicted and actual BG values.

---

## 📊 Analysis Overview

The main analysis involves:
- Cleaning and preprocessing glucose and activity data.
- Classifying PA into quantile-based levels.
- Creating personalised predictive models using a **10-day moving average**.
- Evaluating predictions with statistical metrics like MAE and Bland–Altman plots.

---

## 📁 Repository Structure

```
My Data/
├── IDxxxx/                   # Individual participant folders
├── *_summary.csv            # Aggregated summaries by participant
├── *.ipynb                  # Jupyter Notebooks for analysis
├── *.xlsx                   # Processed results by PA level
└── README.md                # This file
```

---

## 🚀 Getting Started

### 🔧 Clone the Repository

```bash
git clone https://github.com/acp18ab/AQGD.git
cd AQGD
```

### 💻 Requirements
- Python 3.8+
- Jupyter Notebook

---

## 📄 Usage

1. Run `Final_results_mean.ipynb` for the main results analysis pipeline.
2. Use `Plots.ipynb` for visual summaries including Bland–Altman plots.
3. Explore participant-level insights in corresponding summary CSVs.

---

## 📚 Citation

If you use this repository or build on this model, please cite:

> Ahmad Bilal et al., *"Activity Quantification and Glucose Dynamics (AQGD): A Predictive Model for Type 1 Diabetes in Free-Living"*, The University of Manchester, 2025.

---

## 📬 Contact

**Ahmad Bilal**  
📧 [ahmad.bilal@manchester.ac.uk](mailto:ahmad.bilal@manchester.ac.uk)  
🔗 [research.manchester.ac.uk](https://www.research.manchester.ac.uk/en/persons/ahmad.bilal)

---
