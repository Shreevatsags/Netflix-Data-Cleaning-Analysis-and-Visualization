🎬 Netflix Data Analysis Project


📌 Overview

This project performs data cleaning, analysis, and visualization on the Netflix dataset to discover insights into content types, genre trends, and viewing patterns over time.

🧰 Tech Stack

Python

Pandas – Data cleaning and manipulation

NumPy – Numerical computations

Matplotlib / Seaborn – Data visualization

Jupyter Notebook – Interactive exploration

🧹 Data Cleaning

Removed missing values and duplicates

Standardized column names and formats

Converted date_added to datetime format

Split and cleaned multi-genre columns for clarity

📊 Exploratory Data Analysis (EDA)

The analysis focuses on:

Distribution of content types

Ratings distribution

Year-wise content addition

Top genres on Netflix

📈 Visualizations
1️⃣ Distribution of Content by Type


Movies make up the majority of the Netflix catalog, outnumbering TV shows by a large margin.

2️⃣ Rating on Netflix


Most of the Netflix content falls under TV-MA and TV-14, showing that mature and teen audiences form a major viewership base.

3️⃣ Total Content on Netflix


Roughly 70% of Netflix’s content library consists of Movies, while TV Shows make up around 30%.

4️⃣ Content Added Over Time


The number of titles added increased sharply after 2015, peaking around 2019–2020, indicating Netflix’s rapid global expansion.

5️⃣ Most Common Genres on Netflix


International Movies, Dramas, and Comedies are the most represented genres on Netflix, highlighting diverse content offerings.

💡 Key Insights

Movies dominate the Netflix library

TV-MA and TV-14 are the most common ratings

Content addition saw a massive rise post-2015

Netflix offers diverse genres, with a strong presence of international films

🚀 How to Run

Clone the repository

git clone https://github.com/Shreevatsags/Netflix-Data-Cleaning-Analysis-and-Visualization


Install dependencies

pip install -r requirements.txt


Open Jupyter Notebook

jupyter notebook notebooks/Netflix_EDA.ipynb

📚 Dataset

Dataset Source: Kaggle – Netflix Movies and TV Shows

🧠 Future Enhancements

Add an interactive dashboard (using Plotly Dash or Streamlit)

Build a content recommendation engine

Perform sentiment analysis using descriptions
