# Videogame Sales & Ratings Analysis - [Notebook](https://github.com/jaysic470/Videogame-SDA/blob/main/Videogame-SDA.ipynb)

This project explores patterns and insights in the video game industry using sales and user rating data. It was completed as part of a structured learning curriculum focused on data preprocessing, analysis, visualization, and hypothesis testing.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Objectives](#key-objectives)
- [Process](#process)
- [Insights & Results](#insights--results)
- [Business Recommendations](#business-recommendations)
- [Tools Used](#tools-used)
- [Project Structure](#project-structure)

---

## Project Overview

The goal of this project is to help a gaming company understand regional sales trends and consumer preferences to inform future game development and marketing strategies. By analyzing patterns in sales, genres, platforms, and ratings, we provide actionable insights backed by data.

---

## Dataset

The dataset contains information on:
- Game titles
- Platforms
- Genres
- Release years
- Critic/user scores
- Global and regional sales (NA, EU, JP)

---

## Key Objectives

- Identify top-performing platforms and genres globally and by region.
- Assess how critic and user ratings relate to sales performance.
- Test hypotheses regarding differences in user ratings across platforms and genres.
- Evaluate review impact on game sales.

---

## Process

1. **Data Overview**
   - Inspected structure, column types, and high-level statistics.

2. **Preprocessing**
   - Renamed columns, handled nulls and duplicates, converted data types.
   - Added derived features for cleaner analysis.

3. **Exploratory Data Analysis**
   - Grouped sales data by platform and genre.
   - Analyzed regional trends and visualized top-selling games.
   - Explored correlations between review scores and sales.

4. **Hypothesis Testing**
   - Used t-tests to compare user rating distributions across:
     - Xbox One vs PS4
     - Action vs Sports genres

---

## Insights & Results

- **PS4 and Xbox One** dominate global sales, but preferences vary regionally.
- **Action games** are top sellers, while **Sports games** show mixed performance by region.
- Higher **critic scores** loosely correlate with better sales, but **user scores** are more polarized.
- Statistical testing showed significant differences in user ratings between platforms and genres.

---

## Business Recommendations

- Focus new game development on **Action** and **Shooter** genres for global appeal.
- Continue investing in **PS4** and **Xbox One** platforms, but monitor emerging platforms.
- Emphasize **early review campaigns** to influence initial sales momentum.

---

## Tools Used

- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Data visualization
- `scipy.stats` – Hypothesis testing
- `Jupyter Notebook` – Development environment

---

## Project Structure
Videogame-SDA/
├── Videogame-SDA.ipynb # Main notebook
├── README.md # Project overview
└── data/
└── games.csv # Raw dataset
