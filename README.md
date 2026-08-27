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

- Amazon
    - `Multiple Shot` gains **+12% Damage** per level of `Guided Arrow`
    - `Guided Arrow` gains **+12% Damage** per level of `Multiple Shot`
    - `Strafe` gains **+5% Damage** per level of `Multiple Shot` 
        - Gains **+10% Damage** per level of `Guided Arrow`
    - `Exploding Arrow` synergy increased from 12% to **14%**
        - Fire damage has been increased
    - `Immolation Arrow` cast delay reduced from 1 second to **0.6** second
    - `Power Strike` synergy increased from 10% to **14%**
        - Removed synergy from `Lightning Fury`
    - `Poison Javelin`
        - Maximum poison damage over skill level 28 has been increased
    - `Charged Strike` synergy increased from 10% to **14%**
        - Removed synergy from `Lightning Fury`
    - `Plague Javelin` synergy increased from 10% to **14%**
        - Poison damage has been significantly increased
        - Reduced poison length
        - Cast delay reduced from 4 seconds to **1** second
    - `Lightning Strike` synergy increased from 8% to **11%**
        - Removed synergy from `Lightning Fury`
    - `Valkyrie` cast delay reduced from 6 seconds to **0.6** second

- Sorceress
    - `Frozen Armor` base duration increased from 120 seconds to **144** seconds
    - `Frost Nova` cold damage per level has been increased
    - `Shiver Armor` base duration increased from 120 seconds to **144** seconds
        - Cold damage per level has been increased
    - `Chilling Armor` base defense bounus increased from 45% to **60%**
        - Cold damage has been increased
        - Cold damage synergy increased from 7% to **9%**
        - Defense bounus per level increased from 5% to **9%**
        - Duration per level increased from 6 seconds to **12** seconds
    - `Nova` gains **+5% Lightning Damage** per level of `Static Field`
    - `Thunder Storm` gains **7% Lightning Damage**  per level of `Static Field`
    - `Energy Shield` duration per level reduced from 60 seconds to **24** seconds
    - `Inferno` fire damage has been increased
        - Fire damage synergy increased from 13% to **16%**
    - `Blaze` fire damage per level has been increased
        - Fire damage synergy from `Warmth` increased from 4% to **6%**
        - Added **+2%** `Walk/Run Speed` per level when activated
        - Removed synergy from `Fire Wall`
    - `Fire Ball` radius display has been corrected to **2.6** yards
    - `Hydra` removed cast delay, limited up to 6 hydras

- Necromancer
    - `Bone Spear` damage synergy increased from 7% to **8%**
    - `Bone Spirit` damage synergy increased from 6% to **8%**

- Paladin
    - `Holy Fire` fire damage damage has been significantly increased
        - Fire damage synergy from `Salvation` increased from 6% to **10%**
        - Fire synergy from `Resist Fire` increased from 18% to **21%**
    - `Holy Freeze` maximum aura cold damage has been doubled
    - `Holy Shock` maximum aura lightning damage has been doubled
    - `Sancturary` maximum aura magic damage has been doubled
    - `Fist of the Heavens` cast delay reduced from 1 second to **0.4** second

- Barbarian
    - `Leap` base distance increased from 4.6 yards to **7.3** yards
    - `Double Throw` added **+8% Damage** per level
    - `Leap Attack` base damage increased from 100% to **210%**
    - `Whirlwind` base damage increased from -50% to **+30%**
        - Damage per level reduced from 8% to **5%**
        - Added **+50% Attack Rating** at level 1
    - `Find Item` gains **+1% Chance** per level of `Find Potion`
    - `War Cry` physic damage has been increased

