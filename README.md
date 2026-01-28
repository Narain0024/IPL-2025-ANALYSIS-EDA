# IPL-2025-ANALYSIS-EDA
# 🏏 IPL 2025 - Exploratory Data Analysis (EDA)

## 📌 Overview

This project performs comprehensive exploratory data analysis (EDA) on IPL 2025 cricket datasets to extract meaningful insights about player performance, team outcomes, match conditions, and game strategy.

Using batting (Orange Cap), bowling (Purple Cap), match-level metadata, and ball-by-ball deliveries data, this analysis reveals patterns around run scoring, wicket taking, toss impact, venue advantages, and more.

---

## 📂 Dataset Description

The dataset consists of 4 CSV files:

| File | Description |
|------|-------------|
| `deliveries.csv` | Ball-by-ball event data (runs, wickets, extras, venue, etc.) |
| `matches.csv` | Match-level data (venue, winner, toss decision, top scorer, etc.) |
| `orange_cap.csv` | Batting leaderboard stats (runs, strike rate, boundaries, etc.) |
| `purple_cap.csv` | Bowling leaderboard stats (wickets, economy, best figures, etc.) |

---

## 🧰 Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

---

## 📁 Project Structure

ipl-2025-eda/
│
├── data/
│ ├── deliveries.csv
│ ├── matches.csv
│ ├── orange_cap.csv
│ └── purple_cap.csv
│
├── notebooks/
│ └── 01_eda.ipynb
│
├── images/
│ └── plots/
│ ├── top_run_scorers.png
│ ├── top_wicket_takers.png
│ ├── toss_impact.png
│ ├── venue_win_count.png
│ ├── strike_rate_vs_runs.png
│ └── ...
│
├── requirements.txt
└── README.md

---

## 📊 Key Visual Insights

Some of the most important visual findings from the EDA:

### 🟧 **Top Run Scorers**
![Top Run Scorers](ipl-2025-eda\images\plots\TOP 10 RUN SCORERS IPL2025.png)

### 🟣 **Top Wicket Takers**
![Top Wicket Takers](images/plots/top_wicket_takers.png)

### 🎯 **Toss Impact on Match Result**
![Toss Impact](images/plots/toss_impact.png)

### 🏟 **Most Active Venues**
![Venue Win Count](images/plots/venue_win_count.png)

*(More charts available in `/images/plots/` folder)*

---

## 🧠 Insights Summary

Major insights discovered during analysis:

- Toss winners won **X% of matches**, indicating that winning the toss provides a strategic advantage.
- **Top run scorer** was **\<player>** with **\<runs> runs**, showing high batting consistency.
- **Most wickets** were taken by **\<bowler>**, making them the leading Purple Cap contender.
- **Best economy bowler** maintained an economy of **\<value>**, demonstrating strong control in bowling.
- Venues like **\<venue>** showed higher scoring trends (higher run rate & boundaries).
- Teams defending batting first won more matches at **\<venue>**, suggesting pitch advantage.
- Boundary percentage strongly correlated with match-winning performance for several teams.
- **\<Team>** had the highest boundary contribution rate across the season.

\* You can edit `<player>`, `<bowler>`, `<venue>`, `<Team>` based on your results.

---

## ▶️ How to Run the Project

### **1. Clone Repository**
### **2.Install Dependencies
pip install -r requirements.txt
### **3.Launch Notebook
jupyter notebook notebooks/01_eda.ipynb


📦 Dependencies

Listed in requirements.txt:
pandas
numpy
matplotlib
seaborn
jupyter


🚀 Future Work

Planned enhancements:

🧮 Predictive modeling (match outcome prediction)

📈 Player comparison dashboards

🧩 Clustering (Player similarity analysis)

🏆 Fantasy team suggestions based on stats



🙌 Acknowledgments

Dataset source: Kaggle IPL 2025 Dataset
This project was created for learning, sports analytics, and portfolio purposes.




