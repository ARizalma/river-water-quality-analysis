# River Water Quality Analysis

An end-to-end data analysis project that evaluates river water quality using Python. This project covers data preprocessing, exploratory data analysis (EDA), water quality compliance assessment, river-level analysis, parameter-level analysis, temporal trend analysis, and data visualization to identify pollution patterns and support environmental monitoring.

---

## Project Objectives

- Clean and prepare raw river water quality data.
- Explore water quality characteristics across multiple rivers.
- Evaluate compliance with environmental quality standards.
- Identify rivers with the highest pollution levels.
- Determine which water quality parameters most frequently exceed regulatory standards.
- Analyze temporal (monthly) variations in water quality.
- Develop an interactive Power BI dashboard for data exploration.

---

## Dataset

The dataset contains river water quality monitoring results collected during 2023, including:

- River name
- Water quality parameter
- Measurement value
- Water quality standard
- Sampling month
- Geographic coordinates
- Monitoring location

---

## Project Workflow

- Data Understanding
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Water Quality Compliance Analysis
- River Quality Analysis
- Parameter Analysis
- Monthly Trend Analysis
- Summary of Key Findings
- Power BI Dashboard (Coming Soon)

---

## Project Structure

```
river-water-quality-analysis/
│
├── Data/
│   ├── river-water-quality-data-for-2023.csv
│   └── river-water-quality-data-clean.csv
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_eda.ipynb
│   └── 04_water_quality_analysis.ipynb
│
├── Image/
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Key Findings

- Approximately **67%** of water quality measurements complied with environmental quality standards.
- Approximately **33%** of observations exceeded the applicable standards.
- **Fecal Coliform** and **Total Coliform** showed the highest exceedance rates.
- Organic pollution indicators such as **BOD** and **COD** frequently exceeded environmental standards.
- Several rivers, including **Kalibaru Timur**, **Kamal**, and **Blencong**, consistently exhibited relatively high exceedance percentages.
- Monthly exceedance rates remained relatively stable throughout the monitoring period, indicating persistent pollution rather than strong seasonal variation.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Folium
- Jupyter Notebook
- Power BI *(Dashboard in progress)*

---

## Dashboard Preview

**Coming Soon**

The project will include an interactive Power BI dashboard featuring:

- Overall water quality compliance
- River performance comparison
- Parameter exceedance analysis
- Monthly monitoring trends
- Interactive filters and KPIs

---

## Repository

This repository demonstrates an end-to-end data analysis workflow, from raw environmental monitoring data to actionable insights through data cleaning, exploratory analysis, statistical summaries, and visualizations.
