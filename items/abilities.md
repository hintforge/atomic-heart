# Atomic Heart — Polymer Glove Abilities (CHAR-1)

**status:** research-integrated (converged main + sandbox 2026-05-09)
**last_updated:** 2026-05-09
**research_run:** P1 deep research 2026-05-08 (sandbox base) + P3 deep research 2026-05-09 (DLC + main-side flags)

---

## Overview

**8 skill trees total** (correction from pre-research signal of 3): six Polymer Glove ability lines + Energy Management + Character tree. The Character tree is in `upgrades.md`.

**Slot system:** Two abilities can be slotted at any time (swap with D-Pad ↑ / F key). **Shok is permanently equipped as a free third ability** — it does not occupy a slot and is always active. Respecs cost nothing at NORA stations.

All upgrades purchased at NORA stations with **Neuropolymer** (a separate currency that drops from any kill).

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 6 sources — DenOfGeek, SegmentNext, GameRant, GBTimes, dotesports, TheGamer; ru: StopGame, VGTimes]

**Note on Polymer cost precision:** Exact Neuropolymer costs cited below are ±10%. Russian community sources (StopGame, VGTimes) tend to be more precise than English guides. Treat all costs as approximate until verified in-game. (See also `upgrades.md` for canonical P3-confirmed values.)

---

## Quick-reference tier list

Cross-language consensus (English + Russian community; 5+ sources, 2 languages). Use this for at-a-glance loadout decisions; per-tree skill detail is below.

| Tier | Ability | Key upgrades | Notes |
|---|---|---|---|
| S | **Mass Telekinesis** | Forced Fall Acceleration, Increased Power (lift heavyweights), Energy Vampire | Best single-target/AoE crowd-control; dominant counter to lab-tech swarms. **Energy Vampire is near-required for Armageddon difficulty** (final boss). RU community agrees with EN consensus. |
| S | **Frostbite** | Absolute Zero (DoT on frozen targets), Drastic Measures (HP-for-ammo) | Must-have for mid-game survival; vgtimes.ru calls it the top upgrade after early HP nodes. |
| A (always-on) | **Shok** | Chain Lightning, Extended Topology, Full Contact | Passive / always-equipped — does not use an ability slot. Max early; free third ability. |
| A (boss/situational) | **Polymeric Shield** | Sponge Effect (energy-on-hit), Kinetic Reflector (reflect ranged), Med Unit Feedback (HP-on-hit) | Slot in only for boss fights (Hedgehog, Belyash, Natasha). Swap back out post-boss. |
| B (synergy) | **Polymeric Jet** | — | Inefficient unless paired with electric or fire cartridges. RU forum users (playground.ru) rate it lower than EN guides. |
| A (build-enabling) | **Energy Management tree** | Energy Density nodes (×3) | Top priority for Dominator/Electro/Railgun builds — doubles energy reserve. |

**Recommended opening order (RU community consensus):** Character tree (HP/dodge/inventory) → Shok → Mass Telekinesis **or** Frostbite depending on play style (ranged kiting = Telekinesis; melee survival = Frostbite).

---

## Tree 1 — Shok (permanently equipped, no slot cost)

| Skill | Effect | Community priority |
|---|---|---|
| **Power Amplifier** | Shok pushes enemies back + damage bonus | 1st |
| **Electrization** | Shok applies electrification DoT + stun | 2nd |
| **Chain Lightning** | Arc jumps to 3 targets | 3rd |
| **Extended Topology** | Larger arc radius | 4th |
| **Full Contact** | Secondary arc jumps deal full damage (not reduced) | 5th |
| **Neuro-polymer Acceleration** (shared) | Reduces Shok cooldown | last |

**Community priority:** Power Amplifier → Electrization → Chain Lightning → Full Contact. Fill Extended Topology + Neuro-polymer Acceleration last — Shok is effective at base levels, and the other trees give more value per Neuropolymer early. [Confirmed: PrimaGames, GamesRadar, PCGamesN]

**Best vs.:** robots (Vovas, Pchelas). Weaker vs. organic mutants (mutants are Shok-resistant) — switch to Fire cartridge or Fat Boy for organic enemies.

