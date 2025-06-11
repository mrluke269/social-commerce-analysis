# Social vs. Traditional Commerce: Customer Behavior & Engagement Analysis

## Project Definition

This project analyzes customer behavior across two major digital commerce environments:
1. **Traditional e-commerce** (REES46 dataset)
2. **Social commerce** (Instagram and TikTok engagement datasets)

As social commerce channels like TikTok Shop and Instagram Shopping emerge, it’s important for businesses to understand how customer behavior differs across digital platforms. This analysis uncovers platform-level engagement trends and user-level behavioral patterns, helping inform better channel and content strategies.

---

## Project Objectives

### 1. Behavioral Comparison
> Compare overall engagement behavior across traditional e-commerce and social platforms.

- Measure how customers interact on e-commerce websites (views, clicks, purchases) vs. social media (likes, replies, comments).
- Visualize engagement structure differences.

### 2. Audience Behavior Insights
> Explore user-level engagement patterns and identify what drives value on each platform.

- **Traditional e-commerce**:
  - Identify high-value vs. low-value user profiles
  - Analyze purchase funnel drop-offs and session behavior
  - Explore repeat visits, purchase frequency, and time between actions

- **Social commerce (Instagram/TikTok)**:
  - Analyze comment content, likes, replies, and mentions
  - Explore which content generates the most interaction
  - Derive potential content strategies from user engagement

---

## Datasets Used

| Platform | Dataset | Description |
|----------|---------|-------------|
| **Traditional E-commerce** | REES46 Customer Model | 112K+ rows of user-level behavioral features (clicks, purchases, time steps, aggregates) |
| **Instagram** | Bright Data Sample | 1K comment-level rows with comment text, likes, replies, hashtags |
| **TikTok** | Bright Data Sample | 1K comment-level rows with user info, likes, replies, comment text |


---

## Tools & Technologies

- Python: `pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`
- Jupyter Notebooks for EDA and documentation
- Power BI for dashboard-style visualizations 
- Git & GitHub for version control

---

## 🗂️ Project Structure
```social-commerce-analysis/
├── data/
│ ├── raw/
│ │ ├── traditional/ # REES46 source file (via Google Drive)
│ │ └── social/ # Instagram + TikTok raw CSVs
│ ├── processed/ # Cleaned datasets
│ └── external/ # Metadata (e.g., REES46 data dictionary)
├── notebooks/
│ ├── 01_data_exploration.ipynb
│ ├── 02_data_cleaning.ipynb
│ ├── 03_data_integration.ipynb
│ ├── 04_analysis_traditional.ipynb
│ ├── 05_analysis_social.ipynb
│ ├── 06_comparative_analysis.ipynb
│ └── 07_insights_recommendations.ipynb
├── reports/ # Summary findings
├── visualizations/ # Exported charts and images
├── requirements.txt
└── README.md

```

---

## Key Outputs

- Cleaned and documented datasets
- Visuals comparing engagement across platforms
- Insights on high- and low-value customer behavior
- Actionable recommendations for content and platform strategy

- ### 🔍 Traditional E-Commerce Analysis Summary

- ✅ Funnel metrics reveal that most drop-offs occur between product views and cart additions (20.3% conversion).
- ✅ High-value users act faster and more consistently, making them prime targets for retention strategies.
- ✅ Engagement is quick at the viewing stage but slows before purchase, indicating a need for better early-funnel optimization.
- ✅ Behavior segments help isolate profitable vs. loss-making user patterns.


---

## Business Impact

This project simulates how an analyst can support a brand deciding where and how to grow their digital sales. With insights from both traditional and social commerce environments, businesses can:
- Design better content for social channels
- Identify high-value customers
- Tailor strategies by channel

---

## 🙋 About the Author

Created by **Luke Mai**  
🔗 [LinkedIn](https://www.linkedin.com/in/lukemai)
📂 [GitHub Profile](https://github.com/mrluke269)

