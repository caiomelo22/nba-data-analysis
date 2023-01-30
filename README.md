# NBA-Data-Analysis
Project to explore the progression of a stat of a NBA team. In this project, we take the user input for a team, a stat they want to visualize and a line to set as a threshold. After that, we take the last n games of the selected team in the league for a season, displaying it's means for that stat based on a general context and on a home/away context.

The last part of the project is about giving information about the selected team. First, we display all of the last n games for the team, printing the wins in green and the losses in red. After that, we print the % of those games that the team was above the selected line for that stat. We do that both in a general context and in a home/away context.

Finally, we plot three charts. One that represents the progression of made/conceded for that stat, annotating each point with A for away games and H for home games. We also number each game so it's easier to find that matchup in the list mentioned earlier. The second chart plots the progression of totals for that stat, setting a vertical line that represents the threshold set earlier. And last, but not least, the final chart plots the relationship between the made and conceded for that specific stat with a scatterplot chart.

## Example
With the Philadelphia 76ers as a chosen team, PTS as the chosen stat and 231 as the chosen line, we would get the following charts:

![PHI - PTS Made-Conceded Progression](https://user-images.githubusercontent.com/49076270/215479058-76bc77be-690d-412e-a7de-768a50970769.jpg)

![PHI - PTS Totals Progression](https://user-images.githubusercontent.com/49076270/215479206-18ea3006-3226-49a6-af00-c2c0c79cf243.jpg)

![PHI - PTS Made-Conceded Scatter Progression](https://user-images.githubusercontent.com/49076270/215478832-7f27b42c-39a5-42c4-97fb-042113aeb0d1.jpg)


