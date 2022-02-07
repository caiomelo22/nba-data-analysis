# NBA-Data-Analysis
Project to explore data from the NBA API. In this project, we take the user input for two teams, a stat they want to visualize and a line to set as a threshold. After that, we take the last 15 games of every team in the league for the 2021 season, displaying their means for that stat based on a general context and on a home/away context.

The last part of the project is about giving information about the selected teams. First, we display all of the last 15 games for a team, printing the wins in green and the losses in red. After that, we print the % of those games that the team was above the selected line for that stat. We do that both in a general context and in a home/away context.

Finally, we plot two charts. One that represents the progression of made/conceded for that stat, annotating each point with A for away games and H for home games. We also number each game so it's easier to find that matchup in the list mentioned earlier. The last chart plots the progression of totals for that stat, setting a vertical line that represents the threshold set earlier.

## Example
For the the Milwaukee Bucks as a chosen team, PTS as the chosen stat and 227 as the chosen line, we would get the following charts:

![MIL - PTS Made-Conceded Progression](https://user-images.githubusercontent.com/49076270/152710351-8ded5015-11e0-4ec0-95c1-8c619f085ecb.jpg)

![MIL - PTS Totals Progression](https://user-images.githubusercontent.com/49076270/152710357-79b381c5-995f-4a02-a1be-ad0d665afcc3.jpg)
