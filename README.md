# T20 Cricket Player Performance Analysis

### [Live Interactive Dashboard Link]([Your-Power-BI-Publish-to-Web-Link-Here](https://github.com/Barrie20/ricket-Player-Performance-Analysis-PowerBI/blob/main/Data/17.%20ESPN.pdf))

---


This project presents a comprehensive analysis of T20 cricket players' performance across three key areas: **batting, bowling, and fielding**. The primary objective was to leverage data visualization to identify top performers and uncover insights from complex match data. I developed an interactive dashboard using Power BI to provide a clear and dynamic view of player statistics.

---

## Data Source

The dataset was sourced from **ESPN Cricinfo** and contains detailed T20 player statistics. The raw data includes multiple tables covering batting, bowling, and fielding metrics, which were cleaned and modeled for this analysis.

* **Column Definitions:** Detailed explanations for each metric used in the analysis are provided in the `/data` folder.

---

## Tools & Technologies

* **Data Cleaning & Modeling:** Microsoft Excel, Power Query
* **Data Analysis:** DAX (Data Analysis Expressions)
* **Data Visualization:** Power BI
* **Version Control:** Git & GitHub

---

## Project Methodology

1.  **Data Extraction & Cleaning:** The raw data was imported into Power BI. I used Power Query to clean and transform the data by handling missing values, correcting data types, and splitting columns to ensure data integrity.
2.  **Data Modeling:** I established relationships between the batting, bowling, and fielding tables to create a unified data model. This allowed for cross-functional analysis within the dashboard.
3.  **DAX Measures:** I developed over 15 custom DAX measures to calculate key performance indicators (KPIs) such as Batting Average, Strike Rate, Bowling Economy, and Fielding Dismissals per Match.
4.  **Dashboard Development:** I designed a multi-page interactive dashboard with dedicated views for each aspect of player performance. The design focuses on intuitive navigation and clear data storytelling.

---

## Key Insights & Findings

* **Batting:** The analysis highlighted the top 5 batsmen with the highest strike rates who also maintained an average above 30, identifying them as the most effective power-hitters.
* **Bowling:** By analyzing bowling economy against the number of wickets taken, the dashboard identified several "economy-strikers"—bowlers who are both cost-effective and effective at taking wickets.
* **Fielding:** The dashboard revealed a strong correlation between the number of catches taken and a team's overall win percentage, underscoring the importance of a strong fielding unit.

---

## Dashboard Preview

Here is a glimpse of the three main pages of the dashboard.

#### Batting Analysis
*This dashboard showcases key batting metrics like total runs, strike rate, averages, and performance against different teams.*
![Batting Dashboard](10.%20Batting.png)

#### Bowling Analysis
*This view focuses on bowler effectiveness, visualizing wickets taken, economy rates, and performance in different phases of the game.*
![Bowling Dashboard](10.%20Bowling.png)

#### Fielding Analysis
*This section analyzes fielding contributions, including catches, stumpings, and run-outs to identify the most impactful players on the field.*
![Fielding Dashboard](10.%20Fielding.png)
