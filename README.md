# Gamedev Sales Analysis

This project presents a comprehensive analysis of global video game sales across platforms, genres, publishers, and regions for the year 2021. The goal is to uncover key patterns in consumer behavior and business performance in the gaming industry using real sales data.

---

## Project Stage
This is an earlier project that represents my initial steps in exploratory data analysis (EDA). More advanced analytical and business-oriented projects can be found in my latest repositories.

---

## Overview

The project includes:

1. **Data Cleaning and Preprocessing**  
   - Removal of low-relevance platforms and genres (e.g., Visual Novel).  
   - Fixing missing values and correcting key data points.  
   - Extraction of release year and restructuring of columns.

2. **Genre Popularity**  
   - Identifying top-selling genres worldwide.  
   - Regional differences in genre preferences.

3. **Platform Sales Analysis**  
   - Discovering the most profitable gaming platforms by total units sold.

4. **Regional Trends**  
   - Comparative analysis of game sales in North America, Europe + Africa + Oceania, Japan, and other regions.  
   - Regional genre preferences visualized through bar charts.

5. **Publisher Performance**  
   - Top 5 publishers by total sales.  
   - Deep dive into genre portfolios of leading publishers such as EA, Rockstar, and Activision.

6. **Correlation Analysis**  
   - Heatmap showing relationships between critic scores and sales in different regions.  
   - Evaluating if critic scores significantly impact performance.

---

## Visualizations

- **Pie Charts**:  
  - Global sales distribution by genre.  
  - Top 5 publishers' contribution to global sales.  
  - Genre breakdowns for each of the top 5 publishers.

- **Bar Charts**:  
  - Sales by platform.  
  - Regional genre preferences.  
  - Total sales by region.

- **Heatmap**:  
  - Correlation matrix between total sales, regional sales, and critic scores.

---

## Technologies Used

- **Language**: Python   
- **Libraries**:
  - `pandas` – data manipulation  
  - `numpy` – numerical operations  
  - `matplotlib` & `seaborn` – data visualization  

---

## Dataset

- **Source**: [Kaggle - Video Game Sales 2024 Dataset](https://www.kaggle.com/datasets/asaniczka/video-game-sales-2024/data)  
- Contains information on game title, genre, platform, publisher, critic score, release date, and sales by region.

---

## Conclusions

- **Top Genres**: Shooter, Action, and Sports lead global sales. Japan favors Role-Playing games.
- **Best-Selling Platforms**: PS3 and Xbox 360 dominate; PS4 is the only newer-gen console with high sales. Xbox One lags.
- **Leading Publishers**: EA, Activision, Ubisoft, Rockstar, and EA Sports are the most profitable. Their main focus is on Action and Shooter games.
- **Critic Scores**: No strong correlation with sales — hits don’t always need top critic ratings.
- **Regions**: North America is the most profitable market; Japan ranks lowest in overall sales.

---

## Author

Project by **[loktionov-data](https://github.com/loktionov-data)**  
Feel free to clone, explore, and reach out for collaboration!
