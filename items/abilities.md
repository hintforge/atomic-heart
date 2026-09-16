# Atomic Heart — Polymer Glove Abilities (CHAR-1)

**status:** research-integrated; all seven base-game trees cost-and-prerequisite complete (2026-09-16)
**last_updated:** 2026-09-16
**research_run:** P1 deep research 2026-05-08 (sandbox base) + P3 deep research 2026-05-09 (DLC + main-side flags) + node-cost pass 2026-09-16

_source: Atomic Heart Fandom wiki, Skills page (costs + prerequisites) cross-checked against in-game skill-screen screenshots on IGN, All Powers and Upgrades (branch shape) · capture: web_clip 2026-09-16 · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 2 sources, independently cross-validated against the 13 Character costs already in `upgrades.md` (Twinfinite + GameRant, P3)]

---

## Overview

**8 skill trees total** (correction from pre-research signal of 3) — but **seven of them are in the base game and the eighth is DLC-only**. The base-game seven are five Polymer Glove ability lines (Shok, Frostbite, Mass Telekinesis, Polymeric Jet, Polymeric Shield) plus Energy Management and Character. Techno-Stasis, in *Annihilation Instinct*, is the eighth. The Character tree is in `upgrades.md`.

> **Corrected 2026-09-16.** P1 recorded "six Polymer Glove ability lines" and this file then only ever named five. There is no sixth base-game glove line: the skill screen's own tree list, legible in IGN's in-game screenshots, reads Shok · Character · Frostbite · Mass Telekinesis · Polymeric Jet · Polymeric Shield · Energy Management and stops there.

**Slot system:** Two abilities can be slotted at any time (swap with D-Pad ↑ / F key). **Shok is permanently equipped as a free third ability** — it does not occupy a slot and is always active. Respecs cost nothing at NORA stations.

All upgrades purchased at NORA stations with **Neuropolymer** (a separate currency that drops from any kill).

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 6 sources — DenOfGeek, SegmentNext, GameRant, GBTimes, dotesports, TheGamer; ru: StopGame, VGTimes]

**Note on Polymer costs — upgraded from "±10%" to sourced, 2026-09-16.** Every node cost and prerequisite below now comes from the Atomic Heart Fandom wiki *Skills* page, with each tree's branch shape checked against the in-game screenshots on IGN's *All Powers and Upgrades*. The cross-check is strong: all 13 Character-tree costs match the figures in `upgrades.md`, which P3 confirmed independently against Twinfinite and GameRant.

**The standing caveat is patch drift, not source quality.** Mundfish changed upgrade values silently in patches 1.6, 1.8 and 1.9.2, and the wiki reflects some version of the game rather than necessarily yours. If a NORA terminal disagrees with a number here, the terminal is right.

**Reading the tables below:** each tree lists every node with its cost and the node that unlocks it. Because most nodes sit behind a chain, a node's price and what it actually costs you to reach are different numbers — the per-tree notes call out the cases where that gap is large enough to change a buying decision.

---

## Quick-reference tier list

Cross-language consensus (English + Russian community; 5+ sources, 2 languages). Use this for at-a-glance loadout decisions; per-tree skill detail is below.

| Tier | Ability | Key upgrades | Notes |
|---|---|---|---|
| S | **Mass Telekinesis** | Forced Fall Acceleration, Increased Power (lift heavyweights), Energy Vampire | Best single-target/AoE crowd-control; dominant counter to lab-tech swarms. **Energy Vampire is near-required for Armageddon difficulty** (final boss). RU community agrees with EN consensus. |
| S | **Frostbite** | Absolute Zero (DoT on frozen targets, 333 to reach), Drastic Measure (HP-for-ammo, 58 to reach) | Must-have for mid-game survival; vgtimes.ru calls it the top upgrade after early HP nodes. |
| A (always-on) | **Shok** | Chain Lightning, Extended Topology, Full Contact | Passive / always-equipped — does not use an ability slot. Max early; free third ability. |
| A (boss/situational) | **Polymeric Shield** | Sponge Effect (melee-to-energy), Neuro-Polymer Reflector (reflect ranged), Med Unit Feedback (HP-on-hit) | Slot in only for boss fights (Hedgehog, Belyash, Natasha). Swap back out post-boss. **Ranged reflection is Neuro-Polymer Reflector, not Kinetic Reflector** — see Tree 5. |
| B (synergy) | **Polymeric Jet** | — | Inefficient unless paired with electric or fire cartridges. RU forum users (playground.ru) rate it lower than EN guides. |
| A (build-enabling) | **Energy Management tree** | Energy Density nodes (×3) | Top priority for Dominator/Electro/Railgun builds — doubles energy reserve. |

