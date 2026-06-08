# Puzzles — Combination Locks & Sequence Puzzles

**status:** research-integrated (converged main + sandbox 2026-05-09)
**last_reconciled:** 2026-05-09
**research_run:** P1 (Compass/Deep Research 2026-05-08, both ingestion runs) + P3 DLC (2026-05-09)

Keypad codes, button sequences, sequence-matching, collect-and-return, and other ordered-input puzzles. Each entry uses the hint ladder: ask what level P-3 wants before giving the answer.

**Hint ladder:**
- **Lvl 1** — What to look at / what the puzzle is asking for. No solution.
- **Lvl 2** — The approach or method. Still no answer.
- **Lvl 3** — Full solution with exact inputs.

Current puzzle tier: 1 (auto-give Lvl 1 on zone entry; wait for explicit request before Lvl 2 or Lvl 3).

Base-game puzzles below. DLC (Annihilation Instinct) puzzles: see §DLC Puzzles at bottom of this file.

---

## Maglev Tunnel Restart Code

**Zone:** `vavilov_maglev_tunnels` (Ch.1) · **Edge:** E05
**puzzle-tier: 2** (solution is a specific input pattern)
_source: walkthroughs.games, gameranx · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 2 · category: mainline · spoiler: progression_

- **Lvl 1:** There's a code panel on the maglev control station. Look at the panel face and the surrounding environment for a pattern hint.
- **Lvl 2:** The panel uses a dot grid. The correct input is a recognizable symbol formed by selecting specific dots. Think about what shape "an upside-down letter" would look like on a dot grid.
- **Lvl 3:** Select all dots in the upper-left area of the panel that form an **upside-down "C"** shape. This is the only way past the Maglev Tunnels.

---

## Vavilov 4-Canister Assembly

**Zone:** `vavilov_birch_distribution_hall` (central hub) → wings: hot/cold/pesticide/algae workshops (Ch.1)
**puzzle-tier: 1** (collect-and-return mechanic)
**missable:** no (required for story progression — but **chirpers/corpses in each wing ARE missable on exit**)
_source: walkthroughs.games, StopGame, Fandom, Gameranx — 4 sources confirmed · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 1 · category: mainline · spoiler: none_

- **Lvl 1:** You need one canister from each of the four workshop wings around the central Birch chamber. The wings are: Thermarium (Hot), Cold Lab, Pesticide, and Algae. Any order works — the central hub is bidirectional until you press the exit elevator.
- **Lvl 2:** Each wing requires navigating its area and activating the canister mechanism at the end. Some wings have mini-obstacles (polymer swim, mechanical puzzles) before reaching the canister. After collecting all 4, return to the Birch hub and insert each one in the indicated slots.
- **Lvl 3:** Order is completely free — no wing locks out another. (1) Navigate to any of the 4 workshop wings from the Birch hub. (2) Progress through each wing to its canister room (Thermarium = thermal/hot, Cold Lab = cold/ice, Pesticide = chemical, Algae = organic/plant). (3) Activate the canister at the end of each wing. (4) Return to the Birch hub and insert each canister in its designated slot. (5) After all 4 inserted, the exit elevator becomes available.

> **Sweep rule:** clear chirpers + corpses in each wing before moving to the next — all are missable on exit.

> **Cross-system dependency** — see `dependencies.md` DEP-008: Taking the Algae wing zip-line shortcut before sweeping permanently misses that wing's chirpers/corpses. Take the long route through the Algae wing if going for collectibles.

---

## VDNH Tokamak Door Code (Hall of Fame)

**Zone:** `vdnh_pavlov_floor` / Tokamak room (Ch.4)
**puzzle-tier: 2** (8-button keypad sequence; code is in-zone but read from a blackboard)
**missable:** **yes — VDNH exit is permanent.** Latest safe = Ch.4. Loot behind door includes Snowball blueprint (alternate; also in Vavilov Cold Lab) + Large Neuromed Capsule.
_source: GamesRadar, TheLoadout, walkthroughs.games — 3 sources · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 2 · category: mainline · spoiler: none_

- **Lvl 1:** The code isn't on a chest or on the keypad itself — look around the immediate area for a surface that could display information. The office layout is designed so the code is visible from a specific vantage point.
- **Lvl 2:** There's an office **directly opposite** the keypad door. Inside that office is a **blackboard**. The 8-pad code is written on the blackboard. You can also use a **Volan camera** (if you have access) to read the blackboard through the door without entering the office.

> **Cross-system dependency** — see `dependencies.md` DEP-009: Volan camera "remote blackboard read" is independently documented in `sections/ch2_forester.md`. Applies wherever a Volan-accessible camera has line-of-sight to a code surface.
- **Lvl 3:** Enter the office opposite the keypad, read the code from the blackboard, then return and enter the sequence on the keypad. The code itself isn't hardcoded in research — read it from the blackboard in your playthrough. (If the blackboard is unclear in-game, GamesRadar or TheLoadout walkthroughs have screenshots.)

---

## VDNH Darwin Test (Tereshkova)

