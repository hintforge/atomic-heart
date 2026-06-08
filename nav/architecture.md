# Atomic Heart — Zone Architecture

**status:** research-integrated
**last_reconciled:** 2026-05-08
**research_run:** P1 (Compass/Deep Research 2026-05-08)

> Cross-zone structural primitives. The persona reads this file for all cross-zone reasoning: lookahead PoNR warnings, backtrack queries, reachability checks, locks-and-keys. Per-zone gate lists live in `nav/<zone>.md` and reference this file's graph by edge ID. Drift between this file and per-zone files is a bug; run a consistency pass after each ingestion.

---

## Hintforge manifest

corpus-core-version: 5
game-version: "1.16.3.0 (build 23005793)"
game-version-platform: "PC / Steam"
game-version-as-of: 2026-05-27
vector-extensions: puzzles, npcs, optional_zones, testing_grounds

## Vector extensions

- `puzzles/` -- discrete puzzle files with hint ladders, indexed by `puzzles/index.md`
- `npcs/` -- named enemy and entity files indexed by `npcs/index.md` (renamed from `enemies/` at v5 migration 2026-05-22; all content carries `entity-status: hostile` at first touch)
- `optional_zones/` -- side content keyed to parent zone IDs from the zone graph
- `testing_grounds/` -- per-Testing-Ground reference content keyed to TG-N IDs (folder reserved; per-TG content currently distributed across `nav/`, `npcs/`, `items/`, `puzzles/`)

---

## Zone Graph

**Game-type label:** `hub-and-spoke-with-dungeons`
The story alternates between two open-world hub zones and scripted indoor "Complex" dungeons. Optional Testing Grounds are 8 underground bunkers reached from the open world. Mainstream English guides label it "open world" but the open world only navigates between two story arcs; it's a hub-spoke wrapper around heavily linear dungeons.
_source: Compass/Deep Research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

**Localization-mechanism class:** `hybrid`
Open-world zones use a map system (map button; markers for Testing Grounds, complexes, towers, NORA stations, vehicles). Indoor Complexes and Testing Grounds use landmark navigation only — no map, only objective markers (yellow icon), corridor signage, and Charles voice prompts. Exception: custom map markers cannot be placed in open-world zones. Patch 1.14.x added "Highlight Interactive Objects" option overlaying gold/yellow tints on collectibles.
_source: Compass/Deep Research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

**Entry node:** `chelomey_city_prologue`
**Hub nodes:** `vavilov_birch_distribution_hall`, `granny_zina_hut`, `forester_open_world`, `solnechnaya_open_world`
**Source-language set:** Russian (developer) · English, German, French (top player regions) · Korean (supplementary)

---

### Nodes

| Zone ID | Canonical Name | Aliases (RU / community) | Type | Chapter |
|---|---|---|---|---|
| chelomey_city_prologue | Chelomey City (prologue) | Челомей; Icarus flying platform | indoor-branching | Prologue |
| sechenov_office_prologue | Sechenov's Office (prologue) | Кабинет Сеченова | cutscene-only | Prologue |
| vavilov_entry_road | Vavilov Entry Road | Дорога ко входу | indoor-linear | Ch.1 |
| vavilov_maglev_station_solnechnaya_int | Vavilov Internal Maglev Station | "Solnechnaya" maglev (interior) — **not** the open-world Solnechnaya | indoor-branching | Ch.1 |
| vavilov_maglev_tunnels | Maglev Tunnels | Тоннели маглева | indoor-linear | Ch.1 |
| vavilov_cable_cars | Cable Cars | Канатная дорога | indoor-linear | Ch.1 |
| vavilov_seed_bank | Seed Bank | Семенохранилище | indoor-branching | Ch.1 |
| vavilov_hot_workshop | Hot Workshop / Thermarium | Горячий цех / Термариум | indoor-branching | Ch.1 |
| vavilov_algae_workshop | Algae Workshop | Цех водорослей | indoor-branching | Ch.1 |
| vavilov_pesticide_workshop | Pesticide Workshop | Цех пестицидов | indoor-branching | Ch.1 |
| vavilov_cold_workshop | Cold Workshop | Холодный цех | indoor-branching | Ch.1 |
| vavilov_birch_distribution_hall | Birch Tree Distribution Hall | Распределительный зал берёзы | hub | Ch.1 |
| forester_open_world | Forester Village open world | Посёлок Лесничего; SDC-2 zone | open-world | Ch.2 |
| granny_zina_hut | Granny Zina's Walking Hut | Изба Бабы Зины | hub | Ch.2 |
| sdc2_volan_tower | SDC-2 Volan Tower | Башня "Волан" SDC-2 | indoor-linear | Ch.2 |
| lesnaya_maglev_station | Lesnaya Maglev Station | Лесная (станция маглева) | indoor-linear | Ch.2 |
| solnechnaya_open_world | Solnechnaya open world | "Open World 2" / Солнечная | open-world | Ch.3 |
| kollektiv_village | Kollektiv Complex Village | Деревня "Коллектив" | open-world (sub) | Ch.3 |
| boat_station_lake | Boat Station / Lake area | Лодочная станция | open-world (sub) | Ch.3 |
| arena_park | Arena Park | Парк-арена ВДНХ | indoor-linear | Ch.3 |
| vdnh_atrium | VDNH Atrium | Атриум ВДНХ | indoor-branching | Ch.3 |
| vdnh_chelomey_floor | VDNH Chelomey Floor | Этаж Челомея | indoor-linear | Ch.3 |
| vdnh_vavilov_floor | VDNH Vavilov Floor | Этаж Вавилова | indoor-linear | Ch.3 |
| vdnh_pavlov_floor | VDNH Pavlov Floor | Этаж Павлова | indoor-linear | Ch.3 |
| vdnh_sakhalin_floor | VDNH Sakhalin Floor | Этаж Сахалина | indoor-linear | Ch.3 |
| magnetic_absorption_zone | Magnetic Absorption Zone | Зона магнитного поглощения | indoor-linear | Ch.3 |
| vdnh_drill_mode | VDNH Drill Mode | Режим "Учения" | indoor-linear | Ch.3 |
| sechenov_research_center_ext | Sechenov Research Center exterior | НИИ Сеченова (улица) | open-world (sub) | Ch.4 |
| sechenov_research_center_int | Sechenov Research Center interior | НИИ Сеченова (внутри) | indoor-branching | Ch.4 |
| lastochkin_theater_grounds | Theater grounds | Двор театра; Belyash arena | indoor-linear | Ch.4 |
| lastochkin_theater_int | Lastochkin / Plisetskaya Theater interior | Театр Ласточкина / Плисецкой | indoor-branching | Ch.4 |
| theater_control_room | Theater Control Room | Аппаратная театра | indoor-linear | Ch.4 |
| theater_stage | Theater Stage | Сцена театра | indoor-linear | Ch.4 |
| pavlov_bridge | Pavlov Bridge crossing | Мост к Павлову | indoor-linear | Ch.5 |
| pavlov_sanatorium | Pavlov Sanatorium | Санаторий | indoor-branching | Ch.5 |
| pavlov_hospital | Pavlov Hospital ward | Больница | indoor-branching | Ch.5 |
| pavlov_morgue | Pavlov Morgue (level 34) | Морг | indoor-branching | Ch.5 |
| pavlov_surgical_lab | Pavlov Surgical Lab | Хирургическая лаборатория | indoor-linear | Ch.5 |
| lighthouse_beach | Lighthouse Beach | Маяк / пляж | indoor-linear | Ch.6 |
| academy_underwater | Academy of Consequences (underwater) | Академия Последствий | indoor-linear | Ch.6 |
| academy_archive_room | Academy Archive Room | Архив (3 кинокатушки) | indoor-linear | Ch.6 |
| chelomey_revisit | Chelomey City (revisit, lobby) | Челомей (возврат) | indoor-linear | Ch.6 |
| sechenov_office_final | Sechenov's Office (Twins fight) | Финальный бой | indoor-linear | Ch.6 |
| testing_ground_1 | Testing Ground 1 | Полигон 1 (Solnechnaya, west of Monorail) | testing-ground | Ch.3 (hatch) |
| testing_ground_2 | Testing Ground 2 | Полигон 2 (near Boat Station sewer) | testing-ground | Ch.3 (hatch) |
| testing_ground_6 | Testing Ground 6 | Полигон 6 | testing-ground | Ch.3 (hatch) |
| testing_ground_8 | Testing Ground 8 | Полигон 8 (inside Sechenov Research Center area) | testing-ground | Ch.4 (hatch) — **MISSABLE** |
| testing_ground_9 | Testing Ground 9 | Полигон 9 (Kollektiv village) | testing-ground | Ch.3 (hatch) |
| testing_ground_10 | Testing Ground 10 | Полигон 10 | testing-ground | Ch.3 (hatch) |
| testing_ground_11 | Testing Ground 11 | Полигон 11 (Hawk-zipline + key disc) | testing-ground | Ch.3/4 (hatch) |
| testing_ground_12 | Testing Ground 12 | Полигон 12 (cave near hospital beach) | testing-ground | Ch.5 (hatch) — **MISSABLE** |

_source: Compass/Deep Research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
Note: Testing Ground numbers 3, 4, 5, 7 do not exist in the base game (confirmed cut content, 6 EN+RU sources).

