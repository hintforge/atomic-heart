# Optional Zones — Testing Grounds (Polygons 1–12)

**status:** research-integrated
**zone_ids:** `polygon_1` through `polygon_12`
**parent_zone:** `open_world_main`
**access_window:** Ch.3 (post-train crash) to before Ch.9 "Sky's the Limit" trigger
**failure_mode:** always-available within window; **permanently locked once Ch.9 "Sky's the Limit" triggers**
**research_run:** P1 deep research 2026-05-08

## Overview

> **Community note:** Testing Grounds are frequently skipped by players on first runs. Community strongly recommends completing them -- they are the primary source of weapon attachments (schematics) and are the fastest route to crafting resources. Skipping TGs is the most common cause of mid-game weapon-upgrade bottlenecks. At minimum: TG1 for attachments, TG8/TG12 before their missable windows close.
> _source: r/atomicheart/comments/11tazdc + community consensus · capture: manual_paste · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

12 optional Polygon dungeons (Testing Grounds 1–12) in the open world. All are accessed from `open_world_main`. Inside Polygons, robots **do not respawn** — they stay dead.

**Lootyagin chests:** 8 of the 12 Polygons contain full sets of 3 chest tiers (bronze / silver / gold), totaling 24 chests for the "More Than Profit" achievement. The other 4 Polygons are smaller without full chest sets.

**Note on Polygon count:** older Fandom + Steam guides cite 8 Polygons. The in-game map and 100% completion guides confirm **12 numbered Polygons**. Treat 12 as canonical.

Numbers 3, 4, 5, 7 exist but are open-access (no unlock required). Numbers 3, 4, 5, 7 are in the base game but were absent from older guides that only documented the 8 locked Polygons.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Contradicted — community count disagrees; canonical source: 100pguides, altchar walkthroughs]
[Confirmed: 5 sources, 2 langs — Fandom, walkthroughs.games, 100pguides, StopGame, gamesisart.ru]

## Polygon access conditions and recommended timing

| Polygon | Zone-id | Access condition | Window | Failure mode | Notes |
|---|---|---|---|---|---|
| **Polygon 1** | `testing_ground_1` | Volan camera hack (white spiral staircase tower → aim at blue-roof bunker hatch) | Ch.3+ | always-available | Do at VDNH outdoor (Ch.3) or early Ch.5. NW of arena. |
| **Polygon 2** | `testing_ground_2` | Volan camera hack (camera tower opens sewer pipe entrance near Boat Station) | Ch.3+ | always-available | Do in Ch.5 |
| **Polygon 3** | `testing_ground_3` | Open | Ch.3+ | always-available | Any time in Ch.5 |
| **Polygon 4** | `testing_ground_4` | Open | Ch.3+ | always-available | Any time in Ch.5 |
| **Polygon 5** | `testing_ground_5` | Open | Ch.3+ | always-available | Any time in Ch.5 |
| **Polygon 6** | `testing_ground_6` | Volan camera hack (camera tower across the lake) | Ch.3+ | always-available | One of the easier TGs. Do in Ch.5. |
| **Polygon 7** | `testing_ground_7` | Open | Ch.3+ | always-available | Any time in Ch.5 |
| **Polygon 8** | `testing_ground_8` | "Bug in the System" started (CONFIRMED — 3 Volan/camera unlocks only become interactable once mission is active; NOT freely accessible) | Ch.5–8 | **⚠️ MISSABLE** — must complete before E36 (Theater interior entry). "Petrov flees" cutscene (E35) does NOT close TG8 — confirmed live 2026-05-12. | Do while "Bug in the System" is active, before entering the Theater interior. See `puzzles/combination_locks.md` for three-Volan method. |
| **Polygon 9** | `testing_ground_9` | HAWK reactivation (clear sprout infestation via 4 sewer boilers via manhole) + camera hijack reveals shack near Lenin statue | Ch.3+ | always-available | Candle-throwing platform puzzle inside. NORA booth present. Kollektiv village area. |
| **Polygon 10** | `testing_ground_10` | Volan camera tower hack | Ch.5 | always-available | One of the easier TGs. |
| **Polygon 11** | `testing_ground_11` | Key Disk from walled compound NW of TG11 (HAWK maintenance → zipline in) + combination lock | Ch.4+ (post-Theater stage, before bridge PoNR) | always-available | Reachable from Solnechnaya side; do before crossing bridge or in Open World 2. Across from Theater. |
| **Polygon 12** | `testing_ground_12` | "Petrov of Opera" quest complete | Ch.7+ (post-Theatre) | **⚠️ MISSABLE** — energy barrier drops during Hospital quest (Ch.5 only window for beach cave entrance) | NE side near Infirmary; Open World 2 only. Boss inside: Natasha-class [enemy-tier: 1]. See DEP-010. |

