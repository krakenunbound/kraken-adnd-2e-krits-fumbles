# Kraken's Krits & Fumbles 2E Automation

Critical hits and fumbles with a table for AD&D 2E, applied in Fantasy Grounds Unity.

Rolls the weapon tables of the **Kraken's Krits & Fumbles 2E** module (Critical Hit and Fumble: Slashing, Piercing, Bludgeoning, Missile, Natural Attack; d12) on a critical hit or a natural 1. By default a complication comes 1 time in 3, as in 1.0 (d6 5-6). The module stays the book to read.

![Options](docs/options.png)

## What is applied

- Conditions and penalties go on the combat tracker as effects (prone, blinded, bleeding,
  attack and armour penalties, lost actions), with their duration.
- Extra damage and self damage are real damage rolls in chat, applied the ruleset's way.
- "Maximum damage", "extra die" and "double" results mark the attacker; its next damage roll
  is changed and the mark is removed.
- What Fantasy Grounds cannot track (dropped weapons, maiming, instant death) is announced to
  the GM in the same chat line.
- Player and GM rolls both work (the host applies the results).

## Options (Options > Kraken Krits & Fumbles)

| Option | Values |
| --- | --- |
| Roll on the critical table | Off / Every time / 1 in 2 / 1 in 3 |
| Roll on the fumble table | Off / Every time / 1 in 2 / 1 in 3 |
| Apply results | Automatically / Chat only |
| Tables for | PCs and NPCs / PCs only |
| Results seen by | Everyone / GM only |

`/krakenkrits crit [weapon]` and `/krakenkrits fumble [weapon]` roll a test result for the first two tracker
entries; `/krakenkrits tables` lists the tables.

Results print `[KRAKEN CRITICAL]` / `[KRAKEN FUMBLE]`, which the Kraken Syrinscape extensions play a sound for.

## Install

Copy `Kraken's Krits & Fumbles 2E Automation.ext` into the Fantasy Grounds `extensions` folder and tick it for a AD&D 2E campaign.