**Recommended opening order (RU community consensus):** Character tree (HP/dodge/inventory) → Shok → Mass Telekinesis **or** Frostbite depending on play style (ranged kiting = Telekinesis; melee survival = Frostbite).

---

## Tree 1 — Shok (permanently equipped, no slot cost)

**Full tree: 560 Neuropolymer, 10 nodes.** Two branches off the free root.

| Skill | Cost | Unlocked by | Effect |
|---|---|---|---|
| **Shok** | 0 | story | Electromagnetic discharge; robots are especially vulnerable |
| **Amplified Modulator** | 26 | Shok | Increases effective range |
| **Chain Lightning** | 69 | Amplified Modulator | Part of the discharge bounces to an additional target |
| **Extended Topology** | 75 | Chain Lightning | Chain Lightning hits one more target |
| **Full Contact** | 95 | Extended Topology | Secondary Chain Lightning targets take full damage |
| **Electrization** | 32 | Shok | Shok electrifies enemies |
| **Power Amplifier** | 40 | Electrization | More damage; pushes enemies back |
| **Resister Malfunction** | 61 | Power Amplifier | Electrified targets take increased damage |
| **Neuro-Polymer Accelerator** | 75 | Resister Malfunction | Reduces Shok cooldown |
| **Powerful Electrization** | 87 | Neuro-Polymer Accelerator | Repeated hits stack Electrified and shatter low-HP polymerized enemies |

> **Corrected 2026-09-16 — the old priority order was impossible.** This file previously recommended "Power Amplifier → Electrization". Electrization is Power Amplifier's *prerequisite*, so that order cannot be bought. The cheapest real route into Shok is **Amplified Modulator (26) → Electrization (32) → Power Amplifier (40)** — 98 Neuropolymer for the three nodes the community rates highest. The old list also named "Neuro-polymer Acceleration"; the node is **Neuro-Polymer Accelerator**, and a node by that name appears in five separate trees.

**Community priority, corrected to the real chain:** Electrization → Power Amplifier first (the damage-and-stagger core), then Chain Lightning via Amplified Modulator. Full Contact and Powerful Electrization last — Shok is effective at base level and the other trees give more value per Neuropolymer early. [Confirmed: PrimaGames, GamesRadar, PCGamesN]

**Best vs.:** robots (Vovas, Pchelas). Weaker vs. organic mutants (mutants are Shok-resistant) — switch to Fire cartridge or Fat Boy for organic enemies.

> **Cross-system dependency** — see `dependencies.md` DEP-020: Fire Mutant (Pesticide Workshop) reverses the Fire-vs-mutant rule — switch to Ice cartridge for Fire Mutant specifically.

---

## Tree 2 — Frostbite (slot ability)

**Full tree: 639 Neuropolymer, 12 nodes.** Three branches off High Pressure.

| Skill | Cost | Unlocked by | Effect |
|---|---|---|---|
| **Cryo Jet** | 12 | story | Jet of cryopolymer; frozen enemies cannot move |
| **High Pressure** | 11 | Cryo Jet | Increases maximum range |
| **Drastic Measure** | 35 | High Pressure | Fires from your bloodstream when reserves are empty, at the cost of health |
| **Forced Defrost** | 34 | High Pressure | Frozen targets take extra damage when the freeze ends |
| **Careful Disassembly** | 66 | Forced Defrost | Increased loot from frozen kills |
| **Neuro-Polymer Accelerator** | 70 | Careful Disassembly | Reduces cooldown |
| **Increased Polymer Generation** | 101 | Neuro-Polymer Accelerator | Cryo Jet fires for longer |
| **Fire Extinguisher** | 22 | High Pressure | The spray neutralizes incoming fire damage |
| **Intensive Spraying** | 48 | Fire Extinguisher | Freezes enemies faster |
| **Diffuse Spray Head** | 48 | Intensive Spraying | Spray in a cone |
| **Cryo Sleep** | 88 | Diffuse Spray Head | Longer freeze duration |
| **Absolute Zero** | 104 | Cryo Sleep | Damage every second to frozen targets |

