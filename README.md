# Netflix Analytics Dashboard

A data analytics project that visualizes Netflix's content catalog using Pandas and Matplotlib, uncovering trends in content type, release patterns, ratings, and global production.

## Overview

This project explores the Netflix Movies and TV Shows dataset to answer questions like:
- Is Netflix adding more movies or more TV shows over time?
- Which countries produce the most Netflix content?
- What ratings and genres dominate the catalog?
- How has content addition trended year over year?

## Dataset

The dataset includes metadata for Netflix's catalog:

| Column | Description |
|---|---|
| title | Name of the movie/show |
| type | Movie or TV Show |
| director | Director(s) of the title |
| cast | Lead cast members |
| country | Country of production |
| date_added | Date the title was added to Netflix |
| release_year | Original release year |
| rating | Content rating (e.g. PG-13, TV-MA) |
| duration | Runtime (movies) or number of seasons (TV shows) |

## Tech Stack

- **Python 3**
- **Pandas** – data cleaning, manipulation, and exploratory analysis
- **Matplotlib** – bar charts, line graphs, and pie charts

## Key Analysis & Visualizations

1. **Movies vs TV Shows** – overall split of content type on the platform
2. **Titles released per year** – growth trend of Netflix's catalog over time
3. **Top producing countries** – which countries contribute the most content
4. **Most common genres and ratings** – what dominates the catalog
5. **Content added over time** – trend line of catalog growth by year

## Sample Insights
*(fill in with your actual findings once you re-run the notebook, e.g.:)*
- Movies make up ~X% of the catalog vs Y% TV shows
- The US, India, and UK are the top 3 content-producing countries
- TV-MA and TV-14 are the most common ratings
- Content additions peaked in [year]

## How to Run

```bash
pip install pandas matplotlib
```

```bash
jupyter notebook netflix_analysis.ipynb
```

## Future Improvements

- Turn this into an interactive dashboard (Streamlit or Plotly Dash)
- Add genre-level deep dive (currently grouped broadly)
- Compare Netflix trends against other streaming platforms

