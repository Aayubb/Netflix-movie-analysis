This is the first data science project from DataCamp's the career track Associate Data Scientist with Python.
# 🎬 Netflix Movie Analysis — 1990s Decade

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557c)
![DataCamp](https://img.shields.io/badge/DataCamp-Project-03EF62?logo=datacamp&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)

> An exploratory data analysis (EDA) of Netflix movie data, focused on uncovering trends and insights from the **1990s decade**.


## 📌 Project Overview

This project was completed as part of the **DataCamp Data Science curriculum**. The goal was to perform exploratory data analysis on Netflix movie data to better understand the characteristics of films released during the 1990s — a golden era of cinema.

Key questions explored:
- What was the **most frequent movie duration** in the 1990s?
- How many **short action movies** (under 90 minutes) were released in the 1990s?


## 🗂️ Dataset

**File:** `netflix_data.csv`

The dataset contains information about movies and TV shows available on Netflix, including title, genre, release year, duration, and more.


## 🔍 Analysis Highlights

### 1. Most Frequent Movie Duration in the 1990s
By filtering the dataset to movies released between 1990 and 1999 and analyzing the distribution of durations, the most frequent (mode) movie duration was identified and saved as:

```python
duration = 94  # Most frequent movie duration (in minutes)
```

### 2. Short Action Movies in the 1990s
A movie is classified as **short** if its duration is **less than 90 minutes**. Filtering for action movies in the 1990s that meet this criterion:

```python
short_movie_count = # Integer count of short action movies
```


## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| **Python** | Core programming language |
| **Pandas** | Data loading, filtering, and analysis |
| **Matplotlib** | Data visualization |

## 📊 Key Steps in the Analysis

1. **Data Loading** — Imported `netflix_data.csv` using Pandas
2. **Data Filtering** — Isolated movies released from 1990 onwards through the 1990s decade
3. **Exploratory Analysis** — Examined duration distributions, genre breakdowns, and release trends
4. **Visualization** — Plotted histograms and bar charts to understand the data visually
5. **Insight Extraction** — Derived the most frequent duration and counted short action movies

## 📁 Project Structure

```
netflix-movie-analysis/
│
├── netflix_data.csv          # Raw dataset
├── netflix_analysis.ipynb    # Main Jupyter Notebook
└── README.md                 # Project documentation
```

## 💡 Learnings & Takeaways

- Real-world datasets require careful filtering and cleaning before drawing conclusions.
- Visualizing distributions (like movie durations) quickly reveals patterns that raw numbers can obscure.
- Even simple EDA questions can lead to interesting insights about trends across decades.


## 📄 License

This project is for educational purposes as part of the DataCamp curriculum.