> **Corrected 2026-09-16.** "Frost Density" does not exist in either source — the AoE node is **Diffuse Spray Head**. The HP-for-ammo node is **Drastic Measure**, singular. **Absolute Zero is not an early buy:** it sits at the far end of the Fire Extinguisher branch, so reaching it costs 12+11+22+48+48+88+104 = **333 Neuropolymer**, not the ~104 a flat list implies. The whole Fire Extinguisher chain was missing from this file.

**Synergies:** Frost → freeze → Pashtet melee → shatter kill. This is the core of Build A (Melee/Cryo), the consensus best build for Armageddon.

> **Cross-system dependency** — see `dependencies.md` DEP-015: Frostbite freeze state also enables Zvezdochka Reverse Shot (Saw Dance) blade effectiveness — blades hit frozen targets repeatedly but miss moving grounded targets.

**Community priority:** Absolute Zero first (unlocks freeze-shatter; defines the build), then Careful Disassembly (material economy), then Frost Density. [Confirmed: PlayerMe, GBTimes]

---

## Tree 3 — Mass Telekinesis (slot ability)

**Full tree: 1,207 Neuropolymer, 9 nodes — the most expensive tree in the game and the most back-loaded.**

| Skill | Cost | Unlocked by | Effect |
|---|---|---|---|
| **Mass Telekinesis** | 66 | story | Lifts every enemy in the area into the air |
| **Forced Fall Acceleration** | 70 | Mass Telekinesis | Dropped enemies are accelerated and take fall damage |
| **Amplified Modulator** | 79 | Mass Telekinesis | Wider area of effect |
| **Barotrauma** | 93 | Amplified Modulator | More per-second damage |
| **Drastic Measure** | 144 | Barotrauma | Runs on your ATP when reserves are empty, at the cost of health |
| **Increased Impact** | 210 | Drastic Measure | Enemies are held aloft longer |
| **Increased Power** | 144 | Amplified Modulator | Lifts heavyweight enemies |
| **Neuro-Polymer Accelerator** | 175 | Increased Power | Reduces cooldown |
| **Energy Vampire** | 226 | Neuro-Polymer Accelerator | Drains energy from gripped enemies; needs one Power Cell |

> **Corrected 2026-09-16.** "Extended Range" is **Amplified Modulator**; "Linked Souls" appears in neither source and is dropped. **The costs matter for planning:** Energy Vampire is the single priciest node in the game at 226, and reaching it means buying the whole chain — 66+79+144+175+226 = **690 Neuropolymer**. Calling it "near-required for Armageddon" without that number badly understates the commitment. Increased Power alone (boss lifting) is 66+79+144 = **289**.

**Community priority:** Forced Fall Acceleration → Increased Power (enables boss lifting) → Energy Vampire if going Armageddon. [Confirmed: GameRant, TheGamer]

**Endgame combo:** Increased Power + Railgun — lift heavy enemy with TK, Railgun finisher while airborne.

> **Cross-system dependency** — see `dependencies.md` DEP-015: Mass TK Increased Power (lift state) also enables Zvezdochka Reverse Shot (Saw Dance) blade effectiveness — blades hit lifted targets repeatedly but miss moving grounded targets.

---

## Tree 4 — Polymeric Jet (slot ability)

**Full tree: 506 Neuropolymer, 9 nodes — the cheapest tree to finish.**

| Skill | Cost | Unlocked by | Effect |
|---|---|---|---|
| **Polymeric Jet** | 20 | story | Sprays combat polymer that can then be ignited, electrified or frozen |
| **High Pressure** | 23 | Polymeric Jet | Increases maximum range |
| **Environmental Resistance** | 52 | High Pressure | Applied polymer lasts longer |
| **Neuro-Polymer Air Defense** | 85 | Environmental Resistance | Slows rotors to bring down airborne enemies |
| **Increased Polymer Generation** | 89 | Neuro-Polymer Air Defense | Fires for longer |
| **Increased Chemical Reactivity Distance** | 39 | High Pressure | Polymer on one target affects nearby enemies |
| **Mixture Efficacy** | 46 | Increased Chemical Reactivity Distance | Fire and electrification reactions hit harder |
| **High Viscosity** | 63 | Mixture Efficacy | Polymer slows targets |
| **Neuro-Polymer Accelerator** | 89 | High Viscosity | Reduces cooldown |

