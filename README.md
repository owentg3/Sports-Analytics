# MLB Analysis: Regular Season Dominance vs. October Collapse

An analytical data project designed to evaluate how different MLB player profiles and team philosophies transition from the 162-game regular season to the high-stakes environment of the postseason. 

This project specifically investigates the **"October Slugging Tax"**—testing the narrative that small-ball, walk-reliant teams (like the Milwaukee Brewers) struggle in the postseason compared to high-slugging, home-run-dependent rosters when facing elite pitching.

---

## 📊 Features & Objectives
* **Team-Level Correlation:** Mapping regular season home run production against postseason win percentages over the last decade.
* **The "October Power Drain":** Visualizing the collapse or maintenance of player **ISO (Isolated Power)** and **Hard Hit %** against premium postseason pitching.
* **Lineup Positional Breakdown:** Isolating team offensive production shifts (using Statcast's `xwOBA`) by defensive position.
* **Predictive Quadrant Modeling:** Classifying players into archetypes (*Elite, Slugger, Table-Setter*) to calculate their mathematical probability of surviving October pitching.

---

## 🛠️ Built With
* **Python 3**
* **pybaseball:** For scraping historical team records, FanGraphs leaderboards, and individual Statcast pitch-by-pitch data.
* **Pandas:** For data wrangling, player archetyping, and statistical manipulation.
* **Seaborn & Matplotlib:** For generating clear, scannable data visualizations and statistical regression plots.
* **Scikit-Learn (Optional):** For building a baseline Logistic Regression model to predict postseason performance drops.

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed, then install the required dependencies:

```bash
pip install pandas matplotlib seaborn pybaseball scikit-learn
