# 🦠 COVID-19 Global Data Analysis

A data analysis project exploring global COVID-19 trends using the **Our World in Data (OWID)** dataset — covering case counts, deaths, testing, and demographic/economic factors across 200+ countries

## 📊 Project Overview
This project answers questions like:
- Which countries had the highest total cases and deaths?
- How did continents compare in overall impact?
- What does India's COVID-19 trend look like over time?
- Which countries had the highest Case Fatality Rate (CFR)?
- Do socioeconomic factors (GDP, median age, population density) correlate with COVID impact?

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 📁 Files
- `covid19_analysis.ipynb` — Main analysis notebook (data cleaning, EDA, visualizations, insights)
- `owid-covid-data.csv` — Dataset (source: Our World in Data)
- `*.png` — Exported chart images

## 🔍 Key Insights
- COVID-19 spread and impact were highly uneven across countries and continents.
- India's case/death trends show distinct wave patterns over time.
- Case Fatality Rate varies significantly by country, influenced by testing capacity and healthcare access — not just virus severity.
- Socioeconomic factors like median age and GDP per capita show correlation with deaths-per-million, though correlation ≠ causation.

## 📌 Dataset Source
[Our World in Data — COVID-19 Dataset](https://ourworldindata.org/covid-cases)

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook covid19_analysis.ipynb
```

---
*Project built as part of a Data Analyst portfolio.*
