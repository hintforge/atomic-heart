# Nav — Localization Toolkit

**status:** research-integrated
**research_run:** P2 (Compass/Deep Research 2026-05-08)
**mechanism:** hybrid (open-world zones use map; indoor Complexes and Testing Grounds use landmark-only navigation)

> This file answers: "When P-3 says they're somewhere, how does the guide confirm or narrow down their location without a screenshot?" Landmarks in this file are tier-0 visible — they are definitional anchors, not spoilers.

**Terminology flexibility:** transliteration variants are common (`Kollektiv` / `Collectiv`, `NORA` / `Nora`, and similar Russian/Soviet names). Accept the player's spelling and prefer the canonical in-game English form in guide output.

_source: Compass/Deep Research 2026-05-08 (P2) · capture: web_fetch · confidence: medium-high per entry · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

---

## Ask-the-Player Prompts

### Indoor / Testing Ground zones

When player-position confidence is low in any Complex or TG zone, ask any of:

- "What's the last big thing you passed through — a puzzle room, a NORA booth (red-fridge vendor), or a save room with a terminal?"
- "Is there anything distinctive around you — polymer vats, Soviet propaganda posters, robot assembly lines, botanical lab equipment, medical equipment, or theatrical props?"
- "Are there candles (yellow glowing orbs) in sockets, or magnetized platforms above or below you?"
- "Can you see a giant transparent whale, a birch-tree sculpture, ballerina statues, or a hospital ward?"
- "Is the lighting frost-blue, hot orange-red, or fluorescent white?"
- "What kind of machines or equipment are nearest to you — boilers, a rail wagon, an animal tank, or a lathe?"

### Open-world zones

- "What does your map show as the nearest named location — Arena, Boat Station, Kollektiv, Sechenov Research Center, Theater, Bridge, Infirmary, or Lighthouse?"
- "Are you near a Volan tower (white spiral), a HAWK relay pole, a Testing-Ground hatch (blue mushroom bunker, drainage pipe, or pigsty hatch), or in open patrol territory?"
- "Can you see the Motherland statue, the Worker-and-Kolkhoz-Woman statue, or the Kollektiv giant statue from where you are?"
- "Is there a road, a lake, or a beach visible nearby?"
- "Are robots actively patrolling, or has a HAWK relay overload disabled them in the area?"

---

## Per-Zone Landmarks (indoor zones)

### vavilov_maglev_station_solnechnaya_int
- **Schematic Lock Disc Booth:** cylindrical operator booth with a circular dial of black dots — player inputs a pattern.
- **Polymer Swim Tunnel:** glowing red-orange polymer pool the player dives into.
- **First NORA Save Room:** red-fridge NORA vendor on a back wall with a large blueprint chest.
- _Disambiguation vs. vavilov_seed_bank safe rooms (also red NORA): distinguish by the polymer-pool entry preceding this NORA._

### vavilov_maglev_tunnels
- **Cable-car cab:** overturned, resting on broken track in the pit.
- **Yellow-painted ledges:** climb markers on tunnel walls.
- **Drill-bot patrol floor:** giant industrial robot with a rotating drill arm patrols here.
- **Operator-corpse niche:** small rubble-pile offshoot path off the main tunnel.

### vavilov_cable_cars
- **Crashed cable-car cabin** in a pit below the boarding platform.
- **Climbing wall** with yellow paint markers and pipe traversal.
- **Locked station safe room** with Fox-axe blueprint.

### vavilov_seed_bank
- **PEC-4 birch silhouette:** massive central seed-storage chamber with a white birch electrical-power tree. _Disambiguation: the Distribution Hall has a separate PEC-4 — this one is the first silhouette visible and has no canister sockets._
- **Loader-platform zipline:** orange industrial loader on an overhead cable.
- **Upper catwalk:** laser-drone ambush before the stairs.

