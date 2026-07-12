# 🚀 Investment Opportunities in the Global Space Economy

![Investment Ranking](images/top15.png)

A data-driven investment analysis project exploring publicly listed companies across the global space economy.

This project builds a multi-factor investment framework by combining financial indicators with industry-specific exposure to identify attractive long-term investment opportunities.

---

# Project Overview

The global space economy is expanding rapidly, driven by satellite communications, launch services, earth observation, defence technologies and supporting infrastructure.

Rather than evaluating companies using a single financial metric, this project develops a transparent scoring model that combines multiple dimensions of business quality and investment attractiveness.

The analysis covers companies from several sectors including:

- Applications
- Infrastructure
- Technology
- Industrial
- Defense

---

# Objectives

The project aims to answer the following questions:

- Which publicly listed companies have the strongest exposure to the space economy?
- Which companies demonstrate the strongest financial performance?
- How can multiple financial indicators be combined into a practical investment ranking?
- Which companies appear most attractive based on a systematic scoring framework?

---

# Dataset

The dataset contains publicly listed companies participating in the global space economy.

For each company, the dataset includes:

- Company information
- Industry classification
- Revenue
- Revenue growth
- Profit margin
- Market valuation
- Beta (market risk)

Financial data are converted into a common USD basis for comparison.

---

# Project Structure

```
Investment_Opportunities_in_the_Space_Economy/

│
├── data/
│   ├── space_economy.db
│   ├── companies.csv
│   └── financials.csv
│
├── notebooks/
│   ├── 01_Data_Collection.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Industry_Analysis_using_SQL.ipynb
│   └── 04_Investment_Opportunities_in_the_Space_Economy.ipynb
│
├── README.md
└── requirements.txt
```

---

# Methodology

The project consists of four stages.

## 1. Data Collection

- Collect company information
- Gather financial data
- Build the SQLite database

---

## 2. Data Cleaning

- Handle missing values
- Standardise currencies
- Calculate financial metrics
- Merge datasets

---

## 3. Industry Analysis

SQL is used to explore:

- Sector distribution
- Largest companies
- Most profitable companies
- Revenue rankings
- Industry characteristics

---

## 4. Investment Framework

A composite Investment Score is developed using six factors.

| Factor | Description |
|---------|-------------|
| Space Economy Exposure | Degree of participation in the space economy |
| Company Size | Log-normalised annual revenue |
| Revenue Growth | Winsorised revenue growth |
| Profitability | Profit margin |
| Valuation | Price-to-Sales ratio |
| Market Risk | Beta |

All factors are normalised to a common 0–1 scale before applying weighted scoring.

---

# Technologies Used

- Python
- Pandas
- NumPy
- SQLite
- Matplotlib
- Jupyter Notebook

---

# Visualisations

The project includes:

- Sector distribution
- Revenue growth vs profitability bubble chart
- Top investment opportunities ranking

---

# Key Findings

The analysis suggests that companies with balanced performance across multiple financial dimensions generally achieve the strongest Investment Scores.

Rather than relying on a single indicator, combining industry exposure, company size, growth, profitability, valuation and market risk provides a more comprehensive investment assessment.

---

# Future Improvements

Possible extensions include:

- Free cash flow analysis
- Debt and leverage ratios
- Historical price volatility
- Analyst forecasts
- Dynamic weighting methods
- Machine learning models

---

# Disclaimer

This project is for educational purposes only and should not be interpreted as financial or investment advice.


## Author

**Binyu Xie**

BSc Mathematics

Imperial College London

Interested in Data Analytics, Quantitative Finance and Technology.