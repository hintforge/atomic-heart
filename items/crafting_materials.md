# Atomic Heart — Crafting Materials

**status:** research-integrated
**last_updated:** 2026-05-08
**research_run:** P1 deep research 2026-05-08

---

## Overview

8 crafting materials used for weapon upgrades at NORA stations. **Neuropolymer** is a separate currency (not used for weapon upgrades — it's for character and ability trees; see `upgrades.md` and `abilities.md`).

No materials have hard story-locked acquisition windows. However, some materials are **Pavlov-zone-rich** and become scarcer after leaving Pavlov (one-and-done dungeon). Stock up on Biomaterials before pressing the Pavlov exit elevator.

_source: GameRevolution drop-list page, TechRaptor Crafting Guide, RU Fandom item pages, allmmorpg.ru tips article · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 4+ sources, EN and RU agree — P4 research 2026-05-14. Replaces P1 material-name list which used non-canonical aliases ("Plastic," "Plasticine," "Polymer Jelly").]

---

## Materials list

> **Naming issue -- boss variants vs. standard variants:** Atomic Heart was developed in Russian and uses inconsistent internal names across RU/EN sources. Several enemy names (Hedgie, Belyash, Natasha, Dewdrop, Plyusch) refer to BOTH a unique scripted boss encounter AND a standard enemy variant that appears in the open world or later sections. Research sources often don't distinguish between the two. Tags used below:
> - `[std-variant: confirmed]` -- a regular farmable version of this enemy type is confirmed to exist alongside the boss encounter
> - `[std-variant: suspected]` -- likely exists based on player reports and naming patterns, not yet confirmed in corpus; verify in-game
> - `[std-variant: unknown]` -- corpus has no information on whether a farmable standard variant exists
> - Drop sources listing these names likely refer to the **standard variant**, not the boss encounter. Verify via NORA crafting interface (click a material to see drop sources).
> **Enemy tier 0:** Do NOT proactively name any enemy tagged std-variant or boss in player-facing responses. Say "tougher enemy types" or "mid-tier robots" as a category. Only name standard enemies (Vova, Rotorobot, Engineer, Vatrushka, Laborer, Drofa) freely.

> **Cross-system dependency** -- see `dependencies.md` DEP-023: The `[std-variant]` flags on drop sources below are governed by the taxonomy in `npcs/bosses.md`. Misreading a std-variant source as a boss encounter sends the player to a scripted fight for materials that come from the open-world farmable variant.

| Material | RU Name | Used for | Primary drop sources | Notes |
|---|---|---|---|---|
| **Metal Parts** | Металлические детали | Most weapon upgrades | Robots (Vova, Pchela, Laborer, Rotorobot/ARU-31/6) | Most abundant; farm from Vova clusters in open world |
| **Synthetic Material** | Синтетический материал | Weapon upgrades; ammo crafting | Robots (incl. Rotorobot/ARU-31/6) and chests | Second most abundant. **Not the same as Superconductor.** |
| **Biomaterials** | Биоматериалы | Consumable crafting; some organic-enemy mods | Organic mutants, Sprouts, Plyusch [std-variant: unknown] | Stock up in Pavlov (organic-heavy zone) before exit |
| **Superconductor** | Сверхпроводник | Mid-to-high tier weapon upgrades | Advanced Lab Tech, Engineer, Rotorobot, Shield Lab Tech; Belyash [std-variant: confirmed], Dewdrop [std-variant: unknown], Hedgie [std-variant: confirmed], Natasha [std-variant: suspected] | **Distinct from Synthetic Material.** P1 "Polymer Jelly" alias was likely a misidentification -- [verify in-game] |
| **Chemistry** | Химия | Ammo crafting (shells, rockets); consumables; some weapon mods | Organic mutants and mid-tier robots widely | Also called "Chemicals" in some web sources -- same item |
| **Microelectronics** | Микроэлектроника | Mid-to-high tier weapon upgrades | Advanced Lab Tech, Engineer, Rotorobot (rare); tougher enemy types incl. Belyash [std-variant: confirmed], Dewdrop [std-variant: unknown], Hedgie [std-variant: confirmed], Natasha [std-variant: suspected] (frequent -- likely std-variants, not boss encounters; verify in-game) | **P1 alias "Plastic" was incorrect.** Verify drop sources: open NORA → Weapons → any upgrade and read the requirement line |
| **Energy Module** | Энергомодуль | High-tier weapon upgrades | Tougher enemy types incl. Plyusch [std-variant: unknown], Belyash [std-variant: confirmed], Dewdrop [std-variant: unknown], Hedgie [std-variant: confirmed], Natasha [std-variant: suspected] (frequent -- likely std-variants; verify in-game) | Distinct resource; not listed in P1 -- gap filled by P4 research |
| **Neuromodule** | Нейромодуль | Highest-tier blueprints (e.g., Railgun craft cost: 1 Neuromodule) | Boss-tier enemies only | **Rarest crafting material.** P1 alias "Plasticine" was incorrect |

