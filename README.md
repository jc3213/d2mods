# Diablo II LoD Mods

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

### Skill synergies

Backported skill synergies inspired by Diablo II: Resurrected

- Amazon
    - `Multiple Shot` now gains **+12% Damage** per level of `Guided Arrow`
    - `Guided Arrow` now gains **+12% Damage** per level of `Multiple Shot`
    - `Strafe` now gains **+5% Damage** per level of `Multiple Shot` and **+10% Damage** per level of `Guided Arrow`
    - `Exploding Arrow` synergy increased from 12% to **14%**
    - `Immolation Arrow` cast delay reduced from 1 second to **0.6** second
    - `Plague Javelin` synergy increased from 10% to **14%**, cast delay reduced from 4 seconds to **1** second
    - `Power Strike` synergy increased from 10% to **14%**
    - `Charged Strike` synergy increased from 10% to **14%**
    - `Lightning Strike` synergy increased from 8% to **11%**
    - `Valkyrie` cast delay reduced from 6 seconds to **0.6** second
- Sorceress
    - `Chilling Armor` synergy increased from 7% to **9%**
    - `Nova` now gains **+5% Lightning Damage** per level of `Lightning`
    - `Thunder Storm` now gains **7% Lightning Damage**  per level of `Lightning`
    - `Inferno` synergy increased from 13% to **16%**
    - `Blaze` synergy from `Warmth` increased from 4% to **6%**
        - Removed synergy from `Fire Wall`
    - `Hydra` removed cast delay, and limited up to 6 hydras
- Necromancer
    - `Bone Spear` damage synergy increased from 7% to **8%**
    - `Bone Spirit` damage synergy increased from 6% to **8%**
- Paladin
    - `Holy Fire` damage synergy from `Resist Fire` increased from 18% to **21%**, from `Salvation` increased from 6% to **10%**
    - `Fist of the Heavens` cast delay reduced from 1 second to **0.4** second
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
    - `Blade Sentinel` now gains **+10% Damage** per level of `Blade Fury` and `Blade Shield`
    - `Blade Sentinel` now gains **+10% Damage** per level of `Blade Fury` and `Blade Shield`
    - `Blade Sentinel` now gains **+10% Damage** per level of `Blade Fury` and `Blade Shield`
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

Backported changes on runeword inspired by Diablo II: Resurrected

- Insight
    - Now works on `Missile Weapon`
- Infinite
    - Now works on `Spear`

### Hireling

- Rogue scout
    - Now available to equip `Amazon Bow`