- Assassin
    - `Fire Blast` synergy increased from 9% to **11%**
      - Removed synergy from `Death Sentry`
    - `Shock Web` synergy increased from 11% to **17%**
      - Removed synergy from `Death Sentry`
    - `Charged Sentry` synergy increased from 6% → **9%**
      - Removed synergy from `Death Sentry`
    - `Lightning Sentry` synergy increased from 12% to **18%**
      - Removed synergy from `Death Sentry`
    - `Wake of Fire` synergy increased from 8% to **10%**
    - `Wake of Inferno` synergy increased from 7% / 10% to **18%**
      - Base fire damage has been significantly increased
      - Removed synergy from `Death Sentry`
    - `Blade Sentinel` gains **+10% Damage** per level of `Blade Fury` and `Blade Shield`
        - Cast delay reduced from 2 seconds to **1** second
    - `Blade Fury` gains **+10% Damage** per level of `Blade Sentinel` and `Blade Shield`
    - `Blade Shield` gains **+10% Damage** per level of `Blade Sentinel` and `Blade Fury`
         - Base duration increased from 20 seconds to **120** seconds
         - Duration per level increased from 5 seconds to **12** seconds
    - `Shadow Warrior` cast delay reduced from 6 seconds to **0.6** second
    - `Venom` duration per level increased from 4 seconds to **12** seconds
    - `Shadow Master` cast delay reduced from 6 seconds to **0.6** second
    - `Tiger Strike` base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**
    - `Fists of Fire` base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**
    - `Dragon Claw` damage per level increased from 5% to **15%**
    - `Cobra Strike` base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**
    - `Claws of Thunder` base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**
    - `Dragon Tail` damage per level increased from 10% to **20%**
    - `Blades of Ice` base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**
    - `Dragon Flight` damage per level increased from 25% to **35%**
        - Removed cast delay
    - `Phoenix Strike` base attack rating increased from 15% to **25%**
        - Attack rating per level increased from 7% to **10%**

- Druid
    - `Rabies` synergy increased from 18% to **20%**
    - `Fire Claw` synergies removed from `Fissure` and `Volcano`
        - Fire damage has been significantly increased
    - `Shock Wave` synergy increased from 5% to **10%**
    - `Raven` now gains **+12% Damage%** per level from `Summon Spirit Wolf`, `Summon Dire Wolf`, and `Summon Grizzly`
        - Physic damage has been significantly increased
    - `Poison Creeper` gains **+10% Poison Damage** per level of `Rabies`
        - Poison damage has been significantly increased
    - `Summon Spirit Wolf` won't replace **Dire Wolves** and **Grizzly**
        - Base life has been increased
        - Gains **+10% Life** per level
        - Life synergy from `Summon Dire Wolf` reduced from 25% to **15%**
        - Deals cold damage
        - Cold damage per level has been increased
    - `Summon Dire Wolf` won't replace **Spirit Wolves** and **Grizzly**
        - Base life has been increased
        - Damage has been increased
        - Defense bounus display has been corrected
    - `Summon Grizzly` won't replace **Spirit Wolves** and **Dire Wolves**
        - Base life has been increased
        - Gains **+10% Life** per level
        - Life synergy from `Summon Dire Wolf` reduced from 25% to **15%**
    - `Molten Boulder` synergy increased from 10% to **12%**
        - Cast delay reduced from 2 seconds to **1** second
    - `Volcano` synergy increased from 12% to **16%**
    - `Armageddon` now gains **+18% Damage** instead of **+14% Fire Damage** per level of `Volcano`
        - Physic damage has been significantly increased
        - Physic damage is now displayed
        - Average fire damage has not been reduced yet, **Help wanted**
        - Removed restriction to `Hurricane`
        - Removed cast delay
    - `Hurricane` removed cast delay

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
- Mist
    - Works on `Missile Weapons`
    - `Cham Rune` + `Shael Rune` + `Gul Rune` + `Thul Rune` + `Ith Rune`
- Obsession
    - Works on `Staves`
    - `Zod Rune` + `Ist Rune` + `Lem Rune` + `Lum Rune` + `Io Rune` + `Nef Rune`
- Plague
    - Works on `Swords`, `Knives`, `Claws`
    - `Cham Rune` + `Shael Rune` + `Um Rune`
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

### Misc

- `Stash` size increased from 6x8 to **10x10**
- `Arrow` and `Bolts` quantity has been incresed to **500**
- Gems now share the same drop rate as `Amethyst`
- `Throw Weapons` quantity has been increased by **50%**