> **Cross-system dependency** — see `dependencies.md` DEP-020: Fire Mutant (Pesticide Workshop) reverses the Fire-vs-mutant rule — switch to Ice cartridge for Fire Mutant specifically.

---

## Tree 2 — Frostbite (slot ability)

| Skill | Effect |
|---|---|
| **Absolute Zero** | Heavy damage-over-time vs. frozen targets; also enables melee shatter kills |
| **Careful Disassembly** | Frozen enemies drop bonus loot/materials when killed |
| **Increased Polymer Generation** (shared) | More suit energy generated passively |
| **Frost Density** | Larger Frostbite AoE |
| **Drastic Measures** | HP-for-ammo conversion |

**Synergies:** Frost → freeze → Pashtet melee → shatter kill. This is the core of Build A (Melee/Cryo), the consensus best build for Armageddon.

> **Cross-system dependency** — see `dependencies.md` DEP-015: Frostbite freeze state also enables Zvezdochka Reverse Shot (Saw Dance) blade effectiveness — blades hit frozen targets repeatedly but miss moving grounded targets.

**Community priority:** Absolute Zero first (unlocks freeze-shatter; defines the build), then Careful Disassembly (material economy), then Frost Density. [Confirmed: PlayerMe, GBTimes]

---

## Tree 3 — Mass Telekinesis (slot ability)

| Skill | Effect |
|---|---|
| **Forced Fall Acceleration** | Lifted enemies take heavy impact damage when slammed to the ground |
| **Increased Power** | Lifts heavy and boss-class enemies (otherwise only lighter enemies) |
| **Extended Range** | Wider grab radius |
| **Energy Vampire** | Drains energy from lifted target — **near-required for Armageddon** (final boss) |
| **Linked Souls** (community-translated name) | Links two enemies — damage dealt to one is shared to the other |

**Community priority:** Forced Fall Acceleration → Increased Power (enables boss lifting) → Energy Vampire if going Armageddon. [Confirmed: GameRant, TheGamer]

**Endgame combo:** Increased Power + Railgun — lift heavy enemy with TK, Railgun finisher while airborne.

> **Cross-system dependency** — see `dependencies.md` DEP-015: Mass TK Increased Power (lift state) also enables Zvezdochka Reverse Shot (Saw Dance) blade effectiveness — blades hit lifted targets repeatedly but miss moving grounded targets.

---

## Tree 4 — Polymeric Jet (slot ability)

| Skill | Effect |
|---|---|
| **High Viscosity** | Slows enemies caught in the jet stream |
| **Mixture Efficacy** | Damage bonus to enemies in the jet |
| **Increased Chemical Reactive Distance** | Wider jet AoE |

**Synergies:** Polymeric Jet + Fire cartridge = fire-ignite on enemies slowed in polymer. Pairs well with KS-23 or Kalash + fire cartridge socket.

---

## Tree 5 — Polymeric Shield (slot ability)

| Skill | Effect |
|---|---|
| **Med Unit Feedback** | Blocked damage converts to HP regeneration |
| **Sponge Effect** | Blocked damage converts to suit Energy instead of HP |
| **Kinetic Reflector** | Reflects incoming projectiles back at enemies |

**Note on Kinetic Reflector:** reliably reflects bullets; behavior vs. laser sweeps (e.g., Dewdrop spider boss) is inconsistent — reports of partial/no reflection. [Confirmed but contested: multiple Reddit reports] [Contradicted — treat as: bullets yes, beams unreliably]

**Crucial on Armageddon difficulty.** Sponge Effect + shield-up-vs-Ivy whip damage is a documented Armageddon-survival technique for Pavlov (Ch.8).

---

## Tree 6 — Energy Management (passive tree)

| Skill | Effect | Ranks |
|---|---|---|
| **Energy Density** | Increases suit Power Cell capacity | ×3 (buy all three) |
| **Greedy Guts** | Melee hits restore suit energy | 1 |
| **Recycling** | Reduces ability activation cost | 1 |

**Priority:** Energy Density ×1 early, ×2–×3 as you build toward energy-weapon loadout. Greedy Guts pairs with Fox (energy-on-hit) for near-infinite energy sustain in melee.

---

## Community skill priority order (cross-tree, first 15 Neuropolymer spends)

