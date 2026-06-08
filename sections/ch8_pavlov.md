# Ch.8 — Pavlov Complex

**status:** research-integrated
**zones:** `pavlov_infirmary`, `pavlov_hospital`, `pavlov_morgue`, `pavlov_distribution`
**chapter:** 8 — Pavlov Complex
**research_run:** P1 deep research 2026-05-08

## Main path summary

Four-zone indoor dungeon (Infirmary → Hospital → Morgue → Distribution Center). Heavy on organic encounter mechanics. The cookie-key mechanic introduces a new loot interaction. One-and-done exit: **Pavlov never re-opens**.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: progression_
[Confirmed: walkthroughs.games, StopGame, Fandom, Gameranx]

## ⚠️ Missables — ALL MISSABLE on exit (latest safe: Ch.8)

| Item / event | Location | Notes |
|---|---|---|
| **Chirpers #54–63** ("Burning Ears") | Throughout all Pavlov zones | Scan every room |
| **Talking Corpses #38–43** ("The Necromancer") | Throughout all Pavlov zones | Interact with green-tagged corpses |
| **Pavlov optional code-locked door** | `pavlov_hospital` | Community-found alignment optical illusion puzzle; not a story code; see `puzzles/pavlov_code.md`. **Missable** if you leave Pavlov without solving it. |
| **Hospital ward 5-chest secret room** | `pavlov_hospital` — behind Blood Courier door | Opened by solving the Blood Courier door puzzle. **Permanently locked** once you descend the Morgue elevator (edge E45). Clear this room before going down. See DEP-011. |
| **Polymer Jelly and Biomaterials** | Chests and cabinets throughout | Pavlov is organic-enemy-rich — more Polymer Jelly here than open world. Sweep everything before the exit elevator. |

Point of no return edge: `pavlov_distribution` → `open_world_main` (permanent) — see `nav/architecture.md`.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: progression_
[Confirmed: walkthroughs.games, TrueAchievements, 100pguides, Steam guide]

## Puzzles

- **Blood Courier door code** (`pavlov_infirmary`) — positional code based on colored hospital curtains and a hole-in-wall sight line. Puzzle tier 1: this is an orientation/position puzzle. See `puzzles/blood_courier_door.md`.
- **Section-7 light puzzle, color-dot puzzle, snap-timing door, keycard door** — four distinct lock styles in `pavlov_hospital`. All solvable via in-zone observation; puzzles/files to be created live-observed.
- **Pavlov optional code door** — community-found alignment optical illusion; not solvable from in-game info alone. See `puzzles/pavlov_code.md`.

## Cookie-key mechanic

The "cookie-key" is literally a key baked inside a cookie. When you defeat the Ivy/Plyusch organic enemy holding a cookie-key, you **do not loot the corpse directly** — instead, loot the cabinet the Ivy emerged from. The key is inside the cookie in that cabinet.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 1 · category: mainline · spoiler: none_
[Confirmed: AltChar, walkthroughs.games, Fandom]

## Tube caution (Surgical Lab)

In the Surgical Lab: scythe-arm robots ("Mothers") respawn from disabled tubes if you **shoot the tubes**. Do not shoot inactive tubes — especially near organic enemies in dormant state, as shooting a nearby tube can wake them. [translated from: ru — playbestgames]

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

## Controls note — Auto-QTE

**Turn on Auto-QTE** (Settings > Accessibility, Patch 1.14.4.0) if not already done. Organic enemy grapples are 4-input QTEs — missing any input is an instant kill regardless of HP on any difficulty. Auto-QTE eliminates this entirely.

## Build note

**Polymer Shield (Sponge Effect)** — converts blocked Ivy whip damage to suit energy — is a documented Armageddon-survival strategy for Pavlov. Multiple community Armageddon clears require it here. If you're on Armageddon and struggling, see `items/builds.md` Build A / Polymer Shield tree in `items/abilities.md`.

## Before exiting (stock check)

Before pressing the Pavlov exit elevator:
1. All chirpers #54–63 collected
2. All Talking Corpses #38–43 interacted with
3. Pavlov optional code door solved (or accepted as missed)
4. Biomaterials swept from every chest and cabinet (Polymer Jelly / Neuropolymer is not scarce post-Pavlov; it drops from nearly all enemies throughout the game)

> **Cross-system dependency** — see `dependencies.md` DEP-001: Pavlov is one-and-done. The exit elevator permanently seals this zone — Biomaterials are scarcer in the open world. Sweep every cabinet and chest before pressing it. (Polymer Jelly / Neuropolymer drops from nearly all enemies throughout the game and is NOT scarcer post-Pavlov.)
