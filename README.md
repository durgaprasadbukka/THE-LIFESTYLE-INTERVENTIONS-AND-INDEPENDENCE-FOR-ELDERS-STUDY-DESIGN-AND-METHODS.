# 🧪 Linear Mixed Model Analysis – LIFE Study

This project investigates health trends over time using **Linear Mixed Models (LMMs)** and calculates the **Healthy Eating Index (HEI)** based on LIFE Study data. Python was used for data processing, HEI computation, and LMM modeling, while R was used for generating visualizations across time, study arms, and racial groups.

---

## 📌 Project Overview

The dataset includes repeated measures for physical activity, BMI, sleep quality, glucose, blood pressure, smoking status, LDL cholesterol, and nutrition. HEI was derived to evaluate diet quality, and LMMs were applied to understand the effect of time on each variable, accounting for within-subject variability.

---

## 🔬 Methodology

- Transformed the dataset to long format for repeated measures modeling  
- Calculated **HEI** using dietary variables in Python  
- Standardized and imputed missing values  
- Applied **LMMs** in Python using `statsmodels`  
- Used **R** for visualizations of trends by time, study arm, and race  
- Explored interaction effects (e.g., Time × HEI)

---

## 📈 Key Results

- ✅ **BMI** showed a significant decline over time *(p = 0.001)*  
- ❌ No significant changes in physical activity, glucose, sleep quality, LDL, or blood pressure  
- ❌ HEI remained stable and showed no significant interaction effects  

---

## 🧰 Tools Used

- **Python**: `pandas`, `numpy`, `statsmodels`, `matplotlib`  
- **R**: `ggplot2`, `dplyr`, `tidyr`, `readxl`  
- **Data Source**: LIFE Study Dataset

---

## 📂 Files Included

- `Corrected_Filtered_LIFE_Dataset` – Filtered dataset for timepoint calculations.
- `TimeN1-6_filtered`- files for seperated timepoints from cleaned datsets for easy calculation
- `Graphs.rmd` – R script for plots by time, study arm, and race   
- `.png files` – Images of graphs tells about variables across Time by study arm and race'
- `HEI.ipynb` - Health index calculation
- `Methodology for Nutrition Ingestion Index Calculation.doc`  - Methodology used for HEI calculation
- `Correlation.ipynb` - HEI Correlation
- `README.md` – Project summary

---

## 👤Contact:
📧 durgaprasadbukka7@gmail.com
