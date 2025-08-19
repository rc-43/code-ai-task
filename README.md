
🏏 IPL Exploratory Data Analysis (EDA)

📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the Indian Premier League (IPL) ball-by-ball dataset.
The main objective is to extract meaningful insights, player statistics, and performance trends from the dataset using Python, Pandas, and Matplotlib.

The analysis covers:

Data cleaning & preparation

Player & team performance trends

Powerplay vs Death overs statistics

Visual insights through plots



📂 Dataset

Source: Kaggle IPL deliveries dataset (ball-by-ball data)

Structure:

match_id: Unique identifier for each match

over, ball: Over and ball number

batsman, bowler: Player details

batsman_runs, total_runs: Runs scored

player_dismissed: Wickets info



🛠️ Tools & Libraries

Python 3.x

Pandas → Data cleaning & aggregation

Matplotlib / Seaborn → Data visualization

Jupyter Notebook for analysis



📊 Key Analysis & Insights
1. Top Batsmen

Computed most runs scored overall and strike rates.

Identified consistent top scorers across seasons.

2. Powerplay Analysis (Overs 1–6)

Evaluated teams’ aggression and scoring trends.

Insights into fast starters and early wicket losses.

3. Death Overs Analysis (Overs 16–20)

Identified best finishers and death-over bowlers.

Compared batting strike rates vs dismissal risks.

4. Bowler Performance

Wicket-taking trends by phases.

Economy rate distribution.

</n>

📈 Visualizations

Some key visualizations included in the analysis:

Bar plots → Top batsmen & bowlers

Pie charts → Wicket types distribution

Scatter plots → Runs vs Strike Rate relationships

Line charts → Over-wise scoring patterns



🚀 How to Run

Clone this repo

git clone https://github.com/yourusername/ipl-eda.git
cd ipl-eda


Install dependencies

pip install -r requirements.txt


Run Jupyter Notebook

jupyter notebook



📌 Results & Learnings

Data-driven insights can help understand match strategies.

Certain players dominate specific match phases (powerplay/death overs).

Visualizations reveal hidden patterns & anomalies in performance.



📜 Future Scope

Extend analysis to team-wise win prediction.

Use Machine Learning for match outcome predictions.

Interactive dashboards using Plotly/Streamlit.

✍️ Author: Rhishit Chheda
