# GAMEPLAY UPDATE 7.20+b+c+d

### GENERAL

#### MAP CHANGES

-   All side lanes are now lowground (same elevation as mid)
-  Jungles are now partially highground, all shrines are now situated on highground spaces.
- River has been extended to the Dire Top Bounty Rune
- Moved positions of Radiant Tier 1 Mid and Top tower, and Radiant Tier 2 Mid and Bottom tower
- Moved position of the dire bot bounty rune to be closer to the river (eroded cliff for more river space)
- Trees and rocks are added to simulate vision block from removed cliffs.
- Re-positioned stairs and cliffs
- Other minor tree placements
- Fountain damage now cancels effects similar to hero damage (e.g. salve, heart, blink), and now has 25% Accuracy (Note: This change was added in an update last week)

#### DENY MECHANICS

-   Denies no longer give the denier 25% XP
-   Creep denies now give the denier 20% of the gold bounty
-- Melee creeps 7-8 Gold
-- Ranged creeps 9-11 Gold

#### TELEPORTING

-   Added a new dedicated inventory slot to hold Town Portal Scrolls
-- You must still purchase Scrolls as usual
-   **Boots of Travel:**  No longer shares cooldown with Town Portal Scrolls. Upon teleporting, +10 seconds are now added to your Town Portal Scroll cooldown

#### NEUTRALS

-   Stacked Neutral creeps now give the stacker 35% of the bounty instead of 25%
-   Non-Ancient Neutrals now provide 5% more gold bounty

#### HERO SELECTION

-   Removed Daily Bonus Hero concept
-   Random once again picks from the entire hero pool, but now ignores your 25 least played heroes
-- Bonus for randoming provide One Locked Faerie Fire and One Locked Mango
-   Random can now only be used for the first two hero picks on your team

#### ARMOR

-   Changed the Armor formula to: ( 0.052 * Armor ) / ( 0.9+ 0.048 * Armor)
-- Was previously ( 0.05 * Armor ) / ( 1 + 0.05 * Armor)
-   Updated various armor values to closely align with the new formula:
    
    > -   Tier 1 Towers: 17 to 12
    > -   Tier 2 Towers: 19 to 14
    > -   Tier 3 Towers: 19 to 14
    > -   Tier 4 Towers: 29 to 21
    > -   Melee Barracks: 18 to 13
    > -   Ranged Barracks: 12 to 9
    > -   Ancient: 18 to 13
    > -   Fillers: 14 to 10
    > -   Shrines: 24 to 17
    

#### HERO KILL BOUNTY XP

-   Killing Sprees now give an XP bonus ranging from 200 to 1250
-   Reworked and simplified XP hero kill bounty system. No longer includes a team XP component
---
Old:  
  
===  
Amount per player in each scenario:  
  
1: DyingHeroBaseXPBounty + 20 * DyingHeroLevel + 0.138 * XPComeback  
2: DyingHeroBaseXPBounty + 15 * DyingHeroLevel + 0.138 * XPComeback  
3: DyingHeroBaseXPBounty + 10 * DyingHeroLevel + 0.12 * XPComeback  
4: DyingHeroBaseXPBounty + 7 * DyingHeroLevel + 0.09 * XPComeback  
5: DyingHeroBaseXPBounty + 5 * DyingHeroLevel + 0.072 * XPComeback  
  
  
DyingHeroBaseXPBounty: The base XP values given for kills.  
  
DyingHeroLevel: Numerical level for the dying hero  
  
XPComeback: DyingHeroXP * ( EnemyTeamXP - AlliedTeamXP ) / ( EnemyTeamXP + AlliedTeamXP)  
  

New:

===

All: ( 40+ 0.14 * DyingHeroXP ) / # of killers

----
#### MANA AND HP REGEN

-   Reworked Mana and HP regen from attributes. They are no longer multipliers of your regeneration values  
    
-   Mana Regen: Intelligence now provides 0.05 mana regeneration  

-   Mana Regen: Removed the 0.9 base mana regen value
-- Now covered by Base Intelligence

-   Mana Regen: Rebalanced mana regen values based on the formula change  
