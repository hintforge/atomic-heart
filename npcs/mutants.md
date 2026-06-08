# Enemies — Mutants

**status:** research-integrated
**last_reconciled:** 2026-05-14
**research_run:** P4 research 2026-05-14

> **Enemy tier 0 is active.** This file exists for post-encounter reference only. Do NOT volunteer enemy names, tactics, or weaknesses preemptively. After P-3 encounters an enemy and asks, full post-encounter guidance is permitted.

---

## Mutant (Standard)
*Pavlov Complex, Algae Workshop, VDNH, Solnechnaya forest in patches.*

_source: High Ground Gaming, GameRevolution drop list, RU PlayGround tips · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 3 sources]

- **Visual ID:** `sprites/mutant.jpg` | Icon: `sprites/icons/T_Nurse.png` (internal: T_Nurse) | Backup: `sprites/mutant_2.jpg`
- **Class:** Organic — former humans hijacked by Sprouts; fast/aggressive type.
- **Attacks:** Charge-melee; can knock down. Spawn in groups.
- **Weaknesses:** **Fire cartridge (community consensus).** Mass Telekinesis for crowd control; large slow variants have a **back weak spot** — Freeze + back-hit is the recommended kill chain.
- **Drops:** Biomaterials (primary), Chemistry.
- **Quirk:** Always paired with Mother nests — destroy Mothers first or kills don't stick. Includes Poison Mutant and Fire Mutant variants with different elemental affinity; switch cartridge accordingly before engaging.

---

## Sprout (Sprout-spore)
*Indoor mutant zones; airborne, paired with Mother nests.*

_source: High Ground Gaming, EN Fandom · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 2 sources]

- **Visual ID:** `sprites/sprout.jpg` | Icon: `sprites/icons/T_Pobeg.png` (internal: T_Pobeg -- "побег" = sprout/shoot, RU)
- **Class:** Organic flying spore — seeks corpses to reanimate as new mutants.
- **Attacks:** Low direct damage; the threat is reanimation.
- **Weaknesses:** 1-shot to anything. Scan-tag → Polymer Jet ignited covers a room.
- **Drops:** Biomaterials (small).
- **Quirk:** **Kill mutants only after Mothers are destroyed and Sprouts cleared** — otherwise kills produce new mutants in seconds. Burning mutant corpses removes the reanimation target.

> **Cross-system dependency** — see `dependencies.md` DEP-019: Kill-order prerequisite — Mother → Sprout → Mutant. Kills do not stick until Mothers are cleared.

---

## Plyusch (standard encounter)
*Pavlov mini-boss, recurring as standard enemy in VDNH + Range 9 + "Bloody Courier" side quest.*

_source: GameRant Plyusch guide, High Ground Gaming · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 2 sources]

- **Visual ID:** `sprites/plyusch.jpg` | Icon: `sprites/icons/T_Plyush.png`
- **Class:** Polymer exoskeleton with dog-brain neural core. Fast, aggressive, melee.
- **Attacks:** Lunge (orange-ring tell — dodge sideways), straight-line slingshot leap, sweeping melee swipes.
- **Weaknesses:** **Resistant to gunfire and Shok.** Vulnerable to Fire cartridge + fast melee. Polymeric Shield neutralizes and reflects melee swipes. Adrenaline capsule recommended for extended dodge windows.
- **Drops:** Biomaterials, Chemistry (frequent), Energy Module (frequent).

> See `npcs/bosses.md` for the first-encounter boss version at `vdnh_drill_mode` (Ch.3). Same weaknesses apply; higher HP and boss-fight context.

---

## Poison Mutant
*Algae Workshop and Pesticide areas.*

_source: Steam 100% achievement guide (scanner #12) · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Single source — verify]

- Variant of standard Mutant; signature poison spray attack. Same weakness profile (Fire) but ranged threat is higher. Biomaterials drop.

---

## Fire Mutant
*Pesticide Workshop.*

_source: Steam 100% achievement guide (scanner #13) · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Single source — verify]

- Variant found in Pesticide Workshop. Fire-aligned; **switch to Ice cartridge against this variant** — do NOT use Fire (it's the standard weakness for normal Mutants but reverses here). Biomaterials drop.

> **Cross-system dependency** — see `dependencies.md` DEP-020: abilities.md recommends Fire for all organics; Fire Mutant reverses this — use Ice instead.

---

## Mutant (Large)
*Indoor mutant zones — larger variant of standard Mutant.*

_source: EN Fandom, NamuWiki mirror · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Merged from sprites/index.md per zipper 2026-05-22 -- verify attack profile on encounter]

- **Visual ID:** No jpg. | Icon: `sprites/icons/T_BigMutant.png` (internal: T_BigMutant)
- **Class:** Large variant of the standard Mutant; shoots Sprout projectiles.
- **Attacks:** Ranged Sprout projectile; close-range melee.
- **Weaknesses:** Same as standard Mutant (Fire). Higher HP pool.
- **Drops:** Biomaterials, Chemicals, Neuropolymer.
