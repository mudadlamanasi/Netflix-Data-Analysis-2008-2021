# 💼 Netflix Data Cleaning, Analysis & Visualization 📊

This project is all about exploring Netflix’s content catalog by cleaning the data, analyzing trends, and creating visual insights. The dataset includes information about movies, TV shows, genres, countries, and release details. I’ve also done some feature engineering to get the data ready for future machine learning tasks. The goal is to better understand how Netflix’s content library has evolved and what patterns exist in the types of content they offer.

---

## 📁 Dataset Details

- **Name:** Netflix Titles Dataset  
- **Timeframe:** 2008 to 2021  
- **Description:** A cleaned version of Netflix’s catalog that includes details like title, director, country, release year, genres, and more.

**Main columns you’ll see in the dataset:**

- `show_id` – Unique ID for each title  
- `type` – Movie or TV Show  
- `title` – Name of the content  
- `director` – Director’s name  
- `country` – Country of production  
- `date_added` – When the title was added to Netflix  
- `release_year` – Year the title was originally released  
- `rating` – Content rating (e.g., TV-MA, PG-13)  
- `duration` – Duration in minutes (for Movies) or Seasons (for TV Shows)  
- `listed_in` – Genres the content belongs to  
- `genre_count` – Number of genres assigned  
- `duration_minutes` – Cleaned numeric duration (only for Movies)  
- `is_movie` and `is_tv_show` – Binary flags for easy filtering  
- `year_added` and `month_added` – Extracted from `date_added`  
- `country_encoded` – Frequency-encoded country field for analysis  

---

## 🎯 Project Objectives

- Clean and prepare the Netflix dataset for analysis  
- Explore content trends based on type, genres, countries, and release dates  
- Visualize insights using both Python and Tableau  
- Feature engineer additional fields to prepare the dataset for machine learning  
- Build interactive dashboards to share findings  

---

## 🛠️ Tools Used

- **Python (Pandas, Numpy):** Data cleaning and transformations  
- **Matplotlib & Seaborn:** Visual exploration in Python  
- **Tableau:** Interactive dashboards to share results  
- **Scikit-learn:** Preparing dataset for potential machine learning  
- **Git & GitHub:** Version control and project organization  

---

## 📊 What I Did in Python

**Data Cleaning:**

- Handled missing values  
- Parsed date fields properly  
- Converted duration to a clean numeric format for Movies  
- Counted genres assigned to each title  

**Exploratory Data Analysis:**

- Looked at Movies vs TV Show distribution  
- Analyzed content growth year by year  
- Found top countries contributing to Netflix's catalog  
- Identified most common genres for both Movies and TV Shows  
- Created word clouds of movie titles just for fun  

**Feature Engineering:**

- Added fields like `genre_count`, `duration_minutes`, and time-based fields  
- Encoded countries for better analysis  
- Created binary flags for quick filtering between Movies and TV Shows  

**ML Ready Dataset:**

The cleaned and enhanced dataset is ready for building models like genre prediction, content classification, or duration estimation in the future.

---

## 📊 Tableau Dashboard Highlights

The project includes a Tableau dashboard showing:

- Content breakdown by Movies and TV Shows  
- Yearly trends in content additions  
- Most popular genres overall  
- Distribution of movie durations  
- Easy filters for year, type, or country  

**Tableau Link:** *https://public.tableau.com/shared/WMG23GSH5?:display_count=n&:origin=viz_share_link*

---

## 📌 Key Insights

- Netflix has consistently increased content since 2008  
- Drama and International genres dominate the catalog  
- Most movies are between 90 to 120 minutes long  
- USA, India, and UK are top contributors to content  
- The dataset is fully prepared for future machine learning experiments  

---

## 🔧 Possible Improvements

- Further clean genre fields to handle overlapping categories  
- Add external data like IMDb ratings or user reviews  
- Build predictive models for trends or genre classification  
- Include more advanced visualizations in Tableau  

---

## 🤝 Let’s Connect

**Author:** Manasi Mudadla  
**Email:** manasimudadla0902@gmail.com  

If you like this project or have suggestions, feel free to connect or star the repo!

