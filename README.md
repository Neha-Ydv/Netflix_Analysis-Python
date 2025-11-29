# 🎬 Netflix Analysis using Python

> **A comprehensive, real-world data analytics project leveraging Python to uncover business insights from Netflix’s content catalog.**

---

## 📂 Folder Structure

```
Netflix_Analysis-Python/
├── data/
│   └── netflix_titles.csv
├── visuals/
│   └── (charts and plots)
├── Netflix_Analysis.ipynb
├── requirements.txt
└── README.md
```

---

## 📊 Dataset Information

- **Source:** [Netflix Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Features/Columns:**
  | Column Name    | Description                                         |
  | -------------- | --------------------------------------------------- |
  | `show_id`      | Unique ID for each title                            |
  | `type`         | Movie or TV Show                                    |
  | `title`        | Name of the content                                 |
  | `director`     | Director(s)                                         |
  | `cast`         | Cast members                                        |
  | `country`      | Countries where available                           |
  | `date_added`   | Date content was added                              |
  | `release_year` | Year of release                                     |
  | `rating`       | Maturity rating (e.g., TV-MA, PG, etc.)             |
  | `duration`     | Duration of content                                 |
  | `listed_in`    | Genre & categories                                  |
  | `description`  | Short summary                                       |

---

## 🎯 Objectives / Problem Statement

- Reveal **content trends**: genres, release patterns, audience maturity levels.
- Analyze **movie vs TV distribution** and growth.
- Discover **year-wise patterns** and country-level content differences.
- Extract **duration and rating insights** to assist business decisions.

---

## 🛠️ Tools & Technologies Used

- ![Python](https://img.shields.io/badge/Python-3.8+-blue.svg) **Python**
- ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg) **Jupyter Notebook**
- ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow.svg) **Pandas**
- ![NumPy](https://img.shields.io/badge/NumPy-Array%20Computing-blue.svg) **NumPy**
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange.svg) **Matplotlib**
- ![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-blue.svg) **Seaborn**

---

## 🧹 Data Cleaning & Preprocessing

- Imputed and handled **missing values**
- Standardized and **converted datatypes**
- Removed **duplicate records**
- Cleaned and standardized **text columns** (`country`, `listed_in`, etc.)

---

## 🔍 Exploratory Data Analysis (EDA)

- 📚 **Content Type Distribution**: Movies vs. TV Shows
- 🎭 **Genre Analysis**: Most popular categories
- 📅 **Year-wise Trends**: Releases across years
- 🌍 **Country-wise Content**: Geographical insights
- ⏱️ **Duration Analysis**: Top longest/shortest movies and shows
- 🔞 **Ratings**: Maturity levels and audience targeting

---

## 🗝️ Key Insights & Findings

- **Movies comprise ~70%** of the Netflix catalog, TV shows ~30%.
- **Drama and International Movies** are the top genres.
- USA, India, and the UK lead in content availability.
- **Recent years (2017-2020)** saw a surge in new content.
- Majority of TV shows are multi-national compared to movies.
- **TV-MA and TV-14 ratings** are the most prevalent, indicating adult-oriented catalog.
- **Median duration** of movies is around 90 minutes.
- Several director and actor fields contain missing or inconsistent data.

---

## 📈 Visualizations

- Bar charts: Content type, genres, ratings
- Countplots: Release years, top countries
- Heatmaps: Year vs. ratings, country vs. genres
- Trendlines: Year-on-year content growth
- Pie chart: Genre distribution
- Boxplots: Distribution of durations

---

## ⚡ Challenges Faced

- Data quality and **missing values** in key fields (`director`, `country`)
- **Inconsistent formatting** in columns like `listed_in`
- Multiple categories/genres per entry complicated aggregation
- Need for extensive **text cleaning and normalization**

---

## ✅ Conclusion

Netflix’s catalog is diverse but leans toward movies and drama genres. Content growth accelerated in the late 2010s, with the USA and India as major contributors. Insights from EDA empower business teams to refine acquisition and recommendation strategies, optimize regional offerings, and understand audience maturity preferences.

---
