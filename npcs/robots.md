# Enemies — Standard Robots

**status:** research-integrated
**last_reconciled:** 2026-05-22
**research_run:** P4 research 2026-05-14

> **Enemy tier 0 is active.** This file exists for post-encounter reference only. Do NOT volunteer enemy names, tactics, or weaknesses preemptively. After P-3 encounters an enemy and asks, full post-encounter guidance is permitted.

> **Naming issue:** Atomic Heart was developed in Russian; EN translations and internal dev names often diverge. Several enemy types share names with scripted boss encounters (Hedgie, Belyash, Natasha, Dewdrop, Plyusch). This file covers **standard enemy variants** only. See `bosses.md` for boss encounters. Where a standard variant is confirmed to exist alongside a boss of the same name, it is noted per entry. When in doubt about which variant a source refers to, use NORA's crafting interface (click a material) to verify drop sources in-game.

> **Visual references:** each entry has a `**Visual ID:**` line with image paths relative to `npcs/sprites/`. Icons are game-extracted PNGs from FModel. See the appendix at the bottom of this file for the icon mapping table, material drop quick-reference, and FModel extraction procedure.

---

## VOV-A6 Lab Tech (Vova / Cockroach / Skinny / Mustache)
*Solnechnaya open world, Computational Center, all underground complexes — most common robot in the game.*

_source: EN Fandom (VOV-A6 page), High Ground Gaming, NamuWiki mirror · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 3 sources]

- **Visual ID:** `sprites/lab_tech.jpg` | Icons: `sprites/icons/T_Vov.png` (white/melee), `sprites/icons/T_BlackVov.png` (black/laser), `sprites/icons/T_ShieldVov.png` (shield) | Backup: `sprites/lab_tech_2.jpg`
- **Class:** Humanoid robot. Subtypes: standard VOV-A6, advanced VOV-A6/CH ("Black Vova" — armored, more aggressive, often a mini-boss reappearing as a normal enemy), shielded variant.
- **Attacks:** Mostly melee punches and grappling. Telegraphed heavy strikes show a red circle. Laser-mouth ranged attack on advanced variants — mouth glows before firing, NO red-ring tell. Jump-slam attack is interruptible with a shotgun blast.
- **Weaknesses:** Standard VOV-A6 — Ice, Fire, Physical, Electric (no resistance). VOV-A6/CH (Black) — resistant to Electric; vulnerable to Fire and Physical. Polymer Shield blocks and reflects melee.
- **Drops:** Metal Parts, Synthetic Material (frequent); Advanced variant additionally drops Superconductor and rarely Microelectronics.
- **Quirk:** **Railgun disintegrates Lab Techs cleanly — no loot drop AND permanently removes them from the map.** Pchela cannot restore a Railgun-killed robot. Save Railgun for boss-tier targets if you need crafting parts from kills, or if you want the farming loop to keep working.

> **Cross-system dependency** — see `dependencies.md` DEP-017: Railgun on Lab Techs destroys the Metal Parts / Synthetic Material farming loop -- no loot drops from disintegrated bodies, and Pchela cannot restore permanently-removed robots.
_[Permanent map removal confirmed: r/atomicheart community thread 2026-05-19]_

---

## ARU-31/6 Rotorobot (Rotobot)
*Wheat fields, Solnechnaya outskirts, Forester forest — open-world.*

_source: EN Fandom, High Ground Gaming, NamuWiki · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 3 sources]

- **Visual ID:** `sprites/rotorobot.jpg` | Icon: `sprites/icons/T_Rotorobot.png` | Backup: `sprites/rotorobot_2.jpg`
- **Class:** Heavy agricultural robot. Bulky, high HP, multi-saw arms.
- **Attacks:** Quick dash + heavy melee swing (the dash is the dangerous tell — covers distance fast). Sweep attacks at close range.
- **Weaknesses:** High-damage weapons preferred (Fat Boy, Railgun); Freeze locks it down. Polymer Shield is effective vs. its melee.
- **Drops:** Metal Parts, Synthetic Material (frequent); Superconductor, Chemistry (frequent); Microelectronics (rare). Primary Synthetic source.
- **Quirk:** Repaired by nearby Pchela nests in the open world — destroy the Pchela first if farming. Susceptible to NG+ auras "Daredevil," "Master of the Elements," "Kamikaze," "Lightning Rod."