From community consensus across 6 sources [Confirmed: DenOfGeek, SegmentNext, GameRant, GBTimes, dotesports, TheGamer; ru: StopGame]:

1. **Wild Boar** (Character — see `upgrades.md`) — cheapest HP boost; gets you through Vavilov
2. **Second Wind** (Character) — extra dodge for ~8 Neuropolymer; best value in tree
3. **Juggler** (Character) — use Neuromed without lowering weapon; sustained combat survivability
4. **Sleazeball** (Character) — i-frames during dodge; ~62 Neuropolymer but game-changing on Armageddon
5. **Energy Density ×1** — first Power Cell capacity bump
6. **Frostbite: Absolute Zero** — enables freeze-shatter combo; defines the build pivot
7. **Shok: Power Amplifier** — now that basics are covered
8. **Forced Fall Acceleration** (TK) — ground-slam damage
9. **Med Unit Upgrade** (Character) — passive HP regen
10. **Mass TK: Increased Power** — boss lifting

**Where guides disagree:** TheGamer (EN) pushes Shok upgrades first; StopGame + VGTimes (RU) push Frostbite + melee as the early-Armageddon answer. **Reconciliation:** Shok is best vs. mechanical robots (Vovas, Pchelas); Frost is best vs. all organic bosses except Hedgie.

---

## Synergy summary

| Ability pair | Synergy | Best build |
|---|---|---|
| Frostbite + Pashtet melee | Freeze → shatter kills + Careful Disassembly loot bonus | Build A (Melee/Cryo) |
| Shok + Mass TK | Shock-stun a group, TK-lift and slam the heavy one | Build B (Energy/Shock) |
| Polymeric Jet + Fire cartridge | Slow enemies in polymer, ignite with Fire KS-23 | Hybrid utility |
| Polymeric Shield (Sponge Effect) + high-damage area | Absorb damage into energy, spend on abilities | Armageddon survival |
| Mass TK Energy Vampire + Railgun | Lift, drain energy, Railgun finisher | Armageddon final-boss |

---

## Sources

- [DenOfGeek, SegmentNext, GameRant, GBTimes, dotesports, TheGamer — skill priority]
- [PrimaGames, GamesRadar, PCGamesN — Shok tree priority]
- [PlayerMe, GBTimes — Frostbite/Melee build validation]
- [StopGame, VGTimes — Russian community consensus (translated from: ru)]

---

## DLC Abilities — Annihilation Instinct

**[DLC ONLY]** The DLC restricts ability slots — Techno-Stasis (new) + Polymeric Shield (returning) are confirmed available. Other base-game abilities (Frostbite, Mass Telekinesis, Polymeric Jet) are **not equippable**.

> **[Contradicted across sources]** DLC ability **slot count** (2 vs. 3 with Shok): Two EN review sources (XboxEra, GBAtemp) state 2 slots (Techno-Stasis + Shield only); some RU sources imply Shok also remains as always-equipped third ability. Mundfish has not officially confirmed slot count. **Verify on first DLC run.**

| Ability | Type | How acquired | Notes |
|---|---|---|---|
| **Techno-Stasis** | New — slow-time AoE (minor self-effect as side consequence) | `dlc_aoi_lebedev_lab` — story-mandatory grant | Widely considered "ridiculously powerful"; EN reviews call it the most impactful new mechanic. [Confirmed: XboxEra; gbatemp; gamingbolt — 3 sources] |
| **Polymeric Shield** | Returning from base game | Available from DLC start (restricted to this slot) | Same mechanics as base game |

### Techno-Stasis — detailed

**DLC-scoped only.** Techno-Stasis does not appear in base-game NORA stations and does not carry over after DLC completion.

**Acquisition:** Automatic. Received in Lebedev's chair scene during *It's Complicated*.

**PC keybind:** Q (same as the base-game "Use Polymer ability" key; context-switches with glove mode).

**Mechanic:** Creates a **stationary AOE bubble of slowed time** around P-3. Enemies inside the bubble move and attack at heavily reduced speed. P-3 acts at full speed. Slows enemies **and projectiles** — it is not a freeze, not a rewind, and not single-target. Costs Glove energy (exact cooldown vs. energy-gated behavior differs between sources; treat as energy-gated).

**Upgrade tree (in priority order):**

