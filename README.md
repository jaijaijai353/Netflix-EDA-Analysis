# Netflix-EDA-Analysis
📊 Netflix Data Analysis
This project explores and analyzes the Netflix dataset to uncover insights about content trends, genres, ratings, and production over time. The goal is to draw meaningful conclusions from Netflix's catalog to support business decisions, user experience improvements, or academic research.

📁 Project Structure
kotlin
Copy
Edit
netflix-data-analysis/
├── data/
│   └── netflix_titles.csv
├── notebooks/
│   └── analysis.ipynb
├── outputs/
│   └── visualizations/
├── README.md
└── requirements.txt
📌 Objectives
Clean and preprocess Netflix title data.

Analyze genre distribution, content types (Movies vs TV Shows), and rating trends.

Explore temporal trends in content release (by year).

Identify top countries producing Netflix content.

Generate visualizations to present findings clearly.

🧾 Dataset
Source: Kaggle - Netflix Movies and TV Shows

File: netflix_titles.csv

Columns include:

show_id

title

language

date_added

release_year

rating

listed_in (genre)

description

📈 Key Findings
Top 3 most common genres on Netflix.

Year with the highest number of new titles added.

Comparison of content by country and type.

Most popular content ratings (e.g., TV-MA, PG).

Trends in duration and type of content over the years.

More detailed insights and visualizations are available in the analysis notebook.

🛠️ Tools & Libraries
Python 3.10+

pandas

matplotlib

seaborn

numpy

jupyter
