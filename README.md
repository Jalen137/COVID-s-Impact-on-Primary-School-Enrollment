# 📘 COVID's Impact on Primary School Enrollment

## Overview  
This project explores how the **COVID-19 pandemic affected primary school enrollment rates** in **low- and middle-income countries** from **2019 to 2022**. Using World Bank development indicators and regression analysis, we tested whether enrollment declined during the pandemic and what factors (like GDP per capita and education spending) were most closely associated with that change.

---

## 🔍 Research Question  
**How has the COVID-19 pandemic impacted primary school enrollment in low- and middle-income countries?**

---

## 🧪 Hypothesis  
Primary enrollment in low- and middle-income countries significantly decreased during the COVID-19 pandemic compared to 2018.

---

## 📁 Contents  
- `Merged_Dataset_2018_2022.xlsx`: Final cleaned dataset including dependent and independent variables  
- `Regression_Results_Table.docx`: Table of regression outputs formatted for poster  
- `Poster_Slides.pdf`: Final research poster for ECN 325  
- `summary_stats_table.docx`: Summary statistics for all key variables  
- `README.md`: Project description and documentation

---

## 📚 Data Sources  
All data were sourced from the World Bank’s **World Development Indicators** and one peer-reviewed journal article:

- The World Bank. (2023). *Primary school enrollment, net (% of primary school age children)* [SE.PRM.NENR]. Retrieved from https://data.worldbank.org/indicator/SE.PRM.NENR  
- The World Bank. (2023). *Government expenditure on education (% of GDP)* [SE.XPD.TOTL.GD.ZS]. Retrieved from https://data.worldbank.org/indicator/SE.XPD.TOTL.GD.ZS  
- The World Bank. (2023). *GDP per capita (current US$)* [NY.GDP.PCAP.CD]. Retrieved from https://data.worldbank.org/indicator/NY.GDP.PCAP.CD  
- Bundervoet, T., Dávalos, M. E., & Garcia, N. (2022). *The short-term impacts of COVID-19 on households in developing countries: An overview based on a harmonized dataset of high-frequency surveys.* *World Development, 153*, 105844. https://doi.org/10.1016/j.worlddev.2022.105844  

---

## 📈 Key Variables  

**Dependent Variable:**  
- Net Primary School Enrollment (%)

**Independent Variables:**  
- Education Expenditure (% of GDP)  
- ln(GDP per Capita)  
- Year Dummies (2019–2022, with 2018 as baseline)

---

## 🧮 Methodology  
- **Sample**: 102 low- and middle-income countries (2019–2022)  
- **Analysis**: OLS regression using STATA  
- **Key Finding**: Only education expenditure was statistically significant. Year dummies and GDP per capita were not.

---

## ✅ Key Takeaways  
- Enrollment fell after 2018, but the decline was **not statistically significant**  
- **Education spending** had a **positive, significant effect** on enrollment  
- Pandemic effects were likely shaped by deeper inequality and infrastructure issues  
- Investing in education can help countries build resilience for future crises