> **Corrected 2026-09-16.** The node is "Increased Chemical Reactivity Distance" (not "Reactive"), and Mixture Efficacy improves the *elemental reaction*, not raw jet damage. The Environmental Resistance / Air Defense branch was missing entirely. At 506 to complete, this is the cheapest slot tree by a wide margin — worth weighing against the corpus's low tier rating, since "inefficient without a cartridge" and "cheap to max" pull in opposite directions.

**Synergies:** Polymeric Jet + Fire cartridge = fire-ignite on enemies slowed in polymer. Pairs well with KS-23 or Kalash + fire cartridge socket.

---

## Tree 5 — Polymeric Shield (slot ability)

**Full tree: 948 Neuropolymer, 11 nodes.** One lone node off the root, then two long chains off Overload and Destabilize.

| Skill | Cost | Unlocked by | Effect |
|---|---|---|---|
| **Polymeric Shield** | 28 | story | Blocks melee and ranged damage; feeds some absorbed energy back. Does **not** stop critical attacks |
| **Absorption Coefficient** | 46 | Polymeric Shield | Faster recirculation-chamber refill |
| **Overload and Destabilize** | 43 | Polymeric Shield | Retracting a full shield explodes, spraying combat polymer |
| **Sponge Effect** | 82 | Overload and Destabilize | Melee attacks recharge your energy meter |
| **Kinetic Reflector** | 98 | Sponge Effect | Doubles incoming **melee** damage and reflects it |
| **Neuro-Polymer Accelerator** | 96 | Kinetic Reflector | Reduces cooldown |
| **Kinetic Reflector Upgrade** | 145 | Neuro-Polymer Accelerator | More reflected damage; blocks even critical attacks |
| **Reflective Surface** | 82 | Overload and Destabilize | Reflects **laser** attacks |
| **Neuro-Polymer Reflector** | 98 | Reflective Surface | Reflects **all ranged** attacks |
| **Increased Polymer Generation** | 106 | Neuro-Polymer Reflector | Shield lasts longer |
| **Med Unit Feedback** | 124 | Increased Polymer Generation | Redirects part of incoming damage to the Med Unit, restoring health |

> **RESOLVED 2026-09-16 — the long-standing Kinetic Reflector contradiction.** This file carried a `[Contradicted]` marker reading "bullets yes, beams unreliably", built on Reddit reports of inconsistent reflection against laser sweeps like the Dewdrop spider boss. Both sources agree the reports were describing the wrong node. **Kinetic Reflector is melee-only** — it doubles and returns incoming *melee* damage. Ranged reflection is a separate branch that players were conflating with it: **Reflective Surface** (82) handles lasers and **Neuro-Polymer Reflector** (98) handles all ranged attacks. Players reporting "no reflection" against beams had bought the melee branch. The marker is retired.
>
> **Practical consequence:** the two branches are near-exclusive in practice. Beam-reflection costs 28+43+82+98 = **251**; the melee-reflection line to Kinetic Reflector costs 28+43+82+98 = **251** as well, and Med Unit Feedback — the HP-return node the tier list calls out — is the *last* node on the ranged branch at 28+43+82+98+106+124 = **481**.
>
> **Sponge Effect is also mis-described above the table:** it converts *melee attacks* into energy, not blocked damage.

**Crucial on Armageddon difficulty.** Sponge Effect + shield-up-vs-Ivy whip damage is a documented Armageddon-survival technique for Pavlov (Ch.8).

---

## Tree 6 — Energy Management (passive tree)

**Full tree: 789 Neuropolymer, 7 nodes.** One chain with two terminal branches.