### vavilov_birch_distribution_hall
- **PEC-4 Birchtree altar:** central altar with four canister sockets at its base. _Disambiguation vs. Seed Bank birch: this one has the canister-socket ring._
- **Two-Candle Door:** large red sliding shutter with two cylindrical candle slots.
- **East/West wing branching corridors:** visible from the central hub.

### vavilov_hot_workshop
- **Boiler row:** three large blue-and-orange industrial boilers in a row.
- **Greenhouse jungle overlook:** raised stairs with a view down into a plant-filled chamber.

### vavilov_algae_workshop
- **Polymer pools** with motor-speed valves the player must accelerate.
- **Shattered observation window:** the large glass panel that was smashed by an impact.

### vavilov_pesticide_workshop
- **Animal Tank console:** ring of cylindrical experiment tanks (cow, pig, chicken) with a matching console.
- **PA-400 yellow rail wagon:** industrial rail car on a track through the workshop.
- **Tunnel arena:** where a large mutant ambushes.

### vavilov_cold_workshop
- **Three frost-coated boilers in a row.** _Disambiguation vs. Hot Workshop: Cold = frost/blue lighting + visible breath particles; Hot = orange-red glow + heat haze._
- **Roof-drop locked house** containing a cold candle inside.

### granny_zina_hut
- **Wooden interior with chicken-leg-style movable walls** (Baba Yaga aesthetic).
- **Granny's seat/table area** with KM-4 Kuzmich shotgun.
- **NORA terminal (red fridge)** — unique to this zone.

### sdc2_volan_tower
- **Glass-room top** of the tall white spiral tower.
- **White pedestal device** that cannot be overridden on the first visit.

### lesnaya_maglev_station
- **Red passenger-train carriage** with a bar interior — Rafik the conductor is inside.
- **Statue-base corpse** at the lower-right of the station entrance (holds expired ticket).

### testing_ground_1
- **Magnetic-ceiling chamber:** broken ceiling panels with battery-cluster magnets.
- **Laser-grid puzzle wall.**
- _Disambiguation from TG2: TG1 has only ceiling-magnet polarity; TG2 mixes ceiling + wall-mounted magnets._

### testing_ground_2
- Magnetic Puzzle Room 1 with a red-button platform.
- Magnetic Puzzle Room 2 with horizontal AND vertical magnets.

### testing_ground_6
- **Revolving X-shaped platforms** with red valve cranks.
- **Piston-and-turbine engine room.**

### testing_ground_8
- **Suspended submarine prop** hanging from the ceiling in the final puzzle room.

### testing_ground_9
- **Sewer boilers** (4 total) accessible via a manhole.
- **Candle-throwing platform extension puzzle.**
- **Lenin-statue shack** entrance at the end.

### testing_ground_10
- **Polymeric Jet door** at entry.
- **Pigsty hatch** visible from outside.

### testing_ground_11
- **Mannequin-Lab-Tech diorama room:** combat hidden among display dummies.

### testing_ground_12
- **Beached-whale skeleton** visible at the entry beach.
- **Candle-and-revolving-floor final puzzle** in the deepest section.
- _enemy-tier: 2 note: mid-run boss encounter (Natasha rematch)_

### vdnh_atrium
- **Reception desk** with a central statue holding a hammer in its raised hand.
- **Icarus marble-tilt diorama** — tilt the table to roll a marble.
- **Tereshkova humanoid robot** at the far end.

### vdnh_chelomey_floor
- **Rocketry / Icarus exhibit dioramas.**

### vdnh_vavilov_floor
- **Greenhouse / birch museum exhibit** with roped-off dioramas and placards. _Disambiguation: looks like the real Vavilov Seed Bank but is a museum replica — roped off, not traversable, with placards instead of actual plants._

### vdnh_pavlov_floor
- **Giant transparent whale exhibit:** whale suspended in clear polymer in a glass case. _Disambiguation: the Pavlov Complex hospital also has whale/polymer themes, but VDNH's whale is a museum specimen in a glass case; the hospital has operational MRI machines and ward beds._

