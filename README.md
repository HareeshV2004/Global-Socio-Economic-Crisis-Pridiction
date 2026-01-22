 # Global Socio-Economic Stress Early Warning System

**Statistical Risk Analytics Across 188 Countries**

 

---

##  Problem Statement

Economic crises are rarely sudden. They are typically preceded by **persistent macro-economic stress signals**:

- Sustained inflation
- Energy price volatility
- Structural divergence between regions

**Policymakers, analysts, and institutions need early warning indicators, not post-hoc explanations.**

This project develops a **statistical early warning system** that quantifies socio-economic stress across **188 developed and developing countries** using publicly available macro-economic indicators.

> **Note**: This project focuses on **risk signal detection and monitoring** rather than supervised "crisis prediction" in the absence of labeled crisis events.

---

##  Why This Problem Is Hard

| Challenge | Description |
|-----------|-------------|
|  No ground-truth labels | No validated "crisis onset" labels across countries |
|  Heterogeneous manifestation | Economic stress varies by region |
|  Noisy data | Indicators are non-stationary and temporally lagged |
|  ML limitations | Pure machine learning inappropriate without targets |
|  Real-world alignment | Mirrors World Bank/IMF statistical threshold approaches |

---

##  Data Sources

- **Country-level inflation indicators**
- **Energy price and consumption metrics**
- **Temporal macro-economic data** (multiple years)
- **Coverage**: **188 countries**

*Data sourced from publicly available global economic datasets*

---

##  Methodology

### 1. **Data Cleaning & Harmonization**
-Standardized indicators across countries/time periods

-Handled missing values and temporal gaps

-Aligned to comparable economic timelines


### 2. **Feature Engineering**
-Rolling Z-scores (deviation from historical norms)

-Lag features (delayed economic effects)

-Regional aggregation (comparative analysis)



### 3. **Risk Signal Construction**
-Composite stress signals from standardized indicators

-Focus on sustained deviations (not short-term shocks)

-No classification (no validated crisis labels)


### 4. **Visualization & Diagnostics**
-Region-wise stress trend analysis

-Cross-country economic divergence

-Temporal early warning pattern plots


---

##  Key Insights

- **Developing economies**: Higher volatility + persistence in stress signals
- **Energy shocks**: Disproportionately affect inflation-sensitive regions
- **Z-score deviations**: More informative than point anomalies
- **Early warnings**: Several regions show patterns without formal crises

---

##  Assumptions & Limitations

- Signals are **relative**, not absolute crisis indicators
- Z-score normalization assumes **historical stability**
- **Excludes**: Political, social, institutional factors
- Best for **monitoring/prioritization**, not deterministic forecasting

---

##  Practical Applications

- **Macro-economic risk monitoring dashboards**
- **Policy prioritization & early intervention**
- **Economic vulnerability research support**

---

##  Future Work

-  Additional indicators (employment, debt, trade)
-  Validate against historical crisis timelines
-  Probabilistic risk bands (vs fixed thresholds)
-  Real-time monitoring dashboard

---

## Tech Stack

| Category | Tools |
|----------|-------|
| **Language** | Python |
| **Data** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Development** | Jupyter Notebook |

---

## Quick Start

```bash
git clone https://github.com/yourusername/socio-economic-stress-system.git
cd socio-economic-stress-system
pip install -r requirements.txt
jupyter notebook analysis.ipynb
