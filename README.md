<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/9dcd5aa7-e99e-4207-b3e0-1fba75663751" />
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/098808d1-a8db-472a-95ef-e5c69f6df7e3" />
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/a8d090c1-b1ec-483f-8a7b-538f10c413ae" />
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/5b75bbfd-1e63-4f28-b1ba-eb413f62f5c4" />


# 🏀 NBA Performance Analytics Dashboard (2003–2022)

An interactive **Power BI analytics project** that explores NBA performance across **league, team, and player levels** from **2003 to 2022**.  
The project focuses on **performance trends, consistency, efficiency, and strategic insights** using advanced DAX and interactive visuals.

---

## 🎯 Project Objective

This project aims to:
- Analyze long-term **NBA performance trends**
- Compare **team and player-level efficiency**
- Evaluate **home vs away advantage**
- Measure **consistency using statistical metrics**
- Present insights using **business-style storytelling**

The goal is not just visualization, but **decision-oriented analytics**.

---

## 📊 Dashboard Pages Overview

---

### 1️⃣ NBA Overview Dashboard

**Purpose:**  
Provides a **league-level snapshot** of performance and trends.

**Key Metrics**
- Total Games
- Total Points
- Home Wins
- Away Wins
- Home Win %
- Total Turnovers

**Key Visuals**
- Total Games by Season (trend)
- Home vs Away Wins by Conference
- League Scoring Trend (Avg Points per Game)
- Scatter: *Do High-Scoring Teams Always Win?*

**Insights**
- Home teams win ~59% of games → strong home-court advantage
- League scoring has increased steadily over time
- Higher scoring does **not always translate into wins**
- League operations are mostly stable except during disruptions like COVID

---

### 2️⃣ Player Analysis Dashboard

**Purpose:**  
Deep dive into **individual player performance, efficiency, and consistency**.

**Key Metrics**
- Player Points
- Matches Played
- Points Per Game (PPG)
- Total Assists
- Total Rebounds
- Average Plus/Minus

**Key Visuals**
- Player Points, Assists & Rebounds by Season
- Efficiency by Season
- 3-Point Field Goals Made by Season
- Top 5 Seasons by Efficiency
- Scoring Consistency (PPG Standard Deviation)

**Advanced Concepts**
- Player-level slicers
- Seasonal trend comparison
- Consistency measured using **standard deviation**
- Conditional color formatting for interpretation

**Insights**
- Player efficiency varies significantly across seasons
- Peak scoring does not always equal peak efficiency
- Lower PPG standard deviation indicates more consistent scoring
- Some players add value beyond points through efficiency and assists

---

### 3️⃣ Team Performance & Consistency Analysis

**Purpose:**  
Compare teams based on **win %, consistency, and home vs away performance**.

**Key Visuals**
- Home vs Away Win % (Quadrant Analysis)
- Overall Win Percentage by Team
- Win % Trends Across Seasons (Top Teams)
- Most Consistent Teams (Lowest Win % Variation)

**Quadrant Interpretation**
- Top-right: Strong home & away teams
- Bottom-right: Away-resilient teams
- Top-left: Home-dependent teams
- Bottom-left: Weak overall teams

**Insights**
- Teams rarely dominate both home and away games
- High win % does not always imply consistency
- Some teams maintain stability despite league evolution

---

### 4️⃣ League Trends & Evolution Dashboard

**Purpose:**  
Understand **how the NBA has evolved over time**.

**Key Features**
- Metric selector:
  - Points
  - Assists
  - Rebounds
  - Efficiency
  - Turnovers
- Scatter plot showing:
  - Spread
  - Trend
  - Outliers

**Insights**
- Offensive output has increased league-wide
- Efficiency improves gradually but unevenly
- Turnovers remain relatively stable despite faster pace
- League parity increases in recent seasons

---

## 🧮 Key Metrics & DAX Highlights

- Win %
- Home Win %
- Away Win %
- Efficiency Score
- PPG Standard Deviation (Consistency)
- Metric switch using `SWITCH()` + slicers
- Quadrant reference lines using league averages

These measures enable **dynamic interaction and analytical depth**.

---

## 🛠 Tools & Technologies

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Data Modeling
- GitHub (Version Control & Documentation)

---

## 🔮 Future Enhancements

- Playoff vs Regular Season analysis
- Salary vs performance comparison
- Shot efficiency & zones
- Advanced efficiency metrics (PER, TS%)


## 👤 Author
Vidhi Shah