**Zone:** `vdnh_atrium` (Ch.3) · **Edge:** E22
**puzzle-tier: 2** (full object sequence)
_source: gameranx 448005 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 2 · category: mainline · spoiler: progression_

- **Lvl 1:** Tereshkova is asking P-3 to prove humanity by bringing specific objects. Look around the atrium — the reception area, and the two side rooms — for items on display.
- **Lvl 2:** You need three objects: one that captures information, one that builds, and one that grows. Each object is in a different part of the atrium and may require interacting with the environment to reach it.
- **Lvl 3:**
  1. **Radio** — reception desk, behind the central statue.
  2. **Hammer** — right room; grab the raised hand of the statue to get it.
  3. **House plant** — left room; stand on the weight platform to raise the glass cover, then use telekinesis to pull the plant out.

---

## Theater Light-Lock Door

**Zone:** `lastochkin_theater_int` (Ch.4) · **Edge:** E37 (leads to `theater_control_room`)
**puzzle-tier: 2** (fixed sequence — NOT random)
_source: amkstation, walkthroughs.games glava-4 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 2 · category: mainline · spoiler: progression_

- **Lvl 1:** There's a light-panel door in the theater interior. A dead electrician nearby has written down a hint — look at what's on or near the body.
- **Lvl 2:** The poster/note on the electrician shows which of the light positions to activate, and the order matters. The code is the same every playthrough — it's not generated randomly.
- **Lvl 3:** Activate **top-right**, then **top-left**, then **bottom-left**. That's the complete sequence (abbreviated: UR, UL, BL). This opens the door to the Theater Control Room.

---

## Theatre Ballerina Pose Sequence

**Zone:** `theater_stage` (Ch.6, Theatre main stage)
**puzzle-tier: 2** (sequence-matching — replicate ballet poses on stage figure)
**missable:** no (required for story progression)
_source: PCGamesN, walkthroughs.games — 2 sources · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 2 · category: mainline · spoiler: none_

- **Lvl 1:** Look at each display panel around the stage area — they show a ballet pose. You need to find the input (likely a button or dial) that lets you change the on-stage figure's pose, and match what the display panel shows. There's a confirmation beep when a position is correct. Set each position in order before moving to the next.
- **Lvl 2:** There are four poses to set, one at a time. Each pose is a specific named ballet position. The puzzle uses French ballet terminology shown on the displays. Match the body position AND the arm position separately if the input has two components — the arm and body settings are often independent.
- **Lvl 3:** Full sequence (in order):

| Position | Pose name |
|---|---|
| 1 | Croisée 5th position + arms 3rd |
| 2 | Relevé 5th |
| 3 | Effacé |
| 4 | Arms upright (allongé) |

Each position emits a confirmation beep when set correctly. If no beep after what seems like the right pose, check both body and arm position independently.

---

## Blood Courier Door (Pavlov Hospital)

**Zone:** `pavlov_hospital` → `pavlov_morgue` (Ch.5) · **Edge:** E45
**puzzle-tier: 2** (4-button sequence; method = curtain-color alignment)
_source: gameskinny, theloadout, gamerant, walkthroughs.games — 4 sources confirmed · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 2 · category: mainline · spoiler: progression_

- **Lvl 1:** The hospital ward door has a four-button code panel. The clue to the pattern is somewhere on the lower level of the hospital ward — look for a perspective trick.
- **Lvl 2:** **The code is environmental and positional, not a fixed number.** Find the **hole in the wall** near the keypad. Position yourself at the hole and look through it. The colored hospital cubicle curtains visible through the hole, read in the order they appear from your vantage point, give you the color sequence — match curtain colors to keypad buttons.
- **Lvl 3:** When derived correctly, the curtain alignment resolves to **Left, Center, Bottom, Upper-Right** (four buttons in that order — confirmed across 4 EN sources). **The method matters more than memorizing the answer:** if the in-game curtains differ from your vantage, follow the alignment, don't force the sequence. The "Blood Courier" door leads to the elevator for floor 34 (Morgue).

> **Reconciliation note (main + sandbox):** main's research recorded a fixed sequence (LCBR); sandbox's research emphasized the puzzle is method-based with no universal answer. Both are consistent in current builds — the curtains are deterministic, so the method always resolves to LCBR. Trust the method first; LCBR is the expected output.

> ⚠️ **Warning:** the elevator down is a permanent PoNR (edge E45) — complete the hospital ward and its 5-chest secret room before descending.

> **Cross-system dependency** — see `dependencies.md` DEP-011: hospital ward 5-chest room is permanently locked by edge E45. This missable was absent from `sections/ch8_pavlov.md` — now corrected there.

---

## Optional Code-Locked Door (Pavlov Complex)

**Zone:** `pavlov_complex` (Ch.5, exact sub-zone TBD)
**puzzle-tier: 1** (existence noted; solution not available in research)
_source: altchar · capture: web_fetch · confidence: low (single source) · enemy-tier: 0 · puzzle-tier: 1 · category: mainline · spoiler: progression_