---

### Edges

> **PoNR warning display rule:** Warn P-3 of any upcoming permanent PoNR when they are in the "From" zone. The Notes column may reference enemy names (enemy-tier: 1) — gate those details accordingly; PoNR warnings themselves are always-visible (enemy-tier: 0).

| ID | From | To | Type | Direction | Condition | PoNR | Notes |
|---|---|---|---|---|---|---|---|
| E01 | chelomey_city_prologue | sechenov_office_prologue | story-gate | one-way-forward | scripted | none | Linear cinematic |
| E02 | sechenov_office_prologue | vavilov_entry_road | story-gate | one-way-forward | flight cutscene | **PERMANENT** | Phone-booth achievement lost forever if not done in Prologue; cannot return to Chelomey until Ch.6 |
| E03 | vavilov_entry_road | vavilov_maglev_station_solnechnaya_int | story-gate | one-way-forward | clear road robots | none | |
| E04 | vavilov_maglev_station_solnechnaya_int | vavilov_maglev_tunnels | story-gate | one-way-forward | schematic lock + supply key | none | |
| E05 | vavilov_maglev_tunnels | vavilov_cable_cars | story-gate | one-way-forward | restart maglev (3-dot upside-down "C" code panel) | none | See `puzzles/combination_locks.md` |
| E06 | vavilov_cable_cars | vavilov_seed_bank | story-gate | one-way-forward | scripted drop | none | |
| E07 | vavilov_seed_bank | vavilov_birch_distribution_hall | hub-spoke | bidirectional | candles inserted | none | Birch hall is the Ch.1 mini-hub |
| E08 | vavilov_birch_distribution_hall | vavilov_hot_workshop | hub-spoke | bidirectional | none | none | |
| E09 | vavilov_hot_workshop | vavilov_algae_workshop | story-gate | bidirectional | shared corridor | none | |
| E10 | vavilov_birch_distribution_hall | vavilov_pesticide_workshop | hub-spoke | bidirectional | first 2 canisters returned | none | |
| E11 | vavilov_pesticide_workshop | vavilov_cold_workshop | story-gate | bidirectional | none | none | |
| E12 | vavilov_birch_distribution_hall | forester_open_world | story-gate | one-way-forward | 4 canisters; Charles warns of PoNR; elevator | **PERMANENT** | All Vavilov chirpers / blueprints / talking-deads locked forever once elevator taken |
| E13 | forester_open_world | granny_zina_hut | hub-spoke | bidirectional | scripted call after 1st Volan attempt | none | |
| E14 | forester_open_world | sdc2_volan_tower | hub-spoke | bidirectional | none | none | |
| E15 | forester_open_world | lesnaya_maglev_station | story-gate | one-way-forward | open village gate via Volan; valid train ticket | **PERMANENT** | Forester open world locked; train ticket on post-office rooftop corpse (climb via polymer) |
| E16 | solnechnaya_open_world | testing_ground_1 | optional | bidirectional | hack Volan camera (white spiral-staircase tower) toward blue-roof bunker hatch | none | Always-available; post-game free roam also works |
| E17 | lesnaya_maglev_station | solnechnaya_open_world | one-way | one-way-forward | Hedgehog ambush cutscene (train crash) | **PERMANENT** | Cannot revisit Forester or Vavilov after this point |
| E18 | solnechnaya_open_world | kollektiv_village | hub-spoke | bidirectional | none | none | |
| E19 | solnechnaya_open_world | boat_station_lake | hub-spoke | bidirectional | none | none | |
| E20 | solnechnaya_open_world | arena_park | story-gate | one-way-forward | hack lake Hawk relay → ride lowered HAWK pole → zipline | none | |
| E21 | arena_park | vdnh_atrium | story-gate | one-way-forward | boss fight completion | **chapter-bound** | VDNH building interior locks after Ch.3 escape; see E26 |
| E22 | vdnh_atrium | vdnh_chelomey_floor | hub-spoke | one-way-forward | Darwin Test (radio + hammer + plant) + Claire assembled | none | See `puzzles/combination_locks.md` for Darwin Test |
| E23 | vdnh_chelomey_floor | vdnh_vavilov_floor | story-gate | one-way-forward | scripted | none | |
| E24 | vdnh_vavilov_floor | vdnh_pavlov_floor | story-gate | one-way-forward | scripted | none | |
| E25 | vdnh_pavlov_floor | vdnh_sakhalin_floor | story-gate | one-way-forward | scripted | none | |
| E26 | vdnh_sakhalin_floor | magnetic_absorption_zone | story-gate | one-way-forward | scripted | none | |
| E27 | magnetic_absorption_zone | vdnh_drill_mode | story-gate | one-way-forward | scripted | none | |
| E28 | vdnh_drill_mode | solnechnaya_open_world | story-gate | one-way-forward | escape after boss + dream sequences | **PERMANENT** (for VDNH building) | VDNH building interior permanently locked; Solnechnaya open world remains free |
| E29 | solnechnaya_open_world | testing_ground_2 | optional | bidirectional | sewer pipe entry near Boat Station | none | |
| E30 | solnechnaya_open_world | testing_ground_6 | optional | bidirectional | Volan camera hack | none | |
| E31 | solnechnaya_open_world | testing_ground_9 | optional | bidirectional | clear sprout infestation (4 sewer boilers via manhole) → HAWK reactivates → camera hijack reveals Lenin-statue shack | none | |
| E32 | solnechnaya_open_world | testing_ground_10 | optional | bidirectional | Volan hack | none | |
| E33 | solnechnaya_open_world | sechenov_research_center_ext | story-gate | one-way-forward | quest "Red Arrow" | none | |
| E34 | sechenov_research_center_ext | sechenov_research_center_int | story-gate | one-way-forward | rooftop key | none | |
| E35 | sechenov_research_center_int | lastochkin_theater_grounds | story-gate | one-way-forward | Petrov flees | none | |
| E36 | lastochkin_theater_grounds | lastochkin_theater_int | story-gate | one-way-forward | defeat boss on theater grounds | **chapter-bound** | No return to Sechenov Research Center interior once theater entered |
| E37 | lastochkin_theater_int | theater_control_room | optional | bidirectional | Light-Lock door code (see `puzzles/combination_locks.md`) | none | |
| E38 | lastochkin_theater_int | theater_stage | story-gate | one-way-forward | scripted | none | |
| E39 | theater_stage | solnechnaya_open_world | story-gate | one-way-forward | defeat Natasha + collect Petrov's head | **PERMANENT** | Sechenov Research Center, Theater interior, Theater Control Room locked; TG8 becomes inaccessible |
| E40 | sechenov_research_center_int | testing_ground_8 | optional | bidirectional | three Volan cameras (front-of-road / right of building / rooftop) | none | **MISSABLE** — only reachable while Sechenov Research Center is active (before E36/E39). **E35 ("Petrov flees") does NOT close TG8** — confirmed live 2026-05-12; lockout is E36 (Theater interior entry), not E35. |

> **Cross-system dependency** — see `dependencies.md` DEP-002: E36 (Theater interior entry) permanently locks TG8 (via E40). TG8 gold/silver/bronze chests contain Fox blade, Zvezdochka lower blade, Swede extension, Dominator Vortex Transducer, MP Revolver-Type Bolt Frame — 5 weapon mods permanently missed after E36. Window extends into Ch.5 (E35 "Petrov flees" does NOT close TG8 -- confirmed live 2026-05-12).
| E41 | solnechnaya_open_world | testing_ground_11 | optional | bidirectional | Hawk maintenance + key disc + lockpick cabin | none | Gated by Theater completion (bridge across street) |
| E42 | solnechnaya_open_world | pavlov_bridge | story-gate | one-way-forward | "Infirmary" quest → cross bridge | **PERMANENT** | No return to Solnechnaya open world once on Pavlov side |
| E43 | pavlov_bridge | pavlov_sanatorium | story-gate | one-way-forward | scripted | none | |
| E44 | pavlov_sanatorium | pavlov_hospital | story-gate | one-way-forward | scripted | none | |
| E45 | pavlov_hospital | pavlov_morgue | story-gate | one-way-forward | Blood Courier door (4-button code) → elevator floor 34 | **PERMANENT** | Hospital ward + 5-chest secret room locked above; see `puzzles/combination_locks.md` |
| E46 | pavlov_morgue | pavlov_surgical_lab | story-gate | one-way-forward | second combination puzzle | none | |
| E47 | pavlov_surgical_lab | testing_ground_12 | optional | bidirectional | beach cave entrance (energy barrier drops during Hospital quest) | none | **MISSABLE** — barrier only down during Ch.5 Hospital quest; lost once Lighthouse cutscene begins |
| E48 | pavlov_surgical_lab | lighthouse_beach | story-gate | one-way-forward | quest "Everything Illuminated" | **PERMANENT** | Final act begins — complete all Ch.5 content including TG12 before proceeding |

