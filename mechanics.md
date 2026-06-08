# Atomic Heart — Mechanics Reference

**status:** research-integrated
**last_reconciled:** 2026-05-08
**research_run:** P1 (Compass/Deep Research 2026-05-08)

Core game-system rules that apply across all zones. Per-zone tips go in `nav/<zone>.md`. Enemy patterns go in `npcs/`.

---

## HAWK Relay System (anti-respawn)

**Zones:** open-world zones (`forester_open_world`, `solnechnaya_open_world`)
_source: gameranx 442905, dotesports, gamertweak — 5 sources · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

The HAWK relay system is the central anti-respawn mechanic in open-world zones:
1. Find a Volan security tower and **scan the camera** on it.
2. Hack the camera to **trace it to the Volan tower**.
3. Hack the relay at the Volan tower.
4. Select **"Overload Relay"** — this disables ALL cameras and ground robots in the zone for an extended cooldown, preventing respawn.

This must be done per open-world zone. The effect is temporary but long-duration. Enemies that are already dead stay dead during the cooldown.

> **Cross-system dependency** — see `dependencies.md` DEP-005: Relay disable applies to both farming efficiency (`items/crafting_materials.md`) and safe Polygon entry (`optional_zones/polygons.md`). Same mechanic, same precondition in both contexts.

---

## Hawk Transport — Lowering Mechanic

**Zones:** open-world zones (confirmed near Sechenov Research Center / TG8 area)
_source: P-3 in-game observation 2026-05-11 · capture: manual_paste · confidence: confirmed · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

Hawks (large aerial transports visible on the map) can be lowered to ground level via a **ground control terminal** located near the Hawk's hover position. Interacting with the terminal brings the Hawk down. Not captured in web research — confirmed live.

---

## Camera vs. Enemy Alert

**Applies everywhere.**
_source: gameranx 442905 + r/atomicheart community (reddit.com/r/atomicheart/comments/141m67s) · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 2 independent sources agree on camera-only trigger]

**Alarm levels:**
- **Level 1:** triggered by proximity / robots detecting P-3. Robots chase but do not call reinforcements. Manageable.
- **Level 2:** triggered ONLY when a camera has line-of-sight and SEES P-3 killing a robot. Spawns a full reinforcement swarm.

**Practical rule: destroy or disable the camera before engaging.** Fight with no camera watching = fight ends at 0 alarm, no swarm, no escalation. P-3 can fight as loudly as needed -- only camera visibility triggers level 2. Use the scanner to confirm no cameras have line-of-sight before opening fire.

**Exploit:** the alarm system can be deliberately triggered as a farming loop -- see `items/crafting_materials.md` camera-kill farming loop section.

> **Cross-system dependency** -- see `dependencies.md` DEP-022: Camera alarm level 2 trigger + Pchela-Dandelion repair cycle together power the camera-kill farming loop. Both sub-systems must stay active; do not disable the HAWK relay and do not use Railgun while farming this way.

---

## Post-Game Free Roam

**Patch 1.14.4.0 feature.**
_source: PSNProfiles, dsogaming patch notes — 3 sources · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: late-game_

After either ending's credits, the main menu offers "Return to Facility 3826." This loads the player into `solnechnaya_open_world` with free access to the open world and all Testing Grounds. **Complexes (Vavilov, VDNH building, Sechenov Center, Theater, Pavlov) remain locked** — PoNRs in those areas are permanent even in free roam. Use this for collectible and TG clean-up that wasn't missable.

---

## Collectibles Overview

| Collectible | Count | Missable? | Notes |
|---|---|---|---|
| Chirpers (Burning Ears) | 72 | Yes — per-zone | Scan/pickup; locked with zone PoNRs for Complexes; open-world Chirpers always-available |
| Talking Deads (Necromancer) | 53 | Yes — per-zone | Scan + interact; same PoNR windows as Chirpers |
| Enemy scans (Scanner) | 38 | Yes — scan before kill | All boss types must be scanned; Twins require Left and Right scanned individually |
| Blueprints | 63 | Yes — per-zone | Chest pickups; locked with zone PoNRs |
| Lootyagin chests | 24 (3 per TG) | Partly — TG8 + TG12 | Open all bronze/silver/gold in each TG |
| Talking dead animals (Beast Friend) | 3 | No | Hen, cow, third by solar arrays; open-world persistent |

_source: PSNProfiles trophy guide, daynglsgameguides — confirmed · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

---

## Volan Camera Hijacking (mechanic)

**Applies:** all open-world and some indoor zones.
_source: gameranx 442905 — confirmed · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

