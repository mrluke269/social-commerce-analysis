# E-Commerce: Customer Behavior & Engagement Analysis

## Project Definition

This project analyzes customer behavior in digital commerce to Drive Revenue and Engagement

---

## Project Objectives

### 1. Project Goal
> Analyze user behavior on a traditional e-commerce platform using the REES46 dataset to:
- Identify the key behavioral drivers of high customer value.
- Understand drop-offs in the user funnel (view → cart → purchase).
- Segment users based on value, engagement, and session patterns.
- Derive actionable insights to optimize product placement, timing, and conversion strategies.

### 2. Core Questions
> How do users typically move through the funnel from view → cart → purchase?
> What distinguishes high-value vs. low-value users in terms of:
  -  Frequency and timing of actions
  -  Revenue behavior
  -  Latent behavioral patterns
> What behavioral signals indicate likely conversion or churn?

> How do time delays between steps impact customer value?

---

## Datasets Used

REES46 Customer Model | 112K+ rows of user-level behavioral features 

---

## Tools & Technologies

- Python: `pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`
- UMAP or PCA for latent feature exploration
- XGBoost or LightGBM for predictive modeling
- Jupyter Notebooks for EDA and documentation
- Power BI for dashboard visualizations


---

## 🗂️ Project Structure
```ecommerce-behavior-analysis/
├── data/
│   ├── raw/               
│   ├── processed/          # Cleaned versions
│   └── external/           # data dictionary
├── notebooks/
│   ├── 01_data_exploration.ipynb       # Basic stats, missing values, key features
│   ├── 02_feature_selection.ipynb      # Select useful columns, remove noise
│   ├── 03_funnel_analysis.ipynb        # View → Cart → Purchase patterns
│   ├── 04_customer_segmentation.ipynb  # Group by value, behavior, latent vectors
│   ├── 05_time_analysis.ipynb          # Session & inter-purchase timings
│   ├── 06_latent_factors.ipynb         # Interpret latent features (if possible)
│   ├── 07_modeling.ipynb               # Predict high-value or churn risk
│   └── 08_insights_recommendations.ipynb
├── visualizations/        # Saved graphs, charts for Power BI
├── reports/               # Summary findings
└── README.md


```

---

Created by **Luke Mai**  
🔗 [LinkedIn](https://www.linkedin.com/in/lukemai)
📂 [GitHub Profile](https://github.com/mrluke269)

