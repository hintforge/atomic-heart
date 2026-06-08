# Missables -- Full Guide

**status:** research-integrated
**last_reconciled:** 2026-06-05
**scope:** base game + all DLCs

_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

> **General rule:** Each DLC uses an **isolated save slot** with **no chapter select**. Missing a missable in a DLC requires a full replay of that DLC. Base-game missables follow the same rule: no chapter select exists post-1.0.

---

## Base Game Missables

| Item / Achievement | Zone | Window | Failure mode | Notes |
|---|---|---|---|---|
| Gold Polymer (base version) | Various | Before NG+ swap | Permanently missable if not collected before late game cutoff | See `items/crafting_materials.md` |
| Combination lock solutions | Any safe zone | Before exploring beyond | Locks cannot be revisited if zone exits are one-way | See `puzzles/combination_locks.md` |
| Polygon completion (optional) | Open world | Pre-endgame | Some polygons become inaccessible after certain story gates | See `optional_zones/polygons.md` |
| Chirpers (base game) | Various | During zone pass | Most are missable if zone is one-way | See per-chapter section files |

Base-game missables are mostly documented per-zone in `sections/ch*.md`. This file focuses on DLC missables.

---

## DLC #2 -- Trapped in Limbo Missables

**No permanently missable content.** All levels are replayable from the hub at any time. Coins and apples missed in a single pass are recoverable.

| Item | Type | Failure mode |
|---|---|---|
| Gold coins (76 + bonus 77th) | Currency | Missable per pass but levels replayable |
| Apples (3,826 total) | Upgrade resource | Farmable; not permanently missable |
| Chirpers | Collectible audio | Replayable; not permanently missable |
| "The Casino Isn't Always in the Black" achievement | Achievement | Spend coins at slot machine -- replayable |

For achievement-specific notes, see `../achievements.md` (TiL section).

[Confirmed: multiple sources 2 languages]

---

## DLC #3 -- Enchantment Under the Sea Missables

**No chapter select. Backtracking is limited once a zone transition is crossed.**

| Item | Type | Zone | Window | Notes |
|---|---|---|---|---|
| Chirpers (щебетари) | Collectible audio | Multiple zones | During zone pass | Missable -- backtracking limited after zone transitions |
| Hunter's stashes | Collectible | Multiple zones | During zone pass | Required for "Master of Survival" achievement; missable |
| Moby Dick window event | Achievement event | Specific window in Neptune | Specific moment -- listen to chirper at view | **Missable** -- one-time window; see `../achievements.md` |
| Dolphin Footballer toy | Collectible toy | Early Neptune | Once, early pass | Not achievement-tied; appears on safe-room TVs after pickup |
| Yellow chests (weapon upgrades) | Upgrade | All zones | During pass | Mostly recoverable if backtracking available |

For full achievement list see `../achievements.md` (EutS section).

[Confirmed: deep research 2026-05-27]

---

## DLC #4 -- Blood on Crystal Missables

**8 of 13 achievements are missable. No chapter select. Full replay required if any crystal figurine is missed.**

### Crystal Figurines (PRIMARY MISSABLE)

**11 total. One missed figurine = full replay required for "Crystal Platinum" achievement.**

> **Cross-system dependency** -- see `../dependencies.md` DEP-025: Crystal Figurines (11) + no chapter select is independently confirmed in `nav/blood_on_crystal.md`, `achievements.md`, and `nav/architecture.md`.

| Figurine # | Location zone | How to obtain | Notes |
|---|---|---|---|
| #1 | Crystal Complex (early) | Exploration | Community note: tracking bug -- sometimes does not count; reload prior save if it doesn't register |
| #2-#5 | Various Crystal zones | Exploration | -- |
| #6 | `boc_crystal_residential_1` → house #2 | Key from vacuum-cleaner quest ("Sudden Cleanup") | Key unlocks house #2 |
| #7-#11 | Various Crystal zones | Exploration | -- |

Crystal figurines provide permanent buffs. All 11 must be collected in one run for "Crystal Platinum."

[Confirmed: Steam guides, community reports]

### Other BoC Missables

| Item | Type | Zone | Window | Notes |
|---|---|---|---|---|
| Chirpers | Collectible audio | All zones | During pass | Missable |
| Klusha & Secator upgrade locations | Weapon upgrade | Multiple | During pass | Missable if zone one-way |
| Fluffy Easter Egg room | Secret room | `boc_crystal_residential_1` | After polymer key obtained | Code "X" on outhouse lock; wall to the left; see `../nav/blood_on_crystal.md` |
| Better Late Than Never | Secret room | Post-art-gallery arena | After fight | Pyramid/numeric code from wall mural + PEAR terminal emails; dolphin figurine inside |
| Secret Meeting room | Secret room | Burnt save room area | Mid-late Crystal | Answer PEAR terminal questions → get key |
| "Life After Life" | Achievement | `boc_crystal_residential_2` | Validol mission | Kill zero of the 3 crystal humans during the Validol quest; any kill voids it |

### BoC Missable Achievements Summary

See `../achievements.md` BoC section for full details. Key: 8/13 achievements missable; crystal figurines are the hardest to track.

[Confirmed: deep research 2026-05-27 · Steam guides · community reports]

---

## Sources

- Deep Research 2026-05-27 (DLC #2, #3, #4 scope)
- Steam community guides (BoC figurines, EutS chirpers)
- TrueAchievements (achievement missable flags)
- Per-zone nav files: `../nav/trapped_in_limbo.md`, `../nav/enchantment_under_sea.md`, `../nav/blood_on_crystal.md`
