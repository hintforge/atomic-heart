# Dependencies — Atomic Heart
<!-- hintforge · stitch pass · last run: 2026-05-24 (Pass 5: full re-audit all 23 edges; 1 new edge DEP-024; 4 inconsistencies resolved/surfaced) -->
<!-- Every stitch run re-audits ALL existing edges + adds new ones. The per-edge convergence audit (open each cited source, verify the specific value) applies to every row in this file on every run, not just new candidates. A game patch, DLC, or new ingestion phase can change facts that existing edges cite -- only a full re-audit catches that. See `stitch_and_zipper.md` Phase B "Re-run scope: always full." Inconsistencies (cited source contradicts edge text) land in the `## Corpus inconsistencies` section; the edge row stays in place. -->

## Cross-system edges

| Edge ID | System A | System B | Dependency description | Confidence | Source files |
|---------|----------|----------|------------------------|------------|--------------|
| DEP-005 | HAWK relay disable mechanic (`mechanics.md`) | Farming efficiency (`items/crafting_materials.md`) + Polygon entry safety (`optional_zones/polygons.md`) | Disabling the local HAWK relay is a precondition for safe farming AND safe Polygon entry — suppresses Pchela respawns and Dandelion cameras. Applies in all open-world zones. | high | `mechanics.md`, `items/crafting_materials.md`, `optional_zones/polygons.md` |
| DEP-006 | Tier-3 melee weapon upgrades (`items/abilities.md` crafting notes) | TG gold chest drops (`optional_zones/polygons.md`) | TG gold chests contain **weapon mod blueprints** (confirmed: TG8, TG10, TG11, TG12 all drop mod blueprints from gold). Composite material may also drop from gold chests but is NOT the sole contents — prior "sole source of Composite" claim was overstated. Missing TG gold chests blocks both mod blueprints AND potentially Composite. | medium | `items/abilities.md`, `optional_zones/polygons.md` |
| DEP-007 | Plyusch organic enemy weakness (`npcs/bosses.md`) | Bridge organic mutant encounters (`sections/ch7_bridge.md`) | Plyusch weakness profile (fire/explosives/TK vulnerable; gunfire/freeze negligible) independently confirmed in both files: bosses.md documents the full weakness set; ch7_bridge.md independently documents Shok-resistance and fire-cartridge KS-23 recommendation. Carry fire-cartridge KS-23 to Ch.7 bridge. | high | `npcs/bosses.md`, `sections/ch7_bridge.md` |
| DEP-009 | Volan camera "remote blackboard read" mechanic (`sections/ch2_forester.md`) | Code-entry puzzles with visible blackboards (`puzzles/combination_locks.md`) | Two independent files document the same shortcut: Volan camera can read a code off a blackboard remotely without walking to it. Taught in Ch.2 open world; confirmed again in Ch.4 Tokamak door puzzle. Applies to any Volan-accessible zone with a visible code surface. | high | `sections/ch2_forester.md`, `puzzles/combination_locks.md` |
| DEP-010 | Natasha-class boss weakness (`npcs/bosses.md`) | TG12 Natasha variant (`optional_zones/polygons.md`) | Natasha boss weakness (jet ports on back → explosives + high fire-rate; Shok stalls movement) documented for Theater stage encounter applies equally to the Natasha-class variant inside TG12. Both files independently confirm same enemy class in both locations. | high | `npcs/bosses.md`, `optional_zones/polygons.md` |
| DEP-015 | Zvezdochka Saw Dance blade mechanic (`items/weapons.md`) | Frostbite freeze + Mass TK lift (`items/abilities.md`) | Zvezdochka Reverse Shot blades are arc-ballistic and miss moving grounded targets — full effectiveness requires Frostbite (freeze state) or Mass TK Increased Power (lift state) to be active on the target. Without one of these abilities, Saw Dance underperforms. | medium | `items/weapons.md`, `items/abilities.md` |
| DEP-016 | Build D "Zvezdochka Saw Dance" (`items/builds.md`) | Reverse Shot is Polygon 1-locked (`items/weapons.md`, `optional_zones/polygons.md`) | Build D requires Reverse Shot (Saw Dance) — which is Polygon 1-locked. A player who hasn't done Polygon 1 has Crushing Blow instead, a fundamentally different special attack. Polygon 1 is always-available but sealed by DEP-004 (Sky's the Limit). | medium | `items/builds.md`, `items/weapons.md`, `optional_zones/polygons.md` |
| DEP-017 | Railgun weapon mechanic (`items/weapons.md`) | Lab Tech crafting material drops (`npcs/robots.md`) + Metal Parts farming (`items/crafting_materials.md`) | Firing Railgun at VOV-A6 Lab Techs disintegrates the body — no loot drops. Lab Techs are the primary open-world source of Metal Parts and Synthetic Material. Using Railgun on them destroys the farming loop; save Railgun for boss-tier targets. [Confirmed live 2026-05-12] | high | `npcs/robots.md`, `items/weapons.md` |
| DEP-018 | LUC-1 Owl respawn mechanic (`npcs/robots.md`) | Natasha boss encounter (`npcs/bosses.md`) — Theater Stage (Ch.4) and TG12 (Ch.5) | LUC-1 Owls respawn infinitely until their trigger source (Natasha) is killed. Burning ammo on Owls before Natasha is down is a damage sink — focus Natasha first; Owls clear themselves. Applies at both Theater Stage and TG12. | medium (user-confirmed 2026-05-16) | `npcs/robots.md`, `npcs/bosses.md` |
| DEP-019 | Mother nest spawner enemy (`npcs/robots.md`) | Sprout reanimation + Mutant combat (`npcs/mutants.md`) | Mother nests continuously spawn Sprouts that reanimate mutant corpses. Required kill order in all organic-enemy rooms: (1) destroy all Mothers, (2) clear all Sprouts, (3) then engage Mutants. Kills do not stick until Mothers and Sprouts are gone. Applies in Algae Workshop, Pesticide Workshop, VDNH, Pavlov. | medium (user-confirmed 2026-05-16) | `npcs/robots.md`, `npcs/mutants.md` |
| DEP-020 | Fire Mutant elemental reversal (`npcs/mutants.md`) | Fire cartridge general guidance for organics (`items/abilities.md`) | `abilities.md` recommends Fire cartridge for all organic enemies (mutants are Shok-resistant). Fire Mutant is an exception: Fire is ineffective; switch to Ice cartridge instead. Failure to switch reverses the intended damage advantage. Primary zone: Pesticide Workshop (Ch.1). | high | `npcs/mutants.md`, `items/abilities.md` |
| DEP-021 | Farm BEA-D "ostrich" (two-power-element) variants for Energy Modules | Before DLC completion ("7th bead" / "A Girl's Best Friend") — post-completion BEA-D access uncertain | "Maximum Strength" achievement requires fully upgrading both Klusha and Secateur; high Energy Module cost demands farming ostrich BEA-Ds before the DLC endgame. [Ostrich variant specifics: verify in-game via scanner tooltip.] Upgrades pending proposal M-01. | high | `items/weapons.md`, `npcs/robots.md`, `npcs/bosses.md` |
| DEP-022 | Camera alarm level 2 trigger (`mechanics.md`) | Pchela-Dandelion repair cycle (`npcs/robots.md`) + camera-kill farming loop (`items/crafting_materials.md`) | The camera-kill farming loop deliberately chains alarm level 2 (camera sees P-3 kill → reinforcement swarm) with Pchela repairing a destroyed Dandelion camera to restore it as the alarm trigger. Both sub-systems must stay active: HAWK relay must NOT be disabled (stops Pchela repairs, kills cameras) and Railgun must NOT be used (permanent map removal per DEP-017 drains the spawn pool). Deliberately exploiting this loop trades the alarm suppression of DEP-005 for unlimited reinforcement spawns. | high | `mechanics.md`, `npcs/robots.md`, `items/crafting_materials.md` |
| DEP-023 | Boss/std-variant taxonomy (`npcs/bosses.md`, `npcs/robots.md`) | Premium material drop-source interpretation (`items/crafting_materials.md`) | Five enemy names (Hedgie, Belyash, Natasha, Dewdrop, Plyusch) refer to both scripted boss encounters and standard farmable variants. The `[std-variant: confirmed/suspected/unknown]` taxonomy in `bosses.md` governs how the reader interprets every premium-material drop source in `crafting_materials.md` that lists these names. Misreading a std-variant source as a boss encounter sends the player to a scripted fight for farmable materials -- wrong strategy. Belyash confirmed as open-world std-variant (spawns from MTU-7 Bumblebee carriers); Natasha and Dewdrop still suspected/unknown -- verify in-game. | high | `npcs/bosses.md`, `npcs/robots.md`, `items/crafting_materials.md` |
| DEP-024 | Alionka consumable resource (`items/abilities.md`) | "Red October" achievement (`nav/architecture.md` DLC optional content) | Kill 15 enemies with Alionka during the DLC. Achievement permanently lost if all Alionka pickups are consumed before reaching 15 kills. Alionka is found in Mendeleev Complex (circular corridor, Radiochemical Lab, Hangar, Hotel intro). The pickup pool is finite -- track kills before consuming. | medium (DLC -- not yet live-verified) | `items/abilities.md`, `nav/architecture.md` |

