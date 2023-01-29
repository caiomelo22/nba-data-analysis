# NBA-Data-Analysis
Project to explore the progression of a stat of a NBA team. In this project, we take the user input for a team, a stat they want to visualize and a line to set as a threshold. After that, we take the last n games of the selected team in the league for a season, displaying it's means for that stat based on a general context and on a home/away context.

The last part of the project is about giving information about the selected team. First, we display all of the last n games for the team, printing the wins in green and the losses in red. After that, we print the % of those games that the team was above the selected line for that stat. We do that both in a general context and in a home/away context.

Finally, we plot two charts. One that represents the progression of made/conceded for that stat, annotating each point with A for away games and H for home games. We also number each game so it's easier to find that matchup in the list mentioned earlier. The last chart plots the progression of totals for that stat, setting a vertical line that represents the threshold set earlier.

## Example
With the Philadelphia 76ers as a chosen team, PTS as the chosen stat and 231 as the chosen line, we would get the following charts:

![PHI - PTS Made-Conceded Progression](https://user-images.githubusercontent.com/49076270/215284241-967ffb32-a2fd-4eeb-99c5-b80514d657a1.jpg)

![PHI - PTS Totals Progression](https://user-images.githubusercontent.com/49076270/215284244-c1f45b5a-fb19-431a-ac49-7884d98a7afd.jpg)