---

## MFU-68 Laborer
*Open-world Solnechnaya and Forester forest, often in pairs.*

_source: EN Fandom, High Ground Gaming · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 2 sources]

- **Visual ID:** `sprites/laborer.jpg` | No InfoIcon found (may be in DLC paks or a different icon set)
- **Class:** Forestry/labor melee robot with saw arms.
- **Attacks:** Melee chops with circular saws; closes distance aggressively.
- **Weaknesses:** Polymer Shield negates melee well. Freeze + heavy melee combo is efficient. Standard variant has modest HP.
- **Drops:** Metal Parts, Synthetic Material.
- **Quirk:** Almost always in pairs; isolate one with Polymer Jet / Telekinesis before engaging.

## MFU-68/CP "Duck"
*Variant of MFU-68 carrying a firearm.*

_source: NamuWiki mirror · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Single source — verify]

- Resistant to firearms ("Body Armor" NG+ aura). Use melee, Shok, or energy weapons instead of Kalash/KS-23. Best dealt with up close.

---

## RAF-9 Engineer
*Algae Workshop and Hot Workshop hallways, open-world repair points.*

_source: EN Fandom, High Ground Gaming, Steam 100% achievement guide · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 3 sources]

- **Visual ID:** `sprites/engineer.jpg` | Icon: `sprites/icons/T_Raf.png` (internal: T_Raf)
- **Class:** Tall, thin engineer/repair drone. Normally **passive** — does not attack unless provoked.
- **Attacks:** When hostile: long-range poison/acid spray, telekinetic shoves at melee range.
- **Weaknesses:** Low HP; goes down quickly to Kalash bursts or Shok-chain.
- **Drops:** Superconductor (frequent — primary farming target), Chemistry (rare), Microelectronics (rare), Energy Module (rare).
- **Quirk:** Killing a passive Engineer can flag other Engineers in the area hostile. Listed in NG+ aura table.

---

## LUC-1 Owl (Laser Owl)
*Ceilings of Vavilov Seed Vault, Theater interior, TG12 Natasha encounter.*

_source: TechRaptor TG12 guide, EN Fandom, NamuWiki mirror · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 3 sources]

- **Visual ID:** `sprites/owl.jpg` | Icon: `sprites/icons/T_Chicken.png` (internal: T_Chicken -- dev codename)
- **Class:** Ceiling-mounted/airborne laser turret-bot. Often spawns in groups of 3+; can respawn infinitely until the trigger source (e.g., Natasha) is killed.
- **Attacks:** Sustained laser beam (track movement or use cover) and rocket barrages. Knockdown is frequent.
- **Weaknesses:** Resistant to firearms ("Body Armor" NG+ aura); use Shok, energy weapons, or melee where possible. Pop them in the air with Polymer Jet + KS-23.
- **Drops:** Superconductor (rare), Microelectronics (rare).

> **Cross-system dependency** — see `dependencies.md` DEP-018: LUC-1 Owls respawn infinitely until Natasha is killed — focus Natasha first; Owls clear themselves. Applies at Theater Stage (Ch.4) and TG12 (Ch.5).

---

## GMC-69 Vatrushka (VShK-69 Vatrushka)
*Mid-game onward; mobile turret deployments in indoor and open-world combat.*

_source: High Ground Gaming, EN Fandom, NamuWiki · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 3 sources]

- **Visual ID:** `sprites/vatrushka.jpg` | Icon: `sprites/icons/T_Vatrushka.png` | Three color variants (shooting / flamethrower / laser)
- **Class:** Fast wheeled/mobile turret. Repositions, deploys, fires sustained gunfire, repeats.
- **Attacks:** Sustained fire while planted; brief unprotected period during repositioning.
- **Weaknesses:** Relatively low HP. Shok stuns instantly. Hit during reposition.
- **Drops:** Metal Parts, Synthetic Material; rarely Microelectronics.

---

## DOC
*Pavlov Complex and later linear sections; uncommon.*

_source: High Ground Gaming, EN Fandom, NamuWiki · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 3 sources]

