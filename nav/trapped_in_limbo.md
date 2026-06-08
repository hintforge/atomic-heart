# Trapped in Limbo -- DLC Zone Gate List (DLC #2)

**status:** research-integrated
**last_reconciled:** 2026-06-05
**zone-id:** limbo_hub, limbo_avenue_of_speed, limbo_plateau_of_responsibility, limbo_tower_of_memory, limbo_cliff_of_perseverance, limbo_goose_finale
**parent chapter:** Trapped in Limbo DLC -- full DLC scope
**zone type:** hub / indoor-linear / indoor-branching

_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:trapped-in-limbo_

> **CRITICAL DISAMBIGUATION:** Ch.3 of the base game contains "Limbo dream sequences" (hallucinatory cutscene content). These are BASE GAME content, NOT this DLC. Zone IDs, gameplay, and story content are entirely distinct. The date "2023" on the Fandom wiki for TiL is a typo -- correct release date is **February 6, 2024**.

---

## Zone List

| zone-id | English in-game name | Russian in-game name | Aliases | Zone type |
|---|---|---|---|---|
| `limbo_hub` | Level Select / Limbo Hub | локация выбора уровней | "level hub", Auntie Motya's shop | hub |
| `limbo_avenue_of_speed` | Avenue of Speed | Аллея скорости | "Surfing", "slide level", "Subway Surfers section" | indoor-linear |
| `limbo_plateau_of_responsibility` | Plateau of Responsibility | Плато Ответственности | "slide level 2" | indoor-linear |
| `limbo_tower_of_memory` | Tower of Memory | Башня памяти (Восхождение) | "climbing level", "Go Up" | indoor-branching |
| `limbo_cliff_of_perseverance` | Cliff of Perseverance | Утёс Настойчивости | "climbing level 2" | indoor-branching |
| `limbo_goose_finale` | Goose Run (finale) | Уровень за Гуся | "Temple Run", "Subway Surfers with Goose" | indoor-linear / cutscene |

All four P1-identified zone IDs confirmed verbatim by in-game achievement text.
[Confirmed: multiple sources, 2 languages]

---

## Entry point

