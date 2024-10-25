# 💉 COVID-19 Vaccine Adverse Event Analysis

This project analyzes adverse events reported after the administration of COVID-19 vaccines, using data from the VAERS (Vaccine Adverse Event Reporting System). The goal is to identify patterns and trends that can support public health decision-making and optimize the management of vaccine-related side effects.

## 🎯 Project Objective

The primary goal is to analyze reports of adverse events associated with COVID-19 vaccines to generate actionable insights that support vaccination policy decisions and public health management.

## 🛠️ Methodology

### 📊 Data Source:

- Data was extracted from Kaggle's Vaccines Database obtained from VAERS, a public database that collects reports of adverse events related to vaccination in the United States.

### 🧹 Data Cleaning:

- Duplicates and irrelevant null values were removed.
- Key columns, including symptoms and patient demographics, were normalized and standardized.

### 💾 SQL Storage:

- Data was organized and managed in a SQL database to enable efficient and structured queries.

### 🔍 Queries and Analysis:

- SQL queries were performed to extract key data subsets, and Tableau was used for visual analysis and dashboard creation.

## 📉 Analyzed Hypotheses

1. **Prevalence of Symptoms by Gender**: Women are more likely to present adverse symptoms after vaccination compared to men.
2. **Mortality and Age**: Older patients are at greater risk of mortality following vaccination.
3. **Incidence in More Populated States**: States with higher populations tend to report more adverse events.

## 🔑 Key Insights

### 1. 👩‍⚕️ Prevalence of Symptoms by Gender:

- Women report a higher number of adverse symptoms, particularly in mild categories.

### 2. 🧓 Mortality and Age:

- Older individuals show a greater risk of severe symptoms and mortality, consistent with the initial hypothesis.

### 3. 🏙️ Incidence by State Population:

- More populous states report a higher number of adverse events, likely related to greater exposure and vaccine distribution.

## 💡 Recommendations

### 1. 📝 Standardization of Symptom Reporting and Coding:

- Implement a uniform method of symptom coding to ensure greater consistency in reports and improve data comparability.

### 2. 🔄 Reduction of Unstructured Text Fields:

- Minimize the use of free-text in reports to reduce errors and facilitate automated data analysis.

### 3. 🧑‍🤝‍🧑 Homogenization of Demographic Data:

- Collect additional information on comorbidities and medical history to allow more precise analysis of risk factors by population group.

### 4. 🧪 Monitoring of Specific Vaccine Lots:

- Conduct additional monitoring of vaccine lots with higher reports of adverse events to ensure consistency in their safety and quality.

## 📊 Visualizations

The analysis included key visualizations developed in Tableau:

1. **Prevalence of Symptoms by Gender**
2. **Mortality and Age**
3. **Symptom Distribution by State**
4. **Analysis of Vaccine Lots**

These visualizations help to understand the relationship between symptoms, gender, age, geographic state, and vaccine lots, providing a comprehensive view of the distribution and severity of adverse effects.

## 🏁 Conclusion

This analysis of adverse events associated with COVID-19 vaccination identifies key trends in symptoms, mortality, and geographic distribution. The resulting recommendations aim to improve the quality of adverse event reports and help reduce risks associated with vaccination in specific populations.
