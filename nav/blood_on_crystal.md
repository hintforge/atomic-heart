# Blood on Crystal -- DLC Zone Gate List (DLC #4)

**status:** research-integrated
**last_reconciled:** 2026-06-05
**zone-id:** boc_orb_lab, boc_wave_platform, boc_submarine, boc_crystal_arrival, boc_crystal_archive, boc_crystal_recreation, boc_crystal_residential_1, boc_crystal_residential_2, boc_crystal_factory, boc_crystal_indoor_beach, boc_crystal_core
**parent chapter:** Blood on Crystal DLC -- full DLC scope (FINAL DLC in season pass)
**zone type:** indoor-linear / indoor-branching / outdoor / cutscene/arena

_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:blood-on-crystal_

> **8 of 13 achievements are missable and there is no chapter select.** Missing a single crystal figurine (11 total) voids "Crystal Platinum" for that run -- full replay required.

---

## Zone List

| zone-id | English in-game name | Russian in-game name | Aliases | Zone type |
|---|---|---|---|---|
| `boc_orb_lab` | Orb laboratory (Lebedev's lab, from DLC #1) | лаборатория «Орб» | "regroup base" | indoor-linear |
| `boc_wave_platform` | Wave Platform | «Волна» (Wave) | "Wave", "port" | indoor-branching / outdoor |
| `boc_submarine` | Submarine | субмарина / подлодка | "sub section" | indoor-linear |
| `boc_crystal_arrival` | Crystal Complex -- arrival/sarcophagus | Хрусталь (Crystal) | "Egyptian area" | indoor-branching |
| `boc_crystal_archive` | Crystal -- archive zone | архив | -- | indoor-branching |
| `boc_crystal_recreation` | Crystal -- recreation/breakroom zone | зона отдыха | "Lunch Break" | indoor-branching |
| `boc_crystal_residential_1` | Crystal -- first Residential Sector | жилой сектор 1 | -- | indoor-branching |
| `boc_crystal_residential_2` | Crystal -- second Residential Sector | жилой сектор 2 | "Validol amusement park" | open-ish |
| `boc_crystal_factory` | Crystal -- Factory / conveyor zone | фабрика, конвейеры | "Engineered Future" | indoor-branching |
| `boc_crystal_indoor_beach` | Crystal -- indoor beach | пляж в помещении | -- | indoor |
| `boc_crystal_core` | Crystal Core / final | Кристальное ядро | "mines", "final" | cutscene/arena |

[Confirmed: Steam guide + showgamer + vgtimes -- 2 languages]

---

## Key missions

| Mission / Objective | Zone(s) | Notes |
|---|---|---|
| Opening ambush -> regroup at Orb lab | `boc_orb_lab` | NORA fitted to glove |
| Wave exploration -> RACCOON boss -> submarine | `boc_wave_platform` -> `boc_submarine` | Enemy-tier: 1 -- RACCOON encounter |
| Submarine exploration (key disk, valve, spark plugs) -> ENOT miniboss | `boc_submarine` | Multi-step exploration; ENOT cargo-robot miniboss |
| Crystal arrival ("get out of the sarcophagus") | `boc_crystal_arrival` | |
| **Making Contact** (Nastya opens doors) | `boc_crystal_archive` area | |
| Medical checkups (ophthalmologist, cardiologist, dentist) | Various Crystal zones | Required to create polymorph body |
| **Validol** mission (3 crystal humans, peaceful) | `boc_crystal_residential_2` | "Life After Life" -- missable achievement if any killed |
| **Lunch Break** (recreation zone) | `boc_crystal_recreation` | |
| **Sudden Cleanup** (vacuum-cleaner quest) | `boc_crystal_residential_1` | Key for figurine #6 |
| **Engineered Future** (industrial presses, factory) | `boc_crystal_factory` | "Projected Future" gate puzzle (Garage Door 19) |
| **Soulmate** quest -> Second Twin boss | mid-Crystal | Enemy-tier: 1 -- fall into Crystal Core |
| Save Sechenov -> fight CHAR-les -> ending | `boc_crystal_core` | Enemy-tier: 1 -- CHAR-les final boss |

Enemy-tier gates apply: do not name RACCOON, ENOT, Second Twin, or CHAR-les as bosses until enemy-tier: 1.

---

## Entry point

Separate campaign from the main menu. Narratively continues directly from EutS -- P-3 and allies are ambushed on the beach; Granny Zina rescues them; they regroup at Lebedev's Orb lab (same location as DLC #1). NORA is fitted into the glove as the new companion (active from the Crystal Complex onward). No save import required. Fully isolated save slot.

_[Narrative prerequisite carries spoiler: dlc:blood-on-crystal -- deliver structural "main menu entry" info freely; gate narrative context]_

## Zone graph edges

| ID | From | To | Type | Direction | Condition | PoNR | Notes |
|---|---|---|---|---|---|---|---|
| BoC-E0 | Main Menu | `boc_orb_lab` | **DLC ENTRY POINT** | one-way | Own DLC / Atomic Pass | No | Flagged: DLC entry edge; NORA fitted here |
| BoC-E1 | `boc_orb_lab` | `boc_wave_platform` | story | one-way | Plan to infiltrate Wave | No | |
| BoC-E2 | `boc_wave_platform` | `boc_submarine` | story | one-way | RACCOON boss / bridge | Yes | Enemy-tier: 1 at BoC-E2 |
| BoC-E3 | `boc_submarine` | `boc_crystal_arrival` | story | one-way | ENOT miniboss; exit generator room | Yes | |
| BoC-E4 | `boc_crystal_*` | Sequential Crystal zones | story | mostly one-way | Quest progression | varies | CHANCE modules introduced |
| BoC-E5 | `boc_crystal_core` | Final boss | story | one-way | Second Twin -> Crystal Core fall | **Yes** | Save Sechenov -> beat CHAR-les -> ending |

Enemy identities at BoC-E2, BoC-E5: enemy-tier: 1 -- do not name preemptively at enemy-tier: 0.

## NORA stations

**NORA functions as P-3's glove companion** (fitted at the Orb lab; active from Crystal Complex). The DLC uses **CHANCE machines** for glove upgrades -- these swap glove abilities on the fly; gaining a new ability removes the oldest upgrade. Save rooms exist throughout (some burnt/damaged). NORA here is the narrative companion + former DLC #1 boss, now allied; not the base-game open-world NORA network.

| zone-id | Location | Function |
|---|---|---|
| `boc_orb_lab` | NORA fitted to glove | Companion active from Crystal Complex |
| `boc_crystal_*` | CHANCE machines | Swap / upgrade glove abilities |
| (various) | Save rooms | Save + supply |

[Confirmed: ClutchPoints + showgamer]

## DLC weapons and abilities

**CHANCE modules** (Polymer Glove): Swap glove abilities on the fly mid-combat. Critical mechanic vs. Polymorphs that switch fire/ice states. Gaining a new ability removes the oldest upgrade.

**Returning DLC weapons** with max-upgrade paths available: Klusha, Secator, Kuzmich (from EutS), Thunderclap/Thunderer (from EutS).

BoC provides access to the **most powerful weapons in the whole game** per community and reviewers.

**New enemies: Polymorphs** -- fire/ice-switching crystal humans. Fire vs. ice elemental counterplay is core to BoC combat. CHANCE modules are specifically designed to counter them.
[Confirmed: GAMES.GG + showgamer]

## Traversal

Crystal and Egyptian-themed environments. Two main settings: the **Wave Platform** (external/internal mix, water-surrounded, Moray eels in water) and the classified **Crystal Complex** -- Egyptian-themed (sarcophagi), crystalline, restricted facility where humans undergo **Polymorph** transformation. Combat is the dominant focus, returning to and expanding the base-game FPS formula with CHANCE-module flexibility.
[Confirmed: 2 languages]

## Optional content registry

| Content name | Type | Parent zone | Unlock condition | Access window | Rec. point | Failure mode |
|---|---|---|---|---|---|---|
| Crystal figurines (11 total) | Collectible (permanent buffs) | Crystal Complex onward | Exploration; appear after reaching Crystal | One playthrough (no chapter select) | Throughout Crystal | **MISSABLE -- no replay; full run lost if one missed** |
| Chirpers | Collectible audio | All zones | Exploration | During pass | As encountered | Missable |
| Klusha & Secator upgrades | Upgrade locations | Multiple | Exploration | During pass | -- | Missable |
| Fluffy Easter Egg room | Secret room | `boc_crystal_residential_1` | Code "X" on outhouse lock | After polymer key | -- | Missable ("Fluffy Easter Egg" ach.) |
| Better Late Than Never | Secret room | Post-art-gallery arena | Code on wall/PEAR terminals | After fight | -- | Missable (dolphin figurine ach.) |
| Secret Meeting room | Secret room | Burnt save room area | Answer PEAR terminal Qs, get key | Mid-late | -- | Missable ("Secret Meeting" ach.) |
| Broken doll | Collectible (no function) | `boc_submarine` | Hidden in chair room | One time | -- | Not tied to achievement |

**Crystal figurines are the primary missable in this DLC.** No chapter select exists; missing any one figurine requires a full replay for "Crystal Platinum." Community notes figurine #1 sometimes does not count (achievement-tracking quirk) -- reload from prior save if it fails.

> **Cross-system dependency** -- see `../dependencies.md` DEP-025: All 11 crystal figurines must be collected in one run (no chapter select); missing any one permanently voids "Crystal Platinum" for that playthrough.

See `../sections/missables.md` for the full DLC missable list.

## Locks-and-keys

| Lock location | Key required | Key source zone | Visible before key? | Notes |
|---|---|---|---|---|
| Residential Sector weapons-disable zone | Polymer key | `boc_crystal_residential_1` | Yes | Re-enables weapons/abilities; needed for Fluffy Easter Egg |
| Fluffy Easter Egg outhouse | Pattern "X" code | Wall nearby (left) | Yes | Secret fluffball room |
| Better Late Than Never door | Pyramid/numeric code | Wall mural + PEAR terminal emails | Yes | Dolphin figurine room |
| Secret Meeting door | Key from dorm room | Opens after answering PEAR terminal | Yes | Observers room |
| Crystal residential house #2 | Key from vacuum-cleaner quest | `boc_crystal_residential_1` | Yes | Figurine #6 inside |
| Submarine compartments | Key disk, valve, captain's valve, spark plugs | `boc_submarine` | Yes | Multi-step exploration |
| Factory gate (Door 19) | Circuit/rod puzzle | `boc_crystal_factory` | Yes | "Engineered Future" / "Projected Future" |

## Soft-locks and bugs

No hard soft-locks, but **8 of 13 achievements are missable** with **no chapter select**.

**CHAR-les boss first-attempt softlock (confirmed community report):** First attempt at the final boss has a confirmed softlock bug. If the fight freezes on first try, reload and re-attempt. Second attempt proceeds normally. See `../npcs/bosses.md` DLC 4 Final Boss entry.

**Crystal figurine #1 tracking bug:** Sometimes does not count. Reload from prior save if first figurine does not register.

**Windows launch bug:** BoC had a Windows-specific launch bug at release. Patched and resolved.
[Confirmed: Steam guides, community reports; patch status confirmed: community]

## Carry-over

Standalone campaign with its own save. The combat formula and glove carry over from base mechanically but no documented item carry-over into the base open-world game. [Structural inference -- verify]

## Story connection

[spoiler: dlc:blood-on-crystal]

Climactic conclusion to the 4-DLC arc. Picks up from EutS's beach ambush. P-3, NORA, Nastya, Nikolai, Hunter infiltrate Crystal while Katya (in a Twin's body) distracts from above. They fight through the Crystal Complex, encountering Polymorphs, RACCOON/ENOT robots, and Burlaks/Burav-type enemies. Key bosses: a RACCOON, the **Second Twin (Lefty)**, and finally **CHAR-les/HRAZ (ХРАЗ)**.

