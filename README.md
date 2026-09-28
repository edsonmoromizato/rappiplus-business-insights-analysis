# 📊 RappiPlus: E-Commerce Business Insights & A/B Testing Analysis

An end-to-end data analytics project evaluating financial performance, marketing efficiency, user cohort retention, and checkout conversion through statistical hypothesis testing and interactive Power BI visualizations.

---

## 🛠️ Project Architecture & Technologies
* **Python (Pandas, Statsmodels, SciPy):** Data cleaning, ETL pipelines, cohort aggregation, and Two-Proportion Z-Testing.
* **Power BI:** Executive dashboard, relational modeling, and interactive drill-through views (`.pbix`).
* **Jupyter Notebook:** Fully documented analysis with executable code and business findings.

---

## 📁 Repository Artifacts

* `rappiplus_business_insights_analysis.ipynb` — Primary analysis notebook (code, pipeline & statistical tests).
* `rappiplus_ecommerce_sales_conversion_dashboard.pbix` — Interactive Power BI report file.
* `orders_clean.csv`, `catalog_clean.csv`, `marketing_clean.csv`, `experiment_checkout_ui.csv` — Processed datasets.
* [🔗 External Cloud Backup / Google Drive Link](https://drive.google.com/drive/folders/1kTwJwe_Lo-Z6yNCp6JFkJ--7V5PImyfR?usp=sharing)

---

## 📈 Executive Summary & Key Findings

### 1. Financial & Marketing Overview
* **Revenue & Profitability:** Generated **USD $51.99M** in total revenue and **USD $8.86M** in net profit.
* **Top Category:** *Electronics* drove the highest revenue and profit margins across all segments.

### 2. A/B Experimentation (Checkout Redesign)
* **Hypothesis:** Tested whether a redesigned checkout UI improves conversion compared to the baseline control.
* **Statistical Result:** Two-Proportion Z-Test yielded a $p$-value $\ge 0.05$.
* **Decision:** **Fail to reject $H_0$**. The new checkout interface did not produce a statistically significant improvement.

### 3. User Retention
* **Cohort Analysis:** Maintained a **100% retention rate** across the first 3 weeks post-registration.

---

## 💡 Strategic Recommendations

1. **Capitalize on Core Drivers:** Bundle *Electronics* with *Home* and *Fashion* products to lift Average Order Value (AOV).
2. **Revert Checkout Iteration:** Roll back the tested checkout UI and explore alternative UX friction points before launching new tests.
3. **Sustain Retention:** Leverage strong initial cohort retention to launch cross-selling campaigns within the first month.
