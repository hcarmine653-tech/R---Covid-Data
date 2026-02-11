# COVID‑19 Outcomes Across Economic Groups: A Cross‑Country Data Analysis
This project explores how COVID‑19 case and death trends varied across countries with different economic capacities. Using publicly available COVID‑19 data, the analysis examines lockdown timing, case trajectories, data quality issues, and the relationship between GDP per capita and COVID‑19 outcomes. The project demonstrates skills in data cleaning, feature engineering, visualisation, and analytical storytelling using R.

## 📌 Project Overview
This analysis investigates four key areas:
- Daily COVID‑19 case trends across multiple countries
- Impact of lockdown timing on case trajectories
- Data quality issues, including missing or anomalous values
- Relationship between GDP per capita and COVID‑19 outcomes, using custom‑engineered economic groupings

## 🛠️ Tools & Technologies
- R Studio
- R Markdown for reproducible reporting
- ggplot2 for visualisation
- dplyr for data wrangling
- here for reproducible file paths

## 🔍 Key Steps in the Analysis
1. Data Cleaning & Preparation
- Standardised column names
- Converted dates to proper formats
- Identified and removed anomalous values (e.g., sudden zeros surrounded by thousands)
- Created cumulative and daily metrics
- Joined COVID‑19 data with country lockdown dates and worldwide vaccine data
2. Handling Data Anomalies
- Detected 40+ dates where new cases and deaths were both zero despite high surrounding values
- Investigated country‑specific anomalies (e.g., Iran’s sudden drop to zero)
- Removed or corrected rows unlikely to represent real epidemiological data
3. Lockdown Impact Analysis
- Added vertical markers for each country’s first lockdown date
- Compared case trajectories before and after restrictions
- Identified patterns such as delayed declines or second waves
4. GDP‑Based Grouping
- Calculated the mean GDP per capita across all countries
- Created a new column classifying each country as “Higher” or “Lower” GDP
- Compared COVID‑19 outcomes across economic groups

## 📊 Visualisations
The project includes several plots, such as:
- Daily new cases by country
- Lockdown timing vs. case trajectories
- GDP group comparisons
- Highlighted anomalies in reporting
All plots are generated using ggplot2 and included in the knitted report.

## 📈 Key Insights
- Most countries peaked in late March to early April, with declines following lockdowns.
- Higher‑GDP countries did not always experience better outcomes — suggesting policy timing and compliance played major roles.
- Data quality issues were common and required careful cleaning to avoid misleading conclusions.
- Second waves often aligned with premature easing of restrictions.

## 📚 Future Improvements
- Incorporate vaccination data
- Add mobility or policy‑stringency indices
- Build predictive models for case trajectories
- Expand dataset to include more countries