## PoNR / lockout edges

| Edge ID | Trigger | Locked out | Notes | Source files |
|---------|---------|------------|-------|--------------|
| DEP-001 | Pavlov exit — E48 (`pavlov_surgical_lab` → `lighthouse_beach`, PERMANENT) | Biomaterials farming window inside Pavlov Complex | Pavlov is one-and-done. Organic-enemy-heavy zone with a concentrated Biomaterials farming window. Sweep all cabinets + chests before pressing the exit elevator. Note: Neuropolymer (Polymer Jelly) drops from nearly all enemies throughout the game and is NOT scarce post-Pavlov. | `nav/architecture.md`, `items/crafting_materials.md` |
| DEP-002 | E36 (`lastochkin_theater_grounds` → `lastochkin_theater_int`, chapter-bound) → TG8 becomes inaccessible (E40) | Fox — Lightweight Titanium Blade; Zvezdochka — Lower Blade With Reflex Booster; Swede — Polymeric Alloy Extension; Dominator — Vortex Transducer; MP — Revolver-Type Bolt Frame | TG8 window is while "Bug in the System" is active, before E36 (Theater interior entry). **E35 "Petrov flees" cutscene does NOT close TG8** — confirmed live 2026-05-12. Prior note said "E39 / Ch.4 only" — both wrong; lockout is E36, not E39, and window extends into Ch.5. | `nav/architecture.md`, `items/weapons.md`, `optional_zones/polygons.md` |
| DEP-003 | Lighthouse PoNR — E48 (`pavlov_surgical_lab` → `lighthouse_beach`, PERMANENT); TG12 window is E47 only (Ch.5 Hospital quest) | KS-23 — Thermal Scope; Pashtet — Polygon 12 ranged projectile mod | TG12 energy barrier is only down during the Hospital quest (Ch.5). E48 permanently seals both TG12 and all remaining Pavlov content. | `nav/architecture.md`, `items/weapons.md`, `optional_zones/polygons.md` |
| DEP-004 | Ch.9 "Sky's the Limit" trigger (final story step before Ch.9 locks) | ALL remaining open-world Polygon blueprints + all Lootyagin chests (24 total) | Sky's the Limit permanently locks every Polygon and all open-world blueprint/chest locations. Operational rule: clean all available Polygons in Ch.5 window; finish remainder in Open World 2 (post-Pavlov) before Ch.9. | `items/weapons.md`, `optional_zones/polygons.md`, `sections/ch9_lighthouse.md` |

