# cape-point-trend-analysis
Timeseries trend analysis of methane and CO2 concentrations at Cape Point using R

# Cape Point Methane & CO2 Trend Analysis 🌍

This R-based analysis evaluates long-term atmospheric methane (CH₄) and carbon dioxide (CO₂) concentrations at Cape Point, South Africa. It applies Mann-Kendall trend testing and visualizes changes over time using openair, ggplot2, and plotly.

## 📊 Features

- Time-series interpolation and cleaning
- Mann-Kendall trend testing (1994–2019)
- Trend plots with Theil-Sen estimators
- Interactive bar charts with confidence lines
- Data preprocessing using `signal::interp1` and `openair`

## 🧰 Technologies Used

- R
- Packages: `openair`, `trend`, `signal`, `plotly`, `ggplot2`, `lubridate`, `dplyr`

## 📂 Data Sources

CH₄ and CO₂ CSV files recorded at Cape Point atmospheric research station, formatted with timestamp and concentration values.

## 🧪 How to Run

1. Install the required R packages (see script).
2. Place your `.csv` files in the correct directory.
3. Run the script to generate plots and annual trend z-scores.

## 👨🏽‍🔬 Author

Project by Bongani Mkhize — passionate about climate analytics and environmental data science.