> **Cross-system dependency** — see `dependencies.md` DEP-003: E47/E48 lock TG12 (KS-23 Thermal Scope + Pashtet Polygon 12 mod permanently missed). DEP-001: E48 also ends the Pavlov Biomaterials farming window — sweep all Pavlov chests before E48. (Polymer Jelly / Neuropolymer is NOT scarce post-Pavlov -- drops from nearly all enemies throughout the game.)
| E49 | lighthouse_beach | academy_underwater | story-gate | one-way-forward | defeat Dewdrop boss + sit on TV chair in lighthouse | **PERMANENT** | |
| E50 | academy_underwater | academy_archive_room | story-gate | one-way-forward | meet Filatova | none | |
| E51 | academy_archive_room | chelomey_revisit | story-gate | one-way-forward | three film reels collected | **point-of-divergence** | Next dialogue is the ending split |
| E52a | chelomey_revisit | (walk-away ending) | story-gate | one-way-forward | Granny Zina dialogue option 1 | **PERMANENT (credits)** | "Joke/good" ending; does NOT unlock Murderous Beauty trophy |
| E52b | chelomey_revisit | sechenov_office_final | story-gate | one-way-forward | Granny Zina dialogue option 2 | **PERMANENT** | Canonical bad/main ending |
| E53 | sechenov_office_final | (kill-twins ending) | story-gate | one-way-forward | defeat Twins (Left + Right) | **PERMANENT (credits)** | Charles betrays P-3 |
| E54 | (post-credits) | solnechnaya_open_world | fast-travel | one-way-forward | patch 1.14.4.0 "Return to Facility 3826" menu option | none | Complexes locked; open world + Testing Grounds free-roamable |

_source: Compass/Deep Research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
Boss names in edge notes (E21, E28, E36, E38, E39) are enemy-tier: 1 — do not volunteer preemptively at enemy-tier: 0.

---

## Chapter ↔ Zone Mapping

| Chapter | Zone IDs | Notes |
|---|---|---|
| Prologue (Chelomey) | chelomey_city_prologue, sechenov_office_prologue | Combat-free. Only missable: phone-booth prank. |
| Ch.1 (Vavilov Complex) | vavilov_entry_road, vavilov_maglev_station_solnechnaya_int, vavilov_maglev_tunnels, vavilov_cable_cars, vavilov_seed_bank, vavilov_hot_workshop, vavilov_algae_workshop, vavilov_pesticide_workshop, vavilov_cold_workshop, vavilov_birch_distribution_hall | Hub is Birch Distribution Hall. Collect 4 canisters to exit. Massive missable cluster at exit elevator. |
| Ch.2 (Forester Village / SDC-2) | forester_open_world, granny_zina_hut, sdc2_volan_tower, lesnaya_maglev_station | First open world. Train ticket on post-office rooftop (not on lower-right corpse). |
| Ch.3 (VDNH / Solnechnaya) | solnechnaya_open_world, kollektiv_village, boat_station_lake, arena_park, vdnh_atrium, vdnh_chelomey_floor, vdnh_vavilov_floor, vdnh_pavlov_floor, vdnh_sakhalin_floor, magnetic_absorption_zone, vdnh_drill_mode, testing_ground_1, testing_ground_2, testing_ground_6, testing_ground_9, testing_ground_10 | Second open world. 5 of 8 TGs here. VDNH building is a multi-floor museum. |
| Ch.4 (Sechenov Center & Theater) | sechenov_research_center_ext, sechenov_research_center_int, lastochkin_theater_grounds, lastochkin_theater_int, theater_control_room, theater_stage, testing_ground_8, testing_ground_11 | TG8 MISSABLE — only while Sechenov Research Center is active. TG11 post-Theater. |
| Ch.5 (Pavlov Complex) | pavlov_bridge, pavlov_sanatorium, pavlov_hospital, pavlov_morgue, pavlov_surgical_lab, testing_ground_12 | TG12 MISSABLE — barrier only during Hospital quest. Final act begins at Lighthouse. |
| Ch.6 (Academy of Consequences) | lighthouse_beach, academy_underwater, academy_archive_room, chelomey_revisit, sechenov_office_final | Point of divergence at Chelomey revisit dialogue. |

_source: Compass/Deep Research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

---

## Optional Content Registry

| Content | Type | Parent Zone | Unlock Condition | Access Window | Rec. Chapter | Failure Mode |
|---|---|---|---|---|---|---|
| Testing Ground 1 | TG dungeon | forester_open_world | Volan camera hack → hatch | Ch.2 onward (post-game free roam works) | Ch.2 | always-available |
| Testing Ground 2 | TG dungeon | solnechnaya_open_world | swim/climb sewer near Boat Station | Ch.3 onward | Ch.3 | always-available |
| Testing Ground 6 | TG dungeon | solnechnaya_open_world | Volan camera hack | Ch.3 onward | Ch.3 | always-available |
| Testing Ground 8 | TG dungeon | sechenov_research_center_ext | three Volan cameras | **Ch.4 only** — before E36 (Theater interior entry); window extends into Ch.5 if Theater interior not yet entered | Ch.4 | **missable** |
| Testing Ground 9 | TG dungeon | kollektiv_village | refuel Hawk + roof statue button | Ch.3 onward | Ch.3 | always-available |
| Testing Ground 10 | TG dungeon | solnechnaya_open_world | Volan hack | Ch.3 onward | Ch.3 | always-available |
| Testing Ground 11 | TG dungeon | solnechnaya_open_world | Hawk maintenance + key disc | Ch.3/4 (post-Theater) | post-Theater Ch.4 | always-available |
| Testing Ground 12 | TG dungeon | pavlov_surgical_lab beach cave | energy barrier drops during Hospital quest | **Ch.5 only** — before E48 (Lighthouse) | Ch.5 | **missable** |
| 72 Chirpers (Burning Ears) | collectible | every chapter | scan / pickup | per zone — clean before PoNR | per zone | **missable** in Vavilov / Forester / VDNH building / Theater / Pavlov; open-world chirpers always-available |
| 53 Talking Deads (Necromancer) | collectible | every chapter | scan + interact | per zone — clean before PoNR | per zone | **missable** same windows as Chirpers |
| 38 enemy scans (Scanner) | collectible | various | scan before kill | per encounter | scan all bosses | **missable** if boss dies unscanned; Twins require individual scans (Left + Right) |
| 12 weapons crafted (Lord of War) | crafting | NORA stations | craft each once | any chapter | by Ch.6 | always-available (with materials) |
| 24 Lootyagins (3 per TG) | chest | each TG interior | open all bronze/silver/gold chests | with each TG | along with TG | partly missable (TG8 + TG12 missable) |
| 63 Blueprints | item | every chapter | chest pickup | per zone — clean before PoNR | per zone | **missable** (location-locked) |
| Phone-booth prank (How Can I Help You?) | achievement | chelomey_city_prologue | interact phone booth — fountain on embankment, turn from boat toward fountain | **Prologue only** — before E02 | Prologue | **missable** |
| Hedgie no-shot kill (Strike achievement) | boss tactic | arena_park | use Shok + statues only; do NOT fire weapons | first encounter only | Ch.3 | **missable** (enemy-tier: 1) |
| Belyash melee-only kill (Chop Chop Chop) | boss tactic | lastochkin_theater_grounds | melee weapon only | first encounter only | Ch.4 | **missable** (enemy-tier: 1) |
| 3 talking dead animals (Beast Friend) | collectible | open world | hen / cow / third by water near solar arrays | OW chapters (Ch.2–5) | by Ch.5 | always-available |
| Optional code-locked door (Pavlov) | puzzle | pavlov_complex | community-sourced code (not found in environment) | Ch.5 (before E48) | Ch.5 | **missable** |
| Train ticket pickup | nav item | forester_open_world | post-office rooftop corpse (climb via polymer at rear) | Ch.2 only | Ch.2 | story-required but easy to miss wrong ticket first |
| TG8 three-Volan unlock | nav/puzzle | sechenov_research_center_ext | three Volans during Bug in the System quest | Ch.4 — before E36 | Ch.4 | **missable** |
| Schematic lock (Zvezdochka blueprint) | puzzle | vdnh_atrium | blackboard solution | Ch.3 | Ch.3 | **missable** |

_source: Compass/Deep Research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
Items marked enemy-tier: 1 in the Failure Mode column should not be volunteered preemptively at enemy-tier: 0.

---

## Support Topology

_source: Compass/Deep Research 2026-05-08 (P2) · capture: web_fetch · confidence: per row · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: progression_

> NORA stations function as **save + crafting + Polymer-ability respec** terminals only. They are NOT fast-travel nodes. [C:5] Every zone's first NORA is flagged on zone entry regardless of spoiler tier — safety-critical. Public walkthroughs conflate "save room" (terminal only) with "NORA station" (terminal + crafting vendor). Entries marked [C:2] or [H] need capture-card verification.

### NORA Booth Locations