- **Visual ID:** `sprites/doc.jpg` | Icon: `sprites/icons/T_Medic.png` (internal: T_Medic)
- **Class:** Mobile medical unit; melee bruiser — does NOT heal anything.
- **Attacks:** Charged melee with a drill/syringe arm; closes distance steadily.
- **Weaknesses:** **Frostbite locks down its charged attacks completely** (HighGroundGaming-recommended tactic). Listed under "Body Armor" NG+ aura — avoid relying on firearms.
- **Drops:** Energy Module (rare), Superconductor (rare).

---

## WSP-9 Pchela (Pchala — repair/security drone)
*Open-world Solnechnaya, all complexes — nests are persistent infinite-respawn sources.*

_source: EN Fandom, High Ground Gaming · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 2 sources]

- **Visual ID:** `sprites/pchela.jpg` | Icon: `sprites/icons/T_Bee.png` (internal: T_Bee)
- **Class:** Small flying rotor-drone. Two roles: security swarm + **robot repair**.
- **Attacks:** Light melee buzz/sting; some carry small cameras that can re-trigger the Hawk-relay alarm.
- **Weaknesses:** 1-2 hits from anything. Shok with chain-lightning clears swarms instantly.
- **Drops:** Metal Parts, Synthetic Material (small amounts).
- **Quirk:** **Repair Pchelas will resurrect downed robots in seconds.** Always destroy the Pchela nest or disable the Hawk relay before farming repeat kills — otherwise the farm becomes a damage sink. Core mechanic behind the Vova-cluster farm.

> **Cross-system dependency** -- see `dependencies.md` DEP-022: Pchela repairing a destroyed Dandelion camera is the reset mechanism for the camera-kill farming loop in `items/crafting_materials.md`. HAWK relay must stay active (not overloaded) for this loop to function.

---

## Dandelion (Security Camera)
*Open-world hubs and complex interiors.*

_source: GamePretty Polygons Guide, High Ground Gaming · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 2 sources]

- **Visual ID:** `sprites/dandelion_camera.jpg` | No InfoIcon (stationary object, not an AI enemy)
- **Class:** Stationary surveillance camera on a stalk. Triggers Hawk-relay alarms that spawn reinforcements.
- **Interaction:** Hackable through their linked Terminal — required to open Testing Ground entrances. Use scanner to trace the line from a Dandelion to its terminal.
- **Weaknesses:** Single Shok pulse disables temporarily; physical destruction is permanent until a Pchela repairs it. Disabling the Hawk relay disables ALL Dandelions in the ecosystem at once.
- **Drops:** Negligible.

---

## Mother (Sprout Nest)
*Indoor mutant zones — Pavlov, Algae/Pesticide Workshops, VDNH interiors.*

_source: High Ground Gaming · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Single source — verify]

- **Visual ID:** `sprites/mother.jpg` | Icon: `sprites/icons/T_Mutant.png` (naming quirk -- nest uses "Mutant" icon internally) | Backup: `sprites/mother_2.jpg`
- **Class:** Organic nest — stationary, circular plant. Spawns Sprouts continuously.
- **Attacks:** None directly; passive spawner.
- **Weaknesses:** Very low HP; any weapon kills it in 1-2 hits. **Scan rooms for Mothers FIRST** — kill them before engaging mutants, otherwise Sprouts keep reanimating any corpse.
- **Drops:** Biomaterials.

> **Cross-system dependency** — see `dependencies.md` DEP-019: Kill Mothers first, then Sprouts, then Mutants — Sprouts reanimate corpses until Mothers are gone.

---

## MTU-7 Bumblebee
*Open-world only (no interior spawns observed).*

_source: High Ground Gaming · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Single source — verify]

- **Visual ID:** `sprites/bumblebee.jpg` | Icon: `sprites/icons/T_Rosa.png` (internal: T_Rosa -- dev codename)
- **Class:** Tanky industrial-construction robot.
- **Attacks:** Volleys of 3 explosive shots. After 3 shots it must vent — body opens revealing yellow/orange heat core, the exposed weak point.
- **Weaknesses:** Open fire during the vent window. Kalash bursts to the core, Fat Boy if grouped with other bots.
- **Drops:** Metal Parts, Synthetic Material.

