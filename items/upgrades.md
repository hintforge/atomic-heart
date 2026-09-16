# Atomic Heart — Character Upgrades

**status:** research-integrated; full 19-node tree with costs and prerequisites (2026-09-16)
**last_updated:** 2026-09-16
**research_run:** P1 deep research 2026-05-08 + node-cost completion pass 2026-09-16

_source: Atomic Heart Fandom wiki, Skills page · capture: web_clip 2026-09-16 · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: all 13 pre-existing costs matched exactly; those were already Twinfinite + GameRant confirmed in P3]

---

## Overview

Character upgrades are separate from Polymer Glove abilities and weapon upgrades. All purchased at NORA stations with **Neuropolymer**. The Character tree covers HP, dodge, inventory, and passive survivability.

Glove ability trees (Shok, Frostbite, Mass TK, Polymeric Jet, Polymeric Shield, Energy Management) are in `abilities.md`.
Weapon upgrade paths are in `weapons.md`.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 6 sources — DenOfGeek, SegmentNext, GameRant, GBTimes, dotesports, TheGamer]

**Note on costs:** Exact Neuropolymer costs below are now confirmed across two independent sources (Twinfinite + GameRant). P1's ±10% variance was likely auto-translation noise from RU mirrors. Use these values as canonical.

_source: Compass P3 deep research 2026-05-09 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: Twinfinite (https://twinfinite.net/guides/all-skills-available-in-atomic-heart/) + GameRant (https://gamerant.com/atomic-heart-best-character-abilities-upgrades/) — identical numbers]

---

## Full Character Upgrade List

**Full tree: 1,434 Neuropolymer, 19 nodes.** Everything hangs off Nora's Kiss, which is free. Costs and prerequisites completed 2026-09-16 against the Fandom *Skills* page; the thirteen costs that were already here all matched, so the pre-existing figures are confirmed rather than replaced.

| Upgrade | Cost | Unlocked by | Effect | Priority notes |
|---|---|---|---|---|
| **Nora's Kiss** | **0** | story | Survive lethal damage at 1 HP for a limited time; has a cooldown | Free, and the root of the entire tree |
| **Wild Boar** | **37** | Nora's Kiss | +HP (tier 1) | **Buy first** — cheapest survivability |
| **Second Wind** | **38** | Wild Boar | Extra dodge charge | **Buy second** — extraordinary value at this cost |
| **Sleazeball** | **62** | Second Wind | Shields you from all damage while dodging | Transforms Armageddon survivability |
| **Cell Division** | **242** | Sleazeball | Medical supplies fully regenerate HP in seconds | Most expensive in the tree; late-game luxury |
| **Parkour** | **43** | Second Wind | Tuck and roll to avoid fall damage — jump just before landing | Cheap; no downside |
| **Full House** | **67** | Parkour | Swap weapons 100% faster | Situational |
| **Born Marksman** | **119** | Full House | Better unaimed accuracy | Gun builds only |
| **Photon Silk** | **27** | Wild Boar | Laser resistance | Gateway to the Med Unit line |
| **Avatar** | **45** | Photon Silk | Elemental damage resistance | Situational |
| **Bulwark** | **78** | Avatar | Physical damage reduction | Gun-build survivability; skip for melee |
| **Med Unit Upgrade** | **57** | Photon Silk | Med Unit restores more HP | Strong; buy after Sleazeball |
| **Musclehead** | **110** | Med Unit Upgrade | +HP (tier 2) | Mid-game |
| **Juggler** | **87** | Musclehead | Use a Neuromed capsule one-handed | Sustained combat efficiency — but 318 to reach |
| **Athlete** | **165** | Juggler | +HP (tier 3) | Late-game |
| **Morning Exercise** | **80** | Wild Boar | Movement speed bonus | **Skip if using the r3visited mod** — sprint-lock makes this wasted on vanilla KB&M |
| **Extra Capacity Cluster Munitions** | **27** | Nora's Kiss | Cluster munitions hold more | Cheap |
| **Neuro-Compression Backpack I** | **75** | Extra Capacity Cluster Munitions | Inventory capacity | Useful on long exploration runs |
| **Neuro-Compression Backpack II** | **75** | Backpack I ⚠ | Inventory capacity | ⚠ The source gives both backpacks the same parent; tier II is chained off tier I here |

> **Corrections, 2026-09-16.** **Nora's Kiss is the root of the whole tree**, not "a prerequisite for Med Unit Upgrade" — and it is free, so the old advice to "buy only to unlock Med Unit" cost nothing to ignore but framed the tree wrongly. **Photon Silk is laser resistance, not HP regeneration.** "Tuck-and-Roll" is the node **Parkour**. Six nodes were missing entirely: Nora's Kiss, Parkour, Full House, Born Marksman, and both backpack tiers as separate skills. IGN spells Photon Silk as "Photon Sink"; the Fandom spelling is used here because it matches what was already in this file.

---

## Recommended priority order

Community consensus across 6 English sources + Russian community (StopGame, VGTimes) [translated from: ru]:

1. **Nora's Kiss** — free, and nothing else in the tree opens without it
2. **Wild Boar** (37) — cheapest HP; gets you through Vavilov
3. **Second Wind** (38, 75 to reach) — an extra dodge charge, the best value in the tree
4. **Sleazeball** (62, 137 to reach) — i-frames on dodge; expensive but mandatory on Armageddon
5. **Energy Density I** (ability tree — see `abilities.md`) — free Power Cell bump
6. **Photon Silk → Med Unit Upgrade** (84 together) — the passive-regen line
7. **Juggler** (87, but **318 to reach**) — use heals without lowering your weapon; a mid-game purchase, not an early one
8. → Then pivot to ability trees (Shok: Power Amplifier at 72 to reach; TK: Forced Fall Acceleration at 136; Frostbite: Absolute Zero at 333)

> **Corrected 2026-09-16.** Second Wind was listed at "~8 Neuropolymer" — it costs **38**, as the table in this same file already said. Juggler was listed third; it sits behind Med Unit Upgrade and Musclehead, so it cannot be bought third without 318 Neuropolymer in hand. Both fixed above, with reach costs (node price plus every prerequisite) shown wherever the two differ enough to change the order.

**For gun-focused builds:** add Bulwark (78, and 150 to reach via Photon Silk → Avatar) plus the backpack line before Sleazeball; gun builds lean on dodge less.

**Morning Exercise caveat:** Movement speed bonus is **wasted on vanilla KB&M** (sprint-lock means you're already at max speed). Install r3visited mod or skip this upgrade unless using a controller.

---

## Weapon upgrade mechanics reference

Weapon upgrades are distinct from character upgrades — they're done at the same NORA terminal but draw from **crafting materials** (Metal Parts, Synthetic, Polymer Jelly, etc.), not Neuropolymer. See `weapons.md` for full weapon upgrade tables and `crafting_materials.md` for component farming.

---

## Sources

- DenOfGeek, SegmentNext, GameRant, GBTimes, dotesports, TheGamer — priority consensus
- StopGame, VGTimes — Russian community priority (translated from: ru)