| Zone-id | Location description | Sequential gate | Confidence | Notes |
|---|---|---|---|---|
| chelomey_city_prologue | None | — | [C:3] | Cutscene-heavy prologue |
| sechenov_office_prologue | None | — | — | Cutscene-only zone |
| vavilov_entry_road | None | — | — | Open-air linear corridor |
| vavilov_maglev_station_solnechnaya_int | Second safe room past the polymer swim tunnel — red booth interior | Gate 6 (post-swim) | [C:5] | **First named NORA in the game** — unlocks Electro pistol blueprint |
| vavilov_maglev_tunnels | None reliably documented | — | [H — verify in-game] | |
| vavilov_cable_cars | Locked station safe room after the yellow-paint climb sequence | Gate 5 | [C:3] | Holds Fox blueprint |
| vavilov_seed_bank | (1) Lower-atrium safe room with EMP Generator blueprint; (2) upper catwalk safe room | Gates 2, 3 | [C:3] | Two NORAs in this zone |
| vavilov_hot_workshop | Entrance safe room ("red section") — Dynamo blueprint chest | Gate 2 | [C:3] | |
| vavilov_algae_workshop | Hallway safe room past the shattered observation window | Gate 3 | [C:2] | |
| vavilov_pesticide_workshop | Post-rail-puzzle safe room | Gate 4 | [C:2] | |
| vavilov_cold_workshop | Cold-section safe room — Adrenaline Canister blueprint | Gate 3 | [C:2] | |
| vavilov_birch_distribution_hall | Distribution-Hall NORA — between canister return runs | Gate 1–5 (hub) | [C:3] | Major hub NORA |
| forester_open_world | Multiple red-roof mushroom safe-room huts along main road — visible from a distance | Distributed | [C:3] | |
| granny_zina_hut | Inside the hut, beside Granny's seat/table area | Post-cutscene persistent | [C:4] [translated from: Russian] | **CONFIRMED** (sportskeeda, gamerjournalist, walkthroughs.games, itemlevel.net) |
| sdc2_volan_tower | None inside tower | — | [C:2] | Use nearby roadside hut |
| lesnaya_maglev_station | Station-platform safe room | Gate 5 | [C:2] | |
| testing_ground_1 | Mid-run safe room near the gold-reward chest | Between puzzles | [C:3] | |
| solnechnaya_open_world | Multiple roadside mushroom huts + landmark safe rooms | Distributed | [C:3] | |
| kollektiv_village | Village outskirts safe-room hut | — | [C:2] | |
| boat_station_lake | Dock safe room near the HAWK Relay | — | [C:2] | |
| arena_park | Outer save room before the transition gate | Pre-gate | [C:2] | _enemy-tier: 2 note: gate leads to HOG-7 boss arena_ |
| vdnh_atrium | Reception-area save room | Gate 2 | [C:3] | |
| vdnh_chelomey_floor | Floor-internal save room | Per floor | [C:2] | |
| vdnh_vavilov_floor | Floor-internal save room | Per floor | [C:2] | |
| vdnh_pavlov_floor | Save room before the lower exhibit section | Pre-lower-exhibit | [C:3] | _enemy-tier: 2 note: lower section contains Plyusch boss arena_ |
| vdnh_sakhalin_floor | Floor-internal save room | Per floor | [C:2] | |
| magnetic_absorption_zone | Save point between puzzle rooms — chest + floor switch present | Mid-zone | [C:2] | |
| vdnh_drill_mode | Save room after the snake-game sequence | Mid-zone | [C:2] | |
| testing_ground_2 | Mid-run safe room between magnetic puzzle rooms | Mid-zone | [C:2] | |
| testing_ground_6 | Save room near the silver-reward chest | Mid-zone | [C:3] | |
| testing_ground_8 | Multiple internal save rooms (distributed throughout) | Distributed | [C:3] | |
| testing_ground_9 | Save room near the silver-reward chest | Mid-zone | [C:2] | |
| testing_ground_10 | Pre-combat-room breakroom | Mid-zone | [C:2] | |
| testing_ground_11 | Save room after the bronze-reward chest | Mid-zone | [C:2] | |
| testing_ground_12 | Entry-cave NORA + multiple internal save rooms | Distributed | [C:3] | |
| sechenov_research_center_ext | None on roof | — | [C:2] | |
| sechenov_research_center_int | Entry foyer save room | Gate 1 | [C:2] | |
| lastochkin_theater_grounds | Walkway save-room/vending machine before the grounds gate | Pre-gate | [C:3] | _enemy-tier: 2 note: gate leads to Belyash boss_ |
| lastochkin_theater_int | Multiple — basement, post-elevator, bar break room | Distributed | [C:3] | |
| theater_control_room | None inside | — | [C:2] | Nearest NORA is the bar break room in lastochkin_theater_int |
| theater_stage | Save room immediately before the stage's final chamber | Pre-final-gate | [C:3] | _enemy-tier: 2 note: final chamber contains Natasha boss_ |
| pavlov_bridge | Bridge-end safe room | End | [C:2] | |
| pavlov_sanatorium | Foyer save room | Early | [C:2] | |
| pavlov_hospital | Multiple ward save rooms | Per floor | [C:2] | |
| pavlov_morgue | Save room before the second-floor combination puzzle | Mid-zone | [C:2] | |
| pavlov_surgical_lab | Pre-cutscene save room | Gate 3 | [C:2] | |
| lighthouse_beach | (1) Cliff-bunker save room before the large-creature encounter; (2) lighthouse-approach save room | Pre-encounter + pre-lighthouse | [C:2] | _enemy-tier: 2 note: encounter is Dewdrop boss_ |
| academy_underwater | Save room post-elevator, near the chair by the glass wall | Mid-zone | [C:2] | |
| academy_archive_room | Save room before the ending-choice sequence | End | [C:2] | _spoiler: story — gated until story opt-in_ |
| chelomey_revisit | Save room on the approach to the final arena | Pre-final | [C:3] | _enemy-tier: 2 note: arena contains Twins boss_ |
| sechenov_office_final | None | — | — | Cutscene/boss only |

### Fast-Travel Network

> **No in-game fast travel during normal play (pre-credits).** NORA stations are NOT fast-travel nodes — save + crafting + respec only. Vehicles (Moskvich cars) provide physical traversal in open-world zones only — not menu fast travel. [C:5]

| Node | Zone-id | Unlock condition | Notes |
|---|---|---|---|
| Return to Facility 3826 | solnechnaya_open_world (spawn point) | Beat the game (any ending), patch ≥1.14.4.0 | **Post-game only.** Complexes locked; open world + TGs free-roamable. Exact spawn point near open-world center — verify on patch 1.14.4.0. [C:5] |
| Vehicle network (Moskvich cars) | forester_open_world, solnechnaya_open_world | Zone open | Physical driving; cars respawn at parking spots. Not menu fast travel. [C:4] |
| HAWK rides | forester_open_world, solnechnaya_open_world | Hijack Volan/HAWK relay | Local short-hop only — not zone-to-zone transport. [C:3] |
| Maglev train (Lesnaya) | lesnaya_maglev_station | Story-gated | One-way story event — not repeatable or player-controlled. [C:5] |

_source: Compass/Deep Research 2026-05-08 (P2) · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

---

## Locks and Keys

_source: Compass/Deep Research 2026-05-08 (P2) · capture: web_fetch · confidence: per row · enemy-tier: 0 · puzzle-tier: 0 (lock/key locations) / 3 (solutions) · category: mainline · spoiler: progression_

> Lock locations and key locations are tier-0 navigation facts. **Codes and combination solutions are puzzle-tier 3** — stored in `../puzzles/combination_locks.md` and delivered only on explicit Lvl 3 request from P-3.

| Lock location (zone-id + feature) | Key required | Key source zone-id | Visible before key? | Confidence | Notes |
|---|---|---|---|---|---|
| vavilov_maglev_station_solnechnaya_int — Supply-Room door | Supply Room Key (physical) | vavilov_maglev_station_solnechnaya_int — Level-3 corridor corpse | Yes | [C:3] | Linear loop within same zone |
| vavilov_maglev_station_solnechnaya_int — Schematic Lock booth (E04/E05 gate) | Schematic note (disc pattern knowledge) | vavilov_maglev_tunnels — operator corpse in side niche | Yes | [C:5/2] | **One-time / not re-lockable** — lever pull permanently restores maglev power. Code → `../puzzles/combination_locks.md` |
| vavilov_birch_distribution_hall — East/West wing red doors | Two "candles" (cryo orbs) | vavilov_birch_distribution_hall — central pillar + corpse cell | Yes | [C:3] | Story gate; both candles required per wing pair |
| forester_open_world — Lesnaya Station road gate | Volan gate-override code (from Granny Zina cutscene) + camera hijack | granny_zina_hut | Yes | [C:5] | Story gate |
| lesnaya_maglev_station — Train conductor (E15) | Valid monthly pass (ticket item) | forester_open_world — **Telemail post office rooftop corpse** (two-story building with fire engine, south-southwest of Lesnaya; second-floor window → polymer swim up the pipe to roof) | Yes | [C:5/2] | **Lower-right statue-base corpse holds an EXPIRED ticket — conductor refuses.** [translated from: Russian, portalvirtualreality.ru, landofgames.ru, showgamer.com] |
| sechenov_research_center_int — Petrov cutscene door | Cookie Key disk | sechenov_research_center_ext — second roof, desk by a corpse | Yes | [C:4] | Plus lockpick mini-game after key insertion |
| testing_ground_11 — bunker outer door | Cylindrical Key Disk | solnechnaya_open_world — walled compound NW of TG11, accessed via HAWK zipline | Yes | [C:3] | Plus a separate combination lock on the bunker door |
| pavlov_hospital — Sister's Room (E45 Blood Courier 4-button door) | Combination code (knowledge — environmental hint on bottom floor) | pavlov_hospital — bottom-floor ward curtain-hole perspective | Yes | [C:6/2] | Optional reward room (5 chests) — not story-required. Code → `../puzzles/combination_locks.md` |
| pavlov_hospital — Surgical Lab keycard door | Surgical Lab keycard ("cookie key") | pavlov_hospital — Surgical Lab #1 locker, near the damaged MRI machine | Yes | [C:4/2] | Story-required |
| pavlov_morgue — Door 2 | Morgue Key Disk | pavlov_morgue — Room 1 cubby | Yes | [C:3] | Plus snap-puzzle on a separate door earlier in the same zone |
| pavlov_morgue — Second-floor exit | Combination puzzle (knowledge, environmental) | pavlov_morgue — environmental clues in zone | Yes | [C:3] | **NOT the morgue elevator** (elevator = simple "34" button). This is the second-floor exit gate. Code → `../puzzles/combination_locks.md` |
| testing_ground_2 — bunker outer door | Camera hijack (knowledge) | solnechnaya_open_world — nearby camera tower | Yes | [C:3] | |
| testing_ground_6 — drainage-pipe outer door | Camera hijack | boat_station_lake — camera tower across the water | Yes | [C:3] | |
| testing_ground_8 — research-center elevator | Three power generators activated via Volan cameras | sechenov_research_center_ext — roof Volan | Yes | [C:4] | |
| testing_ground_9 — Lenin-statue shack | HAWK reactivation (burn 4 sewer boilers) + camera hijack | kollektiv_village area | Yes | [C:4] | |
| testing_ground_10 — pigsty hatch | Camera hijack | solnechnaya_open_world | Yes | [C:3] | |
| theater_control_room — Engineer code door | Engineer's password (on paper near Engineer's body) | lastochkin_theater_int — Coat Check | Yes | [C:5] | Code → `../puzzles/combination_locks.md` |
| theater_stage — ballerina hall exit gate | Knowledge puzzle: pose 4 statues in specific ballet positions (shadow wall hint in corridor) | theater_stage corridor | Yes | [C:5] | Not item-keyed. Solution → `../puzzles/combination_locks.md` |

