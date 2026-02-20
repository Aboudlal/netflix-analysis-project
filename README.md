# 🎬 **Netflix Data Analysis — Beginner Project**
> Complete end-to-end data analysis project using Python, SQL, Power BI & Matplotlib.

## 📌 **Project Overview**
This project analyzes the Netflix titles dataset to understand:

- How Netflix’s content library has changed over time
- Which types of content dominate the platform
- What countries and ratings contribute the most
- What insights can guide business decisions for future investments

The project follows a full data workflow:

> **Data Cleaning → SQL Analysis → Visualization → Dashboard → Insights**

## 🛠️ **Tools & Technologies Used**
| Category | Tools |
|----------|--------|
| Programming | Python, pandas, Matplotlib |
| Databases | SQL, SQLite |
| BI & Reporting | Power BI |
| Environment | Jupyter Notebook / VS Code |

## 🧹 **Part 1 — Data Cleaning (Python / pandas)**
Data preparation tasks:

- Handle missing values (`director`, `country`)
- Convert `date_added` to datetime format
- Extract `year_added` from `date_added`
- Split `duration` into `duration_num` and `duration_type`
- Standardize text formatting
- Remove duplicates and validate data types

## 🗄️ **Part 2 — SQL Business Questions**
| Business Question | Answer / Insight |
|--------------------|------------------|
Movies vs TV Shows? | Movies dominate the platform |
Growth by Year? | Strong increase → peak in 2020 |
Top Countries? | 🇺🇸 USA, 🇮🇳 India, 🇬🇧 UK lead |
Most common ratings? | TV-MA & TV-14 |
Movie duration trend? | Stable; not significantly shorter |

## 📊 **Part 3 — Visualizations (Python / Matplotlib)**
Visuals created:
- Movies vs TV Shows bar chart
- Titles per year line chart
- Country contributions bar chart
- Rating distribution bar chart
- Movie durations histogram
- TV Show seasons histogram

## 📈 **Part 4 — Power BI Dashboard**
Includes:
- **KPIs:** Total Titles, Movies, TV Shows
- **Slicers:** Type, Rating, Year, Country
- **Charts:** Growth over time, Popular ratings, Country contributions
![Power BI Dashboard](Power%20BI%20Dashboard.png)
## 🧠 **Part 5 — Key Insights**
- Growth peak in 2020 → stabilization afterward
- Movies dominate; TV Shows increasing gradually
- Audience focus: mature (TV-MA / TV-14)
- Global expansion strategy (India, UK, Korea rising)

## ⭐ **Final Project Conclusion**
Netflix shifted from **rapid expansion** to **selective, strategic growth**:
| Phase | Strategy |
|-------|-----------|
Early | Build catalog volume |
2015–2020 | Aggressive expansion |
Post-2020 | Selective, quality-focused |

## 🚀 **Next Steps**
- ML predictions for performance
- NLP on descriptions
- Competitor comparison

## 📁 **Project Structure**

```
📦 Netflix-Analysis/
├── README.md
├── notebook.ipynb
├── data_cleaned/
├── visuals/
└── powerbi/
```

## 👤 **Author**
**Abdellah Boudlal**  
Beginner Data Analyst — Python • SQL • Power BI

# 🎉 End of Project
