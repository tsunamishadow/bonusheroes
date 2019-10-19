# Fortnite: Battle Royale Chapter 2, Season 1 Reference Guide

## Dates

* Release: Monday October 14th, 2019

## Experience

Experience and score has now been reworked. There are still remenants of the old scoring system.

It takes 80,000 XP to increase the Battle Pass by one level.

You can get XP by simply playing through the game and doing well (high placement, high damage, high eliminations).

Certain interative actions also earn you XP.

Supercharging works similar to the Rest system in MMORPGs (like World of Warcraft). To Supercharge the bar - Don't Play Fortnite: BR. It's that simple. While not playing Fortnite BR you gain a supercharge state depending on how long you have been away. There is a maximum that can be stored. When you play the game, your XP bar will turn yellow, show "XP SUPERCHARGED" and you will see a little lightning bolt on the bar. Until that point all XP you earn is (up to) quadrupled and will slowly consume the supercharge state.

You have a bonus to your gained XP if you purchased the Season 10 Battle Pass months ago.

Completing medals for the punchcard allows you to earn 24,000 XP a day.

## Arena Queue Scoring<a name="arenaa"></a>

At the start of Season 1 every player has been reset to 0 hype

### Division Prerequisite

| Hype Needed | Division | Name |
|------------:|----------|------|
| 0 | 1 | Open I |
| 500 | 2 | Open II |
| 1000 | 3 | Open III |
| 1500 | 4 | Open IV |
| 2000 | 5 | Contender I |
| 3000 | 6 | Contender II |
| 4500 | 7 | Contender III |
| 6500 | 8 | Champion I |
| 10000 | 9 | Champion II |
| 14000 | 10 | Champion III |

### Hype Scoring

*Duos have not currently been implemented*  
*Trios are not live currently*

| Solo Prerequisite | Duo Prerequisite | Trio Prerequisite | Squads Prerequisite | Hype Scored |
|-------------------|------------------|--------------------|---------------|---------------|
| Victory | Victory | Victory | Victory | 60 |
| Top 5 | Top 3 | Top 2 | Top 2 | 30 |
| Top 15 | Top 7 | Top 4 | Top 3 | 30 |
| Top 25 | Top 12 | Top 8 | Top 6 | 60 |

* You score hype for all placings cumulative, so a Victory will always be 180 hype.

| Size | Hype for Elimination |
|-------|---------------------:|
| Solo | 20 |
| Duos | 10 |
| Trios | 7 |
| Squads | 5 |

### Bus Fare

Bus Fares have been standardised for Season X

| Division | Bus Fare Solo | Bus Fare Trios |
|----------|---------------|--------------|
| 1-2 | 0 | 0 |
| 3 | -10 | -10 |
| 4 | -20 | -20 |
| 5 | -40 | -40 |
| 6 | -40 | -40 |
| 7 | -50 | -50 |
| 8 | -60 | -60 |
| 9 | -70 | -70 |
| 10 | -80 | -80 |

### How hard is the grind?

Assuming a player could consistently score 80 Hype in every arena game, (equivalent to Top 25 and 1 elimination) how much games would that player need to progress to the next division?

| Progression to Division: | Games Needed |
|:------------------------:|-------------:|
| 2 | 7 |
| 3 | 7 |
| 4 | 8 |
| 5 | 9 |
| 6 | 25 |
| 7 | 38 |
| 8 | 67 |
| 9 | 175 |
| 10 | 400 |

This would take this player at least 12 games per day every day throughout the season.

## Fall Damage

You will start taking fall damage when dropping from a distance of at least 13 meters. The smallest amount of fall damage you will take is 10 damage. This scales up to be lethal at 24 meters. The damage is NOT linear.

| Height in meters | Height in tiles | Damage Taken |
|------------------|-----------------|--------------|
| 13 | 3.25 | 10 |
| 16 | 4 | 25 |
| 18 | 4.5 | 40 |
| 20 | 5 | 60 |
| 24 | 6 | 100 |

## Storm Circles

These numbers are taken from a normal Solo game. Different modes, such as Blitz and Arena, may have different values and behaviors.

| Storm Circle Number | DPS | Radius | Still Time | Close Time | Storm Surge Push |
|:-------------------:|----:|-------:|-----------:|-----------:|-----------------:|
| 0 | 0 | 2600m | Varies | Varies | Doesn't |
| 1 | 1 | 800m | 3:20 | 3:00 | 60 |
| 2 | 1 | 400m | 2:00 | 2:00 | 44 |
| 3 | 2 | 200m | 1:30 | 1:30 | 30 |
| 4 | 5 | 100m | 1:20 | 1:10 | 20 |
| 5 | 7.5 | 50m | 0:50 | 1:00 | 16 |
| 6 | 10 | 25m | 0:30 | 1:00 | 14 |
| 7 | 10 | 12.5m | None | 0:55 | 12 |
| 8 | 10 | 10m | None | 0:45 | 6 |
| 9 | 10 | 0m | None | 1:15 | 2 |

Storm Circle Number: When a game starts, the game keeps count of the storm number that it currently is. Starting at 0 when the bus deploys over the island, going up to 1 when the bus has left and going up by 1 once that circle fully closes.  
DPS: The amoutn of damage the storm does to your health per second if you are in that storm.  
Radius: The radius length of the storm circle once it has finished closing. (The distance from the edge of the new circle to the centre)  
Still Time: The grace period and warning time before the storm starts to close in to the target. If there is None, the storm will start closing immediately.  
Close Time: The amount of time the Storm takes to close in to the new circle once the Still Time has ended.  
Storm Surge Push: If there are at least this many players once that storm has *finished* closing, a storm surge will activate doing damage to the players that have dealt the least amount of player damage. (I'm trying to get the exact numbers for Storm Surge, but I believe it's 20 DPS to your health). Storm Surge does NOT activate in Normal games, only in Arena.

In Arena, Storms 5 and higher move direction rather than just shrink in on themselves.
