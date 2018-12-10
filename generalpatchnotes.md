# GAMEPLAY UPDATE 7.20+b+c+d+e

## GENERAL

### MAP CHANGES

-   All side lanes are now lowground (same elevation as mid)
-  Jungles are now partially highground, all shrines are now situated on highground spaces.
- River has been extended to the Dire Top Bounty Rune
- Moved positions of Radiant Tier 1 Mid and Top tower, and Radiant Tier 2 Mid and Bottom tower
- Moved position of the dire bot bounty rune to be closer to the river (eroded cliff for more river space)
- Trees and rocks are added to simulate vision block from removed cliffs.
- Re-positioned stairs and cliffs
- Other minor tree placements
- Fountain damage now cancels effects similar to hero damage (e.g. salve, heart, blink), and now has 25% Accuracy (Note: This change was added in an update last week)

### DENY MECHANICS

-   Denies no longer give the denier 25% XP
-   Creep denies now give the denier 20% of the gold bounty
-- Melee creeps 7-8 Gold
-- Ranged creeps 9-11 Gold

### TELEPORTING

-   Added a new dedicated inventory slot to hold Town Portal Scrolls
-- You must still purchase Scrolls as usual
-   **Boots of Travel:**  No longer shares cooldown with Town Portal Scrolls. Upon teleporting, +10 seconds are now added to your Town Portal Scroll cooldown

### NEUTRALS

-   Stacked Neutral creeps now give the stacker 35% of the bounty instead of 25%
-   Non-Ancient Neutrals now provide 5% more gold bounty

### HERO SELECTION

-   Removed Daily Bonus Hero concept
-   Random once again picks from the entire hero pool, but now ignores your 25 least played heroes
-- Bonus for randoming provide One Locked Faerie Fire and One Locked Mango
-   Random can now only be used for the first two hero picks on your team

### ARMOR

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
    

### HERO KILL BOUNTY XP

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
### MANA AND HP REGEN

-   Reworked Mana and HP regen from attributes. They are no longer multipliers of your regeneration values  
    
-   Mana Regen: Intelligence now provides 0.05 mana regeneration  

-   Mana Regen: Removed the 0.9 base mana regen value

--   Now covered by Base Intelligence

-   Mana Regen: Rebalanced mana regen values based on the formula change  

| Item                      | Old  | New  |
|---------------------------|------|------|
| Aether Lens               | 1.25 | 3    |
| Battle Fury               | 2.25 | 3.75 |
| Bloodstone                | 2    | 3    |
| Bloodstone charge         | 0.35 | 0.3  |
| Bloodthorn                | 2.25 | 5.5  |
| Bottle                    | 20   | 30   |
| Clarity Potion            | 3    | 4.5  |
| Drum of Endurance         | 0.75 | 1.5  |
| Echo Sabre                | 0.75 | 1.25 |
| Eul's Scepter of Divinity | 2.25 | 5    |
| Infused Raindrop          | 0.5  | 0.75 |
| Linken's Sphere           | 2.25 | 5    |
| Lotus Orb                 | 1.75 | 4    |
| Medallion of Courage      | 0.5  | 0.75 |
| Meteor Hammer             | 1.5  | 3    |
| Necronomicon 1            | 1    | 2    |
| Necronomicon 2            | 1.25 | 2.5  |
| Necronomicon 3            | 1.5  | 3    |
| Oblivion Staff            | 0.75 | 1.25 |
| Orchid Malevolence        | 2.25 | 5.5  |
| Perseverance              | 1.5  | 2    |
| Refresher Orb             | 5    | 12   |
| Ring of Basilius          | 0.5  | 0.75 |
| Sage's Mask               | 0.5  | 0.75 |
| Scythe of Vyse            | 2.25 | 9    |
| Solar Crest               | 1    | 1.5  |
| Spirit Vessel             | 1    | 1.5  |
| Urn of Shadows            | 1    | 1.5  |
| Vladmir                   | 1    | 1.75 |
| Void Stone                | 1    | 1.75 |


| Ability          | Old             | New             |
|------------------|-----------------|-----------------|
| Chemical Rage    | 3/7.5/12        | 4/10/16         |
| Arcane Aura Self | 1.8/2.6/3.4/4.2 | 2.4/4.4/6.4/8.4 |
| Arcane Aura Ally | 0.8/1.0/1.2/1.4 | 1.2/1.7/2.2/2.7 |
| Hill Troll Prst  | 1.5             | 2.5             |
| Death Pulse      | 2.25/2.5/2.75/3 | 3/4/5/6         |

-- All mana regen talents have been upgraded to 3 Mana/second except for Omniknight with 5 Mana/second and Techies with 6 Mana/second

-   Health Regen: Strength now provides 0.1 Health Regeneration  
    
-   Health Regen: Base regen values reduced by 1.5
-- Now covered by Base Strength
    
-   Health Regen: Rebalanced health regen values based on the formula change

| Item                  | Old | New |
|-----------------------|-----|-----|
| Abyssal Blade         | 7   | 10  |
| Armlet of Mordiggian  | 4   | 5   |
| Battle Fury           | 6   | 7.5 |
| Bottle                | 40  | 50  |
| Crimson Guard         | 6   | 7   |
| Enchanted Mango       | 0.5 | 0.6 |
| Force Staff           | 2   | 2.5 |
| Guardian Greaves      | 3.5 | 4.5 |
| Boosted Greaves       | 12  | 16  |
| Helm of Iron Will     | 3   | 3.5 |
| Helm of the Dominator | 7   | 8.5 |
| Hood of Defiance      | 6.5 | 8   |
| Hurricane Pike        | 2   | 2.5 |
| Linken's Sphere       | 5.5 | 6.5 |
| Lotus Orb             | 5.5 | 6.6 |
| Mekansm               | 3.5 | 4.5 |
| Meteor Hammer         | 4   | 5   |
| Nullifier             | 5   | 6   |
| Perseverance          | 5.5 | 6   |
| Pipe of Insight       | 6.5 | 8   |
| Pipe Aura             | 2   | 3   |
| Refresher Orb         | 11  | 13  |
| Ring of Health        | 5   | 6   |
| Ring of Regen         | 1.5 | 2   |
| Soul Ring             | 2   | 2.5 |
| Tranquil Boots        | 13  | 16  |
| Vanguard              | 5.5 | 7   |
| Veil of Discord       | 5   | 6   |

| Ability                              | Old             | New           |
|--------------------------------------|-----------------|---------------|
| Chemical Rage                        | 40/55/70        | 50/75/100     |
| Dragon Blood                         | 4/6/8/10        | 4/7/10/13     |
| Press the Attack                     | 30/35/40/45     | 30/40/50/60   |
| Reactive Armor                       | 1/1.15/1.3/1.45 | 1/1.2/1.4/1.6 |
| Inner Vitality threshold heal factor | 22/30/38/46%    | 20/40/60/80%  |
| Inner Vitality normal heal factor    | 6/8/10/12%      | 5/10/15/20%   |
| Death Pulse health regen             | 2/3/4/5         | 2/3.5/5/6.5   |
| Cold Embrace                         | 10              | 15            |
| Sancturary (Shrine)                  | 75              | 90            |

| Hero (Talent)  | Old | New |
|----------------|-----|-----|
| Undying        | 8   | 10  |
| Riki           | 5   | 6   |
| Slardar        | 5   | 6   |
| Spectre        | 5   | 6   |
| Kunkka         | 10  | 12  |
| Spirit Breaker | 10  | 12  |
| Io             | 15  | 16  |
| Underlord      | 20  | 25  |
| Axe            | 20  | 25  |
| Bristleback    | 20  | 25  |
| Sand King      | 35  | 50  |

### ROOT MECHANICS

-   **Town Portal Scroll:**  Can now be canceled and prevented by Root
-   Fixed inconsistencies between different Root sources:
    
    > -   Stasis Trap now provides True Sight
    > -   The following roots no longer interrupt channeling spells or the current action: Dark Troll Ensnare, Searing Chains, Naga Siren Ensnare, Crystal Maiden Frostbite, Entangling Claws, Nature's Guise, and Overgrowth
    

### CLEAVE AND SPLASH CHANGES

-   Cleave damage is now normal physical damage type, causing it to get reduced by the armor of each unit impacted
-   Cleave abilities damage values have been rescaled
-- Tidebringer increased from 150% to 165%
-- Empower cleave damage increased from 20/30/40/50% to 30/45/60/75%
-- Great Cleave damage increased from 40/50/60/70% to 45/60/75/90%
-- Phantom Assassin cleave talent increased from 20% to 30%
-- Alchemist cleave talent increased from 30% to 40%
-- Doom cleave talent increased from 100% to 130%
-   Increased standard Cleave area. Distance increased from 625 to 650, final width increased from 330 to 360  
    Affects: Great Cleave, Empower, Battle Fury, and Talents
  
-   **Templar Assassin:**  Psi Blades can now spill off of illusions
-   Changed how illusions' incoming damage is processed; it now happens at the final step
-- Thus it wont splash over extra damage with things like Psi Blades.
  
  
-   Fixed Splash damage being affected by Spell Lifesteal and Spell Amplification
-   Fixed Splash damage not considering armor type
-   Black Dragon Splash Attack damage type changed from Magical Damage to Physical Damage
-   Black Dragon Splash Attack now does its full damage in the 250 AoE
-- Instead of 100% at 150, 75% at 225, and 50% at 300.
-   Similar adjustments to Dragon Knight's splash damage described below

