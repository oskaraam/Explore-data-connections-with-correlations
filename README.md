# 📊 Project: Exploring Customer Behavior Factors in NovaRetail+

[![Python](https://img.shields.io/badge/Language-Python-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)](https://pandas.pydata.org/)
[![SciPy](https://img.shields.io/badge/Library-SciPy-yellow.svg)](https://scipy.org/)

## 📝 Project Description
This repository contains an **exploratory correlational analysis** developed for **NovaRetail+**, a leading e-commerce platform in Latin America with millions of users. Utilizing a dataset of 15,000 customer records, this study aims to answer a strategic question for the **Growth and Retention** team:

> 🎯 **Which customer behavior factors are most strongly associated with the annual revenue generated?**

*Methodological Note:* This analysis identifies key relationships and numerical patterns between variables or segments, but under no circumstances does it establish or prove relations of cause and effect (**Correlation ≠ Causality**).

---

## 🔑 Key Findings & Numerical Evidence

### 1️⃣ Linear and Monotonic Correlation Analysis (Pearson / Spearman)
Evaluating the relationships between continuous variables and mass attraction metrics within the sales funnel:
* **Targeted Advertising Spend vs. Monthly Visits ($r = 0.58$ Pearson / $0.56$ Spearman):** Shows a moderate positive correlation. Users with a higher number of monthly visits have been more exposed to targeted advertising, validating the effectiveness of campaigns in driving traffic.
* **Monthly Visits vs. Monthly Purchases ($r = 0.35$ Pearson / $0.33$ Spearman):** There is a moderate positive relationship. Frequency of access opens up transactional opportunities, though not in a strictly linear fashion.
* **Targeted Advertising Spend vs. Monthly Purchases ($r = 0.21$ Pearson / $0.19$ Spearman):** Low positive correlation. This indicates that the advertising budget works well to attract visits, but its direct impact on

## 📁 Repository Structure
```text
├── S8 Student Version-Project-NovaRetail.ipynb   # Jupyter Notebook with documented code and analysis
├── README.md                                     # Main documentation and executive summary
└── LICENSE                                       # Project license
