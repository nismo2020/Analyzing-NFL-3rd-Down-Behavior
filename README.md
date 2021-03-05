# Analyzing NFL 3rd Down Behavior
## Executive Summary
In the National Football League, events are broken into individual plays called downs. During each possession, a team gets four downs to obtain ten yards to keep possession of the ball. However, if a team does not obtain ten yards within its first three downs, it will kick the ball away on its fourth down. This puts an onus on 3rd down plays. This analysis looks at play selection during the critical third down (should they pass or run). Many teams will run the ball on 3rd down and short yardage situations (typically defined as three yards or less to go), because they believe this to be the optimal choice. Third down success rate varies significantly depending on yards to go to convert a first down. 

Because 4th downs are essentially an acceptance of the drive ending, 3rd down becomes essential. Gaining the necessary amount of yards and converting the 3rd down keeps the drive going and allows a team the opportunity to score points. Decision making on 3rd down is key, especially to coaches and player-personnel decision makers. There is a high turnover of NFL coaches. In a league with 32 franchises, 68 coaches were fired in the past 10 years. The average tenure of an NFL coach is four seasons. In this highly competitive environment, it is vital to use data to gain the extra edge in game situations. As 3rd down is arguably the most important down in the game, one that swings possession and games, coaches are key stakeholders for this insight.

## Motivation
My motivation for this project is my life long love of football. Growing up in Texas, football was not just a sport, it was religion. On a typical Friday night in any town across Texas you could hear the band playing the school fight song, cheerleaders cheering at the top of their lungs, parents proudly hoisting homemade posters in support of the team, and the student body feverishly rooting for their friends. Is there anything that can bring a community closer than a Friday night high school football game? The part of the game that has intrigued me the most is the play calling strategy.

## Data Question
I can't count how many times I am watching a football game where a team has called a play on third down that has left me confused and frustrated? The commentators may have remarked that it was the “smart” or “safe” play, leading you to believe that you must be wrong because the football experts must know what they’re talking about. I don't believe I am alone. I find myself in this situation every Sunday, so I wanted to analyze play data to determine what play is best to call on third down (run or pass).

## Minimum Viable Product (MVP)
To investigate 3rd down behavior, I obtained play-by-play data from NFL Savant. The datasets were for every play from the 2013 NFL season to December 10th of the 2020 season. I used Python as my programming language of choice for exploratory data analysis (EDA) and creating my datasets, as Python is an open source and has thousands of libraries that allow for vast functionality. Then I used Tableau for further analysis and to create my presentation.

To start my main analysis of 3rd down plays. I created a new data frame, which only included 3rd down plays which were a run or pass (excluding field goals, penalties, etc). I added a new categorical column named “Distance”, which signified how many yards a team had to go to convert the first down. Using conventional NFL definitions, I decided on this:


## Technologies Used
* Python 3
* Jupyter Notebook
* Tableau
* Excel

## Link
https://public.tableau.com/profile/carroll.piker#!/vizhome/NFL3rdDownBehavior/Story-NFL3rdDownBehavior
