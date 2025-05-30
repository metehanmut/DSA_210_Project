# DSA_210_Project: Turkey Cinema and Economy

## Project Topic
**"The Effect of the Economy of Turkey on Movie Theater Attendance"**

This project analyzes how macroeconomic indicators—GDP and inflation—affect annual movie theater attendance in Turkey.

We explore whether people spend more on entertainment during economic prosperity and cut back during downturns, testing this hypothesis using data from 2000–2023.

---

## Datasets Used

1. **Turkey Cinema Data (2000–2023)**
   - Source: [Kaggle - Turkey Cinema Dataset](https://www.kaggle.com/datasets/alimuratsargl/turkey-cinema-data-2000-2023)
   - File: `Turkey_Cinema_Data_(2000 - 2023).csv`
   
2. **Inflation Rate Data (2000–2023)**
   - Source: [MacroTrends - Turkey Inflation](https://www.macrotrends.net/global-metrics/countries/TUR/turkey/inflation-rate-cpi)
   - File: `Turkey-Inflation-Rate-Annual-Change-2025-05-30-22-06.csv`

3. **GDP Data**
   - Source: [World Bank - Turkey GDP](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD?locations=TR)
   - File: `API_NY.GDP.MKTP.CD_DS2_en_csv_v2_19294.csv`

All data was merged on the common key: **Year**.

---

## Methods Applied:

1. **Data Cleaning & Transformation**
   - Cleaned inflation format
   - Formatted GDP values
   - Aligned all datasets by year (2000–2023)

2. **Exploratory Data Analysis (EDA)**
   - Plotted total audience, GDP, and inflation over time
   - Scatter plots for GDP vs Audience, Inflation vs Audience
   - Correlation matrix

3. **Hypothesis Testing**
   - Pearson correlation between GDP and audience
   - P-value calculation

4. **Machine Learning**
   - Linear Regression with standardized GDP and inflation data
   - Evaluation using RMSE and R²

---

## Key Findings

- **GDP-Audience Correlation**: 0.626
- **P-value**: 0.0011 (statistically significant)
- **RMSE**: ~13.4 million
- **R² Score**: 0.392

---

## Conclusion

This analysis reveals a **significant and positive relationship** between GDP and movie theater attendance in Turkey from 2000 to 2023. With a correlation coefficient of 0.626 and a p-value of 0.0011, the hypothesis is supported: **economic growth correlates with increased entertainment spending**.

The linear regression model also showed moderate predictive strength (R² = 0.392), suggesting GDP and inflation are useful—but not exhaustive—predictors of cinema behavior. From a sociocultural standpoint, these findings may indicate that Turkish audiences are sensitive to macroeconomic conditions when allocating budget for entertainment.