### E05 / E15 / E45 Verification (P2 confirmed)

- **E05 Maglev Tunnels restart panel:** Code = 3-dot upside-down "C" in upper-left disc quadrant. **One-time — not re-lockable** (lever pull permanently restores cable-car power). [C:5/2]
- **E15 Train ticket:** Telemail post office is in **forester_open_world** (two-story building with fire engine, south-southwest of Lesnaya along the main road). Rooftop corpse (via second-floor window + polymer swim) holds the **valid monthly pass**. Lower-right statue-base corpse holds an **expired ticket** the conductor refuses. [C:5/2] [translated from: Russian]
- **E45 Blood Courier door:** 4-button code in `../puzzles/combination_locks.md`. **No second 4-button code at the morgue elevator** — elevator = simple "34" button. The "second code" some players reference is the **morgue second-floor exit combination puzzle** — a separate, distinct gate in pavlov_morgue. [C:3]

_source: Compass/Deep Research 2026-05-08 (P2) · capture: web_fetch · confidence: per row · enemy-tier: 0 · puzzle-tier: 0 (locations) / 3 (solutions) · category: mainline · spoiler: progression_

---

## DLC Zone ID Registry

| DLC | Release | Zone-id range | Research phase |
|---|---|---|---|
| Annihilation Instinct | 2023-08-02 | dlc_aoi_* (10 playable zones + 1 cutscene-only — see §DLC — Annihilation Instinct below) | **P3 ingested 2026-05-09** |
| Trapped in Limbo | 2024-02-06 | limbo_hub, limbo_avenue_of_speed, limbo_plateau_of_responsibility, limbo_tower_of_memory, limbo_cliff_of_perseverance, limbo_goose_finale (6 zones) | **doctor ingested 2026-06-05 -- see §DLC -- Trapped in Limbo** |
| Enchantment Under the Sea | 2025-01-28 | neptune_sechenov_complex, neptune_chelomey_ruins, neptune_lakeshore, neptune_babazina_hut, neptune_entry_hub, neptune_flooded, neptune_depot, neptune_railway, neptune_statue, neptune_cafeteria_whale, neptune_zoology, neptune_quarters, neptune_dolphin_rooms, neptune_sub_bay, neptune_open_water, neptune_block_b, neptune_city_of_dolphins, neptune_final_arena (18 zones; prefix corrected from triton_complex_* to neptune_*) | **doctor ingested 2026-06-05 -- see §DLC -- Enchantment Under the Sea** |
| Blood on Crystal | 2026-04-16 | boc_orb_lab, boc_wave_platform, boc_submarine, boc_crystal_arrival, boc_crystal_archive, boc_crystal_recreation, boc_crystal_residential_1, boc_crystal_residential_2, boc_crystal_factory, boc_crystal_indoor_beach, boc_crystal_core (11 zones; final DLC) | **doctor ingested 2026-06-05 -- see §DLC -- Blood on Crystal** |

Note: Ch.3 contains narrative "Limbo dream sequences" — these are base-game content, NOT the Trapped in Limbo DLC. Easy to confuse.
_source: Compass/Deep Research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Annihilation Instinct_

---

## Current Patch

