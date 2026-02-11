# Climate Vulnerability Assessment for Global Agricultural Systems  
**FRE 521D – Data Analytics in Climate, Food, and Environment**  
University of British Columbia | Winter 2026  

**Team:** Adam Dawson, Ethan Ogrodniczuk, Julian Oldham (Group 4)

---

## Project Overview

This project evaluates climate vulnerability in global agriculture over the period **2015–2023**, integrating FAO crop production data with Open-Meteo weather data.  

The analysis addresses three core research questions:

1. **Which major cereal crops are most vulnerable to climate variability?**  
2. **Which countries demonstrate agricultural resilience despite climate stress?**  
3. **Where are production trends stagnating or declining, and what are the projected risks?**

The objective is to generate data-driven insights to support climate adaptation and food security policy decisions.

---

## Key Findings

- **Soybeans** are the most climate-sensitive crop, showing the strongest negative response to extreme heat and precipitation variability.  
- **High-income countries**, particularly Canada, exhibit strong agricultural resilience despite substantial climate variability, largely associated with higher input intensity (fertilizer, irrigation).  
- **Regional divergence exists in production trends**, with maize yields declining in parts of Central America, indicating elevated risk of future production shortfalls under continued climate pressure.

---

## Data & Methodology

**Data Sources**
- FAO country-level crop yield and production data  
- Open-Meteo daily weather data  

**Methods**
- Two-Way Fixed Effects regressions (country + year)  
- Climate variability metric construction (extreme heat, GDD, precipitation SD)  
- Resilience classification using yield variability and climate variability  
- Region- and crop-specific linear trend analysis with forward projections  

Full technical documentation is available in:
- `report.pdf`
- `presentation.pdf`

---


This project was completed as part of **FRE 521D: Data Analytics in Climate, Food, and Environment**, and demonstrates integration of database construction, ETL pipelines, econometric analysis, and policy-focused communication.
