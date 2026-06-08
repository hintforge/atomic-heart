# Facility 3826 Open World (HAWK Regions / Sectors) — Gate List

**status:** research-integrated
**zone-id:** open_world_main
**parent chapter:** Ch.2–9 (active until "Sky's the Limit" trigger)
**zone type:** open-world-region

_source: Compass P2 deep research 2026-05-09 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

## Entry point
First exit from Vavilov surface (red building in forester_village). Persistent thereafter throughout the game.

## Exit / outgoing edges
Connections to all hub/dungeon zones (see architecture.md). The critical one-way: `bridge_to_pavlov` is impassable (collapses) after the Theatre cutscene, sealing the entire southern region.

## NORA stations
**None outdoors.** No manual save terminals exist in the open world. Saves depend on:
- Entering indoor safe rooms in adjacent zones
- Granny Zina's hut (when it lands at marked spots)
- HAWK booth proximity (NOT a save point; only pacification)
- Auto-checkpoints (unreliable for hard saves)

_source: Compass P2 deep research 2026-05-09 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · spoiler: none_
[Confirmed: Steam Community thread consensus]

## Key mechanics

### Vehicle traversal
- **Vehicle type:** Small red four-door sedan (based on 1964 Moskvitch 408); fixed roadside spawn locations.
- **Acquisition:** Walk up to a parked car on any road in open_world_main; press interact. First car is parked outside the Forester Village / Vavilov-exit road junction.
- **Properties:**
  - Faster traversal than on foot, but increases visibility to Dandelion cameras / HAWK alarms.
  - Cars take damage from impacts and are destroyed after repeated rams.
  - Cars respawn at fixed road positions.
  - Cars cannot cross the broken bridge after the Theatre cutscene.
  - No fuel system, no upgrades, no vehicle inventory.
  - Can be used as kinetic weapons (cumulative 20-ram "Tickets, Please!" trophy).
- **Story-gated windows:** Cars available from Forester Village exit onward; prologue Sechenov car is scripted-only (one shot).

_source: Compass P2 deep research 2026-05-09 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · spoiler: none_
[Source: IGCD.net (Moskvitch 408 ID), gameranx HAWK guide]

### HAWK relay system
- Deactivate a HAWK relay (Volan camera hack) to pacify robots in the relay's sector for ~15 minutes.
- HAWK relays do NOT function as save points.
- Each region has multiple relays; open_world_main is split into HAWK sectors visible on the map.
- **Recurring question (RQ4):** "Will disabling the HAWK relay also disable the cameras?" -- Answer: yes, the HAWK relay overload disables ALL cameras AND ground robots in the sector for the cooldown duration. See `mechanics.md` HAWK Relay System section for the full step-by-step procedure.

### Polygon access (open world)
All 12 Polygon entries are in open_world_main. See `optional_zones/polygons.md` for per-polygon gate lists. Active polygons with full Lootyagin sets: 1, 2, 6, 8, 9, 10, 11, 12. Polygons 3, 4, 5, 7 are not present in the shipping base game.

## Live-observed points of interest (undocumented in corpus)

| Location | Observed | Notes |
|---|---|---|
| Vehicle spawn — south of Kollektiv Complex, road behind it (approx. 1,462m from active objective 2026-05-18) | 2026-05-18 | Yellow utility/work truck, fire truck, and a driveable car at this location. Likely a fixed car respawn point. Crashed rotor aircraft wreck nearby (decorative/environmental). No confirmed loot. |

---

## Live-observed camera terminals (no dungeon access)

These Volan terminals were found and accessed in-game but yielded only road/area surveillance footage — no hatch opened, no Polygon unlocked:

| Location | Observed | Notes |
|---|---|---|
| Road between TG6 and TG10, near Sechenov exterior (`t1_x10_y4_Center_Sechennov_props`) | 2026-05-12 | Camera showed road cameras only. Not the TG10 unlock Volan (that one is east of TG8 near a pigsty/wheat field). Purpose unknown — possibly decorative/environmental, possibly a HAWK sector relay with no dungeon tie. |

## Common confusions
- **No outdoor saves**: Players die between dungeons and lose significant progress; always save inside safe rooms.
- **Driving attracts more attention** than walking; cars trigger Dandelion camera alarms and HAWK patrols more readily.
- **Bridge is one-way** after Theatre cutscene; crossing seals the entire southern map.

## Sources
- pcgamesn.com — map, fast travel, EN, 2023
- theloadout.com — map, EN, 2023
- gamesradar.com — HAWK system, EN, 2023
- gamerant.com — HAWK guide, EN, 2023
- steamcommunity.com — save points thread (no outdoor saves confirmed), EN, 2023
- IGCD.net — vehicle identification, EN, 2023