### SPELL IMMUNITY AND DISPELS

-   The following abilities no longer pierce Spell Immunity: Curse of Avernus, Acid Spray, Bloodrage, Thirst, Elder Dragon Form, Lycan Wolf Cripple, Epicenter, Entangling Claws, Spiderling's Poison Sting, Anchor Smash, Nature's Guise, Wave of Terror, Venomancer's Poison Sting, The Swarm, Maledict debuff, Ghost Frost Attack, Wrath of Nature, Netherward Mana Degen, Life Drain targeting, Primal Roar Secondary Knockback, Requiem of Souls, March of the Machines collision, Atrophy Aura, Tombstone, Flesh Golem, Wall of Replica slow, Naga Siren Ensnare, Dark Troll Summoner Ensnare, Wild Axes, Natural Order, Death Pulse projectile, Assassinate, Shiva's Guard Aura, Assault Cuirass Aura, Tempest Tornado Aura, and Orb of Venom
  
-   **Black King Bar:**  Recipe cost increased from 1375 to 1450
  
-   Poison Sting can now be dispelled
-   Hex state can now be removed by strong dispels
  

### TOWERS AND STRUCTURES

-   Towers no longer gain extra armor per nearby enemy hero. Tower health increased to account for some of this:
    
    > -   Tier 1 Towers health increased from 1600 to 1800
    > -   Tier 2 Towers health increased from 1600 to 1900
    > -   Tier 3 Towers health increased from 1600 to 2000
    > -   Tier 4 Towers health increased from 1600 to 2100
    
-   Melee Barracks health increased from 2000 to 2200
-   Ranged Barracks health increased from 1200 to 1300
-   Ancient health increased from 4250 to 4500

### MISC CHANGES

-   Day/Night cycle increased from 4 minutes to 5 minutes
  
-   Scan no longer ignores units in the Roshan pit
  
-   Max attack speed increased from 600 to 700
  
-   Default aura range increased from 900 to 1200
-- Gem of True Sight, Heartstopper Aura, Tower Aura and Natural Order remain unchanged.
  
-   Removed movement speed modifiers from spawned creeps
-- Previously different lanes would have faster/slower creeps during the first 7.5 minutes of the game

-   Added a new sound that gets played when all of a team's barracks are destroyed
-   Opening secondary shops now highlights the items in the full shop UI, rather than switching to a filtered view
-   AoE of other wards are now shown during ward placement
  
-   Added a new game state, Leashed. Leashed units follow the same rules as rooted units with regards to teleport and mobility based abilities, but can still use normal movement. The following abilities now apply the Leashed state: Pounce, Dream Coil and Soulbind
  
-   Self damage no longer disables things like Clarity, Bottle, Blink, etc
  
-   Lifesteal amount is no longer limited by the current HP of the target and uses the full damage you are dealing instead
  
-   Backpack can no longer be manipulated while taunted
  
-   Reduced the following movement speed talents: Abaddon (25->20), Axe (40->30), Bane (65->50), Batrider (50->40), Bounty Hunter (25->20), Dazzle (50->40), Enchantress (25->20), Legion Commander (50->40), Lich (25->20), Naga Siren (25->20), Nature's Prophet (35->25), Night Stalker (45->40), Nyx Assassin (35->30), Ogre Magi (90->75), Oracle (65->50), Outworld Devourer (35->30), Pangolier (25->20), Pugna (25->20), Sand King (25->20), Shadow Demon (35->30), Skywrath Mage (25->20), Techies (60->50), Tidehunter (25->20), Tinker (40->30), Underlord (30->25)
  
-   Intelligence heroes strength gain increased by 0.2
-- Except for Bane, Outworld Devourer, Queen of Pain, Ogre Magi and Zeus
  
-   Killing an Observer or Sentry ward now prints out a notification in chat to your allies
-   Respawn time for level 1/2/3/4 increased from 5/7/9/13 to 6/8/10/14
-   Reverted a global turn rate change done in 7.00
-- Was previously: *Turn rate cap increased by 15% (turn rate ramps up over time as you start turning, the max values that it reaches while you turn are increased by 15%, not the initial value or acceleration/deceleration rate)*

-   Attribute growth values that had 2 decimal points have now been rounded up
-- Affects gains for: Brewmaster Agility, Brewmaster Intelligence, Lich Strength, Lich Intelligence, Lifestealer Intelligence, Luna Intelligence, Magnus Intelligence, Mirana Intelligence, Mirana Strength, Night Stalker Agility, Ogre Magi Agility, Omniknight Agility, Phantom Assassin Strength, Phantom Assassin Agility

-   Shrines' Sanctuary ability now additionally restores 2% HP/Mana pool per second
-- As they no longer naturally scale with the intelligence mana regen changes

## ITEM CHANGES
  
-   Some item-based movement speed bonuses are now rebalanced around being a percentage rather than a constant addition
-- Numbers below are designed being similar with a base of 300 speed, with boot items being -5 and Eul's being -10 of their old values.
    
    > -   Boots of Speed: 15%
    > -   Power Treads: 15%
    > -   Phase Boots: 15%
    > -   Arcane Boots: 15%
    > -   Guardian Greaves: 17%
    > -   Tranquil Boots Active: 24%
    > -   Tranquil Boots Inactive: 20%
    > -   Boots of Travel: 32%
    > -   Drum of Endurance: 6%
    > -   Eul's Scepter: 6%
    > -   Spirit Vessel: 6%
    > -   Wind Lace: 6%
    
### PHASE BOOTS:

-   Reworked Phase Boots Recipe

>Old:  

===  
Requires:  
Boots (500)  
2x Blades of Attack (860)  
Total: 1360  
>
>Provides:  
+50 Movement Speed  
+24 Damage  
  
>New:  

===  
Requires:  
Boots (500)  
Chainmail (550)  
Gloves of Haste (500)  
Total: 1550  
> 
>Provides:  
+15% Movement Speed  
+5 Armor  
+25 Attack Speed

### POWER TREADS:

-   Now requires a Blades of Attack instead of a Gloves of Haste. Grants +16 damage instead of attack speed
-   Attribute bonus increased from 10 to 14

### TRANQUIL BOOTS:
-   No longer gets disabled by attacking creeps

### SANGE:
-   Now provides +12% Status Resistance instead of Maim
- Recipe cost reduced from 700 to 600

### HEAVEN'S HALBERD:
-   Now provides +14% Status Resistance instead of Maim

### SANGE AND YASHA:
-   Now provides +16% Status Resistance instead of Maim
- Movement speed changed from +12% to +35 constant

### YASHA:
- Recipe cost reduced from 700 to 600
- Movement speed changed from +8% to +25 constant (also done for Manta Style)

### KAYA:
- Recipe cost increased from 500 to 600

### YASHA AND KAYA: NEW ITEM
-   Added a new item: Yasha and Kaya

### KAYA AND SANGE: NEW ITEM

-   Added a new item: Kaya and Sange

Rebalanced Sange/Yasha/Kaya and Sange and Yasha stats

>- Sange:  
> ===  
> +16 Strength  
> +12% Status Resistance  
> +8 Attack Damage
>- Yasha:  
> ===  
> +16 Agility  
> +12 Attack Speed  
> +8% Movement Speed
> - Kaya:  
> ===  
> +16 Intelligence  
> +12% Mana Loss Reduction  
> +8% Spell Amp
> - Sange and Yasha:  
> ===  
> +16 Strength  
> +16 Agility  
> +16 Attack Speed  
> +16% Status Resistance  
> +12 Attack Damage  
> +35 Movement Speed
>- Yasha and Kaya  
> ===  
> +16 Intelligence  
> +16 Agility  
> +16 Attack Speed  
> +16% Mana Loss Reduction  
> +12% Spell Amp  
> +35 Move Speed
> - Kaya and Sange  
> ===  
> +16 Intelligence  
> +16 Strength  
> +16% Mana Loss Reduction  
> +16% Status Resistance  
> +12% Spell Amp  
> +12 Attack Damage
> - The Triumvirate (not a real item, but thank you <3)  
> ===  
> +16 Strength  
> +16 Agility  
> +16 Intelligence  
> +16 Attack Speed  
> +16% Status Resistance  
> +12 Attack Damage  
> +35 Movespeed  
> +12% Spell Amp  
> +16% Mana Loss Reduction  

### RING OF TARRASQUE: NEW ITEM

-   Added a new basic item: Ring of Tarrasque. Costs 700 gold. Grants +3.75 HP Regen and +150 Health. Upgrades into Heart of Tarrasque and Holy Locket

### HOLY LOCKET: NEW ITEM

-   Added a new item: Holy Locket. Passive. Causes all heals and hp regen you provide to be amplified by 25%  
      
    Requires:  
    Void Stone (850)  
    Ring of Tarrasque (700)  
    Cloak (550)  
    Recipe (550)  
    Total: 2650  
      
    Provides:  
    +200 Health  
    +4 HP Regen  
    +3 Mana Regen  
    +15% Magic Resistance

### SOLAR CREST: ITEM REWORKED

 - Reworked recipe and bonuses  
  
    Requires:  
    Medallion (1175)  
    Ultimate Orb (2150)  
    Windlace (250)  
    Recipe (300)  
    Total: 3875  
  
    Provides:  
    +10 All Stats  
    +12 Armor  
    +6% Movement Speed  
    +1.5 Mana Regen  
  