| Skill | Cost | Unlocked by | Effect |
|---|---|---|---|
| **Energy Density I** | 0 | story | Adds a Power Cell to the recirculation chamber |
| **ATP Recycling** | 82 | Energy Density I | Lost health is recycled into energy |
| **Energy Density II** | 34 | ATP Recycling | Adds another Power Cell |
| **Greedy Guts** | 146 | Energy Density II ⚠ | Melee attacks restore more energy |
| **Energy Density III** | 104 | Energy Density II | Adds another Power Cell |
| **Thrift** | 184 | Energy Density III ⚠ | Ranged attacks consume less chamber power |
| **Energy Containment** | 239 | Thrift | Faster energy regeneration |

> **Corrected 2026-09-16.** "Recycling" does not exist — the ability-cost node is **Thrift**, and it reduces *ranged weapon* draw, not ability activation cost. The three Energy Density ranks are **not the same price**: 0, then 34, then 104.
>
> ⚠ **Two prerequisites are inferred, not sourced.** The wiki lists the parents of Greedy Guts and Thrift only as "Energy Density", and three nodes share that name, so the table cannot say which rank. The chain above is the reading that matches the in-game layout (a five-node row with one branch up off the left end and one down off the right). Verify at a terminal and correct if wrong.

**Priority:** Energy Density I is free — take it the moment the tree opens. Ranks II and III come cheap-then-dear (34, then 104) and gate every energy-weapon build. Greedy Guts pairs with Fox (energy-on-hit) for near-infinite melee sustain, but at 146 behind a 116-cost run-up it is a mid-game purchase, not an early one.

---

## Community skill priority order (cross-tree, first 15 Neuropolymer spends)

From community consensus across 6 sources [Confirmed: DenOfGeek, SegmentNext, GameRant, GBTimes, dotesports, TheGamer; ru: StopGame]:

Costs added and two errors fixed 2026-09-16. The **reach cost** column is what the node actually costs including every prerequisite you must buy to get to it — which is the number that decides an early-game order, and which the original list omitted.

| # | Skill | Node cost | Reach cost | Why |
|---|---|---|---|---|
| 1 | **Wild Boar** (Character) | 37 | 37 | Cheapest HP boost; gets you through Vavilov |
| 2 | **Second Wind** (Character) | 38 | 75 | An extra dodge charge; best value in the tree |
| 3 | **Energy Density I** | 0 | 0 | Free. Take it the moment the tree opens |
| 4 | **Sleazeball** (Character) | 62 | 137 | I-frames while dodging; game-changing on Armageddon |
| 5 | **Shok: Power Amplifier** | 40 | 72 | Via Electrization (32) — the damage-and-stagger core |
| 6 | **Med Unit Upgrade** (Character) | 57 | 121 | Via Photon Silk (27); passive HP regen |
| 7 | **Juggler** (Character) | 87 | 318 | Neuromed one-handed — but it sits behind Musclehead, so it is a mid-game buy, not a third purchase |
| 8 | **Forced Fall Acceleration** (TK) | 70 | 136 | Ground-slam damage |
| 9 | **Frostbite: Absolute Zero** | 104 | 333 | Enables freeze-shatter; the build pivot — and far dearer to reach than it looks |
| 10 | **Mass TK: Increased Power** | 144 | 289 | Boss lifting |

> **Two corrections.** "Second Wind for ~8 Neuropolymer" was wrong by roughly 5× — it costs **38**, matching `upgrades.md`. And **Juggler cannot be the third purchase**: it requires Musclehead, which requires Med Unit Upgrade, which requires Photon Silk, so it costs 318 to reach. It has been moved down accordingly.
>
> **The general lesson for this tree:** flat "buy this first" lists hide prerequisite chains. Absolute Zero reads as a 104-cost node and is really a 333-cost commitment; Juggler reads as 87 and is really 318. Use the reach column, not the node price, when deciding what to buy next.

**Where guides disagree:** TheGamer (EN) pushes Shok upgrades first; StopGame + VGTimes (RU) push Frostbite + melee as the early-Armageddon answer. **Reconciliation:** Shok is best vs. mechanical robots (Vovas, Pchelas); Frost is best vs. all organic bosses except Hedgie. **The costs favour Shok early on their own merits** — Power Amplifier is reachable for 72 against Absolute Zero's 333.

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
