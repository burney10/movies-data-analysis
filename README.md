# 🎬 Movies Data Analysis Project (Netflix / TMDB Dataset)

## 📌 Project Overview
This project performs **exploratory data analysis (EDA)** on a movies dataset to uncover trends related to **genres, popularity, voting patterns, and release years**.  
The goal is to clean raw movie data, transform it into an analysis-ready format, and extract meaningful insights using Python data analysis libraries.

---

## 🎯 Objectives
- Clean and preprocess raw movie data
- Analyze genre distribution and popularity trends
- Categorize movies based on audience ratings
- Identify most and least popular movies
- Visualize insights using plots and charts

---

## 📊 Dataset Description
- **Rows:** 9,827 movies (expanded to 25,552 rows after genre explosion)
- **Columns Used:**
  - `Release_Date` (Year)
  - `Title`
  - `Popularity`
  - `Vote_Count`
  - `Vote_Average` (Categorized)
  - `Genre`

> Dataset contains no missing or duplicate values.

---

## 🧹 Data Cleaning & Feature Engineering
- Converted `Release_Date` to year format
- Removed unnecessary columns (`Overview`, `Original_Language`, `Poster_Url`)
- Categorized `Vote_Average` into:
  - `not_popular`
  - `below_avg`
  - `average`
  - `popular`
- Split and exploded multi-genre movies into individual genres
- Converted `Genre` and `Vote_Average` into categorical data types

---

## 📈 Exploratory Data Analysis (EDA)
Key questions answered:
1. What is the most frequent genre?
2. Which genre receives the highest votes?
3. Which movie has the highest popularity?
4. Which movie has the lowest popularity?
5. Which year has the highest number of movies?

---

## 🔍 Key Insights
- **Drama** is the most frequent genre (~14% of total movies)
- **Spider-Man: No Way Home** is the most popular movie
- **Year 2020** recorded the highest number of movie releases
- Movies categorized as **popular** make up ~25% of the dataset
- Multi-genre movies significantly influence popularity trends

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📂 Project Structure
movies-data-analysis/
│
├── data/
│ └── mymoviedb.csv
│
├── notebooks/
│ └── movies_analysis.ipynb
│ └── Netflix_movie_analysis.pdf
|
├── visuals/
│ └── plots.png
│
└── README.md

---

## 🚀 How to Run the Project
1. Clone the repository
   ```bash```
   git clone https://github.com/burney10/movies-data-analysis.git
   
2. Install dependencies
   ```bash```
   pip install pandas numpy matplotlib seaborn

3. Run the Jupyter Notebook

---

## 📌 Future Improvements
- Add sentiment analysis
- Build a recommendation system
- Deploy insights using Tableau or Power BI
- Include machine learning-based popularity prediction

---

## 👤 Author
Ankan Senapati
Aspiring Data Scientist | Machine Learning Enthusiast

---