Active Ability: Can be cast on allies or enemies, removing your own +12 Armor bonus. Grants allies +70 Attack Speed, +10% Movement Speed, +12 Armor. On enemies it applies -70 Attack Speed, -10% Movement Speed, -12 Armor
-- Casting this removes only the bonus Armor from your hero

### CROWN: NEW ITEM
- Added a new basic item: Crown, +4 All Stats, 450 Gold (available in side shop). Used in items that previously required Bracer, Wraith Band, and Null Talisman

### RING OF AQUILA
- Removed Ring of Aquila from the game
- Bracer, Wraith Band and Null Talisman can no longer be upgraded into other items
- Bracer/Null/Wraith recipe increased from 165 to 215
- Bracer/Null/Wraith Primary stat decreased from +7 to +6

### BRACER
- Now gives +6% Magic Resistance

### WRAITH BAND
- Now gives +6 Attack Speed

### NULL TALISMAN
- Now gives +3% Spell Amp

Summary: 
=== 
Wraith Band: 
+6 Agility 
+3 Strength 
+3 Intelligence 
+6 Attack Speed 

Bracer: 
+6 Strength 
+3 Agility 
+3 Intelligence 
+6% Magic Resistance 

Null Talisman: 
+6 Intelligence 
+3 Strength 
+3 Agility 
+3% Spell Amp

The following recipes have been updated with the removal of Bracer, Wraith Band and Null Talisman as item components:

### HURRICANE PIKE:

-   Now has a 450 gold recipe instead of Wraith Band

### DAGON:

-   Recipe changed

> **Old:**  
> Requires:  
>
> 1x Staff of Wizardry (1000)
> 1x Null Talisman (465)
> Recipe (1250)
> Total: 2715 (for level 1)  
> 
> Provides:  
>
> +18/21/24/27/30 Intelligence  
> +3 Strength  
> +3 Agility  
>   
> **New:**  
> Requires:
> 
> 1x Staff of Wizardry (1000)
> 1x Crown(450)
> Recipe (1250)
> Total: 2700 (for Level 1)  
> 
> Provides:  
>   
> +18/21/24/27/30 Intelligence  
> +5 Strength  
> +5 Agility

### VEIL OF DISCORD:

-   Recipe changed
-- Now reqires 1 Crown instead of 2 Null Talisman
-- Recipe increased to 700 (Total Price from 2330 -> 2050)
-- Intelligence increased from +14 to +15

### ROD OF ATOS:
- Recipe changed

> **Old:**  
> Requires:  
> 2x Bracer (930)
> 1x Staff of Wizardry (1000)
> Recipe (1100)
> Total: 3030  
>   
> Provides:    
> +15 Strength  
> +6 Agility  
> +20 Intelligence  
>   
> **New:**  
> Requires:
> 2x Crown (900)
> 1x Staff of Wizardry (1000)
> Recipe (850)
> Total: 2750
> 
> Provides:
> +12 Strength  
> +12 Agility  
> +20 Intelligence

### RING OF BASILIUS:
-   Mana regeneration increased from 0.5 to 0.65

### BLOODSTONE:
-   No longer has Pocket Deny
-   No longer reduces respawn times
-   Now passively doubles your mana regeneration
-   Starts with 14 charges, deaths remove 3 charges, kills provide 1 charge
-   Each charge provides 0.3 MP and HP regen
-   Can now be cast, transferring 60% of your current mana to health. Cooldown: 250
-- Regen is provided over 2 seconds

### AEON DISK:
-   Health increased from 250 to 300
-   Mana increased from 250 to 300
-   No longer provides passive Status Resistance
-   Provides +50% Status Resistance during the 2.5s active buff duration

### SATANIC:
-   Passively provides 30% Status Resistance
-   Bonus damage reduced from 50 to 25

### HEART OF TARRASQUE:
-   Now provides +50% Health Regen Amplification
-   Out-of-combat regen reduced from 7% to 5%
-- Adjustment for the heal amp
-   HP bonus reduced from 500 to 400
-   Now requires Reaver, Vitality Booster, Ring of Tarrasque and 400 gold recipe

### SPIRIT VESSEL:

-   No longer amplifies health regen nor provides current health percentage regen
-   Enemy damage per second increased from 20 to 25
-- Matches urn now. Still deals current health as damage and negates regen

### HEADDRESS:
-   Headdress Recipe reduced from 300 to 175

### MEKANSM:
-   Recipe increased from 900 to 950
-- Overall cost reduced by 75

### ARCANE BOOTS:
-   Mana restore increased from 135 to 160

### GUARDIAN GREAVES:
-   Heal increased from 275 to 300
-   Mana restore increased from 160 to 200

### PIPE OF INSIGHT:
-   Now gives the +2 Stats from its components
-- Previously missing from Headdress

### SKULL BASHER:
-   Recipe cost reduced from 1000 to 900

### BUTTERFLY:
-   No longer has an active ability

### CRYSTALYS:
-   Bonus damage increased from +30 to +38

### DESOLATOR:
-   Armor reduction increased from 6 to 7

### FORCE STAFF:
-   Can now override Slark's Pounce

### HAND OF MIDAS:
-   Attack Speed increased from 30 to 40

### SENTRY WARD:
-   Range increased from 850 to 1000

### GEM OF TRUE SIGHT:
-   Grants 300 ground vision and truesight to the team that last held when it is dropped on the ground. Lasts until it is picked up

### MORBID MASK:
-   No longer provides +10 Damage
-   Cost reduced from 1100 to 900

### MASK OF MADNESS:
-   Damage reduced from +20 to +10
-   Movement speed changed from +12% to +25 constant

## HEROES
### ABADDON: ABILITY REWORK

-   Base movement speed increased from 310 to 325
-   Base agility increased by 6
-- Base armor unchanged
-   Mist Coil projectile speed reduced from 1600 to 1300
-   Reworked Curse of Avernus. Passive. Slows the targets you attack by 10/15/20/25% for 4 seconds. If a target gets hit 4 times, they become cursed for 4 seconds and are silenced, slowed by 30/40/50/60% and all allied heroes that attack the target will receive a 40/60/80/100 AS boost
-- You cannot start to increment the hit coutner while they are cursed
-   Level 25 Talent changed from Curse of Avernus to +375 AoE Mist Coil

### ANCIENT APPARITION: ABILITY REWORK
-   Ice Vortex no longer has a self bonus  
-   Reworked Chilling Touch. It is now a passive autocast attack modifier. Cooldown: 15/11/7/3 seconds. Grants you bonus attack range and causes your attack to deal heavy magic damage that slows movement for a brief period. Damage: 50/85/120/155. Slow: 100% for 0.5 seconds. Attack Range Bonus: 60/120/180/240. Manacost: 30/50/70/90

### ANTI-MAGE: ABILITY REWORK
-   Removed Scepter upgrade
-   Replaced Spell Shield with Counterspell. Passively grants you 15/25/35/45% Magic Resistance and can be activated to provide a Counterspell shield for 1.2 seconds. Causes all spells that target you to be blocked and reflected onto the enemy. Cooldown: 15/11/7/3. Manacost: 45/50/55/60

### ARC WARDEN:
-   Tempest Double bounty increased from a fixed 180 Gold/XP to 180/240/300
-   Level 15 Talent changed from +350 Health to +300

### AXE:
-   Berserker's Call armor bonus reduced from 40 to 30
- Counter Helix damage reduced from 75/110/145/180 to 60/100/140/180
- Level 15 Talent reduced from +4 Mana Regen to +3

### BANE: ABILITY REWORK
-   Reworked Enfeeble. Adds a debuff to the enemy unit, applying 36/44/52/60% negative status resistance to the target (which causes debuffs to last longer) and reducing the enemy's attack speed by 40/60/80/100. Lasts 8 seconds. Can be dispelled. Cast Range: 1000. Cooldown: 12/10/8/6. Manacost: 70/90/110/130
-   Level 15 Talent changed from Enfeeble Steals Damage to Enfeeble Steals Attack Speed
-   Level 20 Talent changed from +100 Enfeeble Damage Reduction to +100 Enfeeble Attack Speed Reduction

### BATRIDER
- Flaming Lasso now does 20/40/60 damage per second
-- Scepter no longer provides this. Ticks every 1 second.

### BEASTMASTER: ABILITY REWORK**
-   Call of the Wild has been reworked. It no longer summons a neutral creep, and now has two separate hotkeys for the Boar and the Hawk. The Hawk is a global point target ability that sends a permanently invisible uncontrollable hawk to that location starting from where you are. Adjusted stats on the summoned units.
-   Primal Roar self movement boost increased from 30 to 40%
-   Primal Roar secondary units push distance from 300 to 450
-   Primal Roar secondary units push duration from 0.6 to 1.0
-   Primal Roar secondary unit slow duration now matches primary target
-- 2/3/4 to 3/3.5/4
-   Primal Roar secondary unit slow increased from 50 to 60
- Level 25 Talent changed from +2 Hawks Summoned to -15 Hawk Cooldown
- Level 25 Talent reduced from +40 Inner Beast Attack Speed to +30

