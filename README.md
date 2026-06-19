Amazon Prime Video Content Analysis
https://colab.research.google.com/assets/colab-badge.svg

📊 Project Overview
A comprehensive Exploratory Data Analysis (EDA) of Amazon Prime Video's streaming content library, analyzing over nine thousand titles and one hundred twenty-four thousand cast and crew records to uncover strategic insights about content distribution, quality metrics, regional patterns, and viewer engagement.

🎯 Business Objectives
Content Strategy - Identify dominant genres and content gaps for acquisition decisions

Quality Analysis - Understand content performance through IMDb and TMDB ratings

Regional Expansion - Analyze production country distribution for market growth

Platform Optimization - Compare movie versus show performance

Trend Identification - Track content additions and popularity patterns over time

📈 Key Insights
Insight	Impact	Recommendation
Movies dominate at 87 percent of library	Content mix heavily favors films	Increase investment in original series
Drama and Comedy are top genres	Clear audience preferences	Prioritize these genres for acquisition
Average IMDb score is six	Moderate content quality	Focus on content above six
US produces most content	Regional concentration	Expand UK and Indian production
Shows generate more engagement	Series drive viewer interaction	Develop more original shows
📁 Dataset Description
Titles Dataset (9000+ records)
File: titles.csv

Records: Nine thousand +

Columns: Title, show type, release year, genres, production countries, IMDb scores, TMDB scores

Credits Dataset (124,000+ records)
File: credits.csv

Records: One hundred twenty-four thousand + credits

Columns: Person ID, title ID, name, character name, role (actor/director)

Key Columns:
show_type - MOVIE or SHOW classification

release_year - Year of content release

genres - Multiple genre tags per title

imdb_score - IMDb rating (1-10 scale)

imdb_votes - Number of IMDb votes

tmdb_popularity - TMDB popularity score

🛠️ Tech Stack
Technology	Purpose	Version
Python	Programming Language	3.10+
Pandas	Data Manipulation	1.5.3
NumPy	Numerical Computing	1.24.3
Matplotlib	Basic Visualizations	3.7.1
Seaborn	Statistical Visualizations	0.12.2
Google Colab	Cloud Execution	-
