# 📊 Exploratory Data Analysis of the Major Crime Indicators for the City of Toronto

This repository contains the source notebook and formal report for a project analyzing Toronto’s crime data between 2014 and 2024. The focus is on understanding the spatial and categorical distribution of major crimes across the city using real-world open data.

> 📝 Originally developed and submitted as part of an academic course project in March 2024.

---

## 🔗 Project on Kaggle

You can view and run the full interactive notebook on Kaggle here:  
👉 [EDA of MCI for the City of Toronto](https://www.kaggle.com/code/shadow2406/eda-of-mci-for-the-city-of-toronto)

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `eda-of-mci-for-the-city-of-toronto.ipynb` | Main Jupyter notebook containing code, EDA, and visualizations |
| `Report.pdf` *(or `docs/Report.pdf`)* | Cleaned and formatted academic report summarizing the findings |
| `README.md` | This documentation file |

---

## 📁 Dataset Overview

- **Source**: [Toronto Police Service - Public Safety Data Portal](https://data.torontopolice.on.ca/datasets/TorontoPS::major-crime-indicators-open-data/about)  
- **Format**: CSV  
- **Rows**: ~384,000 (after cleaning)  
- **Period Covered**: January 2014 – April 2024  
- **Crime Categories Analyzed**:  
  - Assault  
  - Break and Enter  
  - Auto Theft  
  - Robbery  
  - Theft Over  

---

## 🧹 Data Processing

- Dropped nulls and irrelevant columns
- Transformed datetime fields into consistent format
- Cleaned dataframe reduced from 31 → 14 meaningful columns
- Saved pre-processed data to a new CSV for reproducibility

---

## 📊 Visualizations

The notebook includes visualizations such as:

- 📈 Line plots of assault trends over time (especially in schools)
- 📊 Bar charts of top crime-prone location types and neighbourhoods
- 🔥 Heatmaps comparing crime categories across locations and areas

---

## 📌 Key Insights

- 🏘️ Residential spaces (apartments, houses) face the most break-ins and assaults  
- 🏫 Schools during supervised activity rank 8th in reported assault cases  
- 📈 A noticeable post-COVID spike in overall crime patterns  
- 🚗 Auto thefts dominate in certain neighbourhoods like West Humber–Clairville  
- 📍 Assault is the most common crime across nearly all geographies

---

## 📄 Formal Report

The cleaned and formatted academic report includes an executive summary, methodology, analysis, and conclusions:
> 📥 [Download Report.pdf](./Report.pdf)

---

## 🔧 Tech Stack

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter / Kaggle Notebook
- Git & GitHub

---

## 📚 References

- Toronto Police Service (2023). *Major Crime Indicators Open Data*.  
  https://data.torontopolice.on.ca/datasets/TorontoPS::major-crime-indicators-open-data/about  
- Institute for Economics & Peace (2023). *Global Peace Index*.  
  https://www.visionofhumanity.org/wp-content/uploads/2023/06/GPI-2023-Web.pdf

---

## 🏷️ License

This project is for educational and demonstrative purposes only. Feel free to fork or reference with attribution.