### BLOODSEEKER
-   Thirst changed from giving attack damage to +30/45/60/75 Attack Speed
-   Thirst movement speed increased from 7/18/29/40% to 12/24/36/48%
-   Bloodrage incoming and outgoing damage reduced from 25/30/35/40% to 10/15/20/25%
-   Bloodrage now does full amplification regardless of the distance
-- Previously did half for units 2200 away from the source
-   Blood Rite damage from 120/160/200/240 to 125/175/225/275
-   Rupture now deals 8% of current health as pure damage per 100 units moved. No longer lethal
-   Rupture duration from 12 to 8/10/12
-   Rupture cast range from 800 to 700/800/900
-   Rupture cooldown from 60 to 70/60/50
-   Level 20 Talent changed from +18% Rupture Damage to +600 Rupture Cast Range

### BOUNTY HUNTER: ABILITY REWORK

-   Strength from 18+2.1 to 20+2.5
- Agility gain reduced from 3.0 to 2.7
-   Shadow Walk no longer deals 30/60/90/120 damage. Attacking out of invisibility now applies a 14/20/26/32% movement slow for 4 seconds
-   Reworked Jinada. Passive cooldown 12/9/6/3. Causes your attack to deal +80/110/140/170 Bonus Attack Damage. Steals 12/18/24/30 Unreliable Gold from enemy heroes. Your weapon glows when the attack is ready to strike
-   Track movement speed bonus is now given to your hero only
-   Track now causes all attacks you do to the Tracked enemy to crit for 1.4/1.6/1.8x
-   Track cast no longer breaks invisibility
-   Track gold radius from 925 to 1200
- Track cast ranged reduced from 1200 to 1000
-   Level 20 Talent changed from +125% Jinada Critical Strike to +90 Jinada Gold Steal

### BREWMASTER: ABILITY REWORK

-   Intelligence gain increased from 1.3 to 1.6
-   Base movement speed increased from 295 to 305
-   Thunderclap manacost from 90/105/130/150 to 90/100/110/120
-   Reworked Drunken Brawler. It is now a self active buff. Lasts for 5 seconds. Grants you 50/60/70/80% evasion and 80% chance to Crit for 170/200/230/260%. Movement speed alternates between -20% and +40% while this is active. Cooldown: 23/21/19/17. Manacost: 35/40/45/50
-   Replaced Drunken Haze with Cinder Brew. Covers a target 400 AoE with alcohol, slowing them by 25% and causes them to have a 20/25/30/35% chance to attack themselves instead of the target. Lasts 7 seconds. If the targets are hit by 80 spell damage or more (including immolation from your Fire Spirit), the duration will refresh and they will ignite and burn for 20/25/30/35 DPS for 3 seconds. Cooldown: 20/18/16/14. Manacost: 50. Self attack is not lethal
-   If you activate it while the debuff is already going, it will extend the ignite debuff duration. If activated after the ignite debuff wears out, a new ignite debuff will be added.
- The Primary Cinder Brew buff duration is not extended when activated (seperate debuffs).
- Primal Split cooldown increased from 140/120/100 to 140/130/120
- Level 10 talent reduced from +30 Damage to +20
-   Level 25 changed from +15% Drunken Brawler Chance to +175% Critical Strike Damage

### BRISTLEBACK:
-   Strength gain increased from 2.2 to 2.5
-   Viscous Nasal Goo armor reduction increased from 1/1.4/1.8/2.2 to 1.4/1.8/2.2/2.6
-   Bristleback now considers damage from towers as valid

### BROODMOTHER:
-   Spiderling/Spiderite magic resistance reduced from 50% to 40%

### CENTAUR WARRUNNER: ABILITY REWORK

-   Strength gain reduced from 4.3 to 4.0
-   Hoof Stomp damage reduced from 100/150/200/250 to 80/110/140/170
-   Double Edge damage changed from 175/250/325/400 to 150/200/250/300 + 40/60/80/100% of Strength as damage
-   Double Edge cast point from 0.5 to 0.4
-   Return has been renamed to Retaliate
-   Retaliate no longer has a strength component
-   Retaliate damage increased from 16/18/20/22 to 16/32/48/64
-   Retaliate now gains charges each time you are attacked by an enemy hero or tower. Can be activated, consuming the charges, to give you a percentage base attack damage increase for 20 seconds. Max Stacks: 13. Provides 6/9/12/15% base damage increase per stack. Cooldown: 55/50/45/40
-   Stampede cooldown increased from 90/75/60 to 110/100/90
-   Stampede manacost increased from 100 to 150
- Stampede slow duration increased from 1.8 to 2.3 seconds
-   Level 10 Talent changed from +10% Magic Resistance to +20 Movement Speed
-   Level 15 Talent changed from +15% Return Strength Damage to +50% Double Edge Strength Damage
-   Level 15 Talent changed from +75 Damage to +30 Base Damage
-   Level 20 Talent changed from +300 Double Edge Damage to +50 Retaliate Damage

### CHAOS KNIGHT: ABILITY REWORK

-   Reworked Chaos Strike. Passive cooldown ability. Lands a critical strike for a random amount, between Min Crit: 120% and Max Crit: 160/190/220/250%. Has 50/55/60/65% lifesteal for this hit. Cooldown: 7/6/5/4
-   Reality Rift no longer reduces armor
-   Reality Rift now moves the target a fixed amount of distance: 250/300/350/400
-   Reality Rift now maims the target applying a 15/25/35/45% movement and 30/50/70/90 attack speed slow for 2 seconds
-   Reality Rift cooldown rescaled from 18/14/10/6 to 20/15/10/5
-   Reality Rift cast range from 550/600/650/700 to 475/550/625/700
-   Chaos Bolt minimum damage rescaled from 75/100/125/150 to 60/90/120/150
-   Chaos Bolt maximum damage rescaled from 200/225/250/275 to 180/210/240/270
-   Chaos Bolt projectile speed reduced from 1000 to 700
-   Phantasm: Phantasm no longer has a chance to summon an extra illusion
-   Phantasm: Illusion count increased from 1/2/3 to 3
-   Phantasm: Illusion damage rescaled from 100% to 50/75/100%
-   Phantasm: Illusion duration reduced from 42 to 30
-   Level 25 Talent changed from -7 Reality Rift Armor Reduction to -2s Chaos Strike Cooldown

### CHEN: ABILITY REWORK

-   Penitence projectile speed reduced from 2000 to 1400
-   Penitence no longer amplifies damage
-   Penitence now causes all allied units attacking the target unit to gain 30/60/90/120 Attack Speed
-   Test of Faith replaced with Divine Favor. Targets allied units, providing 7/13/19/25 HP regen, amplifying all regen and heals on the target by 25% and increasing attack damage by 10/20/40/80. Lasts 12 seconds. Cooldown: 26/24/22/20 Manacost: 110. Cast Range: 800
-   Holy Persuasion now has a neutral creep level requirement of 4/5/6/6
-   Holy Persuasion minimum health increased from 700/800/900/1000 to 1000
-   Holy Persuasion now sends an allied unit anywhere on the map to you instead of sending them home. If the ally takes player based damage during this, the spell is interrupted
-   Holy Persuasion cooldown changed from 32/24/18/10 to 15
-- This used to be Recall on Keeper of the Light, who no longer has it
-   Level 15 Talent changed from -10s Test of Faith Cooldown to -10s Divine Favor Cooldown

### CLINKZ: ABILITY REWORK

- Attack range increased from 640 to 650
-   Replaced Death Pact with Burning Army. Uses Vector Targeting. Spawns 4/5/6 Fiery Skeleton Archers along a 1300 line. Skeletons attack using Searing Arrows, have your base damage, are immobile and take 2 hits to kill from a hero. They only attack enemy heroes (like WD ward, but killable). Attack range matches your hero. Spawn at 0.8 second intervals. Cast Range: 1200. Cooldown 110. Manacost: 125/175/225. Lasts 20 seconds. Base Attack Time: 1.75/1.6/1.45
- Burning Army damage type is Hero
- Level 20 Talent increased from +100 to +125 Attack Range

### CLOCKWERK:

-   Rocket Flare projectile speed increased from 1750 to 2250
-   Power Cogs knockback distance increased from 250 to 300
-   Power Cogs knockback duration increased from 0.85 to 1
-   Power Cogs damage from 50/100/150/200 to 50/125/200/275
-   Power Cogs mana burn from 50/100/150/200 to 50/80/110/140

### CRYSTAL MAIDEN:

-   Base damage increased by 2
-   Frostbite no longer has an interrupt
-- Same as other roots changed, still interrupts teleports
-   Frostbite cast range increased from 525 to 550
-   Freezing Field no longer has a 0.3 cast point

### DARK SEER:

-   Surge duration rescaled from 3/4.5/6/7.5 to 6
-   Surge cooldown rescaled from 13/12/11/10 to 16/14/12/10
-   Surge now causes the target to be unslowable
-   Surge speed changed from 550 to +30/45/60/75%
-   Surge now causes the target to ignore movement speed limit
-   Surge now causes the target to ignore unit collisions
-   Wall of Replica now uses Vector Targeting to cast
-   Wall of Replica cast point reduced from 0.4 to 0.2
-   Wall of Replica cast range increased 500/900/1300 to 1300
-   Wall of Replica always now slows heroes touching the wall continuously, and the debuff lingers for 0.75 seconds after leaving the wall
-- Previously only reapplied the slow when the illusion died
-   Wall of Replica slow reduced from 75% to 50/60/70%

### DAZZLE: ABILITY REWORK