Main Menu → New Game → "Trapped in Limbo: Play" → difficulty. No base-game save needed; fully isolated save slot. Story prerequisite is narrative-only (follows base game's "longer" ending where P-3 shoots Sechenov and is betrayed by CHAR-les) -- no save import required. The DLC does **not** modify the base-game zone graph; inventory cannot be transferred in either direction (except 7 weapon skins -- see Carry-over below).

_[Narrative prerequisite carries spoiler: dlc:trapped-in-limbo -- deliver structural "main menu entry" info freely; gate narrative context]_
[Confirmed: multiple sources, 2 languages]

## Zone graph edges

| ID | From | To | Type | Direction | Condition | PoNR | Notes |
|---|---|---|---|---|---|---|---|
| TiL-E0 | Main Menu | `limbo_hub` | **DLC ENTRY POINT** | one-way | Own DLC / Atomic Pass | No | Flagged: DLC entry edge |
| TiL-E1 | `limbo_hub` | `limbo_avenue_of_speed` | level start | bidirectional (replayable) | None | No | Replayable for coins / apples |
| TiL-E2 | `limbo_avenue_of_speed` | `limbo_plateau_of_responsibility` | progression | one-way (first clear) | Complete Avenue of Speed | No | Replayable after first clear |
| TiL-E3 | `limbo_plateau_of_responsibility` | `limbo_tower_of_memory` | progression | one-way | Complete prior | No | |
| TiL-E4 | `limbo_tower_of_memory` | `limbo_cliff_of_perseverance` | progression | one-way | Complete prior | No | |
| TiL-E5 | `limbo_cliff_of_perseverance` | `limbo_goose_finale` | progression | one-way | Complete one Avenue level + one climbing level (per RU sources) | **Yes** | Goose finale = no return; ending follows |

[Confirmed: multiple sources, 2 languages; E5 condition translated from: Russian]

## NORA stations

**No NORA stations.** Auntie Motya (Тётя Мотя) replaces NORA as the weapon/skin shopkeeper. Isolated from the base-game NORA network; DLC is self-contained.

| zone-id | Location | Function |
|---|---|---|
| `limbo_hub` | Level-select hub / vending machine | Buy weapon skins (gold coins), unlock skills/weapons (apples) |

[Confirmed: Fandom wiki + RU guides]

## DLC loadout constraints

P-3 appears in his white furry "Pushistov"/"Newton" form. [spoiler: dlc:trapped-in-limbo]

The polymer glove is NOT used as in the base game -- P-3 starts without abilities and unlocks limited skills via apples at Auntie Motya. **Unlimited ammo** on all purchased weapons (only reloading matters) -- major departure from base game. Skills available:

- Health-boost perks: "Кабан" / "Амбал" / Силач (= +health tiers)
- Second dash: "Второе дыхание" / "Быстрый как молния"
- Faster reload: "Ловкость рук"
- Polymer Shield: "Полимерный щит"

[translated from: Russian; Confirmed: multiple RU guides]

## Traversal

Two core mechanics, ~90% of gameplay:

1. **Sliding/surfing on rails** (Avenue of Speed, Plateau of Responsibility) -- momentum-based obstacle courses; community compares to CS:GO surf maps and Subway Surfers
2. **Vertical parkour / wall-climbing** (Tower of Memory, Cliff of Perseverance)

Combat arenas are interspersed but represent ~10% of gameplay. Falling/dying in a level resets to that level's start. Levels are fully replayable from the hub.
[Confirmed: multiple sources, 2 languages; % estimates translated from: Russian (Igromania, iXBT)]

## Optional content registry

| Content name | Type | Parent zone | Unlock condition | Access window | Recommended point | Failure mode |
|---|---|---|---|---|---|---|
| Gold coins (76 + bonus 77th) | Collectible currency | All levels | Found on routes / casino / boss arenas | Replayable any time | Collect across multiple passes | Missable in single pass but levels replayable |
| Apples (3,826 total) | Upgrade resource | All levels | Collected on routes; farmable in Avenue of Speed DASH | Replayable | Farm at first slide level | Not permanently missable |
| Chirpers (Щебетари) | Collectible audio | Levels | Exploration | Replayable | As encountered | Not permanently missable |
| Pears (Груши) | Collectible | Levels / arenas | Boss arenas | Replayable | -- | -- |
| 7 weapon skins | Cosmetic reward | Auntie Motya shop | Buy with gold coins | Any time | After coin collection | **Usable in base campaign** |
| Slot machine items | Reward | Hub / casino | Spend coins | Any time | -- | Achievement "The Casino Isn't Always in the Black" |

[Confirmed: multiple sources]

## Locks-and-keys

No traditional lock-and-key system. Progression is gated by completing platforming levels, not physical keys. Weapons/skills are gated behind apple/coin thresholds at Auntie Motya.
[Confirmed: multiple sources]

## Carry-over

The 7 weapon skins purchased with gold coins are **usable in the main base-game campaign**. The DLC is otherwise a self-contained save; no other carry-over documented.
[Confirmed: multiple sources]

## Missables

No permanently missable content -- all levels are replayable from the hub. Coins and apples missed in a single pass are recoverable on replays.

For achievement missables (e.g. "Conservationist" -- get a gold coin without shooting the Pchela), see `../achievements.md`.

## Story connection

[spoiler: dlc:trapped-in-limbo]

Follows the base game's "longer" canon ending: P-3 defeats the Twins, shoots Sechenov, learns CHAR-les (Chariton Zakharov / HRAZ) was the true mastermind, and is betrayed -- CHAR-les stuns him, exits the glove, merges with the Jelly-Man, and traps P-3 in Limbo as "Pushistov." Ekaterina/Katya (Blesna) appears as a Polymer Teardrop to guide him; she reveals Sechenov also survived in Limbo. P-3 recovers memories and escapes, vowing vengeance on Chariton.

Community claim "destroys the alt universe where Charles wins" is NOT directly supported by sources -- sources describe escape and memory recovery only. [Hypothesis -- unverified]
[Confirmed for core narrative: multiple sources, 2 languages]

## The Talking Goose

[spoiler: dlc:trapped-in-limbo]

The Goose from DLC #1 returns as both a playable character and the antagonist of the finale. The final level is an endless-runner where the player controls the Goose chasing P-3. After the run, control returns to P-3, who must kill 25 geese and enter a columned building to trigger the ending. Community refers to the "Eskimo bros" dynamic (recurring companion/foil across DLCs).
[Confirmed: multiple sources, 2 languages]

## Common confusions

- Base-game Ch.3 "Limbo sequences" are NOT this DLC. Never conflate.
- Fandom wiki date "2023" is a typo; correct release is **February 6, 2024**.
- Community claim "destroys alt universe where Charles wins" is unverified -- describe as escape/memory recovery only.

## Length

~3-4 hours (Russian reviews: Igromania, iXBT). Shorter and more compact than DLC #1. Achievement-completion estimate: 2-3 hours with a guide.
[Confirmed: 2 languages]

---

## Reddit sweep additions (2026-05-28)

**Gameplay breakdown (F17):** Community consistently describes TiL as ~90% surfing/platforming, near-zero combat. The "surfing" sections are the dominant mechanic -- momentum-based movement on long obstacle-course runs. Community is split: some find it a fun change of pace, others find it frustrating relative to base-game FPS.

**Skippability (RQ3):** Technically yes -- each DLC uses an isolated save. However, DLC 3 (Enchantment Under the Sea) continues TiL's narrative directly. Community-cited middle ground: watch TiL on YouTube for narrative continuity, skip the gameplay.

_source: r/atomicheart/comments/1tkw1i0 + community threads · capture: manual_paste · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:trapped-in-limbo_

## Sources

Primary: Focus Entertainment press release (Feb 6, 2024); TrueAchievements; GameFAQs; VGTimes.ru; StopGame.ru; Igromania; iXBT; Fandom wiki (use only for structural facts, not dates -- date typo confirmed)
_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:trapped-in-limbo_
