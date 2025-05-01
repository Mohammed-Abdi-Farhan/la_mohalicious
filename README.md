# 🎬 Data-Driven Strategy for Launching a Movie Studio

## 📌 Project Overview

This project analyzes historical movie industry data to uncover trends that influence box office success. The insights are aimed at helping a new movie studio decide what types of films to produce, how much to invest, and when to release them.

---

## 💼 Business Context

### 🎯 Business Problem
A new studio needs guidance on producing profitable films using past industry data.

### 👤 Stakeholder
The executive team (non-technical) of the new movie studio.

---

## ❓ Key Business Questions

1. What genres perform best at the box office?
2. Is there an ideal budget range for profitability?
3. Does release timing affect success?
4. What other features impact box office revenue?

---

## 📁 Data Sources

| Source                     | Description                                |
|----------------------------|--------------------------------------------|
| `im.db`                    | SQLite DB with movie metadata and ratings  |
| `bom.movie_gross.csv.gz`  | Box Office Mojo dataset (gross revenue)    |
| `tn.movie_budget.csv.gz`  | movie budgets dataset    |
| `cleaned dataset` | Cleaned Dataset of ( film_df,  movie_budget,  box_office). |

---

## 📊 Exploratory Data Analysis (EDA)

Conducted using Python in [`index.ipynb`](./index.ipynb)

### 📈 Sample Visualizations

#### 🎭 Most Common Genres Over Time
![Genres Over Time](visualizations/genres_over_time.png)

#### 💸 Top 10 Movies by Domestic Gross
![Top Movies](visualizations/top10_domestic_gross.png)

#### 📆 Revenue by Month
![Monthly Trends](visualizations/monthly_revenue.png)

#### 💰 Budget vs Revenue
![Budget vs Revenue](visualizations/budget_vs_revenue.png)

---

## 🔍 Key Insights

### Insight 1: Genre Performance
- Action and Adventure dominate in average revenue.
- Comedy and Drama are most common but more variable.

### Insight 2: Budget Sweet Spot
- Mid-range budgets ($50M–$100M) perform best overall.

### Insight 3: Seasonal Release Impact
- June–July and December releases are most profitable.

---

## 🎯 Recommendations

- Focus on Action/Adventure genres with wide appeal.
- Invest in mid-range budget films.
- Avoid January/September releases for major titles.
- Track changing trends using dashboards.

---

## 📂 Project Structure

Group4-Phase2-Project/ │ ├── zippedData/ # Raw and cleaned data files │ ├── im.db.zip # Zipped SQLite database (im.db too large for GitHub) │ ├── bom.movie_gross.csv.gz # Box Office Mojo (domestic gross) │ ├── tn.movie_budgets.csv # The Numbers (movie budget data) │ ├── tmdb.movies.csv # TMDb movie metadata │ ├── rt.movie_info.tsv # Rotten Tomatoes metadata │ ├── rt.reviews.tsv # Rotten Tomatoes critic reviews │ ├── all_combined.csv # Combined raw dataset before cleaning │ ├── cleaned_box_office.csv # Cleaned box office dataset │ ├── cleaned_movie_budgets.csv # Cleaned budget dataset │ ├── cleaned_dataset_film_df.csv # ❌ Too large to upload – excluded via .gitignore │ └── cleaned_dataset_film_df.tar.gz # ✅ Compressed cleaned dataset (included for GitHub) │ ├── index.ipynb # 📘 Main analysis notebook: │ ├─ Data Understanding │ ├─ Data Cleaning │ ├─ Exploratory Data Analysis (EDA) │ ├─ Visualizations │ ├─ Summary Statistics │ └─ Hypothesis Testing │ ├── movie_insights_presentation.pdf # 📊 Final non-technical presentation (executive-ready) │ ├── .gitignore # Files excluded from Git │ ↳ cleaned_dataset_film_df.csv │ ↳ im.db │ └── README.md # 📄 Project overview, structure, insights, and documentation





---

## 🛠️ Workflow & Team Responsibilities

| Stage                | Team Member(s)                                         |
|----------------------|--------------------------------------------------------|
| 📂 Data Cleaning      | **Mohammed Abdi**                                      |
| 📊 Exploratory Data Analysis (EDA) | **Faith**, **Ronny Muthomi**                          |
| 📐 Statistical Summary | **Emmanuel Yegon**                                   |
| 🔬 Hypothesis Testing | **Mercy Mercy**, **Austin Mwasi**                     |
| 📑 Non-Technical Presentation | *Entire Team*                                |

---

## ✅ GitHub Limitations

- `cleaned_dataset_film_df.csv` and `im.db` were **too large to upload** (>100 MB).
- We included:
  - `cleaned_dataset_film_df.tar.gz` (compressed)
  - `im.db.zip` (compressed)
- These are excluded from version control in `.gitignore`.

---

## 🧩 Visualization & Presentation

All visuals used in the executive summary were generated in `index.ipynb` and exported to the presentation PDF.

---

## 📌 Trello Board (Project Management)

> [https://trello.com/b/ILhuizXU/group-4-phase-2-project]  
> _(Use Trello to track tasks, deadlines, and project milestones.)_

---

Would you like me to now merge this into your actual `README.md` file and return a finalized version ready for GitHub and submission?







---

## 🧠 Tools Used

- Python: pandas, matplotlib, seaborn
- SQLite & SQLAlchemy
- Jupyter Notebook
- Tableau (dashboard coming soon)
- Git & GitHub

---

## 📤 Deliverables

| Deliverable                | Status          |
|----------------------------|------------------|
| Cleaned Dataset            | ✅ Compressed    |
| Jupyter Notebook (EDA)     | ✅ Complete      |
| Data Visualizations        | ✅ Embedded      |
| Tableau Dashboard          | 🔄 In progress   |
| Non-Technical PDF Report   | 🔄 In progress   |

---

## 👥 Contributors
- **Faith Karimi** — faith.karimi@student.moringaschool.com * Team leader.
- **Emmanuel Yegon** — emmanuel.yegon@student.moringaschool.com  
- **Mercy Mercy** — mercy.mercy1@student.moringaschool.com  
- **Austin Mwasi** — austin.mwasi@student.moringaschool.com  
- **Mohammed Abdi** — mohammed.abdi1@student.moringaschool.com  
- **Ronny Muthomi** — ronny.muthomi@student.moringaschool.com  

---

## 📬 Contact

> Questions? Reach out on [GitHub](https://github.com/KarimzKarimz) or email a team member.