_source: P1 deep research 2026-05-08 (Polygon 8 condition updated P3 2026-05-09; TG access detail from P1+P2) · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 100pguides, Steam guide "Epic Polygons", walkthroughs.games; Polygon 8 condition confirmed: AltChar, GGRecon, Pro Game Guides, wotpack — 4 independent sources; TG access: gamerpillar, sportskeeda, gamerjournalist, atomic-heart.fandom.com/ru, vgtimes, cybersport.ru — 6 sources]

## Difficulty Notes

- **Easiest:** Polygon 6, Polygon 10
- **Moderate:** Polygon 1, Polygon 2, Polygon 9, Polygon 11
- **Hardest / most complex:** Polygon 2 (requires telekinesis + perk "Acceleration of unfree falling" for rotating cross-platform puzzle), Polygon 8

_source: goha.ru, mvideo.ru — 3 sources EN+RU · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: progression_

## Polygon nav notes

- Before entering any Polygon: **shoot the Hawk relay** in the vicinity to disable Pchela drones and Dandelion cameras. See `mechanics.md` — HAWK Relay System for the full procedure.
- Inside: robots stay dead; loot everything before leaving.
- Scan corpses inside — green-tagged corpses count toward "The Necromancer" and may contain blueprint hints.

> **Cross-system dependency** — see `dependencies.md` DEP-005: HAWK relay disable is the shared precondition for both Polygon entry and open-world farming. DEP-002: Polygon 8 chests contain 5 weapon mods — MISSABLE, Ch.4 only window. DEP-003: Polygon 12 gold chest contains 2 weapon mods — MISSABLE, Ch.5 Hospital quest only. DEP-004: Ch.9 "Sky's the Limit" permanently locks all remaining Polygons. DEP-006: TG gold chests contain weapon mod blueprints (and potentially Composite material) — missing them blocks upgrades.

## Polygon 6 and 8 — extended content

Community reports Polygons 6 and 8 are the only ones with a "5-chest" content extension beyond the standard bronze/silver/gold set. Confirm via 100pguides.

## Reward Tables

Bronze/silver/gold Lootyagin chest contents for confirmed Polygons. Unconfirmed TGs: fill from in-game observation or add post-play.

