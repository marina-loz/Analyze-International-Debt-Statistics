# 🌍 World Bank International Debt Analysis

## 📝 Objective
In this project, the goal is to analyze international debt data provided by The World Bank. The dataset contains debt information (in USD) for developing countries across various categories. The aim is to answer key questions related to debt and repayments of different countries.

## ❓ Key Questions
- How many distinct countries are present in the dataset?
- Which country has the highest amount of debt?
- Which country has the lowest amount of principal repayments?

## 📊 Data
- **international_debt** table: Contains details about countries and their respective debt indicators.
  - **Columns**:
    - `country_name`: Name of the country.
    - `country_code`: Code representing the country.
    - `indicator_name`: Description of the debt indicator.
    - `indicator_code`: Code representing the debt indicator.
    - `debt`: Value of the debt indicator in USD.

## 🧠 Approach
1. **Distinct Countries**: Identified the total number of unique countries in the dataset.
2. **Highest Debt**: Found the country with the highest total debt by summing all debt values for each country.
3. **Lowest Repayments**: Determined the country with the lowest principal repayment using the indicator for external debt repayments.

## 📈 Results
- **Total Distinct Countries**: 124.
- **Country with Highest Debt**: China with $285.79 billion.
- **Country with Lowest Repayments**: Timor-Leste with $825,000 in repayments.

## 🚀 Conclusion
This analysis provides a high-level overview of the debt owed by developing countries, identifying the countries with the highest debt burden and the smallest repayment amounts.

## 🛠️ Tools & Libraries
- **SQL**: Querying and analyzing the dataset