- **Lvl 1:** There's an optional code-locked door in the Pavlov Complex that's not required for story progression — the third such door in the game.
- **Lvl 2:** The code for this door is **not findable in the game environment** — it's community-discovered, not telegraphed by in-world hints.
- **Lvl 3:** Code not available in this research brief. Web-search "Atomic Heart Pavlov optional code door" for community solutions.

---

## TG8 Access — Three-Volan Sequence

**Zone:** `sechenov_research_center_ext` (Ch.4) · **Edge:** E40
**puzzle-tier: 1** (method explained; exact Volan positions in-world)
_source: mvideo.ru polygons RU, walkthroughs.games · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 1 · category: mainline · spoiler: progression_

- **Lvl 1:** Testing Ground 8 is locked and requires hacking a specific set of Volan security cameras in the Sechenov Research Center area to open the hatch. Look for Volans around the building exterior.
- **Lvl 2:** There are three Volan cameras that all need to be accessed: one at the front of the road, one to the right of the Sechenov Research Center building, and one on the rooftop. Best approached during the "Bug in the System" quest while the area is fully accessible.
- **Lvl 3:** Hack all three Volans in the Sechenov Research Center area (front-of-road / right of building / rooftop) — this unlocks the TG8 bunker hatch. **Do this before the Theater PoNR (edge E39)** — TG8 becomes inaccessible after leaving the Theater.

> **Cross-system dependency** — see `dependencies.md` DEP-002: Theater PoNR permanently locks TG8 and all 5 weapon mods inside it. Three-Volan sequence must be completed and all 3 chests collected before E39.

---

## TG1 Access — Volan Camera to Hatch

**Zone:** `forester_open_world` (Ch.2) · **Edge:** E16
**puzzle-tier: 0** (mechanic explanation, not a puzzle solution)
_source: progameguides, gameranx 443223 — 4 sources · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

Hijack a Volan security camera in the Forester open world and aim it at the Testing Ground 1 bunker hatch. The hatch unlocks remotely when targeted. This is the same Volan-hijack mechanic used throughout the game — not a puzzle per se, just the standard method for TG access in open-world zones.

---

## DLC Puzzles — Annihilation Instinct

### DLC Laser-Beam Mirror Puzzle

**Zone:** `dlc_aoi_mendeleev_hangar` / `dlc_aoi_mendeleev_complex` · **DLC:** Annihilation Instinct
**puzzle-tier: 1** (mechanic named on entry)
_source: walkthroughs.games · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 1 · category: mainline · spoiler: dlc:annihilation-instinct_

- **Lvl 1:** Laser-beam puzzle — you need to redirect a beam to hit a target node by rotating mirror splitters. Same mechanic as base-game laser puzzles in the Vavilov Complex.
- **Lvl 2:** The picture-hint pane on the wall is **decorative / broken** in the DLC version — it won't help. Solve by physically rotating each splitter and tracing the beam path to the target.
- **Lvl 3:** [Not documented from research — web-search for walkthroughs.games DLC mirror puzzle walkthrough or ask after attempting Lvl 2.]

---

### DLC Recombination Puzzle (Eleanor's Heart — final puzzle)

**Zone:** `dlc_aoi_noras_cradle` · **DLC:** Annihilation Instinct
**puzzle-tier: 2** (involves a specific spatial arrangement)
_source: wotpack.ru; notesread.com — 2 sources [Confirmed: 2 sources] · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 2 · category: mainline · spoiler: dlc:annihilation-instinct_

- **Lvl 1:** Arrange chains of BEA-D spheres on the floor according to two wall diagrams — one shows color arrangement, the other shows spatial positioning.
- **Lvl 2:** The puzzle requires 5 chains (sizes 1+2+3+4+5 = 15 BEA-Ds total). Read both diagrams fully before placing any chain — one gives the correct color sequence, the other gives the correct floor positions. Treat them as a pair, not independently.
- **Lvl 3:** [Exact chain-placement sequence not reproduced in structured form — source wotpack.ru/zagadka-s-sharami-v-atomic-heart has a step-by-step diagram. Use this URL if P-3 is stuck after Lvl 2.]

---

### DLC BEA-D Containment Puzzle (Radiochemical Lab)

**Zone:** `dlc_aoi_radiochemical_lab` · **DLC:** Annihilation Instinct
**puzzle-tier: 1** (mechanic named on entry)
_source: notesread.com; walkthroughs.games — 2 sources · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: dlc:annihilation-instinct_

- **Lvl 1:** Two mirrored sub-labs. Electromagnetically charged BEA-D spheres are wandering and need to be lured into individual containment rooms. Close the door on each once inside.
- **Lvl 2:** The two sub-labs are structured identically (paired layout). Clear and contain each BEA-D one at a time — trying to chase two simultaneously will cause them to regroup. Lure by staying in the doorway threshold, then step back into the containment room to draw it in.
- **Lvl 3:** [Room-by-room sequence not in research brief — use notesread.com or walkthroughs.games DLC walkthrough if needed.]
