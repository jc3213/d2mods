# Diablo II LoD Mods

## About

This mod backported all possible changes inspired by Diablo II: Resurrected

## How to use

### Vanilla

- Download latest [release](//github.com/jc3213/d2mods/releases/latest)
- Extract to the folder where your Diablo II installed
- Run **Game.exe** with parameters `-direct -txt`
    - Create a shortcut to run `C:\Diablo II\Game.exe -direct -txt` for example

### Play with PlugY

- Modify **PlugY.ini** and add `-direct -txt` to `[LAUNCHING] > Param`
```ini
[LAUNCHING]
Param=-direct -txt
```
- Run **PlugY.exe**

### Full Version

- Download latest [d2mods-full.zip](https://github.com/jc3213/d2mods/releases/latest/download/d2mods-full.zip)
    - Full package includes `PlugY` by [Yohann](http://plugy.free.fr), and `D2DX` /w `D2FPS` & `SGD2FreeRes` by [Jarcho](https://github.com/Jarcho/d2dx)
- Extract to the folder where your Diablo II installed
- Run `PlugY.exe`, and enjoy

## Changes

### Skills

#### Amazon

- Bow and Crossbow Skills
    - `Multiple Shot`
        - Gains **+12% Damage** per level of `Guided Arrow`
    - `Guided Arrow`
        - Gains **+12% Damage** per level of `Multiple Shot`
    - `Strafe`
        - Gains **+5% Damage** per level of `Multiple Shot`
        - Gains **+10% Damage** per level of `Guided Arrow`
        - Gains **30%** base attack rating
        - Gains **9%** attack rating per level
    - `Exploding Arrow`
        - Synergy increased from 12% to **14%**
        - Fire damage has been increased
    - `Immolation Arrow`
        - Cast delay reduced from 1 second to **0.6** second
        - Average fire damage has been increased
- Javelin and Spear Skills
    - `Power Strike`
        - Synergy increased from 10% to **14%**
        - Removed synergy from `Lightning Fury`
    - `Poison Javelin`
        - Maximum poison damage over skill level 28 has been increased
    - `Charged Strike`
        - Synergy increased from 10% to **14%**
        - Removed synergy from `Lightning Fury`
    - `Plague Javelin`
        - Synergy increased from 10% to **14%**
        - Poison damage has been significantly increased
        - Reduced poison length
        - Cast delay reduced from 4 seconds to **1** second
    - `Lightning Strike`
        - Synergy increased from 8% to **11%**
        - Removed synergy from `Lightning Fury`
- Passive and Magic Skills
    - `Inner Sight`
        - Radius increased from 13.3 yards to **18** yards
    - `Slow Missiles`
        - Radius increased from 13.3 yards to **18** yards
        - Updated calibration
    - `Valkyrie`
        - Cast delay reduced from 6 seconds to **0.6** second

#### Sorceress

- Cold Spells
    - `Frozen Armor`
        - Base duration increased from 120 seconds to **144** seconds
    - `Frost Nova`
        - Cold damage per level has been increased
    - `Shiver Armor`
        - Base duration increased from 120 seconds to **144** seconds
        - Cold damage per level has been increased
    - `Chilling Armor`
        - Cold damage has been increased
        - Cold damage synergy increased from 7% to **9%**
        - Base defense increased from 45% to **60%**
        - Defense per level increased from 5% to **9%**
        - Duration per level increased from 6 seconds to **12** seconds
- Lightning Spells
    - `Nova`
        - Gains **+5% Lightning Damage** per level of `Static Field`
    - `Thunder Storm`
        - Gains **7% Lightning Damage** per level of `Static Field`
        - Base duration increased from 32 seconds to **144** seconds
        - Duration per level increased from 5 seconds to **24** seconds
        - Display **Radius**
    - `Energy Shield`
        - Duration per level reduced from 60 seconds to **24** seconds
        - Display **Mana Consumption**
- Fire Spells
    - `Inferno`
        - Base range increased from 3.3 yards to **5.3** yards
        - Fire damage has been increased
        - Fire damage synergy increased from 13% to **16%**
        - Mana per second reduced from 7 to **4**
    - `Blaze`
        - Fire damage per level has been increased
        - Fire damage synergy from `Warmth` increased from 4% to **6%**
        - Gains **+2%** `Walk/Run Speed` per level when activated
        - Removed synergy from `Fire Wall`
    - `Fire Ball`
        - Radius display has been corrected to **2.6** yards
    - `Fire Wall`
        - Base range increased from 4 yards to **6** yards
    - `Hydra`
        - Removed cast delay, limited up to 6 hydras

#### Necromancer

- Summoning Spells
    - `Blood Golem`
        - Gains **+20% Life** per level
        - Base damage has been increased
        - Damage per level increased from 35% to **55%**
- Poison and Bone Spells
    - `Bone Spear`
        - Damage synergy increased from 7% to **8%**
    - `Bone Spirit`
        - Damage synergy increased from 6% to **8%**
- Curses
    - `Weaken`
        - Gains **-1% Enemy Damage** per level
    - `Decrepify`
        - Display **Detailed Weakening**

#### Paladin

- Offensive Auras
    - `Holy Fire`
        - Fire damage damage has been significantly increased
        - Fire damage synergy from `Resist Fire` increased from 18% to **21%**
        - Fire damage synergy from `Salvation` increased from 6% to **10%**
    - `Thorns`
        - Gains extra `Attacker Takes Damage of` property when activated
    - `Blessed Aim`
        - Display **Attack Rating (Passive)**
    - `Holy Freeze`
        - Maximum aura cold damage has been doubled
    - `Holy Shock`
        - Maximum aura lightning damage has been doubled
    - `Sancturary`
        - Maximum aura magic damage has been doubled
- Defensive Auras
    - `Resist Fire`
        - Display additional **Maximum Fire Resist**
    - `Resist Cold`
        - Display additional **Maximum Cold Resist**
    - `Resist Lightning`
        - Display additional **Maximum Lightning Resist**
- Combat Skills
    - `Holy Bolt`
        - Heal synergy increased from 15% to **20%**
    - `Conversion`
        - Maximum chance of conversion increased from 50% to **90%**
    - `Fist of the Heavens`
        - Cast delay reduced from 1 second to **0.4** second

#### Barbarian

- Combat Masteries
    - `Sword Master`
        - Base attack rating increased from 28% to **40%**
    - `Axe Master`
        - Base attack rating increased from 28% to **40%**
    - `Mace Master`
        - Base attack rating increased from 28% to **40%**
    - `Pole Arm Master`
        - Base attack rating increased from 30% to **44%**
    - `Throwing Master`
        - Base attack rating increased from 30% to **44%**
        - Gains **8-55%** chance to pierce
    - `Spear Master`
        - Base attack rating increased from 30% to **44%**
- Combat Skills
    - `Leap`
        - Base radius increased from 4.6 yards to **7.3** yards
        - Display **Knockback Radius**
    - `Double Throw`
        - Added **+8% Damage** per level
    - `Leap Attack`
        - Base radius increased from 4.6 yards to **7.3** yards
        - Base damage increased from 100% to **200%**
        - Base attack rating increased from 50% to **100%**
        - Attack rating per level increased from 15% to **20%**
        - Mana cost increased from 9 to **10**
        - Not area attack yet, **Help wanted**
    - `Whirlwind`
        - Base damage increased from -50% to **+30%**
        - Damage per level reduced from 8% to **5%**
        - Gains **50%** base attack rating
- Warcries
    - `Shout`
        - Base duration increased from 20 seconds to **30** seconds
    - `Find Item`
        - Gains **+1% Chance** per level of `Find Potion`
    - `War Cry`
        - Physic damage has been increased
    - `Battle Command`
        - Base duration increased from 5 seconds to **30** seconds

#### Druid

- Shape Shifting
    - `Werebear`
        - Damage per level increased from 8% to **15%**
        - Base defense increased from 25% to **40%**
        - Defense per level increased from 6% to **10%**
    - `Maul`
        - Damage per charge increased from 20% to **30%**
        - Gains **+3% Attack Speed** per charge
        - Base attack rating increased from 20% to **40%**
        - Attack rating per level increased from 10% to **15%**
    - `Rabies`
        - Synergy increased from 18% to **20%**
        - Attack rating per level increased from 7% to **10%**
    - `Fire Claw`
        - Synergies removed from `Fissure` and `Volcano`
        - Fire damage has been significantly increased
    - `Shock Wave`
        - Synergy increased from 5% to **10%**
    - `Fury`
        - Attack rating per level increased from 7% to **10%**
- Summoning
    - `Raven`
        - Gains **+12% Damage** per level of `Summon Spirit Wolf`, `Summon Dire Wolf` and `Summon Grizzly`
        - Physic damage has been significantly increased
        - Display **Attack Rating**
        - Attack rating per level increased from 15% to **30%**
    - `Poison Creeper`
        - Gains **+10% Poison Damage** per level of `Rabies`
        - Poison damage has been significantly increased
    - `Summon Spirit Wolf`
        - Won't replace **Dire Wolves** and **Grizzly**
        - Base life has been increased
        - Gains **+10% Life** per level
        - Life synergy from `Summon Dire Wolf` reduced from 25% to **15%**
        - Deals cold damage
        - Cold damage per level has been increased
    - `Carrion Vine`
        - Base life steal increased from 3% to **4%**
        - Gains **+1% Life Steal** per level
    - `Summon Dire Wolf`
        - Won't replace **Spirit Wolves** and **Grizzly**
        - Base life has been increased
        - Damage has been increased
        - Defense display has been corrected
    - `Solar Creeper`
        - Base mana steal increased from 1% to **4%**
        - Gains **+1% Mana Steal** per level
    - `Spirit of Barbs`
        - Removed base radius ~~20 yards~~
        - Use `Attacker Takes Damage of` instead of `% Damage Returned`
    - `Summon Grizzly`
        - Won't replace **Spirit Wolves** and **Dire Wolves**
        - Base life has been increased
        - Gains **+10% Life** per level
        - Life synergy from `Summon Dire Wolf` reduced from 25% to **15%**
- Elemental
    - `Molten Boulder`
        - Synergy increased from 10% to **12%**
        - Cast delay reduced from 2 seconds to **1** second
    - `Arctic Blast`
        - Cold damage has been increased
        - Removed synergy from `Hurricane`
    - `Volcano`
        - Synergy increased from 12% to **16%**
    - `Armageddon`
        - Display **Physic Damage**
        - Physic damage has been significantly increased
        - Gains **+18% Damage** instead of **+14% Fire Damage** per level of `Volcano`
        - Removed restriction to `Hurricane`
        - Removed cast delay
    - `Hurricane`
        - Removed cast delay

#### Assassin

- Traps
    - `Fire Blast`
        - Synergy increased from 9% to **11%**
        - Removed synergy from `Death Sentry`
    - `Shock Web`
        - Synergy increased from 11% to **17%**
        - Removed synergy from `Death Sentry`
    - `Charged Sentry`
        - Synergy increased from 6% → **9%**
        - Removed synergy from `Death Sentry`
    - `Lightning Sentry`
        - Synergy increased from 12% to **18%**
        - Removed synergy from `Death Sentry`
    - `Wake of Fire`
        - Synergy increased from 8% to **10%**
    - `Wake of Inferno`
        - Synergy increased from 7% / 10% to **18%**
        - Base fire damage has been significantly increased
        - Removed synergy from `Death Sentry`
        - Display inferno range
    - `Blade Sentinel`
        - Gains **+10% Damage** per level of `Blade Fury` and `Blade Shield`
        - Cast delay reduced from 2 seconds to **1** second
    - `Blade Fury`
        - Gains **+10% Damage** per level of `Blade Sentinel` and `Blade Shield`
    - `Blade Shield`
        - Gains **+10% Damage** per level of `Blade Sentinel` and `Blade Fury`
        - Base duration increased from 20 seconds to **120** seconds
        - Duration per level increased from 5 seconds to **12** seconds
    - `Fade`
        - Display damage resist
- Shadow Disciplines
    - `Shadow Warrior`
        - Cast delay reduced from 6 seconds to **0.6** second
        - Defense display has been corrected
    - `Venom`
        - Duration per level increased from 4 seconds to **12** seconds
    - `Shadow Master`
        - Cast delay reduced from 6 seconds to **0.6** second
        - Minimum resist all increased from 5% to **17%**
- Martial Arts
    - `Tiger Strike`
        - Base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**
    - `Fists of Fire`
        - Base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**
        - Fire damage radius increased from 2.6 yards to **4** yards
    - `Dragon Claw`
        - Damage per level increased from 5% to **15%**
    - `Cobra Strike`
        - Base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**
    - `Claws of Thunder`
        - Base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**
    - `Dragon Tail`
        - Damage per level increased from 10% to **20%**
    - `Blades of Ice`
        - Base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**
    - `Dragon Flight`
        - Damage per level increased from 25% to **35%**
        - Removed cast delay
    - `Phoenix Strike`
        - Base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**

### Unique Items

- `Pluckeye`
    - Short Bow
    - Added **+25% Increased Attack Speed**
- `Rogue's Bow`
    - Composite Bow
    - Added **+1-3 Fire Arrow (Amazon Only)** or **+1-3 Cold Arrow (Amazon Only)**
- `Bane Ash`
    - Short Staff
    - Removed **+20% Increased Attack Speed**
    - Removed **+50-60% Enhanced Damage**
    - Added **+20% Faster Cast Rate**
- `Gravenspine`
    - Yew Wand
    - Added **+10% Faster Cast Rate**
- `Blinkbat's Form`
    - Leather Armor
    - Faster Run/Walk increased from 10% to **30%**
    - Added **+1 Mana After Each Kill**
- `The Battlebranch`
    - Poleaxe
    - Base item level reduced from 34 to **30**
    - Required level reduced from 25 to **17**
- `The Ward`
    - Gothic Shield
    - Added **Socketed (1)**
- `Bloodletter`
    - Gladius
    - Added **+20% Faster Run/Walk**
- `Manald Heal`
    - Ring
    - Added **+10% Faster Cast Rate**

### Set Items

#### Angelic Raiment

- `Angelic Sickle`
    - Sabre
    - Added **+6 Damage** 
        - 3 pieces equipped
- `Angelic Mantle`
    - Ring Mail
    - Added **+100% Damage to Undead**
        - 3 pieces equipped
- **Full Set**
    - Added **+1 to All Skills**

### Runewords

- Bulwark
    - Works on `Helms`
    - `Shael Rune` + `Io Rune` + `Sol Rune`
- Cure
    - Works on `Helms`
    - `Shael Rune` + `Io Rune` + `Tal Rune`
- Flickering Flame
    - Works on `Helms`
    - `Nef Rune` + `Pul Rune` + `Vex Rune`
- Ground
    - Works on `Helms`
    - `Shael Rune` + `Io Rune` + `Ort Rune`
- Hearth
    - Works on `Helms`
    - `Shael Rune` + `Io Rune` + `Thul Rune`
- Hysteria
    - Works on `Body Armors`
    - `Shael Rune` + `Ko Rune` + `Eld Rune`
- Infinity
    - Works on `Polearms`, and **`Spears`**
    - `Ber Rune` + `Mal Rune` + `Ber Rune` + `Ist Rune`
- Insight
    - Works on `Polearms`, `Staves`, and **`Missile Weapons`**
    - `Ral Rune` + `Tir Rune` + `Tal Rune` + `Sol Rune`
- Mania
    - Works on `Weapons`
    - `Shael Rune` + `Ko Rune` + `Eld Rune`
- Metamorphosis
    - Works on `Healms`
    - `Io Rune` + `Cham Rune` + `Fal Rune`
- Mist
    - Works on `Missile Weapons`
    - `Cham Rune` + `Shael Rune` + `Gul Rune` + `Thul Rune` + `Ith Rune`
- Obedience
    - Works on `Polearms`, and **`Spears`**
    - `Hel Rune` + `Ko Rune` + `Thul Rune` + `Eth Rune` + `Fal Rune`
- Obsession
    - Works on `Staves`
    - `Zod Rune` + `Ist Rune` + `Lem Rune` + `Lum Rune` + `Io Rune` + `Nef Rune`
- Plague
    - Works on `Swords`, `Knives`, and `Claws`
    - `Cham Rune` + `Shael Rune` + `Um Rune`
- Pride
    - Works on `Polearms`, and **`Spears`**
    - `Cham Rune` + `Sur Rune` + `Io Rune` + `Lo Rune`
- Temper
    - Works on `Helms`
    - `Shael Rune` + `Io Rune` + `Thul Rune`
- Unbending Will
    - Works on `Swords`
    - `Fal Rune` + `Io Rune` + `Ith Rune` + `Eld Rune` + `El Rune` + `Hel Rune`
- Wisdom
    - Works on `Helms`
    - `Pul Rune` + `Ith Rune` + `Eth Rune`

### Hireling

- Rogue scout
    - **Cold Arrow** rogue now fires `Insight`, `Cold Arrow`, and **`Freezing Arrow`**
        - **D2R data needed**
    - **Fire Arrow** rogue now fires `Insight`, `Cold Arrow`, and **`Exploding Arrow`**
        - **D2R data needed**
- Iron wolf
    - **Fire** iron wolf now casts **`Fire Bolt`**, `Fire Ball` and **`Enchant`**
        - **D2R data needed**
    - **Lightning** iron wolf now casts `Charged Bolt`, `Lightning`, and **`Static Field`**
        - **D2R data needed**
- Barbarian
    - Now ues `Bash`, `Stun` and **`Battle Cry`**
        - **D2R data needed**

### Horadric Cube

- Basic Set Weapons → Exceptional
    - `Ral Rune` + `Sol Rune` + `Perfect Emerald`
- Exceptional Set Weapons → Elite
    - `Lum Rune` + `Pul Rune` + `Perfect Emerald`
- Basic Set Armors → Exceptional
    - `Tal Rune` + `Shael Rune` + `Perfect Diamond`
- Exceptional Set Armors → Elite
    - `Ko Rune` + `Lem Rune` + `Perfect Diamond`

### Dungeons

#### Act 1

- `Underground Passage Level 2`
    - Increased Level from 83 to **85**

#### Act 2

- `Stony Tomb Level 1`
    - Increased Level from 78 to **85**
- `Stony Tomb Level 2`
    - Increased Level from 79 to **85**

#### Act 3

- `Spider Cave`
    - Increased Level from 79 to **85**
- `Spider Cavern`
    - Increased Level from 79 to **85**
- `Swampy Pit Level 1`
    - Increased Level from 80 to **85**
- `Swampy Pit Level 2`
    - Increased Level from 81 to **85**
- `Swampy Pit Level 3`
    - Increased Level from 82 to **85**
- `Sewers Level 1`
    - Increased Level from 84 to **85**
- `Ruined Temple`
    - Increased Level from 84 to **85**
- `Disused Fane`
    - Increased Level from 84 to **85**
- `Forgotten Reliquary`
    - Increased Level from 84 to **85**

#### Act 5

- `Echo Chamber`
    - Increased Level from 84 to **85**
- `Glacial Caves Level 2`
    - Increased Level from 83 to **85**
- `Hell 1`
    - Increased Level from 81 to **85**
- `Hell 2`
    - Increased Level from 82 to **85**
- `Hell 3`
    - Increased Level from 83 to **85**

### Weapons

#### Knife

- `Blade`
    - Maximum sockets increased from 2 to **3**
- `Stilleto`
    - Maximum sockets increased from 2 to **3**
- `Legend Spike`
    - Maximum sockets increased from 2 to **3**

#### Throwing

- `Throwing Knife`
    - Quantity increased from 160 to **240**
- `Throwing Axe`
    - Quantity increased from 130 to **200**
- `Balanced Knife`
    - Quantity increased from 160 to **240**
- `Balanced Axe`
    - Quantity increased from 130 to **200**
- `Javelin`
    - Quantity increased from 60 to **90**
- `Pilum`
    - Quantity increased from 50 to **75**
- `Short Spear`
    - Quantity increased from 40 to **60**
- `Glaive`
    - Quantity increased from 40 to **60**
- `Throwing Spear`
    - Quantity increased from 80 to **120**
 - `Battle Dart`
    - Quantity increased from 160 to **240**
- `Francisca`
    - Quantity increased from 130 to **200**
- `War Dart`
    - Quantity increased from 160 to **240**
- `Hurlbat`
    - Quantity increased from 130 to **200**
- `War Javelin`
    - Quantity increased from 60 to **90**
- `Great Pilum`
    - Quantity increased from 50 to **75**
- `Simbilan`
    - Quantity increased from 40 to **60**
- `Spiculum`
    - Quantity increased from 20 to **30**
- `Harpoon`
    - Quantity increased from 80 to **120**
- `Flying Knife`
    - Quantity increased from 200 to **300**
- `Flying Axe`
    - Quantity increased from 180 to **270**
- `Winged Knife`
    - Quantity increased from 200 to **300**
- `Winged Axe`
    - Quantity increased from 180 to **270**
- `Hyperion Javelin`
    - Quantity increased from 100 to **150**
- `Stygian Pilum`
    - Quantity increased from 90 to **140**
- `Balrog Spear`
    - Quantity increased from 80 to **120**
- `Ghost Glaive`
    - Quantity increased from 75 to **120**
- `Winged Harpoon`
    - Quantity increased from 80 to **120**

### Misc

- `Stash` size increased from 6x8 to **10x10**
- `Arrow` and `Bolts` quantity has been incresed to **500**
- Gems now share the same drop rate as `Amethyst`
- `Throw Weapons` quantity has been increased by **50%**