Scan a Volan security camera → hack it → camera can then be directed. Used for:
- Unlocking Testing Ground hatches (aim camera at hatch)
- Tracing to the Volan relay tower for the HAWK relay overload
- Opening doors/gates remotely

---

## NG+ Mode (Patch 1.8.0.0+)

**Unlock:** beat the game (either ending). Select "New Game+" from main menu.
_source: dsogaming patch 1.8.0.0; PSNProfiles · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: progression_

NG+ adds colored-aura enemy modifiers that change resistances. Pre-patch English guides do not cover these — treat any pre-1.8 walkthrough as NG+-unaware.

| Aura color | Effect | Notable enemies |
|---|---|---|
| Red (Master of Elements) | Immune to glove abilities and cartridge guns | VOV-A6 Lab Tech, ARU-31/6, MFU-68, RAF-9 Engineer |
| Yellow (Body Armor) | Immune to firearms | LUC-1 Owl, GMC-69 Vatrushka, DOC, MFU-68/CP Duck |
| Green (Athlete) | All attacks now ground the player | All types |
| Orange (Kamikaze) | Explode on approach | All types |
| Turquoise (Lightning Rod) | Drain energy on hit | All types |
| Blue (Translocator) | Teleport-close to player | All types |

> Body Armor on Owls is particularly punishing — pre-patch shotgun strategies fail. Prioritize glove abilities on yellow-aura enemies.

_source: Compass/Deep Research 2026-05-09 (P3); dsogaming patch notes · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: progression_

---

## Ledge Grab / Platform Landing -- Camera Angle

**Applies:** all zones with ledges and platforms.
_source: P-3 in-game observation 2026-05-21 · capture: manual_paste · confidence: confirmed · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

Looking **up** while jumping allows P-3 to land on platforms that are at the same height as where he is currently holding on. Without looking up, the grab registers as a hang rather than a vault. Useful in TG magnetic puzzle rooms where the target ledge appears reachable but the grab fails.

---

## Patch Awareness Notes

Pre-patch (pre-1.6) English guides are unreliable for:
- "Bug in the System" key-disk soft-lock workarounds — **patched in 1.6.0.0**, no workaround needed
- NG+ enemy behavior — **didn't exist pre-1.8.0.0**
- Any published damage/material-count numbers — silent rebalances unconfirmed but probable
- DLC content — all pre-Aug 2023 guides predate Annihilation Instinct

Guides from Feb–Apr 2023 vintage remain broadly accurate for blueprint locations, puzzle solutions, and qualitative ability tier listings.

_source: Compass/Deep Research 2026-05-09 (P3); PCGamingWiki · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

---

## Accessibility Options (Patch 1.14.x)

_source: Steam patch notes 1.14.4.0 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

- **Highlight Interactive Objects:** Overlays gold/yellow tints on collectibles in indoor zones. Partially overrides landmark-only search indoors. Useful for Chirper and Blueprint hunting in Complexes.
- Colorblind and contrast options also added in this patch.

---

## Testing Ground Chest Preview (Map Hover)

**Applies:** open-world map, any Testing Ground marker.
_source: P-3 in-game observation 2026-05-18 · capture: manual_paste · confidence: confirmed · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

Hovering over a Testing Ground (Polygon) marker on the open-world map displays its bronze, silver, and gold chest contents before entry. Each tier's reward is shown with weapon name and mod name. This is the canonical way to read TG rewards for a given playthrough.

**Important:** rewards appear to be state-dependent (RNG pool adjusted by blueprints already collected — same pattern observed for TG9 confirmed via wotpack.ru). The hover reflects what **this** playthrough will receive, not a fixed global table. Check the hover before entering any TG to confirm the specific drops available to you.

---

## Repair Bot Pathfinding Limitation

**Applies:** open-world zones (all).
_source: r/atomicheart/comments/11ugobu · capture: manual_paste · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

Pchela repair bots **do not navigate inside buildings**. Enemies lured through a doorway or window into an interior space take full damage without repair bots being able to patch them. This is especially useful in the early open world when P-3 does not yet have a disabled HAWK relay and enemy health regeneration makes open fights resource-expensive.

**Practical use:** line-of-sight aggro an enemy from an open doorway, then back into the building before firing. The fight ends in an interior; robots don't regenerate; smaller loot cost.

---

## Weapon and Perk Upgrade Respec -- Free

**Applies:** all NORA stations.
_source: items/abilities.md Overview (P1 ingestion); r/atomicheart/comments/11ugobu · capture: manual_paste · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

Respeccing weapons and abilities costs **nothing** at NORA stations. You can freely change your upgrade loadout at any time without spending resources. (See `items/abilities.md` Overview for the slot system.)