## Missable / sequencing dependencies

| Edge ID | Action | Window | Consequence | Source files |
|---------|--------|--------|-------------|--------------|
| DEP-002 | Enter TG8 and collect all 3 chests | Ch.4 — "Bug in the System" quest active, before E36/E39 | 5 weapon mods permanently missed (Fox blade, Zvezdochka lower blade, Swede extension, Dominator Vortex Transducer, MP Revolver-Type Bolt Frame) | `nav/architecture.md`, `items/weapons.md`, `optional_zones/polygons.md` |
| DEP-003 | Enter TG12 and collect all 3 chests | Ch.5 — during Hospital quest, before E48 | 2 weapon mods permanently missed (KS-23 Thermal Scope, Pashtet Polygon 12 mod) | `nav/architecture.md`, `items/weapons.md`, `optional_zones/polygons.md` |
| DEP-001 | Sweep Pavlov Complex chests before exit elevator | Ch.5 — before E48 | Biomaterials scarcer for remainder of game; no return to Pavlov after E48. Polymer Jelly (Neuropolymer) is NOT scarcer -- drops from nearly all enemies throughout the game. | `nav/architecture.md`, `items/crafting_materials.md` |
| DEP-006 | Collect TG gold chests (especially TG8 + TG12 before their MISSABLE windows) | Per-TG window (TG8: Ch.4; TG12: Ch.5) | Composite material may be unavailable for tier-3 melee upgrades if gold chests missed | `items/abilities.md`, `optional_zones/polygons.md` |
| DEP-008 | Take the Algae Workshop zip-line shortcut before sweeping chirpers/corpses | Ch.1 Vavilov — Algae wing, before wing exit | Zip-line skips ~5 min of corridor and bypasses chirper/corpse locations in that wing. Taking it before sweeping permanently misses those collectibles. Sweep the Algae wing on foot first; then exit normally. | `sections/ch1_vavilov.md`, `puzzles/combination_locks.md` |
| DEP-011 | Descend Morgue elevator (edge E45) before clearing hospital ward 5-chest room | Ch.8 Pavlov — hospital ward, before Morgue elevator descent | Blood Courier door leads to a ward containing a 5-chest secret room. Edge E45 (Morgue elevator) is a permanent PoNR that seals this room. `ch8_pavlov.md` missable table was missing this item — now corrected. | `puzzles/combination_locks.md`, `sections/ch8_pavlov.md` |
| DEP-012 | Skip scanning Left and Right Twins individually during Ch.10 final encounter | Ch.10 — final Twins fight only | "Scanner" achievement requires scanning each Twin individually during the Ch.10 fight. Their Chelomey prologue appearance does NOT count. This is the only valid window. | `npcs/bosses.md`, `sections/ch10_endgame.md` |
| DEP-013 | Use any weapon during first Hedgie encounter | Ch.3 — first arena encounter only | "Strike" achievement requires zero weapon use — statues must deal all damage. Any weapon hit forfeits permanently. One-shot window; no second chance. | `npcs/bosses.md`, `sections/ch3_vdnh_outdoor.md` |
| DEP-014 | Use any ranged weapon during first Belyash encounter | Ch.4 — first theater grounds encounter only | "Chop Chop Chop" achievement requires melee weapons only. Any ranged weapon use forfeits permanently. One-shot window. | `npcs/bosses.md`, `sections/ch6_theatre.md` |
| DEP-021 | Farm BEA-D "ostrich" (two-power-element) variants for Energy Modules | Before DLC completion ("7th bead" / "A Girl's Best Friend") -- post-completion BEA-D access uncertain | "Maximum Strength" achievement requires fully upgrading Klusha and Secateur; Energy Module farming window may close after DLC completion | `items/weapons.md`, `npcs/robots.md`, `npcs/bosses.md` |
| DEP-024 | Use Alionka to kill 15 enemies during the DLC | Before consuming all Alionka pickups in the DLC | "Red October" achievement permanently lost if all Alionka pickups are consumed before reaching 15 kills. Track kill count before each use; pickup pool is finite. | `items/abilities.md`, `nav/architecture.md` |
| DEP-025 | Collect all 11 crystal figurines during the Blood on Crystal DLC | Before DLC endgame PoNR -- no chapter select; all 11 must be found in one playthrough | "Crystal Platinum" achievement permanently missed for that run; full DLC replay required. Figurine #1 has a known tracking bug -- reload prior save if it does not register. | `nav/blood_on_crystal.md`, `sections/missables.md`, `achievements.md`, `nav/architecture.md` |

