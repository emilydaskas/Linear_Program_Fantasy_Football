# Fantasy-Football-Linear-Program
Project to create a linear program which creates an optimal fantasy football lineup.

## Data:

fantasy_football_data.csv

Features: Name, Position, Team, Projected Points, Price

## Parameters
- max budget of 200
- roster has exactly 15 players
- roster has 1 QB, 3 WR, 2 RB, 1 TE, 1 K, 1 DEF, 6 Bench
- a slot can only be taken up by a player of that type
- a Bench slot can be ay player type
* a player on your roster can only be assigned to one slot
* at most 2 QB and 2 TE on your roster
* at most 1K and 1DEF on your roster
* a player on bench will only generate 1/2^d of their project points 
    * d is the depth of their position
        * example: you have RB1, RB2, RB3, RB4 on your team with projected points P1, P2, P3, P4
        * the expacted points from these player would be P1 + P2 + 1/2 * P2 + 1/4 * P3

## Questions to Answer
Who would you choose to maximize points while staying within budget?
How many points is your team expected to generate?
How much of your budget did you spend?

## Emily Daskas
