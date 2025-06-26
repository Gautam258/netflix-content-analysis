# Netflix Content Analysis & Clustering 📊🎬

This project performs Exploratory Data Analysis (EDA), visualization, and KMeans clustering on the Netflix titles dataset to uncover trends across genres, countries, and ratings.

## 🔍 Project Overview
- Dataset: Netflix Titles (`netflix_titles.csv`)
- Tools: Python, Pandas, Seaborn, Matplotlib, Scikit-learn
- Methods: EDA, Feature Engineering, TF-IDF, KMeans, PCA

## 📌 Key Steps
1. **Data Cleaning & Feature Engineering**
   - Handled missing values
   - Extracted content duration and year added
   - Created genre tokens and content age

2. **EDA & Visualizations**
   - Rating distribution, top genres, year-wise additions
   - Country-wise and director-wise content trends

3. **Clustering (KMeans)**
   - TF-IDF on genres
   - Grouped similar titles into 5 clusters
   - Visualized using PCA scatter plot

## 🎯 Findings & Insights
- TV-MA and TV-14 are the most common ratings.
- Drama, Comedy, and Documentary dominate the genre space.
- The US leads in content production, followed by India and the UK.
- Clustering revealed five genre-based groups helpful for recommendations.

## 💼 Stakeholder Value
- **Content Teams**: Find gaps by genre/country
- **Marketing Teams**: Target by country/genre
- **Recommendation Engines**: Use clusters to improve suggestions
- **Analysts**: Visualize growth and production trends