## Stitch run log

| Date | Scope | Edges written | Edges proposed (pending) | Inconsistencies surfaced | Model |
|------|-------|---------------|--------------------------|--------------------------|-------|
| 2026-05-12 | Pass 1: `nav/` + `mechanics.md` + `items/` | DEP-001 through DEP-006 (6 edges) | 0 auto-declined; medium-confidence proposals below | 0 | claude-sonnet-4-6 |
| 2026-05-12 | Pass 2: `sections/` + `optional_zones/` + `npcs/` + `puzzles/` | DEP-007 through DEP-014 (8 edges: 4 auto + 4 user-confirmed) | 0 declined | 0 | claude-sonnet-4-6 |
| 2026-05-12 | Scoped re-run: `items/` + `optional_zones/` | DEP-015 through DEP-016 (2 medium-confidence edges, user-confirmed) | 0 declined | 0 | claude-sonnet-4-6 |
| 2026-05-16 | Scoped: P4 delta (npcs/robots.md, npcs/mutants.md, updated items/) | DEP-017 through DEP-021 (5 edges: 3 auto-write + 2 user-confirmed; M-01 upgraded to DEP-021) | 0 declined | 0 | claude-sonnet-4-6 |
| 2026-05-22 | Scoped: stale-claim delta (mechanics.md, npcs/robots.md, npcs/mutants.md, npcs/bosses.md, items/weapons.md, items/crafting_materials.md) | DEP-022 (1 edge auto-write) | 0 declined; boss/std-variant taxonomy skipped (structural, single-directory); Railgun permanent-removal skipped (already DEP-017) | 0 | claude-sonnet-4-6 |
| 2026-05-22 | Post-hoc: pass 4 skip-reasoning review (boss/std-variant taxonomy wrongly dismissed as single-directory; Belyash flag inconsistency fixed in crafting_materials.md) | DEP-023 (1 edge) | 0 | 0 | claude-opus-4-6 |
| 2026-05-24 | Pass 5: full re-audit all 23 edges (DEP-001 through DEP-023) under v45-v49 per-edge convergence audit procedure | DEP-024 (1 edge: Alionka "Red October" missable) | 0 | 4 (DEP-001 Polymer Jelly alias removed; DEP-002 Dominator mod renamed; Klusha Handle location conflict; Klusha Blade location conflict) | claude-sonnet-4-6 |
| 2026-06-05 | Pass 6: zipper (DLC 2/3/4 nav file overlap survey; 3 accepted-as-design; 2 cross-ref additions) + full re-audit all 25 edges (DEP-001 through DEP-025) post-DLC-ingestion; DLC 2/3/4 new content scan for new edges | DEP-025 (1 edge: Crystal Figurines/Crystal Platinum BoC missable) | 0 | 4 (DEP-004 source column fixed: architecture.md → ch9_lighthouse.md; DEP-002 MP mod count corrected 4→5; Life After Life naming conflict open; Moby Dick missable conflict open) | claude-sonnet-4-6 |

