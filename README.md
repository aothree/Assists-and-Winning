# Assists-and-Winning
The Pass is what makes basketball flow, it's what makes offense work, it's what makes defenses crumble, it's what makes basketball beautiful.  

Since the mid 80s, the pass seemingly became un-cool.  Cool was crossovers and monster jams--unequivacably "ME" plays, or 1 on 1 plays that eschew the pass in favor of flair.  It's impossible to know for sure what inspired the shift in style of play.  But looking at that line chart, and thinking about what icon of the sport came on the scene in the mid 80s...you have to think about His Airness.  

<p align="center">
  <img src="https://github.com/aothree/Passing-in-Basketball/blob/main/Visuals/Assists%20per%20game%20line%20chart.png"/>
</p>

This projects investigates passing and asks does passing more lead to winning more?  

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