**Separate from the 8 crafting materials:**

| In-Game Name | RU | Use | Notes |
|---|---|---|---|
| **Neuropolymer / "Jelly"** | Нейрополимер / Желе | NORA character/glove ability upgrades ONLY — NOT for weapon upgrades | Drops 2–5 per kill from nearly all enemies; most abundant resource in the game. P1 listed this as a weapon material — that was a misidentification |

_source: GameRevolution drop-list, TechRaptor Crafting Guide, Twinfinite Crafting Guide, RU Fandom, allmmorpg.ru · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 4+ sources EN and RU; P4 research 2026-05-14]

**Sanity check (Railgun craft cost):** 261 Metal Parts, 28 Superconductors, 20 Microelectronics, 20 Energy Modules, 1 Neuromodule. [Source: GameRiv] This composition confirms the canonical 8-material set and shows no "Plastic" or "Plasticine" line.

---

## Farming tips

### Best early farm — Metal Parts + Synthetic

**Forester forest** (Ch.2 and open world): 5+ Vovas in a dense cluster near Granny Zina's area. Pchela drones respawn them continuously. Kill Vovas → loot → wait for Pchela respawn → repeat.

**More efficient variant:** Shoot down the local **Hawk relay** first (drone in the sky) — this disables all Pchela in that ecosystem for ~5 minutes, stopping respawns. Then kill the static Vovas at your leisure without pressure. Downside: no respawn farming until Hawk relay is restored.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: GamingBolt, GameRevolution, YouTube farming videos]

### Biomaterials — Pavlov window

Pavlov Complex (Ch.8) is organic-enemy-heavy. **Before pressing the Pavlov exit elevator (permanent — one-and-done), sweep every cabinet and chest.** You will not return. Neuromodule drops from boss-tier enemies; Pavlov bosses are the only boss concentration before late game.

> **Cross-system dependency** — see `dependencies.md` DEP-001: Pavlov exit (E48) is permanent. Biomaterials are scarcer for the rest of the game after this point; no return possible. (Polymer Jelly / Neuropolymer is NOT scarce post-Pavlov -- drops from nearly all enemies throughout the game; the P1 "Polymer Jelly is scarce post-Pavlov" claim was a misidentification.)

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: progression_

### Open-world robot farming — Hawk relay disable method

1. Identify the local **Hawk relay** drone (large hovering unit).
2. Shoot it down → all Pchela (repair/respawn drones) + Dandelion cameras in the ecosystem go offline for ~5 minutes.
3. Kill all robots without respawn pressure; loot freely.
4. Optional: if a robotic Mother (giant repair unit) spawns to fix the relay, killing it drops a guaranteed rare component. [Single source — VGTimes ru; verify]

**Warning:** Disabling the HAWK relay also locks ALL Polygon doors in the region until repair bots restore it. Do NOT disable the relay mid-Polygon-run.

> **Cross-system dependency** — see `dependencies.md` DEP-005: HAWK relay disable also applies before entering any Polygon dungeon. Same mechanic, same precondition across farming and Polygon entry contexts.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: Gameranx, GameRevolution; Mother-unit loot: Single source — verify]

### Camera-kill farming loop (infinite respawn method)

Use this when you want robots to keep coming without disabling the HAWK:

1. **Destroy** a Dandelion camera in the area.
2. **Wait** for a Pchela to fly in and repair it.
3. **Kill the Pchela** while standing in front of the now-restored camera -- the camera sees the kill, raises alarm, spawns a fresh batch of robots.
4. Kill the robots, loot, then repeat from step 1.

Key rules:
- **Do NOT use the Railgun.** Railgun kills permanently remove robots from the map -- Pchela cannot restore them. Use Kalash, Zvezdochka, or other weapons that leave a body.
- This loop works because the camera triggering alarm level 2 is what calls in reinforcements -- you're using the alarm system as a spawn mechanic.
- Alarm level 1: robots just chase you. Alarm level 2 (camera sees you killing): full reinforcement swarm. This loop deliberately targets level 2.

_source: r/atomicheart community thread (reddit.com/r/atomicheart/comments/141m67s) · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Single source -- verify loop behavior in-game; Railgun permanent-removal confirmed via DEP-017]

> **Cross-system dependency** -- see `dependencies.md` DEP-022: This loop chains alarm level 2 (`mechanics.md`) with Pchela-Dandelion repair behavior (`npcs/robots.md`). Both sub-systems must stay active for the loop to work.

---

## Sources

- [WhatIfGaming — Materials guide](https://whatifgaming.com/)
- [GameRevolution — Crafting and farming guide](https://www.gamerevolution.com/)
- GamingBolt; YouTube farming videos