- Intelligence gain reduced from 3.4 to 3.2
-   Poison Touch mana cost increased from 80 to 95/110/125/140
-   Poison Touch cast range reduced from 600/700/800/900 to 500/600/700/800
-   Poison Touch debuff now stacks
-   Shallow Grave cooldown increased from 60/45/30/15 to 60/46/32/18
-   Replaced Weave with Bad Juju. Passive ability. Grants you 20/35/50% Cooldown Reduction. Anytime you cast a spell, all enemies within a 1200 AoE around you lose 2/2.25/2.5 armor for 8 seconds. Debuffs stack and refresh duration. Doesn't affect Roshan
-   Shadow Wave cooldown increased from 12/10/8/6 to 14/12/10/8
-   Level 25 Talent changed from +0.5 Weave Armor Per Second to +0.5 Bad Juju Armor Reduction
-   Level 25 Talent changed from -4s Shadow Wave Cooldown to +40% Poison Touch Slow

### DEATH PROPHET:

-   Movement speed increased from 305 to 315
-   Spirit Siphon now drains 4/6/8/10% speed
-   Spirit Siphon charge replenish time reduced from 60/55/50/45 to 60/52/44/36
-   Exorcism damage increased from 56-61 to 59-64
- Level 10 Talent increased from +12% Magic Resistance to +15%
- Level 20 Talent increased from -2s Crypt Swarm Cooldown to -3s

### DISRUPTOR:
-   Thunder Strike damage increased from 40/60/80/100 to 45/70/95/120

### DOOM:

-   Base attack range increased from 150 to 175
-   Devour no longer has a restriction on consuming while another unit is being consumed
-   Devour now gives you 4/8/13/18 HP regen per second while the creep is being consumed
-   Devour now takes a constant 80 seconds to consume a creep
-   Devour can now be toggled off to not steal the creep ability
--  If autocast is on, it'll steal, otherwise it won't
-   Scorched Earth no longer heals
-   Scorched Earth cooldown reduced from 55 to 55/50/45/40
-   Scorched Earth damage increased from 16/24/32/40 to 20/30/40/50
-   Level 10 Talent changed from +10 Scorched Earth Damage/Heal to +20 Scorched Earth Damage

### DRAGON KNIGHT:

-   Elder Dragon Form Splash Attack now does 75% damage in the 300 AoE
-- Instead of 100% in 50 AoE, 50% in 150 AoE, 25% in 250 AoE
-   Elder Dragon Form Splash Attack no longer does partial damage if the attack misses

### DROW RANGER: ABILITY REWORK

-   Precision Aura now provides attack speed based on 20/36/52/68% of your Agility, rather than Damage based on 10/20/30/40% of your agility
-   Reworked Marksmanship. Now provides a 20/30/40% chance to land a piercing attack that cannot be evaded and strikes through the enemy's defenses, ignoring their armor entirely and dealing 120 physical damage. Instantly kills creeps. Gets disabled if an enemy hero is within 400 range of you
-   Level 20 Talent changed from +20 Marksmanship Agility to +25% Evasion
-   Level 25 Talent changed from +20% Precision Aura Damage to +25% Precision Aura Attack Speed

### EARTHSHAKER:

-   Fissure cooldown increased from 18/17/16/15 to 21/19/17/15

### EARTH SPIRIT:

-   Strength gain increased from 3.5 to 3.8
-   Rolling Boulder changed from an 80% slow for 0.4/0.6/0.8/1.0 seconds to a stun for 0.4/0.6/0.8/1.0
-   Rolling Boulder stun duration lasts an extra 0.4/0.6/0.8/1.0 seconds when using a rock
-   Boulder Smash changed from a stun for 0.5/1/1.5/2 seconds to an 80% slow for 1.25/2.5/3.25/4 seconds
-   Boulder Smash damage increased from 50/100/150/200 to 105/170/235/300
-   Stone Remnant max charges increased from 6 to 7
-   Magnetize AoE increased from 300 to 350
-   Level 25 Talent changed from +1s Boulder Smash Stun duration to +0.75s Rolling Boulder Stun Duration

### ELDER TITAN:

-   Astral Spirit damage reduced from 60/90/120/150 to 50
-   Astral Spirit return speed increased from 600 to 800
-   Astral Spirit attack damage per hero from 15/30/45/60 to 15/30/60/80
-   Astral Spirit now provides +1.5/3/4.5/6 Armor per hero hit and +0.5 per creep
-   Astral Spirit movement speed increased from 5% to 7%
-   Astral Spirit movement speed cap increased from 30% to 40%
-   Astral Spirit bonus duration increased from 9 to 10 seconds
- Astral Spirit cooldown increased from 16 to 17
-   Level 25 Talent changed from +100% Lifesteal to +600 Echo Stomp Wake Damage

### EMBER SPIRIT:

- Base armor increased by 1
- Strength increased from 20 + 2.4 to 21 + 2.6
- Sleight of Fist damage increased from 30/60/90/120 to 40/80/120/160
-   Fire Remnant now does damage along the way (at half radius) instead of only at the destination
-- Only hits enemies once per remnant.
- Ember Spirit: Level 10 Talent increased from +200 Flame Guard Absorption to +250  
- Ember Spirit: Level 15 Talent increased from +50 Flameguard DPS to +60

### ENIGMA:

-   Base movement speed reduced from 300 to 290

### FACELESS VOID: ABILITY REWORK

-   Time Lock now causes Faceless Void to land a free second attack while the target is locked in place. Deals bonus 25/30/35/40 damage and bashes for 0.75 seconds
- Time Lock chance reduced from 10/15/20/25% to 10/14/18/22%
- Level 10 Talent reduced from +20 Damage to +15
-   Level 15 Talent from +100 Time Lock Damage to +70

### GRIMSTROKE: ADDED TO CAPTAINS MODE

-   Enabled Grimstroke in Captains Mode
-   Soulbind now applies a Leashed state to the targets, disallowing teleportation and mobility based abilities
-   Soulbind duration reduced from 6/8/10 to 6/7/8
- Soul Bind cooldown increased from 80/65/50 to 100/75/50
-   Phantom's Embrace creature now gets closer to the target before latching on
-   Ink Swell now does its maximum impact based on the duration it hit any hero, rather than amount of DPS dealt to all heroes combined
-- Scales linearly from 0 to 3 seconds
-   Ink Swell max stun duration reduced from 2.2/2.8/3.4/4 to 1.4/2.2/3/3.8
- Ink Swell max damage reduced from 160/240/320/400 to 100/200/300/400
-   Level 20 Talent changed from +2 Hits to Kill Phantom to +1

### GYROCOPTER:

- Strength gain increased from 2.1 to 2.3
- Agility gain increased from 2.8 to 3.1

### HUSKAR: ABILITY REWORK

-   Berserker's Blood no longer gives magic resistance. Now provides health regen up to 20/40/60/80% of Strength based on missing health
-   Berserker's Blood now ramps up faster when lower health
-   Replaced Inner Vitality with Inner Fire. In a fiery rage, knocks all enemies within 500 range away from you, dealing 100/155/210/265 damage and disarming them for 1.75/2.5/3.25/4 seconds. Enemies are knocked back to 550 range away from you. Knockback duration: 0.6. Cooldown: 18/16/14/12 seconds. Manacost: 75/100/125/150
-   Level 10 Talent reduced from +20 Damage to +15
-   Level 15 Talent increased from +15% Lifesteal to +20%
-   Level 15 Talent increased from +10 Burning Spears DPS to +15
-   Level 20 Talent increased from +15 Strength to +20
-   Level 25 Talent increased from +150 Attack Range to +175

### IO:

- Tether heal/mp transfer rate from 1.2/1.3/1.4/1.5 to 1.05/1.2/1.35/1.5
-   Spirits Cooldown increased from 26/22/18/14 to 26/24/22/20

### JAKIRO:

-   Macropyre damage now lingers on the affected units for 2 seconds

### JUGGERNAUT:

-   Base Agility increased by 10 (base damage unchanged)
-   Changed how Omnislash does the strikes from just physical damage nukes (with occasional invisible attacks depending on attack speed) to all full real attacks that can proc your crit and items. Lasts 3/3.25/3.5 seconds and attacks at 1.8x your attack rate. Provides +30/40/50 Damage. Scepter lasts 4/4.25/4.5 seconds and 70 cooldown
-   Omnislash no longer constantly issues self interrupts during each attack
-- Would cause it to drop your orders
-   Omnislash no longer instantly kills creeps
- Omnislash now self-dispells on cast
- Level 15 Talent reduced from +25 Attack Speed to +20
-   Level 25 Talent changed from +5 Omnislash Strikes to +1s Omnislash Duration

### KEEPER OF THE LIGHT: ABILITY REWORK