**1.16.3.0** (post-Apr 2026) — final base-game polish pass for "Blood on Crystal" DLC compatibility. Adds ray tracing (PC), accessibility options, post-game "Return to Facility 3826" free-roam mode (1.14.4.0), NG+ with colored-aura enemy modifiers (1.8.0.0). Pre-1.6 guides are unreliable for "Bug in the System" workarounds (now patched) and NG+ enemy behavior (didn't exist pre-1.8). See `../reference.md` §NG+ for aura-modifier table.
_source: dsogaming, mp1st, Steam patch notes, exputer, updatecrazy · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

---

## DLC Play Order and Narrative Structure

_source: r/atomicheart/comments/1tkw1i0 (score 122, 0.94 ratio; community consensus) · capture: manual_paste · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: story_

> **[Narrative structure below contains story-tier spoilers -- withheld at enemy-tier 0 / story-tier control; deliver only when player asks about DLC order or has completed the base game]**

**Recommended play order:** DLC 1 (Annihilation Instinct) → DLC 2 (Trapped in Limbo) → DLC 3 (Enchantment Under the Sea) → DLC 4 (Blood on Crystal).

**Narrative structure (story tier -- withheld by default):**
- DLC 1 connects to the base-game "leave" ending narrative branch.
- DLCs 2-4 form a connected trilogy tied to the base-game "fight" ending narrative branch.
- DLC 3 (EutS) continues directly from DLC 2 (TiL); DLC 4 (BoC) continues from both DLC 3 and DLC 1.
- Playing out of order is technically possible (each DLC uses an isolated save slot with preset loadout) but the narrative connections make the recommended order the intended experience.

**Community note on skipping:** DLC 2 (TiL) is commonly considered the weakest entry (platforming-heavy, near-zero combat) and some players skip it or watch on YouTube. DLC 3 continues its narrative, so skipping TiL means missing DLC 3 context. See `nav/trapped_in_limbo.md` for the TiL gameplay overview.

**Upgrade carry-over:** None. Each DLC starts with a preset developer-determined loadout. Base-game upgrades do not transfer. See `items/builds.md` DLC Loadout System section.

---

## DLC — Annihilation Instinct

> **See also:** [`mendeleev_complex.md`](mendeleev_complex.md) — consolidated DLC zone gate list (added 2026-05-09 convergence). Per-DLC-node detail is below; the consolidated file covers the whole DLC as a single linear zone with sequential gates, NORA stations, and missables, useful as a play-time reference. The two views are redundant by design.

**Access:** Main Menu → New Game → "Annihilation Instinct: Play" → difficulty. No base-game save needed; fully isolated save slot. DLC does **not** modify the base-game zone graph; DLC inventory cannot be transferred in either direction; DLC NORA stations are isolated from the base-game fast-travel network.

_source: Compass/Deep Research 2026-05-09 (P3) · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:annihilation-instinct_

> Note on naming: in Russian, NORA = Элеонора (Eleanor). English releases retained "NORA" but some assets use "Eleanor." The DLC also canonizes the base-game "good" ending (refused Khraz / loyal to Sechenov). [translated from: Russian; spoiler: story · enemy-tier: 3]

### DLC Nodes

| Zone ID | Canonical Name | Aliases | Type |
|---|---|---|---|
| `dlc_aoi_intro_cinematic` | Intro / Refusal cinematic | "Eleanor's Cradle awakening" | cutscene-only |
| `dlc_aoi_lyogkaya_hotel` | Lyogkaya Hotel | Legkaya Hotel; "Light Inn"; гостиница «Лёгкая» | indoor-branching (geodesic dome with floating bungalows) |
| `dlc_aoi_flooded_village` | Flooded Village | Swamp; затопленная деревня; болота | open-world (semi-linear; flooded huts + farms) |
| `dlc_aoi_freedom_park` | Freedom Park | Park of Freedom; парк Свободы | indoor-branching |
| `dlc_aoi_greenhouse_sector` | Greenhouse Sector | teplichniy sektor | indoor-linear (combat arena before Lebedev) |
| `dlc_aoi_lebedev_lab` | Lebedev's Laboratory | Лаборатория Лебедева; "ORB lab" | hub (Eleanor station, phone booth to Sechenov, Strekoza takeoff) |
| `dlc_aoi_mendeleev_memorial` | Mendeleev Memorial | "Periodic Table plaza"; Мемориал Менделеева | hub (Strekoza platform; elevator to Mendeleev Complex) |
| `dlc_aoi_mendeleev_hangar` | Mendeleev Complex Hangar | aircraft hangar; ангар | indoor-linear (chests, Strekoza terminus, BEA-D loading bell) |
| `dlc_aoi_mendeleev_complex` | Mendeleev Complex (interior) | underground complex; комплекс Менделеев | indoor-branching (multi-floor labs, circular corridor, statue arena) |
| `dlc_aoi_radiochemical_lab` | Radiochemical Laboratory | radio-chemical labs; Радиохимическая лаборатория | indoor-linear (paired sub-labs with BEA-D containment puzzle) |
| `dlc_aoi_noras_cradle` | NORA's Cradle / NORA's Brain | "Eleanor's Heart" puzzle room; колыбель Элеоноры | indoor-linear (final puzzle + colossus arena) |

_source: Compass/Deep Research 2026-05-09 (P3) · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: dlc:annihilation-instinct_

### DLC Missions (Chapter ↔ Zone Mapping)

| Mission | RU | Sub-quests | Zones |
|---|---|---|---|
| Meddlesome Lady (intro) | Назойливая леди | escape hotel; rejoin glove; receive Klusha | `dlc_aoi_intro_cinematic` → `dlc_aoi_lyogkaya_hotel` |
| Surface Approach | Поверхностный метод | "Magnetokhod BUS-A"; "Scarlet Flower"; "Life is Like a Box of Chocolates" | `dlc_aoi_flooded_village` → `dlc_aoi_freedom_park` → `dlc_aoi_greenhouse_sector` → `dlc_aoi_lebedev_lab` → `dlc_aoi_mendeleev_memorial` |
| It's Complicated | Комплексный подход | "Divide Et Impera!"; collect 5 underground BEA-Ds | `dlc_aoi_mendeleev_hangar` → `dlc_aoi_mendeleev_complex` → `dlc_aoi_radiochemical_lab` → BEA-D Colossus (statue arena) |
| Desperate Measures / Eleanor's Heart | Отчаянные меры / Сердце Элеоноры | recombination puzzle; second BEA-D Colossus; ending | `dlc_aoi_lebedev_lab` (return) → `dlc_aoi_mendeleev_memorial` → `dlc_aoi_noras_cradle` |

_source: Compass/Deep Research 2026-05-09 (P3) · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 1 · category: mainline · spoiler: dlc:annihilation-instinct_
Sub-quest names that reveal story beats carry enemy-tier: 3 — gate accordingly.

### DLC Edges

| ID | From | To | Type | Direction | Condition | PoNR | Notes |
|---|---|---|---|---|---|---|---|
| DLC-E00 | MAIN MENU → New Game | `dlc_aoi_intro_cinematic` | menu | one-way | Select "Annihilation Instinct: Play" + difficulty | n/a | **DLC ENTRY POINT** — no base-game save needed; DLC ignores base-game progress [Confirmed: 4 sources, 2 languages] |
| DLC-E01 | `dlc_aoi_intro_cinematic` | `dlc_aoi_lyogkaya_hotel` | scripted | one-way | watch cutscene | yes (cinematic) | Eleanor turns off storm; bridges become controllable |
| DLC-E02 | `dlc_aoi_lyogkaya_hotel` | `dlc_aoi_flooded_village` | scripted | one-way | acquire Klusha from impaled robot at dome #34; exit through wall hole | **PERMANENT** | Hotel cannot be re-entered |
| DLC-E03 | `dlc_aoi_flooded_village` | `dlc_aoi_freedom_park` | linear | one-way | follow swamp route; survive M4D-5 mannequin waves | no | Goose first appears here; talking corpses |
| DLC-E04 | `dlc_aoi_freedom_park` | `dlc_aoi_greenhouse_sector` | linear | one-way | clear park dolls | no | First chirper-rich zone |
| DLC-E05 | `dlc_aoi_greenhouse_sector` | `dlc_aoi_lebedev_lab` | scripted | bidirectional (after Strekoza acquired) | clear arena; Lebedev opens elevator | no | Lebedev grants Secateur, Techno-Stasis, glove repair; first NORA station of DLC |
| DLC-E06 | `dlc_aoi_lebedev_lab` | `dlc_aoi_mendeleev_memorial` | scripted | bidirectional | take Strekoza | no | First Strekoza ride triggers "Lord of the Flies" achievement |
| DLC-E07 | `dlc_aoi_mendeleev_memorial` | `dlc_aoi_lebedev_lab` | fast-travel | bidirectional | Strekoza platform | no | DLC's only fast-travel pair; functions like base-game gondola |
| DLC-E08 | `dlc_aoi_mendeleev_memorial` | `dlc_aoi_mendeleev_hangar` | fast-travel/elevator | bidirectional | Strekoza platform + all 3 surface BEA-Ds fed to loading bell | no | Memorial platform also serves as hangar elevator |
| DLC-E09 | `dlc_aoi_mendeleev_hangar` | `dlc_aoi_mendeleev_complex` | linear | one-way (returns possible until story gate) | all 3 surface BEA-Ds delivered | partial | |
| DLC-E10 | `dlc_aoi_mendeleev_complex` | `dlc_aoi_radiochemical_lab` | linear | bidirectional within complex | follow markers; circular corridor | no | Paired-lab BEA-D containment puzzle |
| DLC-E11 | `dlc_aoi_mendeleev_complex` | `dlc_aoi_mendeleev_complex` (statue arena) | scripted | one-way per visit | activate statue | no | Enemy-tier: 1 — gate boss identity at tier 0 |
| DLC-E12 | `dlc_aoi_lebedev_lab` (return, after BEA-D #7) | `dlc_aoi_noras_cradle` | scripted | one-way | call Sechenov from phone booth; return to memorial; descend elevator | **PERMANENT — final PoNR** | Recombination puzzle; second boss encounter; ending cinematic; "Return to Utopia" achievement |

_source: Compass/Deep Research 2026-05-09 (P3) · capture: web_fetch · confidence: high · enemy-tier: 0 (PoNR facts and entry point) · puzzle-tier: 0 · category: mainline · spoiler: dlc:annihilation-instinct_
Boss identity in DLC-E11/E12: enemy-tier: 1 — do not name preemptively at enemy-tier: 0.

### DLC Support Topology (NORA Stations)

> DLC NORA stations are isolated from base-game NORA network. Inventory and crafting do not transfer across the DLC boundary in either direction.

| Zone | Location | Function |
|---|---|---|
| `dlc_aoi_lyogkaya_hotel` | Pre-glove room — "Eleanor mannequin without functions" | Dialogue only; non-functional until glove reattached |
| `dlc_aoi_lebedev_lab` | Lebedev's lab (after glove restored) | Full save + upgrade + craft — **first functional NORA of DLC** |
| `dlc_aoi_mendeleev_complex` (entrance) | Corridor after expanded-storage blueprint (post BEA-D #2) | Save + upgrade |
| `dlc_aoi_mendeleev_complex` (mid) | Side-room near statue arena entrance | Save + upgrade |
| `dlc_aoi_radiochemical_lab` | Right-hand branch before paired sub-labs | Save + upgrade |
| `dlc_aoi_mendeleev_complex` (post-statue) | After circular corridor near restroom hallway | Save + upgrade |
| `dlc_aoi_noras_cradle` approach | Pre-finale corridor (last station before final PoNR) | Save + upgrade |

_source: Compass/Deep Research 2026-05-09 (P3) · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:annihilation-instinct_
[Single-source-cluster — notesread.com + Steam Community guide; count ~6–7, approximate — verify on first run]

### DLC Fast-Travel (Strekoza)

| Node | Zone-id | Unlock condition | Notes |
|---|---|---|---|
| Strekoza (Freedom Park side) | `dlc_aoi_lebedev_lab` | Complete Greenhouse Sector arena; Lebedev grants access | Permanent unlock once granted |
| Strekoza (Memorial side) | `dlc_aoi_mendeleev_memorial` | Same as above | Bidirectional with Lebedev Lab |
| Strekoza (Hangar elevator) | `dlc_aoi_mendeleev_hangar` | Feed all 3 surface BEA-Ds to loading bell | Memorial platform doubles as hangar elevator |

_source: Compass/Deep Research 2026-05-09 (P3) · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:annihilation-instinct_

### DLC Optional Content Registry

| Content | Type | Parent zone(s) | Unlock condition | Access window | Rec. | Failure mode |
|---|---|---|---|---|---|---|
| Chirpers (10 total) | collectible | All DLC zones — esp. Freedom Park, Mendeleev Complex, Radiochemical Lab | scan/pickup | Until Eleanor's Heart PoNR | Gather as you go | Post-PoNR access lost |
| Alionka cards (5 total) | collectible | Lyogkaya, Swamp, Freedom Park, Mendeleev Complex, Radiochemical Lab | pickup | Until PoNR | Gather as you go | None |
| Klusha — Handle blueprint | weapon upgrade | **Flooded Village / Swamp** (before Lebedev — note: many EN video guides incorrectly say park area) | exploration | Until PoNR | Surface Approach | **MISSABLE** — required for "Maximum Strength" |
| Klusha — Blade blueprint | weapon upgrade | Mendeleev Complex (deeper rooms, post BEA-D #4) | exploration | Until PoNR | It's Complicated | **MISSABLE** — required for "Maximum Strength" |
| Klusha — Cartridge/extra mod | weapon upgrade | Mendeleev Complex Hangar (yellow chest in container) | exploration | Until PoNR | It's Complicated | **MISSABLE** |
| Secateur — Energy Supercharger blueprint | weapon upgrade | Mendeleev Complex (Eleanor side-room near 4th BEA-D) | exploration | Until PoNR | It's Complicated | **MISSABLE** |
| Secateur — Wide-Spread blueprint | weapon upgrade | Mendeleev Complex (chest near "Alenka" stand, circular corridor) | exploration | Until PoNR | It's Complicated | **MISSABLE** |
| Secateur — Extended Magazine blueprint | weapon upgrade | Mendeleev Complex (early corridor after first hangar return) | exploration | Until PoNR | It's Complicated | **MISSABLE** |
| Alionka consumable pickups (multiple) | consumable | Mendeleev Complex circular corridor + Radiochemical Lab + Hangar + Hotel intro | pickup | Until PoNR | Save 3+ for "Red October" | **"Red October" missable** if all consumed before 15 kills -- see `dependencies.md` DEP-024 |
| Strekoza first ride | achievement trigger | `dlc_aoi_lebedev_lab` → `dlc_aoi_mendeleev_memorial` | story-mandatory | One-time | — | Story-guaranteed; "Lord of the Flies" achievement |
| Talking corpses | lore | Swamp + Lyogkaya + Mendeleev Complex | scanner/interact | Until PoNR | Gather as you go | None |
| Talking Goose | recurring NPC | Swamp + Mendeleev Complex | proximity | Open | — | Flavor only |
| BEA-D Colossus 1st encounter | boss (enemy-tier: 1) | `dlc_aoi_mendeleev_complex` (statue arena) | activate statue | Mandatory | It's Complicated | Story-guaranteed |

_source: Compass/Deep Research 2026-05-09 (P3) · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:annihilation-instinct_
[Confirmed: 4+ sources for collectible counts: PSNProfiles, Steam Community Guide, notesread.com, walkthroughs.games]
Klusha Handle location: [Single source for swamp vs. park disambiguation — Steam Community 100% guide. Park location in multiple EN video walkthroughs. Verify first run.]
Individual collectible/achievement rows are enemy-tier: 0; boss row carries enemy-tier: 1 — gate accordingly.

### DLC Locks-and-Keys

| Lock location | "Key" | Source zone | Visible before key? | Notes |
|---|---|---|---|---|
| Hotel bridge platforms | Electrical-panel circuit breaker (in-zone elevator shaft) | `dlc_aoi_lyogkaya_hotel` | Yes | Soft puzzle; not item-keyed |
| Hotel exit hole | Klusha melee weapon (dome #34 impaled robot) | `dlc_aoi_lyogkaya_hotel` | Yes | Wall broken by scripted event after pickup |
| Surface BEA-D loading bells (3) | 3 surface BEA-Ds | `dlc_aoi_flooded_village` + `dlc_aoi_freedom_park` | Yes | Quest gate; items spawned by scripted events |
| Mendeleev Hangar elevator (down) | All 3 surface BEA-Ds delivered + Lebedev cutscene | `dlc_aoi_freedom_park` / `dlc_aoi_mendeleev_memorial` | Yes | Story NPC gate |
| Hangar/Complex laser-beam locks | In-zone mirror splitters | Within zone | Yes | Reuses base-game laser-beam puzzle; picture-hint pane is **decorative/broken** — solve by manipulating splitters directly. Solution → `../puzzles/combination_locks.md` |
| Eleanor's Heart final puzzle | 8 BEA-Ds + recombination diagram (in-zone) | `dlc_aoi_mendeleev_complex` | Yes | Two-diagram puzzle: color-arrangement + spatial arrangement. Solution → `../puzzles/combination_locks.md` |
| Strekoza (DLC fast-travel) | Unlocked permanently after Lebedev mission | `dlc_aoi_lebedev_lab` | Yes | DLC's only fast-travel key |

_source: Compass/Deep Research 2026-05-09 (P3) · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 1 · category: mainline · spoiler: dlc:annihilation-instinct_

---

## DLC -- Trapped in Limbo

> **See also:** [`trapped_in_limbo.md`](trapped_in_limbo.md) -- research-integrated DLC zone gate list. Per-DLC-node detail is below; the consolidated file covers the whole DLC with zone graph edges, Auntie Motya shop (NORA replacement), loadout constraints, traversal notes, and missables, useful as a play-time reference. The two views are redundant by design.
> **status: research-integrated (doctor ingested 2026-06-05)**
> **CRITICAL:** Ch.3 base-game "Limbo dream sequences" are NOT this DLC. Fandom date "2023" is a typo; correct release is 2024-02-06. Never conflate.

**Access:** Main Menu → New Game → "Trapped in Limbo: Play" → difficulty. No base-game save needed; fully isolated save slot. Fundamentally different from base-game FPS -- platformer/obstacle-course format (~90% sliding/surfing and parkour; ~10% combat). Unlimited ammo on purchased weapons.

_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:trapped-in-limbo_

### DLC Nodes

| Zone ID | Canonical Name | Russian Name | Type |
|---|---|---|---|
| `limbo_hub` | Level Select / Limbo Hub | локация выбора уровней | hub (Auntie Motya shop) |
| `limbo_avenue_of_speed` | Avenue of Speed | Аллея скорости | indoor-linear (sliding/surfing) |
| `limbo_plateau_of_responsibility` | Plateau of Responsibility | Плато Ответственности | indoor-linear (sliding/surfing) |
| `limbo_tower_of_memory` | Tower of Memory | Башня памяти (Восхождение) | indoor-branching (vertical parkour) |
| `limbo_cliff_of_perseverance` | Cliff of Perseverance | Утёс Настойчивости | indoor-branching (vertical parkour) |
| `limbo_goose_finale` | Goose Run (finale) | Уровень за Гуся | indoor-linear / cutscene |

### DLC Edges

| ID | From | To | Type | Direction | Condition | PoNR | Notes |
|---|---|---|---|---|---|---|---|
| TiL-E0 | Main Menu | `limbo_hub` | **DLC ENTRY POINT** | one-way | Own DLC / Atomic Pass | No | |
| TiL-E1 | `limbo_hub` | `limbo_avenue_of_speed` | level start | bidirectional (replayable) | None | No | Replayable |
| TiL-E2 | `limbo_avenue_of_speed` | `limbo_plateau_of_responsibility` | progression | one-way (first clear) | Complete Avenue | No | Replayable after |
| TiL-E3 | `limbo_plateau_of_responsibility` | `limbo_tower_of_memory` | progression | one-way | Complete prior | No | |
| TiL-E4 | `limbo_tower_of_memory` | `limbo_cliff_of_perseverance` | progression | one-way | Complete prior | No | |
| TiL-E5 | `limbo_cliff_of_perseverance` | `limbo_goose_finale` | progression | one-way | Complete one Avenue + one climb | **Yes** | Goose finale = no return; ending follows |

### DLC Support Topology

No NORA stations. **Auntie Motya (Тётя Мотя)** in `limbo_hub` replaces NORA as the shop; buys weapon skins (gold coins) and unlocks skills/weapons (apples). Isolated from base-game NORA network. DLC is self-contained except 7 weapon skins carry into base campaign.

### DLC Optional Content Registry

| Content | Type | Zones | Access | Failure mode |
|---|---|---|---|---|
| Gold coins (76 + bonus 77th) | Collectible currency | All levels | Replayable | Missable in single pass; replayable |
| Apples (3,826 total) | Upgrade resource | All levels | Replayable | Not permanently missable |
| Chirpers | Collectible audio | Levels | Replayable | Not permanently missable |
| 7 weapon skins | Cosmetic | Auntie Motya shop | Any time | Usable in base campaign |

### DLC Locks-and-Keys

No traditional lock-and-key system. Progression gated by completing platforming levels.

_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:trapped-in-limbo_
[Confirmed: multiple sources, 2 languages]

---

## DLC -- Enchantment Under the Sea

> **See also:** [`enchantment_under_sea.md`](enchantment_under_sea.md) -- research-integrated DLC zone gate list. Per-DLC-node detail is below; the consolidated file covers the whole DLC with zone graph edges, NORA stations, loadout constraints, traversal notes, and missables, useful as a play-time reference. The two views are redundant by design.
> **status: research-integrated (doctor ingested 2026-06-05)**
> **Zone prefix corrected: `neptune_*` (not `triton_complex_*` -- Triton is a sub-complex name).**

**Access:** Main Menu → separate campaign → own difficulty selection. Isolated save slot. January 28, 2025. Return to base-game FPS combat with new Whip grapple mechanic and undersea BioShock/Rapture atmosphere. ~5-6 hours.

_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:enchantment-under-sea_

### DLC Nodes

| Zone ID | Canonical Name | Type |
|---|---|---|
| `neptune_sechenov_complex` | Sechenov Complex (interior) | indoor-linear |
| `neptune_chelomey_ruins` | Destroyed Chelomey | open-ish / outdoor |
| `neptune_lakeshore` | Lakeshore / lighthouse beach | outdoor |
| `neptune_babazina_hut` | Baba Zina's hut / Kurortnaya stop | hub-ish |
| `neptune_entry_hub` | Neptune entry hall / dolphin aquarium hub | indoor-branching |
| `neptune_flooded` | Flooded complex interior | indoor-linear |
| `neptune_depot` | Depot / cistern hall | indoor-linear |
| `neptune_railway` | Railway / metro tunnels | indoor-linear |
| `neptune_statue` | Neptune statue / admin offices | indoor-branching |
| `neptune_cafeteria_whale` | Cafeteria + Whale hall | indoor-linear |
| `neptune_zoology` | Zoology / reception / mannequin offices | indoor-branching |
| `neptune_quarters` | Decontamination / Nastya & Hunter quarters | indoor-linear |
| `neptune_dolphin_rooms` | Dolphin aquarium-tunnel rooms / show hall | indoor-branching |
| `neptune_sub_bay` | Submarine bay / engine room hatch | indoor-linear |
| `neptune_open_water` | Open underwater lake-bottom section | open-world (underwater) |
| `neptune_block_b` | Block "B" / assembly shop & repair cabinets | indoor-branching |
| `neptune_city_of_dolphins` | City of Dolphins | indoor-linear |
| `neptune_final_arena` | Final boss arena (Thalassophobia) | cutscene/arena |

### DLC Edges

| ID | From | To | Type | Direction | Condition | PoNR | Notes |
|---|---|---|---|---|---|---|---|
| EutS-E0 | Main Menu | `neptune_sechenov_complex` | **DLC ENTRY POINT** | one-way | Own DLC / Atomic Pass | No | |
| EutS-E1 | `neptune_sechenov_complex` | `neptune_chelomey_ruins` | story | one-way | Pick lock, descend | No | |
| EutS-E2 | `neptune_chelomey_ruins` | `neptune_lakeshore` | story | one-way | Robogirl boss | No | Enemy-tier: 1 |
| EutS-E3 | `neptune_lakeshore` | `neptune_babazina_hut` | story | one-way | Get Kuzmich shotgun | No | |
| EutS-E4 | `neptune_babazina_hut` | `neptune_entry_hub` | elevator | one-way | Baba Zina drop-off | Yes | Enter Neptune Complex |
| EutS-E5 | `neptune_entry_hub` -> ... | Sequential interior zones | story | mostly one-way | Quest progression | varies | Mostly linear |
| EutS-E6 | `neptune_sub_bay` | `neptune_open_water` | airlock dive | one-way | Diving hatch | Yes | Underwater stealth -- cannot fight |
| EutS-E7 | `neptune_city_of_dolphins` | `neptune_final_arena` | story | one-way | Reach gates | **Yes** | Final boss (enemy-tier: 1); sub escape |

### DLC Support Topology

Repair cabinets **Eleanor (Элеанора)** and **Samodelkin (Самоделкин)** in `neptune_block_b` replace NORA for upgrades. Rest/safe rooms as save points throughout. Isolated from base-game NORA network.

### DLC Weapons and Abilities

**Weapons:** Thunderclap/Громовержец (electric hammer/flail); KM-4/Kuzmich (double-barrel shotgun with grenade alt-fire).
**Glove abilities:** Whip (grapple hook; 3D mobility); Blaze/Загар (burning polymer fireballs; burns polymer growths).

### DLC Optional Content Registry

| Content | Type | Zones | Failure mode |
|---|---|---|---|
| Chirpers (Щебетари) | Collectible | Multiple | **Missable** -- backtracking limited |
| Hunter's stashes | Collectible | Multiple | **Missable** |
| Moby Dick window song | Achievement event | Specific window | **Missable** |

### DLC Locks-and-Keys

Dolphin cage ("Candle" socket); graphic-key door ("Where Are They?!"); submarine bay override/valve sequence (cistern puzzle: Down -> Rotate -> Up). See `enchantment_under_sea.md` for details.

_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:enchantment-under-sea_
[Confirmed: VGTimes EN/RU, ShowGamer, Fandom, cyber.sports.ru -- 2 languages]

---

## DLC -- Blood on Crystal

> **See also:** [`blood_on_crystal.md`](blood_on_crystal.md) -- research-integrated DLC zone gate list. Per-DLC-node detail is below; the consolidated file covers the whole DLC with zone graph edges, NORA stations, weapons/mechanics, loadout constraints, traversal notes, and missables, useful as a play-time reference. The two views are redundant by design.
> **status: research-integrated (doctor ingested 2026-06-05)**
> **FINAL DLC in the Atomic Heart season pass. 8 of 13 achievements missable; no chapter select.**

**Access:** Main Menu → separate campaign → own difficulty. Isolated save slot. April 16, 2026. Released alongside the Ultimate Edition (digital). Physical Ultimate Edition released March 24, 2026. Free OST Volume 6 released alongside. ~8+ hours (Focus Entertainment: "longest DLC yet").

_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:blood-on-crystal_

### DLC Nodes

| Zone ID | Canonical Name | Type |
|---|---|---|
| `boc_orb_lab` | Orb laboratory (Lebedev's lab, from DLC #1) | indoor-linear |
| `boc_wave_platform` | Wave Platform | indoor-branching / outdoor |
| `boc_submarine` | Submarine | indoor-linear |
| `boc_crystal_arrival` | Crystal Complex -- arrival/sarcophagus | indoor-branching |
| `boc_crystal_archive` | Crystal -- archive zone | indoor-branching |
| `boc_crystal_recreation` | Crystal -- recreation/breakroom zone | indoor-branching |
| `boc_crystal_residential_1` | Crystal -- first Residential Sector | indoor-branching |
| `boc_crystal_residential_2` | Crystal -- second Residential Sector | open-ish |
| `boc_crystal_factory` | Crystal -- Factory / conveyor zone | indoor-branching |
| `boc_crystal_indoor_beach` | Crystal -- indoor beach | indoor |
| `boc_crystal_core` | Crystal Core / final | cutscene/arena |

### DLC Edges

| ID | From | To | Type | Direction | Condition | PoNR | Notes |
|---|---|---|---|---|---|---|---|
| BoC-E0 | Main Menu | `boc_orb_lab` | **DLC ENTRY POINT** | one-way | Own DLC / Atomic Pass | No | NORA fitted here |
| BoC-E1 | `boc_orb_lab` | `boc_wave_platform` | story | one-way | Plan to infiltrate Wave | No | |
| BoC-E2 | `boc_wave_platform` | `boc_submarine` | story | one-way | RACCOON boss / bridge | Yes | Enemy-tier: 1 |
| BoC-E3 | `boc_submarine` | `boc_crystal_arrival` | story | one-way | ENOT miniboss; exit generator room | Yes | |
| BoC-E4 | `boc_crystal_*` | Sequential Crystal zones | story | mostly one-way | Quest progression | varies | CHANCE modules introduced |
| BoC-E5 | `boc_crystal_core` | Final boss | story | one-way | Second Twin -> Crystal Core fall | **Yes** | Enemy-tier: 1; endings follow |

Enemy identities at BoC-E2, BoC-E5: enemy-tier: 1 -- gate accordingly.

### DLC Support Topology

**NORA is P-3's glove companion** (fitted at Orb lab; active from Crystal Complex). **CHANCE machines** throughout Crystal Complex swap glove abilities (gaining new ability removes oldest). Save rooms throughout (some burnt). Isolated from base-game NORA network.

### DLC Weapons and Mechanics

CHANCE modules (Polymer Glove) for mid-combat ability swapping. Returning DLC weapons with max-upgrade paths: Klusha, Secator, Kuzmich, Thunderclap. New enemies: **Polymorphs** (fire/ice-switching crystal humans) -- CHANCE modules counter them.

### DLC Optional Content Registry

| Content | Type | Zones | Failure mode |
|---|---|---|---|
| Crystal figurines (11 total) | Collectible (permanent buffs) | Crystal Complex onward | **MISSABLE -- no chapter select; full run lost if any missed** -- see `../dependencies.md` DEP-025 |
| Chirpers | Collectible | All zones | Missable |
| Fluffy Easter Egg room | Secret room / achievement | `boc_crystal_residential_1` | **Missable** |
| Better Late Than Never | Secret room / achievement | Post-art-gallery arena | **Missable** |
| Secret Meeting room | Secret room / achievement | Burnt save room area | **Missable** |

### DLC Locks-and-Keys

Polymer key (residential weapons-disable zone); Fluffy Easter Egg outhouse code "X"; Better Late Than Never pyramid/PEAR code; Secret Meeting PEAR terminal key; vacuum-cleaner key (figurine #6); submarine multi-step exploration; Factory gate Door 19 circuit/rod puzzle. See `blood_on_crystal.md` for details.

_source: Deep Research 2026-05-27 · capture: web_fetch · confidence: high (base facts) / medium (post-launch details -- released ~7 weeks before brief) · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:blood-on-crystal_
[Confirmed: Steam guide + ShowGamer + VGTimes -- 2 languages]
