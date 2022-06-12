# Assists-and-Winning
The Pass is what makes basketball flow, it's what makes offense work, it's what makes defenses crumble, it's what makes basketball beautiful.  

Since the mid 80s, the pass seemingly became un-cool.  Cool was crossovers and monster jams--unequivacably "ME" plays, or 1 on 1 plays that eschew the selfless pass in favor of flair.  It's impossible to know for sure what inspired the shift in style of play.  But looking at that line chart, and thinking about what icon of the sport came on the scene in the mid 80s...you have to think about His Airness.  And then an MJ disciple, Kobe Bean Bryant, carried that style of play torch into the 2000s.   

<p align="center">
  <img src="https://github.com/aothree/Passing-in-Basketball/blob/main/Visuals/Assists%20per%20game%20line%20chart.png"/>
</p>

But then around 2013-14, something happens.  Assists go up.  My theory as to why?  The 2013-14 San Antonio Spurs played some breathtakingly beautiful basketball in beating the Miami Heat in the Finals.  But it wasn't just that they beat the Heat, it was how they did it.  The Spurs averaged 25 assists per game to Miami's 15. Over those whole playoffs, the Spurs averaged 313 passes per game vs. Miami's 278.   

This projects aims to two different things: 

1. Investigate assists per game and see if there is evidence that more assists lead to more wins.

2. Investigate total passes themselves.  Since we only have `total passes` tracked since 2013-14, what's happened since then?

## Method

Scrape all NBA team statistics from 1980-2022 from https://www.basketball-reference.com, clean and merge these statistics into a dataframe.  

## Results

1. A higher number of assists surprisingly does not lead to a higher winning %.  

2.  Even more surprising is the data shows the opposite.  Here is the distribution of `Assists per game` for all teams from 1980-2022:

<p align="center">
  <img src="https://github.com/aothree/Assists-and-Winning/blob/main/Visuals/Assists%20per%20Game.png"/>
</p>

* The teams in the 75th percentile and better for `Assists per game` have a collective winning % of .477 (the equivalent of winning 39 games).

* The teams in the 25th percentile or worst for `Assists per game` have a collective winning % of .589 (the equivalent of winning 48 games).

3. Total passes are down since that epic '13-'14 Spurs team.  

