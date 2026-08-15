# Diablo II LoD Mods

## About

Backported all possible changes inspired by Diablo II: Resurrected

## How to use

- Download latest [release](//github.com/jc3213/d2mods/releases/latest)
- Extract to the folder where your Diablo II installed
- Run **Game.exe** with parameters `-direct -txt`
    - Create a shortcut to run `C:\Diablo II\Game.exe -direct -txt` for example

## Play with PlugY

- Modify **PlugY.ini** and add `-direct -txt` to `[LAUNCHING] > Param`
```ini
[LAUNCHING]
Param=-direct -txt
```
- Run **PlugY.exe**

## Changes

### Skills

- Amazon
    - `Multiple Shot` gains **+12% Damage** per level of `Guided Arrow`
    - `Guided Arrow` gains **+12% Damage** per level of `Multiple Shot`
    - `Strafe` gains **+5% Damage** per level of `Multiple Shot` 
        - Gains **+10% Damage** per level of `Guided Arrow`
    - `Exploding Arrow` synergy increased from 12% to **14%**
    - `Immolation Arrow` cast delay reduced from 1 second to **0.6** second
    - `Plague Javelin` synergy increased from 10% to **14%**
        - Cast delay reduced from 4 seconds to **1** second
    - `Power Strike` synergy increased from 10% to **14%**
    - `Charged Strike` synergy increased from 10% to **14%**
    - `Lightning Strike` synergy increased from 8% to **11%**
    - `Valkyrie` cast delay reduced from 6 seconds to **0.6** second

- Sorceress
    - `Chilling Armor` cold damage synergy increased from 7% to **9%**
    - `Nova` gains **+5% Lightning Damage** per level of `Lightning`
    - `Thunder Storm` gains **7% Lightning Damage**  per level of `Lightning`
    - `Inferno` fire damage synergy increased from 13% to **16%**
    - `Blaze` fire damage synergy from `Warmth` increased from 4% to **6%**
        - Removed synergy from `Fire Wall`
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
    - `Leap Attack` base damage increased from 100% to **210%**
    - `Whirlwind` base damage increased from -50% to **+30%**
        - Damage per level decreased from 8% to **5%**
        - Added base **+50% Attack Rating**

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
    - `Inferno Sentry` synergy increased from 7% / 10% to **18%**
      - Removed synergy from `Death Sentry`
    - `Blade Sentinel` gains **+10% Damage** per level of `Blade Fury` and `Blade Shield`
    - `Blade Fury` gains **+10% Damage** per level of `Blade Sentinel` and `Blade Shield`
    - `Blade Shield` gains **+10% Damage** per level of `Blade Sentinel` and `Blade Fury`
         - Base duration increased from 20 seconds to **120** seconds
         - Duration per level increased from 5 seconds to **12** seconds
    - `Venom` duration per level increased from 4 seconds to **12** seconds

- Druid
    - `Rabies` synergy increased from 18% to **20%**
    - `Fire Claw` synergies removed from `Fissure` and `Volcano`
        - Fire damage has been significantly increased
    - `Shock Wave` synergy increased from 5% to **10%**
    - `Raven` now gains **+12% Damage%** per level from `Summon Spirit Wolf`, `Summon Dire Wolf`, and `Summon Grizzly`
        - Physic damage has been significantly increased
    - `Summon Spirit Wolf` won't replace **Dire Wolves** and **Grizzly**
    - `Summon Dire Wolf` won't replace **Spirit Wolves** and **Grizzly**
    - `Summon Grizzly` won't replace **Spirit Wolves** and **Dire Wolves**
    - `Molten Boulder` synergy increased from 10% to **12%**, cast delay reduced from 2 seconds to **1** second
    - `Volcano` synergy increased from 12% to **16%**
    - `Armageddon` now gains **+18% Damage** instead of **+14% Fire Damage** per level of `Volcano`
        - Physic damage is now displayed and has been significantly increased
        - Average fire damage has not been decreased yet, **Help wanted**
        - Removed restriction to `Hurricane`
            - Need fix for UI **Help wanted**
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
    - Now available to equip `Amazon Bow`

### Horadric Cube

- Basic Set Weapons → Exceptional
    - `Ral Rune` + `Sol Rune` + `Perfect Emerald`
- Exceptional Set Weapons → Elite
    - `Lum Rune` + `Pul Rune` + `Perfect Emerald`
- Basic Set Armors → Exceptional
    - `Tal Rune` + `Shael Rune` + `Perfect Diamond`
- Exceptional Set Armors → Elite
    - `Ko Rune` + `Lem Rune` + `Perfect Diamond`
