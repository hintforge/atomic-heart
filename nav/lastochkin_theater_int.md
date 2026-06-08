# Nav — Lastochkin Theater Interior

**zone-id:** lastochkin_theater_int
**status:** research-integrated
**research_run:** P2 (Compass/Deep Research 2026-05-08)

## Entry / Exit

- **Entry (E36):** Ventilation crawl from lastochkin_theater_grounds.
- **Exits:**
  - (E37) theater_control_room — optional, bidirectional; requires Engineer code from Coat Check.
  - (E38) theater_stage — story-gate, one-way forward.

**NORA booths:** Multiple — basement, post-elevator, bar break room. [C:3] The bar break room NORA is closest to the theater_control_room door.

## Before Proceeding

> This zone has several sub-areas with collectibles (Mutiny chirper, Supply Room laser-puzzle chirper). Clear them before taking E38 to theater_stage, which is the PoNR for Theater Interior content. The Engineer's code paper (for theater_control_room) is in the Coat Check via the tapestry stairs.

## Sequential Gates

1. **Basement Wall Puzzle** (puzzle) — solve to exit the basement. [C:3]
2. **Elevator to Top Floor** (trigger) — ascend.
3. **Ivy-Spawning Hall** (enemy-clear) — hallway with Ivy encounters.
4. **Burning Dressing Room** (enemy-clear) — mommy-mutant encounter.
5. **Bar / Stage Hall + Engineer Code Door** (puzzle lock) — locked door requires the Engineer's password (from Coat Check); the paper is on the Engineer's body near Coat Check tapestry stairs. Code → `../puzzles/combination_locks.md`.
6. **Coat Check** (item-pickup) — Mutiny chirper; Engineer's password on paper near Engineer's body; access via tapestry stairs off the main hallway.
7. **Supply Room** (optional, item-pickup) — laser-puzzle chirper via yellow hardhat console.
8. **"Not a Password at All" Puzzle Door** (puzzle) — a separate locked door with its own challenge.

## Optional Branches

- **Theater Control Room (E37):** Engineer code door → bidirectional access. Hosts the relay puzzle and the mutant horde event. See `theater_control_room.md`.
- **Coat Check:** Required for the Engineer's password; also has the Mutiny chirper.
- **Supply Room:** Laser-puzzle chirper.

## Common Confusions

- Engineer's password is on paper near Engineer's body in Coat Check — reached via tapestry stairs, backtracking from the bar hall.
- The "Not a Password at All" puzzle door is a separate gate from the Engineer code door.
- Theater control room and theater stage are both accessible from this zone — complete the control room before taking the stage gate.

_source: Compass/Deep Research 2026-05-08 (P2) · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 1 · category: mainline · spoiler: none_
