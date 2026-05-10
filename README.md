# AQI Data Science Project

**Student Name:** Muskan Awan  
**Registration Number:** 2280118  
**Course:** Introduction to Data Science — One-Week Applied Project (BSCS)

---

## Dataset

**Name:** Global Urban Air Quality Index Dataset (2015–2025)  
The dataset contains air quality records from 20 major cities across 15 countries, including pollutant measurements (PM2.5, PM10, CO, NO2, O3, SO2), weather data, and AQI values.

---

## Problem Statement

This project analyzes global air quality data from 2015 to 2025. The purpose is to understand AQI trends across cities and countries, identify important pollutants, classify AQI categories using basic supervised learning algorithms (KNN and Naive Bayes), and discover pollution patterns using unsupervised learning techniques (K-Means and PCA).

---

## Repository Structure

```
AQI-Data-Science-Project/
├── dataset/
│   └── global_urban_aqi_dataset.csv
├── notebook/
│   └── AQI_Data_Science_Project.ipynb
├── outputs/
│   ├── charts/
│   └── results/
├── report/
│   └── AQI_Data_Science_Report.docx
├── requirements.txt
└── README.md
```

---

## Tools and Libraries Used

| Library | Purpose |
|---------|---------|
| pandas | Data loading and manipulation |
| numpy | Numerical operations |
| matplotlib | Data visualization |
| seaborn | Statistical visualizations / heatmaps |
| scikit-learn | Machine learning (KNN, Naive Bayes, K-Means, PCA) |

---

## How to Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/MuskanAwan/AQI-Data-Science-Project.git
   cd AQI-Data-Science-Project
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Create the output folders:
   ```bash
   mkdir -p outputs/charts outputs/results
   ```

4. Open and run the notebook:
   ```bash
   jupyter notebook notebook/AQI_Data_Science_Project.ipynb
   ```

   Run all cells from top to bottom (Cell → Run All).

---

## Summary of Main Findings

- **PM2.5** has the strongest correlation with AQI (>0.95), making it the key pollution driver
- **Delhi** has the highest average AQI (172.99); **New York** has the lowest (32.77)
- AQI showed a **gradual downward trend** from 2015 to 2025, indicating slow global improvement
- **Naive Bayes** (87.04%) outperformed **KNN** (84.39% at k=7) in AQI category classification
- **K-Means** (k=3) identified three distinct pollution clusters: low, medium, and high pollution
- **PCA** explained 58.6% of total variance in just 2 components, with clear category separation

---

## Key Results

| Method | Result |
|--------|--------|
| KNN (k=7) | Accuracy = 84.39% |
| Naive Bayes | Accuracy = 87.04% |
| K-Means | 3 meaningful clusters |
| PCA | 58.6% variance in 2 components |

---

## Report

The full written report is located at: `report/AQI_Data_Science_Report.docx`

---

*Note: AI tools (Claude by Anthropic) were used to assist in code generation and analysis for this assignment.*
