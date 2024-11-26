#Football Analysis: Penalty Shootouts and Home Team Advantage

**Objective**

This project analyzes the impact of home-team advantage and the first shooting team in penalty shootouts. 
Also examines the outcomes of games played by European national teams during UEFA Euro Qualification, UEFA Nations League, and FIFA World Cup Qualification over the past 30 years, where neutral = False.

The analysis explores:
How playing at home influences penalty shootout outcomes.
The advantage (if any) of the team shooting first in penalties.
The home team results in Uefa national teams competitions 

**Features**

Data-driven insights into penalty shootout trends for European teams.
Exploration of historical data spanning 30 years.
Visualization of key findings using Python and Seaborn.

**Technologies Used**

Python
Pandas: For data manipulation and analysis.
Seaborn: For creating visualizations.

**Instructions**

Download the dataset from Kaggle: International Football Results from 1872 to 2017.
Clone this repository or download the project files.
Open the football_analysis.ipynb file using Jupyter Notebook.
Place the dataset in the same directory as the notebook or adjust the file path in the code.
Run the cells step by step to reproduce the analysis.

**Data Source**

The dataset used in this project is sourced from Kaggle, containing results of international football matches.

https://www.kaggle.com/datasets/martj42/international-football-results-from-1872-to-2017/data
-----

 ***Key Findings***
 
**Penalty Shootouts**

  *Home-Team Advantage:*

Home teams slightly outperform away teams in penalty shootouts, with a win ratio of 53.5% to 46.5%.
However, the lack of tournament-specific data makes it difficult to conclude whether this advantage is significant.
For example, Greece participated in three shootouts (friendly, World Cup knockout, Euro qualification), losing all as the away team.

  *First Shooter Advantage:*

Teams that shoot first in penalties have a minor advantage, with a win ratio of 53.9% to 46.09%.
This may be due to increased pressure on the second team to match the initial score.

*Notable Performers:*

Germany leads with a 75% success rate in penalty shootouts.
The Netherlands has the lowest success rate, winning only 20%.
Argentina has played the most shootouts (23), winning 15 of them (65.22%).


**UEFA National Team Matches**

*Impact of Competition Format:*

Since 2000, the total number of matches increased due to the introduction of the UEFA Nations League, replacing friendlies.
Home-team win percentages dropped below 40% during the COVID-19 pandemic (2020–2021), when many games were played without spectators.
A similar dip in home wins occurred in 2000 and 2004, though the cause is unclear.

*Competition-Specific Trends:*

Home wins are lowest in the Nations League due to closely matched teams and lower stakes, leading to more draws.
Straight qualification formats (Euro and World Cup qualifiers) see higher home-win rates as teams are more motivated to secure a win.

*Statistical Insights:*

Home wins exhibit the largest variance over time, reflecting their inconsistency.
Away wins are more stable, with the smallest variance and range.
In 2024, home wins are at their highest-ever percentage, while away wins have reached a record low.

-----
**Contributions**
Contributions are welcome! Feel free to fork this repository and submit a pull request with your improvements or suggestions.

**License**
This project is for educational and personal use. Ensure proper attribution when using the dataset or insights from this analysis.
