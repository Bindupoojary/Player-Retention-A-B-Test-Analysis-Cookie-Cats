# Player Retention & A/B Test Analysis – Cookie Cats 🎮📊

## Overview
This project analyzes player engagement and retention for a casual mobile game using a publicly available **Cookie Cats** dataset.  
The goal is to evaluate the impact of a gameplay design change (progression gate placement) on player behavior and long-term retention using product analytics and A/B testing.

This project is designed to reflect the responsibilities of a **Product Data Analyst (Gaming)** role.

---

## Problem Statement
The game team introduced a progression gate at different levels to understand its impact on player experience.  
Players were split into two groups:
- **gate_30**: Progression gate at level 30  
- **gate_40**: Progression gate at level 40  

The objective was to determine whether moving the gate affects:
- Player engagement
- Short-term retention (Day 1)
- Long-term retention (Day 7)

---

## Dataset
- **Source**: Public Cookie Cats dataset
- **Granularity**: Player-level data

### Key Columns
- `userid` – Unique player identifier  
- `version` – Experiment group (gate_30, gate_40)  
- `sum_gamerounds` – Total number of game rounds played  
- `retention_1` – Day 1 retention indicator  
- `retention_7` – Day 7 retention indicator  

---

## Analysis Performed
- Exploratory data analysis and data quality checks  
- Player engagement analysis using total game rounds  
- Retention analysis (Day 1 and Day 7 retention rates)  
- A/B test evaluation using statistical testing  
- Product-level insights and recommendations  

---

## Tools & Technologies
- **Python**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy
- **Jupyter Notebook**

---

## Key Insights
- Player engagement is comparable across both gate versions.
- Gate placement at level 40 shows **better Day-7 retention**.
- The difference in long-term retention between the two versions is statistically significant.
- Moving the progression gate does not negatively impact early player engagement.

---

## Recommendation
Based on improved long-term retention and comparable engagement levels, moving the progression gate from level 30 to level 40 is recommended to enhance player retention without harming early gameplay experience.

---

## Files in This Repository
- `Cookie_Cats_Retention_Analysis.ipynb` – Main analysis notebook  
- `cookie_cats.csv` – Dataset used for analysis  
- `README.md` – Project overview and insights  

---

## Notes
This project demonstrates how data-driven experimentation and product analytics can guide gameplay design decisions in casual mobile games.
