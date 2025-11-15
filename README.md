# IPL 2022 Performance Analysis

## Overview

This repository contains a detailed performance analysis of the Indian Premier League (IPL) 2022 season. The project focuses on analyzing key data points to uncover insights related to venue distribution, team dominance, and standout individual performances in batting and bowling. This analysis serves as a capstone project demonstrating data cleaning, processing, and visualization techniques.

---

## 🎯 Goal

The primary goal of this project is to analyze and present key findings from the IPL 2022 dataset. The analysis centers on three core areas:
1.  **Venue Distribution:** Understanding where the matches were concentrated.
2.  **Team Performance:** Identifying dominant team victories.
3.  **Individual Brilliance:** Highlighting the best batting and bowling performances of the season.

---

## 📊 Key Analyses and Insights

### 1. Venue Usage Analysis

A significant portion of the tournament was geographically concentrated in Mumbai and Pune.

-   **Key Finding:** The majority of matches were hosted at four main venues, indicating a localized tournament structure.
-   **Data Reference:** `df['venue'].value_counts()`

| Venue | Matches Hosted |
| :--- | :--- |
| Wankhede Stadium, Mumbai | 21 |
| Dr DY Patil Sports Academy, Mumbai | 20 |
| Brabourne Stadium, Mumbai | 16 |
| Maharashtra Cricket Association Stadium, Pune | 13 |
| Eden Gardens, Kolkata | 2 |
| Narendra Modi Stadium, Ahmedabad | 2 |

### 2. Highest Team Dominance (By Runs)

This analysis answers the question: *Which team achieved the largest victory margin by runs?*

-   **Analysis Method:** Filtered the dataset where `won_by` was 'Runs' and sorted by the `margin` column.
-   **Key Insight:** Chennai recorded the highest winning margin with a **91-run victory**.

### 3. Top Individual Batting Performance

This analysis identifies the highest individual score by a player in a single match.

-   **Analysis Method:** Found the maximum value in the `highscore` column (`df['highscore'].max()`).
-   **Key Insight:** **Quinton de Kock** achieved the highest individual score of the tournament with **140 runs**.

### 4. Best Bowling Figures

This analysis pinpoints the most outstanding bowling performances of the season.

-   **Analysis Method:** Identified players with the maximum value in the `highest_wickets` column.
-   **Key Insight:** While several bowlers took 5-wicket hauls, **Jasprit Bumrah's 5 wickets for 10 runs (5/10)** stood out as the most impactful spell.

| Bowler | Best Bowling Figure |
| :--- | :--- |
| Jasprit Bumrah | 5/10 |
| Wanindu Hasaranga | 5/18 |
| Umran Malik | 5/25 |
| Yuzvendra Chahal | 5/40 |

---

## 🛠️ Tools and Libraries Used

-   **Python:** For data manipulation and analysis.
-   **Pandas:** For data cleaning, filtering, and aggregation.
-   **Matplotlib / Seaborn:** For data visualization (e.g., bar plots for venue analysis).
-   **Jupyter Notebook:** As the development environment.

---

## 📜 Conclusion

The IPL 2022 season was characterized by geographical concentration, dominant team performances, and exceptional individual talent. Key takeaways include the heavy reliance on Mumbai/Pune venues, a commanding 91-run victory by Chennai, a peak batting score of 140 by Quinton de Kock, and a remarkable bowling spell of 5/10 by Jasprit Bumrah.

This project showcases a fundamental approach to sports analytics, turning raw data into meaningful insights. [web:18, web:20]