-   Removed Mana Leak and Spirit Form
-- Recall has been moved to Chen  
-   Illuminate cooldown increased from 10 to 11
-   Changed how Chakra Magic works. Restores 80/160/240/320 mana and removes 3/4/5/6 seconds off of basic abilities currently on cooldown. Cooldown: 20/18/16/14
-   Reworked Blinding Light into a basic ability. Causes everyone in a 600 AoE to be blinded, missing 70% of their attacks for 3/4/5/6 seconds. Knocks targets back 350 units and deals 50/100/150/200 damage. Cooldown: 30/25/20/15. Manacost: 100/125/150/175. Cast Range: 550/600/650/700
-   Added a new Ultimate, Will-o-Wisp. Spawns an attackable light entity, Ignis Fatuus. The light flickers on for 1.3 seconds and off for 1.85 seconds. Enemies within a 675 Radius are hypnotized and forced to look at it whenever it is emitting light, unable to act. The light entity can be killed with 4/5/6 attacks, otherwise it will flicker 3/4/5 times before going away. Cooldown: 120. Cast Range: 900. Manacost 250/350/450. Dormant for 1 second before the first flicker begins.
- Has a 100/125/150 gold bounty when killed (can be denied)
-   Scepter now just causes your Illuminate to heal during the day 
-- This turns your hero into the spirit form visually during daytime
-   Level 25 Talent changed from +2s Mana Leak Stun to +2 Will-O-Wisp Flickers

### KUNKKA:

- Tidebringer cleave damage increased from 150% to 165%

### LEGION COMMANDER:

-   Winning a Duel automatically casts a free Press the Attack on you

### LICH: ABILITY REWORK

-   Intelligence increased from 16 + 3.3 to 20 + 3.6
- Base movement speed reduced from 315 to 310
-   Frost Nova manacost reduced from 125/150/170/190 to 105/130/155/180
-   Replaced Sacrifice with Sinister Gaze. Channeling single target. Causes the enemy to slowly walk towards you. Lasts up to 1.6/1.9/2.2/2.5 seconds. Cast Range: 500/525/550/575. Cooldown: 30. Manacost: 120/130/140/150
-- Moves to a point 32/38/44/50% between you two
-   Replaced Ice Armor with Frost Shield. Targets self or an ally and applies a frost shield. Reduces physical attack damage taken by 30/40/50/60% for 6 seconds. Every second, all enemies within a 600 AoE will take 20/30/40/50 damage and be slowed by 35% for 0.5 seconds. Cooldown: 30/25/20/15. Manacost: 100/110/120/130. Can target towers.
-   Level 20 Talent changed from 180 Gold/Min to +2s Frost Shield
-   Level 20 Talent reduced from +175 Cast Range to +150
-   Level 25 Talent increased from Ice Armor Provides +30 HP Regen to Frost Shield Provides +60 HP Regen

### LIFESTEALER:

-   Agility gain increased from 1.9 to 2.4
-   Feast changed from 4.5/5.5/6.5/7.5% of Current Health to 1.75/2.5/3.25/4% of Max Health
-   Level 25 Talent changed from +2% Current Health to +1% Max Health

### LINA

- Base armor increased by 2

### LION:

-   Mana Drain slow increased from 16/19/22/25% to 20/24/28/32%
-   Finger of Death now gets stronger with each kill. Gains +50 Damage per hero kill. If the enemy dies within 3 seconds of being hit by the ability, the bonus is still granted

### LONE DRUID: ABILITY REWORK

-   Base movement speed increased from 320 to 340
- Base armor reduced by 2
- Agility reduced from 24 + 2.7 to 20 + 2.4
-   Spirit Bear movement speed increased from 320/330/340/350 to 340/350/360/370
-   Spirit Bear attack backswing time reduced from 0.67 to 0.4
-   Spirit Bear attack damage increased from 35/45/55/65 to 35/50/65/80
-   Spirit Bear now has a level 1 ability, Defender. Passively causes 30% of the damage Lone Druid takes to be instead dealt to the Spirit Bear if you are within the leash range
-   Replaced Rabid with Spirit Link. Grants both of you 30/50/70/90 Attack Speed and causes 40/50/60/70% of damage you deal to restore life to your Spirit Bear, and damage your Spirit Bear deals to restore life to you. Duration: 10 seconds. Cooldown: 43/36/29/22. Manacost: 50/60/70/80
- Level 10 Talent reduced from +175 Attack Range to +125
- Level 20 Talent changed from +40 Spirit Link Attack Speed to -0.3 Spirit Bear Base Attack Time

### LUNA:

- Agility gain reduced from 3.3 to 3.1
-   Lunar Blessing now provides +6/12/18/24 Primary Attribute bonus as the aura bonus, rather than bonus damage
- Lunar Blessing night vision reduced from 250/500/750/1000 to 200/400/600/800
- Level 10 Talent reduced from +20 Attack Speed to +15
- Level 20 Talent reduced from +10 All Stats to +8
-   Level 15 Talent changed from +24 Lunar Blessing Damage to +30 Movement Speed

### LYCAN: ABILITY REWORK

-   Reworked Howl. Now grants +20/30/40/50 Attack Speed, +3/4/5/6 Armor and +4/6/8/10 HP regen to all player controlled units on the map. Lasts 9 seconds. Cooldown: 50/45/40/35. Manacost: 25/30/35/40.
  
-   Level 25 Talent changed from +600 Howl Health to +40% Chance Shapeshift Critical Strike

### MAGNUS: ABILITY REWORK

-   Empower bonus damage reduced from 20/30/40/50 to 10/20/30/40%
- Empower cleave damage reduced from 30/45/60/75% to 14/34/54/74%
-   Skewer cooldown reduced from 25 to 26/24/22/20
-   Reworked Shockwave. Releases a wave towards a target point, pulls units towards it slightly and deals 75/150/225/300 damage. Slows enemies by 60% for 0.75 seconds. Width: 200, Distance: 1200, Projectile Speed: 900. Pull Duration: 0.2. Manacost: 90/100/110/120. Cooldown: 14/13/12/11
-   Reverse Polarity cooldown increased from 120 to 130
- Level 15 Talent reduced from +15 Strength to +12
- Level 20 Talent reduced from +12 Armor to +10

### MEDUSA:

- Agility increased from 20 + 2.5 to 22 + 3.4
-   Stone Gaze no longer grants enemies +100% Magic Resistance
-   Stone Gaze no longer instantly kills illusions
-   Mystic Snake no longer changes damage type against Stone Gazed enemies
- Level 15 Talent increased from +20% Mystic Snake Mana Steal to +35%

### MEEPO: ABILITY REWORK

- Agility gain reduced from 2.2 to 1.4
-   Base movement speed increased from 310 to 320
- Poof damage reduced from 80/100/120/140 to 70/90/110/130
-   Replaced Geostrike with Ransack. Each attack steals 6/10/14/18 health from your enemy heroes (and 4/6/8/10 from creeps) and heals all Meepos by the same amount
-- Has no range limit. This hurts enemies as well. Does not affect Roshan.
-   Clones now only drain 40% of normal XP from the area
-   Level 10 Talent reduced from +20 Damage to +10
- Level 15 Talent reduced from +40 Poof Damage to +30
- Level 15 Talent changed from +10% Lifesteal to +15% Evasion
- Level 20 Talent changed from +15% Evasion to +10% Lifesteal
- Level 25 Talent reduced from +600 Health to +400

### MIRANA:

-   Leap now causes the direction Mirana is facing to point towards the leap direction

### MONKEY KING:

-   Mischief will now always transform into a courier when nearby another courier
-   Mischief now grants you 0.2 seconds of invulnerability when transforming into another unit
-   Mischief cooldown increased from 3 to 20

### MORPHLING:

-   Waveform cooldown increased from 14/13/12/11 to 17/15/13/11

### NAGA SIREN: ABILITY REWORK

-   Mirror Image duration reduced from 30 to 24
-   Mirror Image cooldown reduced from 40 to 45/40/35/30
-   Mirror Image manacost rescaled from 70/80/90/100 to 70/85/100/115
-   Mirror Image incoming damage reduced from 550/500/450/400% to 475/450/425/400%
-   Rip Tide has been reworked. Now a passive attack chance ability. Gives a chance that your attack will trigger a Rip Tide that deals AoE damage and reduces armor. Illusions can proc this. Chance: 17%. Duration: 4. Armor Reduction: 2/4/6/8. Damage: 30/40/50/60. AoE: 300
- Level 15 Talent reduced from +15 Agility to +12

### NATURE'S PROPHET:

- Base armor increased by 1
- Agility gain increased from 2.4 to 2.8
-   Treants experience bounty reduced from 30 to 20
-   Treants gold bounty reduced from 21 to 16

### NECROPHOS:

-   Base attack range reduced from 550 to 500
  
-   Heartstopper Aura now provides the unit kill regeneration instead of Death Pulse
-- If Necro himself gets the kill

### NIGHT STALKER: ABILITY REWORK

-   Reworked Crippling Fear. It is now an activated 375 range aura that silences all enemies while they are nearby. Aura lasts 5/6/7/8 seconds (3 during day). No longer has a miss chance. Cooldown: 30/25/20/15. Manacost: 50
-- Since this is an aura, it can't be dispelled
  
-   Hunter in the Night no longer has an active.
  
-   Replaced Darkness with Dark Ascension. Causes you to transform into a stronger flying creature that has +50/100/150 bonus damage and 900 unobstructed vision. Lasts for 30 seconds. Daytime is turned to night during this. Cooldown: 140/130/120. Manacost: 125/175/225
  
-   Level 25 changed from -8s Crippling Fear Cooldown to -40s Dark Ascension cooldown

### NYX ASSASSIN:

-   Vendetta now applies a break debuff on the target for 4 seconds

### OGRE MAGI:

-   Multicast now affects targeted offensive items. Will cause the item to cast again at a different random enemy unit
-   Multicast no longer provides passive improvements to the base abilities
-   Ignite cast range increased from 700 to 700/800/900/1000
-   Ignite base cast launches two projectiles
-- One at the primary target, one at the closest unit to it  
-   Fire Blast cooldown rescaled from 12 to 12/11/10/9
-   Bloodlust cooldown reduced from 20 to 20/18/16/14
-   Bloodlust movement speed reduced from 10/12/14/16% to 8/10/12/14%

### OMNIKNIGHT: ABILITY REWORK

-   Purification can now be cast on Spell Immune units
-   Replaced Repel with Heavenly Grace. Targets an allied unit and applies a strong dispel, and then increases status resistance by 50/60/70/80% and health regeneration by 8/12/16/20 for 8 seconds. Cooldown: 17/16/15/14. Manacost: 75. Cast Range: 500
-   Guardian Angel AoE increased from 600 to 1200
-   Guardian Angel cooldown reduced from 180/170/160 to 160/150/140
-   Level 25 Talent changed from +3s Repel Duration to -8s Heavenly Grace Cooldown

### ORACLE:

-   Fortune's End damage increased from 90/120/150/180 to 120/150/180/210

### OUTWORLD DEVOURER: ABILITY REWORK

- Intellegence increased from 24 + 2.7 to 28 + 3.0
- Base armor increased by 1
-   Arcane Orb now splashes its bonus damage in a 175 AoE around the target
-   Arcane Orb no longer does bonus damage to illusions
- Arcane Orb no longer ignores Ancient creeps
-   Replaced Essence Aura with Equilibrium. Self buff. Causes all spell damage you deal to restore 65/90/115/140% of damage back as mana and slow enemies by 12/22/32/42% for 1.75 seconds. Lasts 7 seconds. Cooldown: 18 Manacost: 50
-   Level 15 Talent changed from +15% Essence Aura Chance to +6 Armor

### PANGOLIER: ABILITY REWORK

-   Replaced Heartpiercer with Lucky Shot. Gains a 20% chance to apply a debuff for 2/3/4/5 seconds that slows the target by 40% and causes the target to be either Silenced or Disarmed. Multiple instances of this debuff stack

### PHANTOM ASSASSIN: ABILITY REWORK

-   Stifling Dagger manacost increased from 30/25/20/15 to 30
-   Phantom Strike Cooldown rescaled from 14/11/8/5 to 11/9/7/5
-   Phantom Strike cast point reduced from 0.3 to 0.25
-   Phantom Strike Attack Speed rescaled from 130 to 100/125/150/175
-   Phantom Strike no longer has an attack limit
-   Phantom Strike Attack Speed bonus now lasts for 2.5 seconds
- Phantom Strike attack speed duration reduced from 2.5 to 2
-   Phantom Strike Manacost rescaled from 50 to 35/40/45/50
-   Phantom Strike Attack Speed bonus no longer depends on attacking the specific target
-   Blur's non-evasion passive component has been changed into an active, evasion component is unchanged. Causes enemies to be unable to see you (like smoke) until you are within 600 units of an enemy hero or buildings. Does not dispel when attacking. Lingers around for 0.75 seconds before going away after being near an enemy hero. Lasts 25 seconds. Cast Point: 0.4. Cooldown: 60/55/50/45. Manacost: 50
- Coup de Grace damage reduced from 230/340/450% to 200/325/450%
- Level 15 Talent reduced from -4 Armor to -3

### PHANTOM LANCER:

-   Phantom Lance slow reduced from 10/20/30/40% to 10/18/26/34%
-   Juxtapose incoming damage increased from 600% to 650%

### PHOENIX:

-   Icarus Dive slow rescaled from 28% to 19/22/25/28%

### PUCK:

-   Base armor increased by 1
- Intelligence gain increased from 2.4 to 2.7
-   Illusory Orb cooldown reduced from 14/13/12/11 to 13/12/11/10
-   Dream Coil now applies a Leashed state to the targets, disallowing teleportation and mobility based abilities
- Dream Coil stun duration from 1.5/2.25/3 to 1.8/2.4/3
-   Level 15 Talent increased from +50 Attack Damage to +90
-   Level 15 Talent increased from +8% Spell Amplification to +15%

### PUDGE:

-   Flesh Heap no longer gives Magic Resistance
-   Flesh Heap now grants 3/6/9/12 HP regen
-   Dismember strength based damage increased from 30/45/60% to 30/60/90%

### QUEEN OF PAIN:

-   Agility increased from 18 + 2 to 22 + 2.2
-   Sonic Wave now knocks units back 350 units over 1.4 seconds
-- Does not stun
-   Scream of Pain manacost reduced from 110/120/130/140 to 95/110/125/140

### RAZOR:

-   Unstable Current no longer slows or purges a random enemy unit every 5 seconds
-   Unstable Current now deals 60/80/100/120 damage to every enemy unit within 500 AoE every 6/5/4/3 seconds
-   Plasma Field now applies a slow on units it hits, Minimum 5% Maximum 25/30/35/40% for 1.5 seconds. Slow instances stack
-- Plasma hits twice
-   Level 25 Talent changed from -3s Unstable Current to +200 Unstable Current Damage

### RIKI:

-   Base damage increased by 3
-   Blink Strike cooldown rescaled from 16/12/8/4 to 10/8/6/4
-   Blink Strike damage rescaled from 100 to 75/90/105/120

### RUBICK: ABILITY REWORK

-   Base damage increased by 3
-   Agility increased from 14 + 1.6 to 19 + 2.1
-   Intelligence gain increased from 2.4 to 2.7
- Telekinesis cooldown increased from 28/26/24/22 to 34/30/26/22
- Telekinesis lift duration reduced from 1.1/1.5/1.9/2.3 to 1/1.4/1.8/2.2
-   Replaced Null Field with Arcane Supremacy. Passive. Gains 14/18/22/26% Spell Amplification and causes all debuffs you apply to the enemy to last 20/28/36/44% longer
-   Spell Steal ability cast points now have a min of 0.15 instead of 0
-   Level 15 Talent increased from +100 Cast Range to +125
-   Level 20 Talent changed from +5% Null Field to -5s Fade Bolt Cooldown
-   Level 25 Talent changed from +75% Spell Amp For Stolen Spells to +50%

### SAND KING:

- Base damage reduced by 2
- Strength gain reduced from 2.9 to 2.8
- Agility gain reduced from 2.1 to 1.8
- Burrow Strike stun duration from 1.9/2/2.1/2.2 to 1.6/1.8/2/2.2
-   Sand Storm is no longer a channeled ability. The Sand Storm and the invisibility ends immediately once you leave the area. Attacking or casting temporarily reveals you for 0.7 seconds
-   Sand Storm AoE changed from 525 to 350/450/550/650
-   Sand Storm damage reduced from 40/60/80/100 to 20/40/60/80
-   Sand Storm cooldown rescaled from 34/26/18/10 to 40/34/28/22
-   Sand Storm duration reduced from 50 to 20/25/30/35
- Sandstorm manacost rescaled from 60/50/40/30 to 60
-   Sand Storm visual effects updated slightly
-   Epicenter AoE growth now always increases by 50 per pulse, instead of sometimes 25/50/75
- Level 15 Talent reduced from +50 Sand Storm DPS to +40

### SHADOW DEMON: ABILITY REWORK

-   Reworked Soul Catcher. Targets a 175/200/225/250 AoE area. Causes all enemy units in the area to lose 25/30/35/40% of their current health, and gain half of it back after 10 seconds. Cooldown: 26/24/22/20 Cast Range: 700. Manacost: 110
-- Dispelling this gains your health back as well
-   Disruption illusions health is now determined at the start of the cast
-   Disruption duration increased from 2.5 to 2.75

### SHADOW FIEND:

-   Base armor increased by 2

### SHADOW SHAMAN:

-   Mass Serpent Wards now spawn in a circle, with a slightly bigger empty spot in the middle
-   Mass Serpent Wards now has an AoE spawn indicator

### SKYWRATH MAGE:

-   Concussive Shot now hits a creep if there are no nearby enemy heroes
-- Deals 75% damage to creeps

### SLARDAR: ABILITY REWORK

-   Base armor increased by 1
-   Reworked Bash of the Deep. Passive. Every 4th attack your hero does (on any target) applies a bash for 1/1.1/1.2/1.3 seconds dealing 75/125/175/225 physical damage
-   Slithereen Crush stun duration reduced from 1.25/1.5/1.75/2 to 1 second. Attack and Movement Slow duration increased from 2 to 3/4/5/6 and slow amount increased from 20 to 20/25/30/35%. Damage increased from 75/125/175/225 to 80/140/200/260
-   Level 15 Talent changed from +100 Bash Damage to +75
- Level 20 Talent changed from +50 Attack Speed to +30% Lifesteal
-   Level 25 Talent changed from +15% Bash Chance to +1.5s Slithereen Crush Stun

### SLARK:

-   Turn rate improved from 0.6 to 0.7
- Dark Pact manacost from 55/50/45/40 to 60
-   Pounce now applies a Leashed state to the target, disallowing teleportation and mobility based abilities
- Pounce leash duration from 3.5 to 2.5/2.75/3/3.25
- Pounce leash range from 325 to 400
-   Shadow Dance duration rescaled from 4 to 4/4.25/4.5
- Shadow Dance cooldown increased from 60 to 80/70/60
- Shadow Dance movement speed reduced from 30/40/50% to 20/35/50%
-   A dying with Essence Shift debuff on them causes Slark to permanently steal 1 Agility if they died within 300 units
- Level 10 Talent reduced from +8 Agility to +6 Agility
- Level 20 Talent reduced from +2s Pounce Leash to +1.25s
- Level 25 Talent reduced from +120s Essence Shift Duration to +80s

