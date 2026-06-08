# Ch.1 — Vavilov Complex

**status:** research-integrated
**zones:** `vavilov_entrance`, `vavilov_seed_archive`, `vavilov_maglev`, `vavilov_thermarium`, `vavilov_cold_lab`, `vavilov_pesticide`, `vavilov_algae`, `vavilov_birch_hub`
**chapter:** 1 — Vavilov Complex
**research_run:** P1 deep research 2026-05-08

## Main path summary

First indoor dungeon, ~3–4 hours. Tutorial for melee, scanning, polymer-swim, magnetic puzzles, NORA crafting, and the Polymer Glove (Shok). The objective is to collect 4 canisters from 4 workshop wings (any order) and insert them into the central Birch (PEC-4) chamber. Exit elevator at the Birch hub is the point of no return.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: progression_
[Confirmed: 5 sources — walkthroughs.games, StopGame, Fandom, Gameranx, gamesisart.ru]

## ⚠️ Missables — ALL MISSABLE on exit elevator (latest safe: Ch.1 throughout)

Exit the Birch hub elevator = **permanent** — Vavilov never re-opens.

| Item / event | Location | Notes |
|---|---|---|
| **All 23 Vavilov Chirpers** ("Burning Ears" — 72 total) | Scattered across all Vavilov wings | Scan to collect; use scanner in every room |
| **All Vavilov Talking Corpses** ("The Necromancer" — 53 total) | Scattered across all Vavilov wings | Scan/interact with green-tagged corpses |
| **Fox blueprint** | Vavilov Maglev / cable-car breakroom | Grab on the way through |
| **KS-23 shotgun** | Story-path corpse, early Vavilov | Can be looted naturally but don't miss it |
| **Pashtet blueprint** | Vavilov Algae Workshop hallway breakroom | |
| **Snowball blueprint** | Vavilov Cold Lab breakroom | |
| **Kalash blueprint** | Vavilov Cold Lab breakroom | |

Point of no return edge: `vavilov_birch_hub` → `forester_village` (permanent) — see `nav/architecture.md`.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 100pguides, Steam guide, GamingBolt + Gameranx blueprint guides; community Steam achievement guide]

## Vavilov navigation note (undercovered)

The **Algae Workshop** has a hidden auto-loader puzzle — riding the loader correctly drops you onto a zip-line that skips ~5 minutes of corridor. **If you want to collect all chirpers/corpses in this area, do not take the zip-line.** Take the long route.

> **Cross-system dependency** — see `dependencies.md` DEP-008: Algae zip-line skip permanently misses chirpers/corpses in this wing — confirmed against the sweep rule in `puzzles/combination_locks.md` Vavilov canister entry.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[translated from: ru — VGTimes, StopGame]

## Canister order

The 4 canister wings (Thermarium / Cold Lab / Pesticide / Algae) can be completed in any order. The central Birch hub (`vavilov_birch_hub`) is bidirectional until you press the exit elevator. Sweep each wing for chirpers and corpses before moving to the next.

## Controls note (apply now if not done in Ch.0)

On KB&M, the sprint-lock problem is immediately obvious in Vavilov's corridors. Install **r3visited controls mod (Nexus Mods #46)** — adds Shift-to-sprint and sets default movement to jog. Without it, the "Morning Exercise" character upgrade is wasted. See `controls.md`.

## Build note (early skill spend)

Coming out of Vavilov, recommended first skill spends (at first NORA station in `vavilov_seed_archive`):
1. **Wild Boar** — cheapest HP boost
2. **Second Wind** — ~8 Neuropolymer for an extra dodge; best value in the game

Save remaining Neuropolymer. Don't invest in Shok upgrades yet — Wild Boar + Second Wind outweigh them early. See `items/upgrades.md`.

## Polymer-swim caution

Polymer-swim in Vavilov's water sections is presented as harmless, but **on Armageddon difficulty it deals damage after ~30s of submersion**. [Single source — Steam Armageddon thread; verify]

## Enemy mechanic — Hawk relay system (no spoilers, pure mechanic)

The Pchela (red-eyed flying drone) **respawns destroyed robots** within ~30s if a Hawk relay is alive in the area. Shooting down the local Hawk relay disables all Pchela in that ecosystem. This mechanic applies throughout the entire game — learning it in Vavilov saves frustration everywhere.

> **Cross-system dependency** — see `dependencies.md` DEP-005: HAWK relay disable is the shared precondition for safe open-world farming and safe Polygon entry throughout the entire game.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: walkthroughs.games, Gameranx, GameRevolution]
