#Amazon Prime Video Content Analysis — Exploratory Data Analysis (EDA)

#  Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Amazon Prime Video content to uncover meaningful insights about content distribution, audience preferences, production trends, and platform growth patterns.

The analysis uses multiple datasets containing title-level and credit-level information such as genres, ratings, runtime, actors, and directors. The goal is to extract data-driven insights that help support strategic decisions in content production and audience engagement.

---

##  Business Objective

The objective of this project is to analyze Amazon Prime Video content data to:

- Understand content diversity across genres
- Identify trends in content production over time
- Analyze audience ratings and popularity patterns
- Explore regional production distribution
- Evaluate actor and director participation trends
- Support data-driven decision-making for content investment and platform growth

---

## Dataset Description

This project uses **two datasets**:

### titles.csv

Contains information about Amazon Prime titles.

**Columns include:**

- id — Unique title identifier
- title — Name of the content
- type — Movie or TV Show
- description — Content summary
- release_year — Year of release
- age_certification — Age rating
- runtime — Duration of content
- genres — Genre list
- production_countries — Country of production
- seasons — Number of seasons
- imdb_score — IMDb rating
- imdb_votes — Number of votes
- tmdb_score — TMDB rating
- tmdb_popularity — Popularity metric

---

###  credits.csv

Contains cast and crew details.

**Columns include:**

- person_id — Unique person ID
- id — Title ID
- name — Actor/Director name
- character — Character name
- role — ACTOR or DIRECTOR

---

##  Technologies Used

The following Python libraries were used:

- **Python**
- **Pandas** — Data manipulation
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Advanced visualizations

---

##  Data Preprocessing Steps

The following preprocessing steps were performed:

- Handling missing values
- Removing duplicate records
- Converting data types
- Splitting genre and country lists
- Exploding multi-value columns
- Handling outliers
- Merging titles and credits datasets
- Creating derived variables (e.g., actor count)

---

##  Exploratory Data Analysis

EDA was performed using:

###  Univariate Analysis

- Content Type Distribution
- Release Year Trends
- Runtime Distribution
- IMDb Score Distribution
- TMDB Score Distribution
- Genre Distribution

---

###  Bivariate Analysis

- Runtime vs Content Type
- IMDb Score vs Content Type
- Runtime vs IMDb Score
- IMDb Score vs TMDB Score
- Production Countries Distribution
- Content Growth by Type

---

###  Multivariate Analysis

- Genre vs IMDb Score
- Correlation Heatmap
- Pair Plot Analysis

---

###  Merged Dataset Analysis

After merging titles and credits datasets:

- Top Actors by Number of Titles
- Top Directors by Number of Titles
- Role Distribution (Actors vs Directors)
- IMDb Score Distribution by Role
- Actor Count vs IMDb Score
- Correlation Heatmap of Merged Dataset

---

##  Key Insights

Some major insights from the analysis include:

- Movies dominate the platform compared to TV Shows.
- Significant growth in content production occurred after 2015.
- Drama is the most common genre.
- Documentary and History genres received higher average ratings.
- United States produces the majority of content.
- IMDb and TMDB scores show strong positive correlation.
- Runtime and cast size do not strongly influence ratings.
- Certain actors and directors appear frequently across titles.

---

##  Business Recommendations

Based on the analysis:

- Invest more in high-demand genres such as Drama and Comedy.
- Increase production of high-rated genres like Documentary.
- Expand international content production.
- Focus on storytelling quality rather than runtime length.
- Improve content discoverability using recommendation systems.
- Maintain diversity in casting and direction.

---

