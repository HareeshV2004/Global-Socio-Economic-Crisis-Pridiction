 # 🌍 Global Socio-Economic Stress Early Warning System

**Statistical Risk Analytics Across 188 Countries**

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)

---

## 🔍 Problem Statement

Economic crises are rarely sudden. They are typically preceded by **persistent macro-economic stress signals**:

- Sustained inflation
- Energy price volatility
- Structural divergence between regions

**Policymakers, analysts, and institutions need early warning indicators, not post-hoc explanations.**

This project develops a **statistical early warning system** that quantifies socio-economic stress across **188 developed and developing countries** using publicly available macro-economic indicators.

> **Note**: This project focuses on **risk signal detection and monitoring** rather than supervised "crisis prediction" in the absence of labeled crisis events.

---

## 🤔 Why This Problem Is Hard

| Challenge | Description |
|-----------|-------------|
| ❌ No ground-truth labels | No validated "crisis onset" labels across countries |
| 🌍 Heterogeneous manifestation | Economic stress varies by region |
| 📊 Noisy data | Indicators are non-stationary and temporally lagged |
| 🚫 ML limitations | Pure machine learning inappropriate without targets |
| 🏦 Real-world alignment | Mirrors World Bank/IMF statistical threshold approaches |

---

## 📊 Data Sources

- **Country-level inflation indicators**
- **Energy price and consumption metrics**
- **Temporal macro-economic data** (multiple years)
- **Coverage**: **188 countries**

*Data sourced from publicly available global economic datasets*

---

## 🛠️ Methodology

### 1. **Data Cleaning & Harmonization**
-Standardized indicators across countries/time periods

-Handled missing values and temporal gaps

-Aligned to comparable economic timelines

