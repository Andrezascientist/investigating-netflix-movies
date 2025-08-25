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

1. What runtime trends dominated 1990s movies?
2. How prevalent is short-form (< 90 min) content, especially in **Action**?
3. Which years were most prolific?
4. Which genres dominated the decade?
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

Python version used: 3.12.7
Dependencies: pandas, numpy, matplotlib (install with pip install -r requirements.txt)



## How to Reproduce

1. Place `data/netflix_data.csv` in the `data/` folder.
2. Open `netflix_1990s_case_study.ipynb`.
3. **Run cells top-to-bottom.**
4. See answers under sections **Q1–Q5**, with insights and recommendations. Appendix includes validation plots (e.g., exact-minute runtime counts confirming the mode at **94 min**).



## Appendix

Includes the **A1** validation plot and brief alternative solution methods for **Q1–Q3**. These are provided for transparency and quick cross-checks; 

## Skills Demonstrated

- Python programming fundamentals  
- Data manipulation with **pandas**  
- Exploratory Data Analysis (EDA)  
- Filtering and grouping data  
- Basic statistics and counting