### vdnh_sakhalin_floor
- **Lighthouse-keeper diorama** with a miniature lighthouse model.

### magnetic_absorption_zone
- **Magnetic-coil ceilings** with blue/red flap platforms.
- **Floor switch** in the final corridor.

### sechenov_research_center_int
- **Cookie-Key door:** disk-shaped slot in the door frame.
- **Office hallway** beyond reception.

### lastochkin_theater_int
- **Coat Check tapestry stairs** leading back toward the Engineer's body.
- **Bar with stage view** — the bar break room has the nearest NORA.
- **Ballerina performance hall** — numbered statues on pedestals.
- **Supply room** with a laser-puzzle yellow-hardhat console.

### theater_stage
- **Numbered ballerina pedestals (1-4)** in the hallway before the stage.
- **Shadow wall** at the end of the hallway.
- **Large red-velvet auditorium** visible through the stage doors.

### pavlov_hospital
- **21-button piston lock with bloody handprints** (E45 Blood Courier door).
- **Surgical Lab #1** with a damaged MRI machine and a locker nearby.
- **Ward beds** along the corridors.
- _Disambiguation vs. vdnh_pavlov_floor: real hospital has functioning (if damaged) equipment, fluorescent lighting, ward signage, and hostile activity; VDNH floor has clean diorama beds and placards._

### pavlov_morgue
- **Long body-storage drawer rows.**
- **Room 1 cubby:** small alcove with a Key Disk.
- **Second-floor combo door:** the combination puzzle gate before the exit.

### pavlov_surgical_lab
- **Two inactive Plyusch specimens in tubes** (do not shoot them — they activate if attacked).
- **Distribution Center snap-puzzle door** in the corridor.

### lighthouse_beach
- **Beached whale carcass** (usable as cover; visible from the approach path).
- **Cliff bunker mineshaft** entry at the far end.

### academy_underwater
- **Glass elevator** with a view of the submerged Neptune facility.
- **Chair where a character sits** for a conversation sequence.

### academy_archive_room
- **Three film reels/bobbins** — one nearby, two on the flanking stairs.
- **Exit room** where Granny Zina appears. _spoiler: story_

### chelomey_revisit
- **Dark, depopulated plaza** — contrast with the bright prologue version.
- **Lift between arena floors.**
- _Disambiguation from chelomey_city_prologue: prologue is bright, populated, fountain-and-flag aesthetic; revisit is dark, depopulated, fight-ready._

---

## Open-World Named Landmarks (map-visible)

### forester_open_world
Forester Village hub (red building exit, garage, grocery store, log cabin "3") · Volan tower / SDC-2 (tall white spiral — unique in this zone) · Granny Zina's farm (washing-station summon) · Telemail post office (two-story, fire engine parked outside) · Destroyed road tunnel · Lesnaya Maglev Station

### solnechnaya_open_world
Monorail Station · Arena · Boat Station (dock + lake) · Kollektiv Complex (giant statue + dam) · Worker-and-Kolkhoz-Woman statue · Motherland statue · Reaper monument · Plants 1 & 2 · Sechenov Research Center (NE) · Lastochkin Theater (SE walkway) · Pavlov Bridge (north crossing) · Infirmary (far side of bridge) · Lighthouse (far coast) · Testing Ground hatches: TG2 (sewer near Boat Station), TG6 (drainage pipe), TG8 (inside Research Center), TG9 (Kollektiv manhole), TG10 (pigsty), TG11 (across from Theater), TG12 (beach cave)

---

## Disambiguation Table

