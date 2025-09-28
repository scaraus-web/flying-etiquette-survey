#  Exploring Passenger Etiquette: Who Thinks What’s Rude?

**Tools:** Python (pandas) for cleaning • Jupyter Notebook • Tableau Public for visualization  
**Live dashboard:**  [View on Tableau Public](https://public.tableau.com/app/profile/serge.caraus/viz/FlyingEtiquetteSurveyDashboard/FlyingEtiquetteSurveyDashboard)

---

##  Problem Statement

Air travel is one of the most common shared spaces where people from different backgrounds interact in close quarters.  
But what exactly do passengers consider **“rude behavior” on a plane**, and how does that perception vary by **age, gender, travel frequency, region, and income**?  

Understanding these attitudes matters because it:  
- Provides insights for **airlines** into customer satisfaction drivers.  
- Highlights **cultural and demographic differences** in tolerance.  
- Helps researchers and businesses explore **behavioral patterns** in shared environments.  

This project uses survey data to uncover **who thinks what’s rude in the sky** — from crying babies to reclining seats.

---

## Methods

### 1. Data Cleaning (Python + Jupyter)
- Removed duplicates and missing values.  
- Normalized categories (e.g., age groups, travel frequency labels).  
- Exported cleaned dataset for visualization.  
- Notebook: [Flying etiquette cleaning.ipynb](https://github.com/scaraus-web/flying-etiquette-survey/blob/main/notebook/Flying%20etiquette%20cleaning.ipynb)  
- Clean dataset: [flying-etiquette_clean.csv](https://github.com/scaraus-web/flying-etiquette-survey/blob/main/data/flying-etiquette_clean.csv)

### 2. Visualization (Tableau Public)
- Built dashboards with **filters and interactive views**:
  - Demographic snapshots (age, gender, travel frequency, region).  
  - Ranking of “What’s Rude?” behaviors (% respondents).  
  - US choropleth map of regional tolerance.  
  - Demographic selector (income, education, age).  
- Dashboard link: [View on Tableau Public](https://public.tableau.com/app/profile/serge.caraus/viz/FlyingEtiquetteSurveyDashboard/FlyingEtiquetteSurveyDashboard)  

---

##  3 — Key Insights
- **Top complaints:** *Bringing unruly children* and *waking passengers (walk-around)* dominate.  
- **Age effect:** Middle-aged travelers are least tolerant.  
- **Education:** Tolerance rises with higher education.  
- **Travel frequency:** Frequent travelers are more tolerant.  
- **Regional map:** Mountain West least tolerant; Northeast/Midwest more tolerant; CA/TX moderate.  

---
