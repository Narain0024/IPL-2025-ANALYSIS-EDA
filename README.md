# 🏏 IPL 2025 – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of the **IPL 2025 season**, focusing on match outcomes, player performances, team strategies, venue characteristics, and ball-by-ball trends.

The analysis combines:
- Match-level metadata
- Ball-by-ball delivery data
- Orange Cap (batting) statistics
- Purple Cap (bowling) statistics  

to uncover meaningful insights using Python-based data analysis and visualization techniques.

---

## 📂 Dataset Description

The project uses **four CSV datasets**:

| File Name | Description |
|----------|-------------|
| `matches.csv` | Match-level information (winner, toss, venue, stage, player of match, etc.) |
| `deliveries.csv` | Ball-by-ball data including runs, wickets, extras, venue, and teams |
| `orange_cap.csv` | Batting statistics (runs, strike rate, averages, boundaries, etc.) |
| `purple_cap.csv` | Bowling statistics (wickets, economy, strike rate, maidens, etc.) |

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
│ ├── Top Run Scorers.png
│ ├── TOP 10 WICKET TAKERS IPL 2025.png
│ ├── DOES WINNING THE TOSS INCREASE THE CHANCE OF WINING.png
│ ├── MOST MATCHES PLAYES - VENUES.png
│ ├── STRIKE RATE VS RUNS.png
│ ├── ECONOMY VS WICKETS IPL 2025.png
│ └── ... (many more)
│
├── requirements.txt
└── README.md


---

## 📊 Key Visual Insights

Below are some of the most important visual findings from the analysis.

### 🟧 Top Run Scorers
![Top Run Scorers](images/plots/Top Run Scorers.png)

### 🟣 Top Wicket Takers
![Top Wicket Takers](images/plots/TOP WICKET TAKERS IPL 2025.png)

### 🎯 Toss Impact on Match Result
![Toss Impact](images/plots/DOES WINNING THE TOSS INCREASE THE CHANCE OF WINING.png)

### 🏟 Most Active Venues
![Most Matches Played - Venues](images/plots/MOST MATCHES PLAYES - VENUES.png)

### 📈 Strike Rate vs Runs
![Strike Rate vs Runs](images/plots/STRIKE RATE VS RUNS.png)

### ⚖️ Economy vs Wickets
![Economy vs Wickets](images/plots/ECONOMY VS WICKETS IPL 2025.png)

> 📌 Many more plots are available in the **`images/plots/`** folder, covering:
> - Boundary analysis  
> - Bowling strike rates  
> - Extras breakdown  
> - Venue run rates  
> - Match stages  
> - Player consistency metrics  

---

## 🧠 Insights Summary

Some key insights derived from the EDA:

- Winning the toss shows a noticeable impact on match outcomes in IPL 2025.
- A small group of batters contributed a disproportionately high number of total runs.
- Strike rate and boundary percentage strongly influenced batting impact.
- Certain venues consistently favored higher run rates.
- Economical bowlers with better strike rates had a greater match influence.
- Teams with stronger bowling attacks performed better in knockout stages.
- Extras (wides and no-balls) played a significant role in match momentum.

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash

git clone https://github.com/Narain0024/ipl-2025-eda.git
cd ipl-2025-eda

```

###2️⃣ Install Dependencies
```
pip install -r requirements.txt

```

###3️⃣ Run the Notebook
```
jupyter notebook notebooks/01_eda.ipynb

```

---

📦 Dependencies
Listed in requirements.txt:
pandas
numpy
matplotlib
seaborn
jupyter

---

🚀 Future Enhancements

Predictive modeling for match outcome prediction

Player similarity and clustering analysis

Interactive dashboards using Plotly / Power BI

Fantasy IPL team recommendations

Team-wise powerplay vs death overs analysis

---

🙌 Acknowledgments

Dataset Source: Kaggle (IPL 2025 Records)

This project was created for learning, sports analytics, and portfolio purposes.

---

🧑‍💻 Author

GitHub: https://github.com/Narain0024

---