---

## Medium-confidence proposals (Pass 1 — pending user confirmation)

### ~~Proposed edge M-01~~ — WRITTEN as DEP-021 (2026-05-16)

P4 ingestion added `npcs/robots.md` which independently documents the BEA-D ostrich → Energy Module connection. Two-file, two-directory support confirmed; upgraded from medium (pending) to high confidence and written as DEP-021.

---

## Medium-confidence proposals (Pass 2 — all confirmed, written as DEP-011 through DEP-014)

### Proposed edge M-02 (medium confidence): Blood Courier PoNR → hospital ward 5-chest room missable

**Proposed edge:** Blood Courier door (Pavlov Hospital) + hospital ward 5-chest room ↔ Morgue elevator PoNR (edge E45)

**Rationale:** `puzzles/combination_locks.md` warns explicitly that the Morgue elevator descent (edge E45) is a permanent PoNR and the hospital ward's 5-chest secret room must be cleared first. `sections/ch8_pavlov.md` missable table does NOT include this 5-chest room — creating a gap where a player relying only on ch8_pavlov.md would miss it. Single source documents both the PoNR and the secret room.

**Source:** `puzzles/combination_locks.md` (Blood Courier door entry)

Write this edge? (yes / no / reword):

---

### Proposed edge M-03 (medium confidence): Twins Scanner achievement → Ch.10 final encounter only