P-3 saves Sechenov's consciousness from the Massif and defeats CHAR-les. The 4-DLC arc: base "longer" ending (betrayal -> Limbo) -> DLC2 escape Limbo with Katya -> DLC3 Neptune/recover rings, Katya into Twin body -> DLC4 confront and beat CHAR-les.

Ending sets up **Atomic Heart 2** (announced at Summer Game Fest 2025) and the MMO-shooter spin-off **The Cube**. Note: Kolya is stabbed by CHAR-les via Nastya's hijacked polymer clone; victory is bittersweet, and a final beach scene shows the group ambushed again with one Twin catching the Beta Connector case mid-air.
[Confirmed: 2 languages]

**Titanic film reference:** Community references a "Titanic" reference; plausibly tied to the submarine section and the Nastya/Kolya romantic scene (upper-deck beat). Direct "Jack & Rose"/Titanic homage NOT explicitly confirmed by sources. Strongest candidate: submarine/underwater romance framing. [Hypothesis -- unverified; no direct source confirmation]

## Common confusions

- "MOR-4Y" is the EutS boss (from DLC #3); BoC final boss is **CHAR-les/HRAZ** (enemy-tier: 1).
- Polymorphs are introduced HERE in BoC, not in EutS.
- No chapter select exists -- crystal figurines are permanently missable per run.
- CHANCE modules REPLACE the oldest upgrade when a new one is acquired; don't upgrade carelessly.

## Length

8+ hours (Focus Entertainment describes BoC verbatim as "longest DLC yet (8+ hours)").
[Confirmed: Focus Entertainment + Bleeding Cool + GAMES.GG]

---

## Reddit sweep additions (2026-05-28)

**CHAR-les boss strategy (F19):** Ignore tentacles and blobs -- they are not the priority. Focus all fire on the face. Watch platform edges (falling off is the primary failure mode). Shotgun recommended for face shots. (enemy-tier: 1 -- deliver post-encounter)

**Content scope (F16):** Community rates BoC as "expansion-level" content -- the most substantial DLC in the season pass. Narrative bridges DLC 1 and DLC 3 storylines.

_source: r/atomicheart/comments/1tkw1i0; r/atomicheart/comments/1suhzwz · capture: manual_paste · confidence: medium · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:blood-on-crystal_

---

## Sources

Primary: Steam guide + ShowGamer.ru + VGTimes.ru (2 languages), GAMES.GG (Apr 2026), iXBT.games (Apr 2026), TrueAchievements, GameFAQs, Focus Entertainment (press release + Ultimate Edition announcement)
_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high (base facts) / medium (BoC post-launch patches -- released ~7 weeks before brief) · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:blood-on-crystal_
