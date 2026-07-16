# 🎬 Netflix Movies Analysis using Power BI

## 📌 Project Overview

This project presents an interactive **Power BI dashboard** built to analyze a large catalog of movies to uncover insights into ratings, popularity, genre performance, and language-based trends.

The dashboard was developed using **Microsoft Power BI**, **Power Query**, and **DAX**, following an end-to-end Business Intelligence workflow—from data cleaning and modeling to visualization and storytelling.

---

## 🎯 Project Objectives

- Analyze overall movie catalog performance (ratings, popularity, votes)
- Identify which genres drive the highest popularity and ratings
- Study the relationship between popularity and average rating
- Assess audience trust by examining rating volume vs average rating
- Compare genre content volume against genre popularity
- Analyze language-based audience engagement and rating patterns
- Track content growth by release year

---

## 📂 Dataset

The dataset contains movie-level records with the following attributes:

- Movie Title
- Genre
- Language
- Release Date
- Rating (Average)
- Rating Count (Votes)
- Popularity Score

---

## 🛠️ Data Preparation

The dataset was cleaned and transformed using **Power Query**.

### Transformations Performed

- Converted data types (dates, numeric fields)
- Extracted Release Year from Release Date
- Handled missing/NA genre values
- Standardized language codes (en, ja, es, fr, ko, etc.)
- Removed unnecessary columns
- Optimized the data model for reporting

---

## 📈 DAX Measures

The following measures were created for analysis:

- Total Movies
- Average Rating
- Average Popularity
- Total Votes (Rating Count)
- Total Genres
- Total Languages
- Average Popularity by Genre
- Average Rating by Genre
- Average Popularity by Language
- Average Rating by Language

---

# 📊 Dashboard Pages

## 1️⃣ Executive Overview

### Purpose

Provides a high-level snapshot of the overall movie catalog.

### Visuals

- KPI Cards
  - Total Movies
  - Average Rating
  - Average Popularity
  - Total Votes
  - Total Genres
  - Total Languages

- Area/Line Chart
  - Total Movies by Year

- Donut Chart
  - Movies by Language

- Bar Chart
  - Top 10 Movies by Popularity

### Filters

- Release Date (range)
- Genre
- Language

---

## 2️⃣ Rating & Popularity Analysis

### Purpose

Understand how popularity and audience rating volume relate to average rating.

### Visuals

- Scatter Plot
  - Popularity vs Ratings

- Scatter Plot
  - Genre Popularity vs Content Volume

- Scatter Plot
  - Audience Trust: Rating Count vs Average Rating

### Filters

- Release Date (range)
- Genre
- Language

---

## 3️⃣ Genre Analysis

### Purpose

Break down catalog composition and performance by genre.

### Visuals

- Bar Chart
  - Movies by Genre (volume, sorted descending)

- Bar Chart
  - Top 10 Genre by Avg Popularity

- Bar Chart
  - Top 10 Genre by Average Rating

### Filters

- Release Date (range)
- Genre
- Language

---

## 4️⃣ Language Analysis

### Purpose

Analyze audience engagement and rating trends across languages.

### Visuals

- Treemap
  - Movies by Language

- Bar Chart
  - Top 10 Language by Avg Popularity

- Bar Chart
  - Top 10 Language by Average Rating

### Filters

- Release Date (range)
- Genre
- Language

---

# 🔍 Key Insights

- English-language titles dominate the catalog by volume, but do not top the charts for either popularity or rating — smaller-volume languages like Malayalam (ml) and Hindi (hi) lead on popularity, while languages like Malay (ms) and Ukrainian (uk) lead on average rating.
- High-volume genres (Drama, Action, Comedy) are not the highest-rated or most popular per title — genres like War, Animation, and Western score highest on average rating despite lower content volume.
- The Audience Trust chart (Rating Count vs Average Rating) shows ratings stabilize and trend upward as vote count increases, suggesting low-vote titles carry more rating volatility/noise.
- Movie output has grown sharply since the 1980s, with a peak around 2020 followed by a decline — worth noting as a possible data coverage/collection cutoff rather than an actual industry decline.

---

# 🎨 Design

Built using Netflix's brand palette for visual consistency.

| Role | Hex |
|---|---|
| Netflix Red | `#E50914` |
| Background Black | `#141414` |
| Card Background (Dark Grey) | `#1F1F1F` |
| White Text | `#FFFFFF` |
| Muted Grey Text | `#B3B3B3` |

---

# 📊 Dashboard Preview

> **Add your dashboard screenshots here after uploading them.**

```
Dashboard_Screenshots/
│
├── Page1_Executive_Overview.png
├── Page2_Rating_Popularity_Analysis.png
├── Page3_Genre_Analysis.png
└── Page4_Language_Analysis.png
```

---

# 🧰 Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Data Visualization
- Git & GitHub

---

# 📁 Repository Structure

```
netflix-movies-analysis-powerbi/
│
├── README.md
├── Netflix_Analysis_Dashboard.pbix
├── Dataset.csv
├── Dashboard_Screenshots/
│   ├── Page1_Executive_Overview.png
│   ├── Page2_Rating_Popularity_Analysis.png
│   ├── Page3_Genre_Analysis.png
│   └── Page4_Language_Analysis.png
├── Images/
│   └── Dashboard_Preview.png
└── LICENSE
```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Transformation
- Power Query
- DAX Calculations
- Data Modeling
- Dashboard Design
- Business Intelligence
- Data Visualization
- Analytical Storytelling

---

# 📌 Future Improvements

- Add drill-through pages by genre and language
- Implement Row-Level Security (RLS)
- Publish the dashboard to Power BI Service
- Connect the dashboard to a live database
- Automate data refresh using scheduled refresh

---

# 🤝 Connect With Me

If you enjoyed this project or have suggestions for improvement, feel free to connect with me.

- 💼 LinkedIn: https://www.linkedin.com/in/rohit-kushwaha-3482153b0/
- 📧 Email: rohit0614kushwaha@gmail.com

---

## ⭐ If you found this project helpful, consider giving it a star!