**Proposed edge:** "Scanner" achievement ↔ Ch.10 final Twins encounter (Chelomey prologue appearance does NOT count)

**Rationale:** `npcs/bosses.md` states explicitly that scanning Left and Right twins during the Ch.10 fight is the only valid window — the prologue appearance does not register. Neither `sections/ch10_endgame.md` nor `sections/ch0_chelomey.md` documents this constraint. Single source.

**Source:** `npcs/bosses.md` (Twins entry)

Write this edge? (yes / no / reword):

---

### Proposed edge M-04 (medium confidence): Hedgie "Strike" achievement → zero weapon use

**Proposed edge:** Hedgie Ch.3 encounter ↔ "Strike" achievement (statues must deal all damage — any weapon use forfeits permanently)

**Rationale:** `npcs/bosses.md` documents that using ANY weapon during the first Hedgie encounter permanently forfeits "Strike." One-shot window. `sections/ch3_vdnh_outdoor.md` hides arena content at enemy-tier 0. Single source.

**Source:** `npcs/bosses.md` (Hedgie entry)

Write this edge? (yes / no / reword):

---

### Proposed edge M-05 (medium confidence): Belyash "Chop Chop Chop" achievement → melee only

**Proposed edge:** Belyash Ch.4 theater grounds encounter ↔ "Chop Chop Chop" achievement (melee only — any ranged weapon forfeits permanently)

**Rationale:** `npcs/bosses.md` documents that using any ranged weapon during the first Belyash encounter permanently forfeits the achievement. One-shot window. `sections/ch6_theatre.md` hides encounter content at enemy-tier 0. Single source.

**Source:** `npcs/bosses.md` (Belyash entry)

Write this edge? (yes / no / reword):

---

## Corpus inconsistencies

Stitch's per-edge convergence audit (see [`../../hintforge/stitch_and_zipper.md`](../../hintforge/stitch_and_zipper.md) Phase B) populates this section when a candidate edge's cited sources contradict each other. Each row records the contradiction; resolving it is the user's call (or a follow-up doctor / ingestion run). Edges blocked on an unresolved entry are NOT written to the tables above until the inconsistency is closed.

| Detected | Files | Conflicting values | Suspected authoritative source | Status |
|----------|-------|--------------------|--------------------------------|--------|
| 2026-05-24 | `items/weapons.md` vs `nav/architecture.md` | Klusha Handle location: weapons.md says "Freedom Park"; architecture.md says "Flooded Village / Swamp (before Lebedev -- note: many EN video guides incorrectly say park area)" | `nav/architecture.md` (explicitly flags EN video guides as wrong) but unverifiable without in-game confirmation | open -- verify on first DLC run |
| 2026-05-24 | `items/weapons.md` vs `nav/architecture.md` | Klusha Blade location: weapons.md says "Yellow rooftop chest near first BUS-A dome"; architecture.md says "Mendeleev Complex (deeper rooms, post BEA-D #4)" | Cannot determine; architecturally different claims suggesting different chests | open -- verify on first DLC run |
| 2026-06-05 | `sections/missables.md` vs `achievements.md` | Achievement name for Validol zero-kill constraint: missables.md labels it "Life After Life"; achievements.md names it "Validol's Our Bro." "Life After Life" is the mission name, not the achievement name. | `achievements.md` (canonical Steam achievement name from primary sources) | open -- fix missables.md label on first BoC run |
| 2026-06-05 | `sections/missables.md` vs `achievements.md` | Moby Dick chirper missability: missables.md says "Missable -- one-time window"; achievements.md says `missable: no`. EutS has no chapter select but enchantment_under_sea.md doesn't clarify chirper replayability per zone. | Unknown -- verify in-game on first EutS run | open -- verify |

<!-- Status vocabulary: open (just surfaced) | resolved (user picked authoritative value + corrected the other file) | accepted (user accepted both -- rare; usually means the claim is genuinely ambiguous in-game). When status flips to resolved, the next stitch run can re-evaluate the edge. -->
