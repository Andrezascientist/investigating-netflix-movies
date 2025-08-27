# Netflix 1990s Movies — Exploratory Case Study

**Author:** Andreza Eufrasio

**Stack:** Python, pandas, numpy, matplotlib

**Notebook:** `netflix_1990s_case_study.ipynb`


A compact analysis of Netflix movies released in the **1990s**. Each question include
**why it matters, method, result, and recommendations**, plus an appendix with
validation plots and alternative approaches.



## Business Context

Netflix’s content team wants to understand **what worked in the 1990s** to support catalog curation and nostalgic promotions.



## Key Questions

1. What was the most frequent movie duration in the 1990s?
2. How many **short-Action** movies (<90 min) were released in the 1990s?
3. Which year in the 1990s had the most movie releases?
4. Which genres dominated the 1990s?
5. Where are the **content gaps** we could fill?
   

## Deliverables

* Clear answers to the five questions, with visualizations.
* **Actionable recommendations** for stakeholders.
* A clean, reproducible notebook following best practices.



## Dataset

* **File:** `data/netflix_data.csv`
* **Source:** Provided by DataCamp for educational purposes
* Cleaning includes: normalized column names, numeric coercion, placeholder detection (e.g., “?”, “Unknown”), duplicate checks, and sanity plots.


## Requirements:
Python 3.12.7  
pip install -r requirements.txt


## How to Reproduce

1. Place `data/netflix_data.csv` in the `data/` folder.
2. Open `netflix_1990s_case_study.ipynb`.
3. **Run cells top-to-bottom.**
4. See answers under sections **Q1–Q5**, with insights and recommendations. 


## Skills Demonstrated

- Python programming fundamentals  
- Data manipulation with **pandas**  
- Exploratory Data Analysis (EDA)  
- Filtering and grouping data  
- Basic statistics and counting


## Summary of Insights

- **Most frequent runtime:** 94 minutes — the standard feature length of 1990s movies.
- **Short Action movies (<90 min):** Only 7 titles (~3.8%) of the catalog, showing scarcity in this niche.
- **Peak release years:** 1997, 1998, and 1999 each released 26 films, nearly double the early 1990s volume (14–16 per year).
- **Top genres:** Action (48), Drama (44), and Comedy (40) dominated, accounting for the bulk of releases.
- **Content gaps:** Genres below the median (~11–12 titles) — such as Stand-Up (8), Thrillers (5), Horror (4), Documentaries (2), and Cult Movies (2) — were underrepresented.

![1990s Movies per Year](images/movies_per_year.png)


## Recommendations for Stakeholders

- **Recommendation engine tuning:** Highlight movies around the 94-minute runtime in “Because you watched 90s classics” suggestions.
- **Quick-watch Action row:** Create a dedicated carousel for sub-90-minute Action films. Explore licensing/production to expand this niche.
- **Anniversary marketing:** Launch seasonal campaigns around late-1990s releases (e.g., “25 Years of 1999 Classics”) to leverage nostalgia.
- **Genre curation:** Feature Action, Drama, and Comedy prominently in catalog and homepage rows, since they defined the decade.
- **Fill content gaps:** Strengthen catalog diversity by targeting Stand-Up, Thrillers, Horror, Documentaries, and Cult Movies — testing demand with low-risk acquisitions.