| Upgrade | Effect | Priority |
|---|---|---|
| **Bonus damage** | Enemies inside bubble take increased damage | **1st** — strongest for boss DPS |
| **Extended duration** | Longer bubble uptime | 2nd |
| **Reduced polymer cost** | Lower energy cost per activation | 3rd |

**Exact Neuropolymer upgrade costs are not documented in any reviewed source (EN or RU).** RU sources note costs are cheap relative to base-game abilities because the DLC frontloads polymer drops. Known corpus gap.

**Synergies:**

| Combo | Effect |
|---|---|
| **Klusha charge-attack inside Stasis** | Guaranteed crit on the Colossus's exposed arm (RU boss guide explicit) |
| **Secateur Energy Wave inside Stasis** | AOE-on-frozen-crowd; enables ***Time in a Bottle* achievement** (3 enemies killed inside Stasis) |
| **Polymeric Shield inside Stasis** | Shield's reflected-damage proc fires consistently because enemy projectiles slow to a crawl; XboxEra describes this as "ridiculously powerful" |

Note: Base-game abilities (Shok, Frostbite, Mass TK, Polymer Jet) are **not available in the DLC**, so synergy exists only with Polymer Shield and Techno-Stasis.

_source: Compass P3 deep research 2026-05-09 · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 0 · category: mainline · spoiler: dlc:annihilation_instinct_
[Confirmed: walkthroughs.games (EN/RU), XboxEra review (EN), notesread/StopGame (EN), Fandom Techno-Stasis stub (EN)]

---

## DLC Consumables

### Alionka (Alenka)

One-shot consumable: detonates a polymer-vortex AoE that pulls enemies in and deals massive damage. **[DLC ONLY]**

_source: clutchpoints; wotpack.ru; walkthroughs.games — 3 sources, 2 languages · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:annihilation-instinct_

- Found throughout the DLC (Mendeleev Complex circular corridor, Radiochemical Lab, Hangar, Hotel intro).
- ⚠️ **"Red October" achievement (MISSABLE):** kill **15 enemies with Alionka**. **If you consume all pickups before reaching 15 kills, the achievement is lost for that run.** Track usage during the DLC.
- A late patch removed the real-world "Alenka" brand from PC packaging (trademark). A Nexus mod restores the original branding.

> **Cross-system dependency** -- see `dependencies.md` DEP-024: Alionka 15-kill "Red October" achievement is permanently missable if all DLC pickups consumed before reaching 15 kills.

---

## Crafting Material Notes

Exact per-upgrade material costs for the full upgrade trees are **not reliably published in any English or Russian source** — costs appear only in-game at the NORA terminal, and Mundfish's balance patches (1.6, 1.8, 1.9.2) silently changed values. **Do not cite any pre-1.6 wiki numbers.** P3 confirmed Neuropolymer costs canonical (see `upgrades.md`).

**Verified resource families (current, patch-independent):** Industrial Plastic, Microcontrollers, Steel Brackets, Electronic Components, Brass Casings, Optical Glass, Polymeric Concentrate, Composite, Neuropolymer. Energy weapons additionally require Power Cells / Lunar Polymer fragments. Tier-3 melee upgrades require at least one Composite (gated behind TG gold chests). **DLC Tier-2/3 weapon upgrades** require **energy modules** (dropped by "ostrich" two-power-element BEA-D variants in DLC).

> **Cross-system dependency** — see `dependencies.md` DEP-006: Composite material for tier-3 melee upgrades comes from TG gold chests. TG8 gold chest is MISSABLE (Ch.4 only). Missing TG8 or TG12 gold chests may block tier-3 melee upgrade ceiling.

_source: Compass/Deep Research 2026-05-09 (P3) — upgrade category structure confirmed, exact costs not verifiable · capture: web_fetch · confidence: high (categories) / low (specific numbers) · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

---

## DLC Ability Sources

- https://walkthroughs.games/lorebase/atomic-heart/guides/ — hidden-features guide (EN/RU, 2023)
- https://notesread.com/atomic-heart-annihilation-instinct-walkthrough/ (EN, 2023)
- XboxEra / playday.one review (EN, 2023)
- https://atomicheart.fandom.com/ — Techno-Stasis stub (EN)
- ClutchPoints, wotpack.ru — Alionka consumable