| Zone A landmark | Zone B landmark | Distinguishing detail |
|---|---|---|
| vavilov_seed_bank PEC-4 birch silhouette | vavilov_birch_distribution_hall PEC-4 birchtree | Distribution Hall birch has a **canister-socket ring at the base**; Seed Bank's is decorative. [C:3] |
| vavilov_hot_workshop boiler row | vavilov_cold_workshop boiler row | Hot = orange-red glow + heat haze; Cold = frost/blue + visible breath particles. [C:3] |
| vdnh_pavlov_floor whale exhibit | pavlov_hospital / pavlov_sanatorium | VDNH whale is **suspended in clear polymer in a glass case** (museum); Pavlov Complex has **operational ward beds, MRI machines, and bloody walls** — no preserved whale. [C:3] |
| vdnh_vavilov_floor greenhouse exhibit | vavilov_seed_bank | VDNH version is a roped-off museum diorama with placards; real Seed Bank is full-scale, traversable, with hostile plant-mutants. [C:3] |
| testing_ground_1 magnetic chamber | testing_ground_2 magnetic chamber | TG1 has only ceiling-magnet polarity; TG2 mixes ceiling + wall-mounted magnets and a button-platform. [C:3] |
| testing_ground_6 revolving rooms | testing_ground_8 revolving rooms | TG6 valve indicators use dot counts (I/II/III/IIII); TG8 uses platform-switching combat puzzles + a hanging submarine. [C:3] |
| testing_ground_9 candle-platform puzzle | testing_ground_12 candle-platform puzzle | TG9 candles activate slide-out platforms in a sprout-themed hall; TG12 candles control revolving floors with magnetic columns. [C:3] |
| theater_stage ballerina puzzle hall | vdnh_drill_mode ballerina display | Theater hall has 4 numbered, posable statues + shadow wall; VDNH ballerinas are static museum exhibits. [C:3] |
| sechenov_research_center_ext roof | lastochkin_theater_grounds arena | Research Center roof is **scaffolded sloping concrete** with a Volan terminal; Theater grounds is a **flat grassy arena with a monument**. [C:3] |
| chelomey_city_prologue plaza | chelomey_revisit arena | Prologue = bright, populated, fountain + flags; Revisit = dark, depopulated, arena-ready. [C:3] |
| forester_open_world Volan tower (SDC-2) | solnechnaya_open_world camera towers | SDC-2 Volan is the **only tall white spiral** in the forester zone; solnechnaya towers are shorter cylindrical platforms with spiral stairs. [C:3] |
| pavlov_hospital wards | vdnh_pavlov_floor wards | Real hospital has **bloody handprints, hostile activity, and MRI machines**; VDNH version has **clean diorama beds and exhibit placards**. [C:3] |

---

## Map-element prompts (open world / `open_world_main`)

When the player's current zone is in open world and a single landmark hasn't pinned them down:

- "Which HAWK sector circle on your map are you currently inside? Look at the colored circle around your player marker."
- "Are you north or south of the long bridge with triangular supports (Pavlov Bridge)?"
- "How many Volan towers are still unhacked in your current sector? Check your map."

_source: P2 sandbox-side ingestion · added 2026-05-09 convergence · capture: web_fetch_

---

## Generic indoor fallback prompts

Use when zone can't be determined from a single landmark in any Complex or TG:

1. "What is the floor type — tile, polymer pool, ventilation grating, grass/soil, carpet/wood?"
2. "Are there Sprouts (zombie plants), Lab-Tech robots, or Mutants (flesh enemies) in this room?"
3. "Do you see a NORA vending machine (woman-faced cabinet / red-fridge) within view? If yes, describe the chest beside it."
4. "What is the dominant wall color — green-tinted (Algae/Pesticide), red (Theatre/Sechenov), white-tile (Pavlov/hospital), wood paneling (Forester Village/Granny hut)?"
5. "Is there a save bench / safe-room marker visible on your HUD?"

_source: P2 sandbox-side ingestion · added 2026-05-09 convergence · capture: web_fetch_

---

## Generic open-world fallback prompts

1. "Are you on an asphalt road or off-road (grass, sand, beach)?"
2. "Can you see the giant Plant 01 cooling tower in the distance, the sky-anchored HAWK balloon, or the Motherland statue?"
3. "What is your alert level showing — 0, 1, or 2 in your HUD?"

_source: P2 sandbox-side ingestion · added 2026-05-09 convergence · capture: web_fetch_