### SNIPER:

-   Take Aim can now be activated to double your attack range for your next attack. Goes on cooldown after the attack is used. Cooldown: 15/12/9/6. Manacost: 30

### SPECTRE:

- Haunt damage increased from 40/50/60% to 40/60/80%

### SPIRIT BREAKER: ABILITY REWORK

-   Nether Strike can no longer be cast when rooted
-   Charge of Darkness no longer moves at a fixed speed. It now unlocks the movement speed cap and adds 300/325/350/375 Movement Speed
-- Previously it fixed your speed to 600/650/700/750
-   Fixed Charge of Darkness not using the movement speed for the impact damage
-   Greater Bash no longer gives you movement speed
-   Greater Bash damage reduced from 12/24/36/48% to 8/16/24/32%
-   Replaced Empowering Haste with Bulldoze. Upon activation, grants your hero +12/18/24/30% Movement Speed and +30/40/50/60% Status Resistance for 8 seconds. Cooldown: 22. Manacost: 25/30/35/40
-- Casting Bulldoze does not interrupt Charge of Darkness
-   Level 20 Greater Bash talent reduced from 30% to 15%
-   Level 20 Talent changed from +400 Charge Speed to -7s Bulldoze Cooldown

### STORM SPIRIT

- Base damage increased by 2
- Intelligence gain increased from 3 to 3.2
- Static Remnant damage increased from 120/160/200/240 to 120/170/220/270

### SVEN: ABILITY REWORK

-   Base movement speed increased from 290 to 295
-   Reworked Warcry. Now grants you and nearby allied heroes bonus movement speed and an HP shield that blocks attack damage based on the shield's health. Lasts 10 seconds. Buff ends if the shield is consumed. Movement Speed: 8/12/16/20% Movement Speed. Attack Shield Health: 110/220/330/440 Health. AoE: 700 Cooldown: 36/32/28/24. Manacost: 40
-   Warcry shield health is 25% stronger on your hero
-- Damage blocked calculated post armor reduction

### TECHIES:

-   Base movement speed increased from 270 to 315
-   Base intelligence increased by 2

### TEMPLAR ASSASSIN:

-   Level 20 Talent changed from Refraction Dispels to Meld Dispels
-   Level 25 Talent changed from Psi Blades Spill Paralyzes to 1.5s Meld Hit Bash

### TERRORBLADE:

-   Metamorphosis movement speed loss increased from 25 to 30
-   Sunder can no longer pierce Spell Immunity
-   Level 20 Talent reduced from -10s Reflection Cooldown to -8

### TIDEHUNTER:

-   Anchor Smash now attacks every unit in the area with a bonus 45/90/135/180 damage on top of your attack
-   Ravage damage increased from 200/290/380 to 200/300/400
-   Level 10 Talent increased from +80 Gush Damage to +100

### TIMBERSAW:

- Strength gain increased from 2.1 to 2.4
-   Chakram projectile damage no longer ignores Ancients
-   Whirling Death is now always pure damage
-   Whirling Death damage changed from 100/150/200/250 to 90/120/150/180
-   Whirling Death stat reduction rescaled from 15% to 12/13/14/15%
-   Whirling Death now deals 10/15/20/25 extra damage per tree cut down
-   Level 25 Talent increased from +8% Whirling Death to +12%

### TINY: ABILITY REWORK

-   Tree Grab area damage no longer works when denying units
-   Tree Grab cooldown increased from 24/20/16/12 to 27/22/17/12
-   Grow no longer provides 30/40/50% Status Resistance
-   Grow armor increased from 5/10/15 to 7/16/25
-   Reworked how Avalanche works. The units in the area are now continuously hit by short ministuns and damage every 0.3 seconds. Each hit stuns for 0.2 seconds
-   Avalanche duration increased from 1 to 1.8
-   Avalanche AoE increased from 275 to 400
-   Avalanche cooldown reduced from 23/21/19/17 to 23/20/17/14
-   Avalanche total damage rescaled from 120/180/240/300 to 90/160/230/300
-   Toss avalanche damage bonus increased from 2x to 3x
-- The entire avalanche duration is no longer covered by toss
-   Level 10 Talent changed from +20% Magic Resistance to +20 Movement Speed
-   Level 25 Talent changed from -12s Avalanche CD to -9s
-- Due to Avalanche cooldown improvement

### TREANT PROTECTOR: ABILITY REWORK

-   Reworked Nature's Guise. Passive. Has a 4/3.5/3/2.5 second fade delay, taking damage resets the counter. Grants you invisibility, treewalking ability, and 14/18/22/26% movement speed bonus as long as you are within 265 distance of a tree. Has a 0.75 linger duration. Attacking a unit out of this roots the target for 0.4/1/1.6/2.2 seconds and deals a total of 30/90/150/210 damage during the root

### TROLL WARLORD: ABILITY REWORK

-   Base damage increased from 38-56 to 44-56
-   Berserker's Rage now applies an ensnare instead of a bash
-   Berserker's Rage proc chance increased from 10% to 10/12/14/16%
-   Basher and Abyssal Blade are no longer restricted items
-   Fervor stack limit increased from 7 to 12
-   Fixed Fervor incrementing when missing attacks
-   Fervor now starts at 0 stacks when attacking a new unit
-   Reworked Battle Trance. Now causes you to go into an uncontrollable trance, forcing you to attack the closest targets in a 900 AoE. During this trance, you are unslowable and cannot die. Grants +140/170/200 Attack Speed, +30/35/40% Movement Speed and +40/60/80% Lifesteal. Lasts 6.5 seconds. You gain normal vision over the target you are currently locked on. Cooldown: 90. Manacost: 150
-   Level 25 Talent changed from Battle Trance Basic Dispel to Battle Trance Strong Dispel
-- Can be cast while stunned

### TUSK: ABILITY REWORK

- Strength gain increased from 3 to 3.4
-   Replaced Frozen Sigil with Tag Team. Activatable Aura. Lasts 5 seconds. Causes affected enemies to take 25/50/75/100 more physical damage from attacks and be slowed by 75% for 0.5 seconds. AoE: 350. Cooldown: 15. Manacost: 40/50/60/70
-- Tusk can crit off this physical damage

### UNDERLORD:

- Intelligence gain reduced from 2.6 to 2.3
-   Atrophy Aura now provides a permanent +2/3/4/5 bonus damage when a hero dies under the aura

### UNDYING: ABILITY REWORK

-   Base movement speed reduced from 305 to 295
-   Reworked Flesh Golem. No longer amplifies damage. Slow is now a constant 24/32/40% in 375 AoE. Does not scale with distance. Enemy units in 400 AoE lose 7% of their Current HP per second as Magic Damage. You gain +400/1000/1600 health when in this mode. Cooldown: 125
-   Level 10 Talent reduced from +10 Health Regen to +8
- Level 20 Talent reduced from +6 Tombstone Attacks To Destroy to +5
- Level 25 Talent increased from Gains Reincarnation 200 CD to 250 CD
-   Flesh Golem model size increased a bit

### URSA:

-  Base movement speed increased from 305 to 315
- Fury Swipes damage reduced from 12/18/24/30 to 10/16/22/28
-   Fixed Overpower not consuming attack count when an attack is evaded
- Level 15 Talent reduced from +16 Agility to +14

### VENGEFUL SPIRIT:

-   Vengeance Aura no longer creates illusions of dying allies
-   Vengeance Aura now creates the Scepter effect on dying as a base mechanic, without the ability to cast spells. Gaining Scepter unlocks casting spells
-   Netherswap cast range rescaled from 700/950/1200 to 700/850/1000
-   Netherswap now has 2 charges with 90/80/70 second replenish time
-- Scepter still reduces this to 10 seconds

### VENOMANCER:

- Base agility increased by 4
-   Poison Nova damage increased from 30/55/80 to 40/65/90	
- Poison Sting slow from 11/12/13/14% to 11/13/15/17%
-   Plague Wards collision size increased
-   Level 15 Talent changed from +200 Cast Range to Gale Hero Impact Summons 2 Wards
- Level 15 Talent increased from +6% Poison Sting Slow to +8%
-   Level 20 Talent changed from Gale Hero Impact Summons 2 Wards to +15% Spell Lifesteal

### VIPER:

-   Nethertoxin AoE increased from 300 to 350
-   Nethertoxin damage rescaled from 20/30/40/50 to 20/35/50/65

### WARLOCK:

-   Fatal Bonds now bounces from unit to unit, rather than just searching units near the target
-   Fatal Bonds no longer ignores units in Fog of War

### WEAVER:

-   The Swarm units now have higher attack priority
-- Follows the same rules as Phantom's Embrace
  
-   Geminate attack cooldown increased from 7/6/5/3 to 9/7/5/3

### WITCH DOCTOR:

-   Death Ward damage increased from 60/105/150 to 75/125/175

### WRAITH KING:

-   Skeletons health reduced from 350 to 250
-   Skeletons now reincarnate 3 seconds after dying the first time

### ZEUS:

-   Nimbus is no longer automatically selected when hitting Tab
-   Nimbus's Lightning Bolt no longer benefits from cooldown reductions on your hero