| Polygon | Bronze | Silver | Gold | Confidence | Notes |
|---|---|---|---|---|---|
| **Polygon 1** | Fox — Ergonomic Handle | PM — Expansive Converter _(Silver, P1 research; chest tier unconfirmed live)_ | KS-23 — Extended Magazine + Zvezdochka — Reverse Shot | **[C:3 -- P2 medium]** Pending live verification. | Merged from `nav/testing_ground_1.md` per zipper 2026-05-22. P1 blueprint table also lists Zvezdochka Reverse Shot + PM Expansive Converter for Polygon 1. |
| **Polygon 9** | RNG from pool | RNG from pool | RNG from pool | **[C:4]** [wotpack.ru 2026-05-16] | Rewards randomized — specific blueprint drawn depends on recipes already learned. Pool: Dominator, KS-23, Kalash, Snowball variants. P-3 drops: KS-23 Collimator / Dominator Impulse Divider / Kalash Electromagnetic Polarizer + Pashtet Ergonomic Handle. |
| **Polygon 2** | PM — Electromagnetic Polarizer | KS-23 — Expansive Converter | Kalash — Thermal Imager + Snowball — Polymeric Alloy Aerodynamic Attachment | **[C:2]** [live in-game hover 2026-05-18 + GamePretty/pilsmer P4] | Tier split confirmed live — prior source had all 4 items listed as gold (now corrected). Rewards may be RNG-pool like TG9 (player-observed hypothesis; source pending). |
| **Polygon 8** | Zvezdochka — Lower Blade With Reflex Booster (a.k.a. "Extra Saw") | Fox — Lightweight Titanium Blade + Dominator — Vortex Transducer | MP — Revolver-Type Bolt Frame + Swede — Polymeric Alloy Extension | **[C:6]** [Confirmed: Gameranx, GameRant, AltChar, Sirus Gaming, DualShockers, TechRaptor] | ⚠️ Previous [Contra:2] flag RESOLVED — "Kalash Expansive Converter" is TG11 bronze, not TG8. "MP Revolver Barrel" in prior flag refers to TG8 **gold**, correctly. |
| **Polygon 10** | Kalash — Extended Mag | PM — Collimator | Fat Boy — Trap Mine + Dominator — High-Intensity Modulators | **[C:6]** [Confirmed: live 2026-05-13 + Fandom, AltChar, TechRaptor, YouTube] | All three tiers confirmed. Dominator mod is "High-Intensity Modulators" — NOT "Receiver shotgun mode" as P1 research claimed. |
| **Polygon 11** | Kalash — Expansive Converter | PM — Thermal Imager | KS-23 — Damper-Polymeric Stock + Fat Boy — Homing Projectiles | **[C:4]** [live in-game hover 2026-05-18 + gamepretty.com, sirusgaming, YouTube TG11] | "MP" corrected to "PM" (same weapon — Makarov Pistol). "Damper-Polymer Stock" corrected to "Damper-Polymeric Stock" per live screenshot. Rewards may be RNG-pool like TG9 (player-observed hypothesis; source pending). |
| **Polygon 12** | KS-23 — Thermal Scope | Fat Boy — Revolver Loading Module + Kalash — Electrokinetic Stock | Electro — Energy Vampire Module + Pashtet — Reflex Blade | **[C:1 — live in-game map hover 2026-05-21]** All three tiers confirmed. Bronze was previously unverified; prior blueprint table had KS-23 Thermal Scope listed as Gold -- **corrected to Bronze**. | ⚠️ MISSABLE. |

_source: Compass/Deep Research 2026-05-09 (P3); Polygon 10 added 2026-05-13 (live + online verification) · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

Other Polygon rewards not yet confirmed from P3 — fill from in-game observation or add post-play.

## Weapon mod blueprints from Polygons

Several weapon upgrade mods are locked behind specific Polygon completions:

| Blueprint / mod | Source Polygon |
|---|---|
| Zvezdochka Reverse Shot | Polygon 1 | Gold chest (shared with KS-23 Extended Magazine) -- P2 medium [C:3, pending live] |
| Snowball Polymeric Cutting Edge | Polygon 2 |
| Snowball Superconducting Rotation Module | Polygon 6 |
| Swede Polymeric Alloy Extension | Polygon 8 |
| Fox Lightweight Titanium Blade | Polygon 8 |
| Zvezdochka Lower Blade with Reflex Booster | Polygon 8 |
| Dominator Vortex Transducer | Polygon 8 |
| Dominator Impulse Divider | Polygon 9 | Silver chest — confirmed live 2026-05-16 |
| Dominator High-Intensity Modulators | Polygon 10 | Gold chest — confirmed live 2026-05-13 |
| Fat Boy Trap Mine | Polygon 10 | Gold chest — confirmed live 2026-05-13 |
| Pashtet Ergonomic Handle | Polygon 9 | Gold chest — confirmed live 2026-05-16 |
| Kalash Electromagnetic Polarizer | Polygon 9 | Gold chest — confirmed live 2026-05-16 |
| KS-23 Collimator | Polygon 9 | Bronze chest — confirmed live 2026-05-16 |
| Pashtet Reflex Blade | Polygon 12 | Gold (shared with Electro Energy Vampire Module) — confirmed P4 |
| KS-23 Thermal Scope | Polygon 12 | **Bronze** chest — corrected from "Gold" (prior P4 error); confirmed live in-game map hover 2026-05-21 |
| Kalash Thermal Scope (Thermal Imager) | Polygon 2 | Gold chest — confirmed live in-game hover 2026-05-18 |
| Kalash Collimator Sight | Polygon 6 |
| Kalash Extended Mag | Polygon 10 | Bronze chest — confirmed live 2026-05-13 |
| Electro Energy Vampire Module | Polygon 12 | Gold (shared with Pashtet Reflex Blade) — confirmed P4 |
| Electro EMP Generator | NOT a Polygon mod | Vavilov Complex, Seed Bank saferoom (right side upon entry, large chest) — confirmed P4 [C:2: Gameranx, The Nerd Stash] |
| Electro Electromagnetic Emitter (chain-arc) | Polygon 6 | Chest tier unverified — confirmed P4 (medium confidence) |
| Fat Boy Revolver Loading Module (Revolver Barrel) | Polygon 12 | Silver (shared with Kalash Electrokinetic Stock) — confirmed P4 [C:3: TechRaptor, AltChar, Pro Game Guides] |
| Fat Boy Trap Mine | Polygon 10 | Gold chest — confirmed live 2026-05-13 |
| Fat Boy Homing Projectiles | Polygon 11 | Gold chest — confirmed P4 [C:3: GamePretty, Fandom EN, Pro Game Guides] |
| PM Collimator | Polygon 10 | Silver chest — confirmed live 2026-05-13 |
| PM Expansive Converter | Polygon 1 | Silver chest -- P1 research [C:3, pending live] |
| Fox — Ergonomic Handle | Polygon 1 | Bronze chest -- P2 medium [C:3, pending live] |
| KS-23 — Extended Magazine | Polygon 1 | Gold chest (shared with Zvezdochka Reverse Shot) -- P2 medium [C:3, pending live] |

