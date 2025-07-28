# Climate Change Analysis: Temperature, Sea Level, and CO₂ Trends (1990–2021)

## Project by: Zach Riethof

### Central Research Question:
**Which countries and cities in the world have experienced the most significant temperature increases due to global warming and climate change over the last three decades?**

---

## Datasets Used:

### 1. Daily Temperature of Major Cities
- Source: [Kaggle](https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities)
- Description: Daily temperatures from major cities worldwide over 20+ years.
- Format: CSV
- Columns: `Region`, `Country`, `State`, `City`, `Month`, `Day`, `Year`, `AvgTemperature`
- Rows: 2,906,329

### 2. Global Sea Level (1993–2021)
- Source: [Kaggle](https://www.kaggle.com/datasets/kkhandekar/global-sea-level-1993-2021)
- Description: Sea level data across global oceans from 1993 to 2021.
- Format: CSV
- Columns include: `Year`, `GMSL_noGIA`, `GMSL_GIA`, `SmoothedGSML_GIA`, etc.
- Rows: 1,049

### 3. Carbon Dioxide Emissions of the World (1990–2018)
- Source: [Kaggle](https://www.kaggle.com/datasets/ankanhore545/carbon-dioxide-emissions-of-the-world)
- Description: CO₂ emissions by country across multiple sectors from 1990 to 2018.
- Format: CSV
- Columns: `Country`, `Data Source`, `Sector`, `Gas`, `Unit`, `1990` through `2018`
- Rows: 196

- ## Methodology & Approach:

1. **Data Wrangling Functions:**
   - `dailyTemps()`: Loads and processes city temperature data.
   - `seaLevel()`: Processes sea level trends data.
   - `carbonDioxide()`: Loads CO₂ emissions data.

2. **Temperature Trend Analysis:**
   - Identify countries and cities with the highest average temperature increases over time using `dailyTemps()`.

3. **Correlation and Evidence Gathering:**
   - Analyze whether rising temperatures in those locations align with trends in:
     - CO₂ levels using `carbonDioxide()`
     - Sea level changes using `seaLevel()`

4. **Ranking Impact:**
   - `greatestTemperature()`: Generates a ranked list of the top 10 most affected countries or cities based on rising temperatures.

---

##  Project Goals:
- Visualize and quantify the impact of climate change across various global regions.
- Understand interrelations between temperature, greenhouse gas emissions, and sea level rise.
- Provide an evidence-based approach to climate change impact assessment.

---

##  Citations:
- [Daily Temperature of Major Cities](https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities)
- [Global Sea Level (1993–2021)](https://www.kaggle.com/datasets/kkhandekar/global-sea-level-1993-2021)
- [Carbon Dioxide Emissions of the World (1990–2018)](https://www.kaggle.com/datasets/ankanhore545/carbon-dioxide-emissions-of-the-world)

---

##  Notes:
- Data is in `.csv` format and sourced from publicly available Kaggle repositories.
- This project is currently in development; please reach out with feedback or suggestions.
