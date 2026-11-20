# ☀️ Egypt Solar Energy Analysis
### Analyzing the Impact of Heat, Dust, and Weather Conditions on Solar PV Performance Across 27 Egyptian Governorates

<p align="center">
  <strong>NTI Graduation Project | Data Analysis</strong>
</p>

---

## 📌 Project Overview

This project focuses on analyzing solar energy performance across **27 governorates in Egypt**, investigating how environmental factors such as heat, dust accumulation, rainfall, and cloud coverage affect photovoltaic (PV) system efficiency and energy production.

The project transforms raw data into meaningful insights through data cleaning, SQL analysis, and interactive dashboards developed using Microsoft Excel and Power BI.

The main goal is to understand regional variations in solar energy yield, quantify potential performance losses, and identify opportunities to improve solar panel efficiency through better cleaning strategies and environmental analysis.

## 🎯 Project Objectives

- Analyze solar energy performance across 27 Egyptian governorates.
- Evaluate the impact of soiling (dust accumulation) on PV energy production.
- Measure solar yield losses associated with environmental conditions.
- Investigate the relationship between rainfall, cloud coverage, temperature, and solar performance.
- Analyze cleaning frequency and its potential impact on system efficiency.
- Compare solar yield rankings before and after considering soiling losses.
- Validate solar energy estimates by comparing NASA and PVGIS datasets.
- Present actionable insights through interactive dashboards.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data cleaning and preprocessing |
| SQL | Data querying and analysis |
| Microsoft Excel | Data analysis and interactive dashboards |
| Power Query | Data transformation and preparation |
| Power Pivot | Data modeling and calculations |
| PivotTables | Data summarization and exploration |
| DAX | Measures and analytical calculations in Power BI |
| Power BI | Interactive visualization and reporting |

## 🔄 Project Workflow

The project follows an end-to-end data analysis workflow:

1. **Data Collection:** Gathering solar energy and environmental datasets.
2. **Data Cleaning:** Using Python to clean, prepare, and organize raw data.
3. **SQL Analysis:** Querying and analyzing structured data.
4. **Data Transformation:** Preparing and transforming datasets for analysis.
5. **Data Modeling:** Organizing data and creating analytical calculations.
6. **Dashboard Development:** Building interactive dashboards using Excel and Power BI.
7. **Insight Generation:** Identifying patterns, performance gaps, and environmental impacts.

## 📊 Excel Dashboard

The Excel dashboard provides an interactive analysis through three main sections.

### 1. Overview

- Average Daily Yield by Region.
- Average Daily Yield by Governorate.
- Best Performing Governorate.
- Yield Gap Percentage.
- Comparison of solar performance across regions.

### 2. Soiling & Cleaning

- Average Cleaning Frequency per Year.
- Soiling Loss Percentage.
- Governorate Ranking Before and After Soiling.
- Rank Changes caused by Soiling.
- Seasonal comparison of Yield with and without Soiling.
- Soiling Loss by Governorate.

### 3. Weather & Validation

- Average Cloud Loss.
- NASA vs. PVGIS Yield Comparison.
- Annual Rainfall Analysis.
- Average Maximum Temperature.
- Average Daylight Efficiency.
- Weather-related performance comparisons.

## 📈 Power BI Dashboard

The Power BI report provides a visually interactive experience with dedicated pages.

### 1. Landing Page

A main navigation page introducing the project and providing access to the different analytical sections.

### 2. Overview

- Best Performing Governorate.
- Heat Loss Percentage.
- Highest Global Horizontal Irradiance (GHI).
- Soiling Loss Percentage.
- Average Yield by Governorate.
- Relationship between GHI, Yield, and Soiling Loss.
- Governorate performance rankings.

### 3. Soiling & Cleaning

- Soiling Loss Percentage.
- Lost kWh per kWp per Year.
- Rainfall per Year.
- Monthly Rainy Days and Soiling Loss.
- Days Above 5% Soiling per Year by Governorate.
- Relationship between Annual Rainfall and Soiling Loss.

### 4. Cloud & Evaluation

Environmental analysis and solar model evaluation, including cloud-related losses and comparisons between NASA and PVGIS solar yield estimates.

## 🔍 Key Analytical Areas

The analysis focuses on answering important business questions:

- Which Egyptian governorates have the highest solar energy yield?
- How much energy production is potentially lost due to dust accumulation?
- Which governorates experience the highest soiling losses?
- Does rainfall have a noticeable relationship with soiling levels?
- How frequently should solar panels be cleaned in different regions?
- How do governorate rankings change when soiling is considered?
- How closely do NASA and PVGIS solar yield estimates compare?

## 📁 Project Structure

The repository contains the project datasets, analysis files, and dashboard deliverables.

```text
Egypt-Solar-Energy-Analysis/
│
├── Data/
│   ├── Raw/
│   └── Cleaned/
│
├── Python/
│   └── Data_Cleaning.ipynb
│
├── SQL/
│   └── SQL_Analysis.sql
│
├── Excel/
│   └── Solar_Energy_Analysis.xlsx
│
├── PowerBI/
│   └── Solar_Energy_Analysis.pbix
│
├── Screenshots/
│   ├── Excel_Overview.png
│   ├── Excel_Soiling.png
│   ├── Excel_Weather.png
│   ├── PowerBI_Landing.png
│   ├── PowerBI_Overview.png
│   └── PowerBI_Soiling.png
│
└── README.md
```

*Note: Folder and file names above represent a suggested organization. Adjust them to match the actual repository structure.*

## 🚀 How to Explore the Project

1. Clone or download this repository.
2. Open the Python notebook to explore the data cleaning process.
3. Review the SQL scripts to understand the data queries.
4. Open the Excel workbook to explore the interactive dashboards.
5. Open the Power BI `.pbix` file using Power BI Desktop to explore the interactive report.

## 💡 Project Value

This project demonstrates how multiple data analysis tools can be integrated into one workflow to transform raw environmental and solar energy data into meaningful insights.

It combines data preparation, querying, analytical modeling, and interactive visualization to support a better understanding of solar PV performance across different environmental conditions in Egypt.

---

## 👨‍💻 Author

**Moataz Abdelsalam**

Data Analysis | Excel | SQL | Python | Power BI

[LinkedIn](https://www.linkedin.com/in/moataz-abdelsalam-1a6270306/)

---

<p align="center">
  <strong>Egypt Solar Energy Analysis | NTI Graduation Project</strong>
  <br>
  Turning Data into Insights ☀️
</p>