---

## Drofa
*Open-world, airborne cargo-class drone; mid-to-late game.*

_source: High Ground Gaming · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Single source — verify]

- **Visual ID:** `sprites/drofa.jpg` | Icon: `sprites/icons/T_Drofa.png`
- **Class:** Sleek flying drone, often in small groups.
- **Attacks:** Explosive rocket volleys; agile evasion.
- **Weaknesses:** Fully upgraded Shok with chain damage shreds them; Electro is also strong.
- **Drops:** Metal Parts, Microelectronics (rare).

---

## DLC — Annihilation Instinct

### BEA-D (base unit)
*Mendeleev Complex — DLC only.*

_source: EN Fandom BEA-D page, Steam DLC 100% guide 3020368999, GamingBolt DLC review · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Annihilation Instinct_
[Confirmed: 3 sources]

- **Class:** Magnetic-walker transport robot. Cylindrical cargo container with spherical control unit and hinged bipedal magnetic chassis.
- **Fusing mechanic:** BEA-Ds combine into multi-unit forms dynamically:
  - **"Mantis"** — 2-unit assembly; higher speed; jumping strikes and ram attacks; upper segment lasers.
  - **"Centaur"** — 3-unit assembly; slower but stronger; enhanced laser salvos + electrical-mine capsules that explode on approach; sweeping "tail" attack.
- **Attacks (single):** Quick melee; weak ranged shocks from spherical head.
- **Weaknesses:** **Secateur Energy Wave separates fused BEA-Ds in one shot** — basis of "Divide et Impera" achievement. Once split, individual BEA-Ds are fragile. Klusha melee handles singles; light attacks lack stagger so commit to charged swings.
- **Drops:** Energy Modules.
- **Quirk:** "Ostrich" variant carries Energy Modules needed to fully upgrade Klusha and Secateur. [Single source — verify in-game by reading BEA-D tooltips after scan.]

> **Cross-system dependency** — see `dependencies.md` DEP-021: Farm ostrich BEA-Ds for Energy Modules before DLC completion — "Maximum Strength" requires both DLC weapons fully upgraded.

---

### M4D-5 Dummy X (Mads)
*Mendeleev Complex — DLC only. Controlled by Baba Zina.*

_source: EN Fandom M4D-5 page, Steam DLC 100% guide 3020368999 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Annihilation Instinct_
[Confirmed: 2 sources]

