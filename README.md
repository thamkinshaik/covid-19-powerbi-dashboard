# COVID-19 Global Impact Dashboard 🦠📊

An interactive Power BI dashboard analyzing global COVID-19 data — cases, deaths, infection rates, and continent-wise trends — built using the **Our World in Data (OWID)** dataset.

## 📌 Overview

This dashboard provides a comprehensive view of the COVID-19 pandemic's global impact, allowing users to explore case counts, mortality rates, and trends across countries and continents through interactive visuals.

## ✨ Features

- **KPI Cards** – Total Cases, Case Fatality Rate (%), Infection Rate (%), Total Population, Total Deaths
- **Interactive Continent Slicer** – Filter the entire dashboard by continent with a single click
- **Top Countries by Cases** – Bar chart showing countries with the highest case counts
- **Cases by Continent** – Donut chart breaking down global cases by region
- **New Cases Trend** – Line chart tracking new cases over time (Jan 2020 – Jul 2020)
- **Top Countries by Deaths** – Bar chart highlighting mortality by country
- **Detailed Data Table** – Country-level breakdown of cases, deaths, and population
- **Cross-Filtering** – All visuals update dynamically based on slicer selection

## 🛠️ Tools Used

- **Power BI Desktop**
- **DAX** (for CFR% and Infection Rate% measures)
- **Data Source:** [Our World in Data - COVID-19 Dataset](https://ourworldindata.org/covid-cases)

## 📊 Key Measures (DAX)

```dax
CFR = DIVIDE(SUM('owid-covid-data'[total_deaths]), SUM('owid-covid-data'[total_cases]))

InfectionRate = DIVIDE(SUM('owid-covid-data'[total_cases]), SUM('owid-covid-data'[population]))
```

## 🎨 Design

The dashboard follows a clean **black & red theme** for high contrast and visual impact, making key metrics easy to read at a glance.

## 📁 How to Use

1. Download the `.pbix` file from this repository
2. Open it in Power BI Desktop
3. Use the **Continent slicer** to filter data by region
4. Explore trends, comparisons, and country-level details

## 👤 Author

**Shaik Thamkin Banu**

---
⭐ If you found this useful, feel free to star this repository!
