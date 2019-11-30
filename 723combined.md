# GAMEPLAY UPDATE 7.23+a+b

## GENERAL

### COURIER

* Each player now has their own courier automatically
* Courier now gains levels when your hero gains levels
* Courier movement speed reduced from 380 to 275
* Courier health reduced from 75 to 70
* Courier now provides 85 GPM while it is alive (this replaces the base 91 GPM that previously existed)
* Courier passively gains +10 movement speed, +10 health and +2 GPM increase per level
* Courier gains flying movement at level 5
* Courier gains Speed Burst active ability at level 10 (6-second duration +50% MS, 120 CD)
* Courier gains ability to use wards at level 15
* Courier gains Shield active ability at level 20 (2s duration, 200 CD)
* Courier gains ability to use items in general at level 25
* Courier vision reduced from 350 to 200
* Courier team bounty is now 25 + 5 * Level
* Courier respawn time changed from 120/180 ground/flying to 50 + 7 * Level
* Courier Return Items ability will now cause the courier to return home even if it doesn't have items

### ECONOMY

* Observer Wards no longer cost gold  
*they still have a stock and restock time*
* Heroes now start with 3 Town Portal Scrolls
* Gold earned from killing an Observer Ward will now always be given to the player that bought the true sight  
*will be given to the player that first gave the true sight on the ward provided it is still there when the ward is killed*
* Heroes that have recently applied damage or a debuff on an enemy hero that dies are now considered part of the area assist gold even if they are no longer alive or in that area
* Assist gold distribution multiplier for Net Worth ranking factor in the area is changed from multiplying based on the heroes in the area, to globally.  
*this means that if you helped for an assist, but are not near enough for assist gold, now you are*
* Net Worth Ranking factor for Gold changed from 1.3->0.7 to 1.6->0.4  
*heroes that assisted on the lower end of the networth table will get more gold for an assist, while richer heroes get less*

### GENERAL

* Map layout redesigned  
** Both ancient camps are now on the opposite side of Roshan pit  
** Roshan pit has moved slightly northwest and rotated slightly counter-clockwise  
** Bounty runes have now moved to 2 into the river near Secret Shops and 1 at the former Side Shops  
** Slightly moved position of secret shops  
** Highground jungles are smaller in all four quadrants  
** Some jungle camps are moved to low ground  
** Replaced some stairs with new ones added to get from river to highground  
** River reshaped and made wider near the ends  
** Moved central filler building in Radiant base to be closer to the the tier 4 towers  
** Moved aroudn trees and some small cosmetic changes to the map  
** Moved around eye spots and added a new eyespot on the safe side jungles  

####
* Heroes can now level up to 30. Once you get to level 30, you unlock the entire talent tree. XP requirement for the levels are 3500/4500/5500/6500/7500. Respawn time does not increase past 25. XP bounties max out at level 25 bounty values.  
** Note 1: A quick refresher on how this currently works: Spells have two properties: 1) whether it applies to Spell Immune targets, and 2) what the damage type is. These are listed in the ability tooltips.  
** Note 2: This change means that if something pierced immunity before, and was magical damage, it will now do damage. If it didn't pierce spell immunity before, it will still not deal any damage.

####
* Removed Side Shops
* Bottle has been removed from the Secret Shop
* All Secret Shop items are now exclusively in the Secret Shop (this means Ring of Health and Void Stone are no longer in the base)

####
* Tier 2 Towers HP increased from 1900 to 2000
* Tier 2 Tower Armor increased from 15 to 16
* Tier 2 Tower Damage increased from 152 to 175
* Tier 2+ towers night vision increased from 800 to 1100
* Tower Glyph multishot targets increased from 2 to 4
* Glyph duration increased from 6 to 7

####
* Improved input processing to feel snappier, as well as fixing some rare input drop bugs
* Denied towers now give half of the bounty to the team that denies it and half to the other team (instead of 0 to both teams)
* Siege damage against heroes increased from 85% to 100%  
** These affect: Fountain, Siege Creeps and every Tower  
* Fountain damage increased from 230 to 275  
** Fountain damage effectively increased by 40%
* Fountain now has 20% Accuracy

### NEUTRAL UNITS BALANCE

* Neutral Cloak Aura no longer stacks  
** This was the Magic Resistance aura found on some smaller creeps
* Neutral Harpy Stormcrafter: Max mana reduced from 400 to 150
* Neutral Harpy Stormcrafter: Mana regeneration increased from 1 to 3
* Neutral Mud Golem: Hurl Boulder damage reduced from 125 to 75
* Neutral Ghost: Frost Attack move slow from 20 to 25%
* Neutral Ghost: Frost Attack attack slow from 20 to 25%
* Neutral Vhoul Assassin: Poison debuff now applies 35% Regen Reduction
* Neutral Centaur Conqueror: War Stomp cooldown reduced from 20 to 12
* Neutral Dark Troll Summoner: Ensnare cooldown reduced from 20 to 15
* Neutral Dark Troll Summoner: Raise Dead cooldown reduced from 25 to 18
* Neutral Ancient Thunderhide: War Drums Aura no longer provides attack damage bonus
* Neutral Ancient Thunderhide: War Drums Aura now provides 40% Accuracy
* Neutral Ancient Thunderhide: War Drums Aura attack speed bonus increased from 15 to 25
* Neutral Ogre Frostmage: Armor bonus reduced from 8 to 6
* Neutral Ogre Frostmage: Slow now works against ranged units as well
* Neutral Ogre Frostmage: Attack slow increased from 20 to 30

### OUTPOSTS
Added a new neutral building type - Outposts  

There are two of these on the map, located where the Side Shops were previously. Right clicking to channel it takes 6 seconds and then you gain control over the outpost. Converts faster with more allies channeling. Having control over an outpost grants you bonus XP upon initially capturing it, and at 5-minute intervals on the game clock. It also provides your team unobstructed vision in that area and allows you to TP to it. Outposts are inactive for the first 10 minutes of the game and cannot be captured then.

* XP bonus is 25 * Min XP to each player
* Provides 500 AoE truesight
* Only gains XP bonus once per period regardless if you have one or two outposts controlled
* Takes 6 seconds to teleport to it (shares the delayed TP duration mechanic with T1 towers)

### NEUTRAL ITEMS

Neutrals now drop unique items that cannot be sold, but can be shared with allies. There are five tiers of items that drop over the course of the game. Within each tier, the odds get cut by half for each subsequent drop. Items of a specific type will only drop once for each team. Drops only begin after 7 minutes.

There are 61 unique neutral items in total.

Backpack slots increased from 3 to 4

NEUTRAL DROP MECHANICS  
7+ MINUTES
Tier 1: 9% Chance

15+ MINUTES
Tier 2: 9% Chance

25+ MINUTES
Tier 3: 9% Chance

40+ MINUTES
Tier 4: 9% Chance

70+ MINUTES
Tier 5: 9% Chance

These are the odds for the first drop of each tier - Each subsequent drop drops to 6% then 3%. Drop chances use Pseudo Random on a per team basis. Only rolls for a drop whenever there is a real hero near the dying neutral. Neutral drops will only drop 3 items per tier. Higher tier items will always roll first.