- **Class:** Humanoid combat robot disguised as testing-dummy mannequins.
- **Attacks:** Stand still in dummy form until detecting P-3, then move quickly. Punch and kick combos with stretching/extending limbs. Will hop on one foot — interruptible animation; basis for **"John Silver's Crew"** achievement (kill 3 M4D-5s while they're hopping on one foot).
- **Weaknesses:** A strong charged blow shatters them but **the body can reassemble** — finish the kill before they reform. **Klusha light attacks do NOT stagger them** — commit to charged swings or Secateur burst-fire. Techno-Stasis freeze + charged melee is effective.
- **Drops:** Metal Parts, Synthetic Material.
- **Quirk:** Static dummies in the Mendeleev hotel area are easy to mistake for set dressing — scan rooms before relaxing.

---

### Strekoza (Dragonfly)
*Mendeleev Complex — DLC only. Flying/airborne unit.*

_source: Steam DLC 100% guide 3020368999 (achievement "Lord of the Flies") · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Annihilation Instinct_
[Single source — verify on first DLC run]

- Flying/airborne unit in Annihilation Instinct. Referenced by the **"Lord of the Flies"** achievement (use a Strekoza for the first time). Full attack profile and weaknesses not documented in surveyed text-form sources; confirm on first DLC run.

---

### Talking Goose
*DLC open world — flavor event, not a standard enemy.*

_source: GamingBolt DLC review · capture: web_fetch · confidence: low · enemy-tier: 0 · puzzle-tier: 0 · category: easter-egg · spoiler: dlc:Annihilation Instinct_
[Single source — verify]

- Recurring world-event creature that randomly attacks P-3 then leaves; explained in an in-game terminal. Not a combat-mechanical encounter in any standardized sense.

---

## Visual reference appendix

### FModel icon extraction

Icons in `sprites/icons/` are game-extracted PNGs. To reproduce: install [FModel](https://fmodel.app/) (.NET 10 required); add game directory `E:\SteamLibrary\steamapps\common\Atomic Heart`, set UE version to 4.27; search for `InfoIcons`; navigate to `AtomicHeart/Content/Development/UI/Textures/AI/InfoIcons/`; select all, right-click → Save Textures. Exports to FModel's `Output/Exports/` folder. Copy the 19 PNGs into `sprites/icons/`.

### Icon file mapping

| Icon file | Enemy | Internal name note |
|---|---|---|
| `sprites/icons/T_Vov.png` | Lab Tech (white/melee) | VOV-A6 base |
| `sprites/icons/T_BlackVov.png` | Lab Tech (black/laser) | Color variant |
| `sprites/icons/T_ShieldVov.png` | Lab Tech (shield) | Variant |
| `sprites/icons/T_Bee.png` | Pchela (WSP-9) | "Bee" = pchela |
| `sprites/icons/T_Raf.png` | Engineer (RAF-9) | Model number |
| `sprites/icons/T_Vatrushka.png` | Vatrushka | Direct |
| `sprites/icons/T_Rosa.png` | Bumblebee (MTU-7) | Dev codename |
| `sprites/icons/T_Chicken.png` | Owl (LUC-1) | Dev codename |
| `sprites/icons/T_Medic.png` | Doc (MED-6) | Role-based |
| `sprites/icons/T_Rotorobot.png` | Rotorobot (ARU-31/6) | Direct |
| `sprites/icons/T_Drofa.png` | Drofa (MUC-1) | Direct |
| `sprites/icons/T_Pobeg.png` | Sprout | "Побег" = sprout (RU) |
| `sprites/icons/T_Mutant.png` | Mother | Naming quirk -- nest uses "Mutant" icon |
| `sprites/icons/T_Nurse.png` | Mutant | Sprout-inhabited corpse |
| `sprites/icons/T_BigMutant.png` | Mutant (large) | Size variant |
| `sprites/icons/T_Belyash.png` | Belyash (MA-9) | Direct |
| `sprites/icons/T_Ejiha.png` | Hedgie (HOG-7) | "Ёж" = hedgehog (RU) |
| `sprites/icons/T_Natasha.png` | Natasha (NA-T256) | Direct |
| `sprites/icons/T_Plyush.png` | Plyusch | Direct |

**Not in InfoIcons set:** Dewdrop, Twins, Laborer (Vova), Dandelion Camera -- check DLC paks or alternative icon folders.

### Backup web-source images

Some enemies have a second web-sourced image: `sprites/belyash_2.jpg`, `sprites/mutant_2.jpg`, `sprites/natasha_2.jpg`, `sprites/rotorobot_2.jpg`, `sprites/mother_2.jpg`.

> **No `lab_tech_2` backup image (2026-07-29).** The fetch attempted for it landed on a dead link: the saved file was a 243KB HTML "Page not found" error page from `guided.news` with a `.jpg` extension, not an image, so it was removed. The primary `sprites/lab_tech.jpg` is a valid JPEG and is unaffected. Do not "restore" this file from the original source -- the link is gone. Re-source from a live page if a second Lab Tech image is ever wanted.

### Material drop quick-reference

| Material | Kill these enemies |
|---|---|
| Metal Parts | Lab Tech, Laborer, Pchela, Engineer, Vatrushka, Bumblebee, Owl, Doc, Rotorobot, Drofa |
| Synthetic Materials | Any robot enemy; also chests |
| Biomaterials | Sprout, Mother, Mutant, Plyusch |
| Chemicals | Sprout, Mother, Mutant |
| Polymer Jelly | Bosses (Belyash, Hedgie, Natasha, Plyusch, Dewdrop, Twins) |
| Neuropolymer | All enemies (universal) |
| Specific named materials (Energy Module, etc.) | Verify in-game -- screenshot the crafting screen for cross-reference |

_source: web images + FModel extracts 2026-05-13; merged from sprites/index.md per zipper 2026-05-22_
_material drops: items/crafting_materials.md (P1 research) + live observations_