_source: P1 deep research 2026-05-08 (Kalash/PM entries from GamingBolt + TechRaptor 2026-05-12) · capture: web_fetch · confidence: high (P1 entries); medium (Kalash/PM entries — dual source) · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[P1: TechRaptor full upgrade tables; Steam guide "Epic Polygons". Kalash/PM: GamingBolt Blueprint Locations, TechRaptor Recipe Locations, IGN Best Upgrades]

**Note:** Dominator Receiver / Torrent Modulation (rifle mode) is from Polygon 9. Polygon 10's Dominator mod is **High-Intensity Modulators** (NOT "Receiver shotgun mode" as P1 research incorrectly claimed — corrected 2026-05-13 via live + online verification).
**Note (P4 resolved):** Fat Boy **Revolver Loading Module (Revolver Barrel)** confirmed as Polygon 12 Silver (shared with Kalash Electrokinetic Stock) — 3 location-organized sources agree. Fat Boy **Trap Mine** confirmed Polygon 10 gold chest (2026-05-13 live). Fat Boy **Homing Projectiles** confirmed Polygon 11 Gold (3 sources). Also note: Pashtet **Blade Flight** and **Magnetic Field Generator** are story-zone mods (Vavilov Hot Workshop Breakroom and Algae Workshop saferoom respectively) — NOT Polygon rewards.

## Per-TG Nav Files

Detailed entry/exit, sequence, and loot for each Polygon:

| File | Polygon | Nav detail |
|---|---|---|
| `nav/testing_ground_1.md` | Polygon 1 | Entry, sequence (specific blueprints -- see Reward Tables above) |
| `nav/testing_ground_2.md` | Polygon 2 | Entry, sequence, bronze/silver/gold loot |
| `nav/testing_ground_6.md` | Polygon 6 | Entry, sequence, common confusions |
| `nav/testing_ground_8.md` | Polygon 8 | Entry, sequence, MISSABLE callout |
| `nav/testing_ground_9.md` | Polygon 9 | Entry, sequence, NORA booth location |
| `nav/testing_ground_10.md` | Polygon 10 | Entry, sequence |
| `nav/testing_ground_11.md` | Polygon 11 | Entry, sequence |
| `nav/testing_ground_12.md` | Polygon 12 | Entry, sequence, MISSABLE callout |

If a Polygon has no dedicated nav file yet, web-search before asking P-3 to describe it. Flag the gap and add the claim after.

> **Cross-system dependency** -- see `dependencies.md` DEP-010: Natasha-class boss weakness (jet ports + explosives + Shok stall) documented in `npcs/bosses.md` for the Theater stage encounter applies equally to TG12's Natasha variant.
