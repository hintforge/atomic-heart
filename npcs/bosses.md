# Enemies — Boss Reference

**status:** research-integrated
**last_reconciled:** 2026-05-08
**research_run:** P1 (Compass/Deep Research 2026-05-08)

> **Enemy tier 0 is active.** This file exists for post-encounter reference only. Do NOT volunteer boss names, tactics, or existence preemptively. After P-3 encounters a boss and asks for help, full post-encounter guidance is permitted from this file.

> **Naming convention -- boss vs. standard variants:** Atomic Heart (Russian-developed) reuses enemy names for both unique scripted boss encounters and standard farmable enemy variants. Each entry below notes its standard-variant status:
> - `[std-variant: confirmed]` -- a regular non-boss version of this enemy type is confirmed to exist
> - `[std-variant: suspected]` -- likely exists as a regular enemy but not yet confirmed in corpus
> - `[std-variant: unknown]` -- no information on whether a standard farmable variant exists
> Drop sources in `crafting_materials.md` that list these enemy names likely refer to the standard variant, not the boss encounter.

> **Cross-system dependency** -- see `dependencies.md` DEP-023: This taxonomy governs how the reader interprets every premium-material drop source in `items/crafting_materials.md`. The flags here are the authoritative source; `crafting_materials.md` mirrors them per-material.

Boss entries are ordered by story encounter. Each entry includes: zone, weaknesses, phase breakdown, and any missable achievement tied to the fight.

---

## Large Mutant (Pesticide Workshop)

**Zone:** `vavilov_pesticide_workshop` (Ch.1)
_source: gameranx blueprints, gamerant hardest-enemies — 2 sources · capture: web_fetch · confidence: medium · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: progression_

- Large mutant with a sprout-nest on its back.
- **Weakness:** Shotgun (KS-23). Glowing orange targets on the back deal critical damage — aim for those.
- Standard Ch.1 boss; no missable achievement tied to this fight.

---

## Hedgie / HOG-7
`[std-variant: confirmed]` -- a non-boss Hedgie appears in Vavilov Algae Workshop (Ch.1); EN wiki conflates the two. The Ch.3 HOG-7 is the scripted boss fight. Standard Hedgie variants may appear elsewhere as farmable enemies.

**Zone:** `arena_park` (Ch.3)
**Visual ID:** `sprites/hedgie.jpg` | Icon: `sprites/icons/T_Ejiha.png` (internal: T_Ejiha -- "ёж" = hedgehog, RU)
_source: PSNProfiles, daynglsgameguides, walkthroughs.games glava-3, pcgamesn — 5 sources · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: progression_

- Rolling sphere boss with coil-based attack pattern.
- **Weakness:** Use Shok ability on the central pedestal — this causes statues to rise from green floor cylinders. Position Hedgie to roll into a statue; it becomes stunned and exposes coils for damage.
- **Missable achievement — Strike:** To unlock "Strike," you must NOT fire any weapon at Hedgie. Let the statues deal all damage. On low difficulty, weapon hits will kill Hedgie before all statues are destroyed, forfeiting the achievement. This is a one-shot opportunity — first encounter only.

> **Cross-system dependency** — see `dependencies.md` DEP-013: "Strike" achievement → zero weapon use, first encounter only.
- **Disambiguation:** A different Hedgie variant appears earlier in the Vavilov Algae Workshop (Ch.1) — it smashes a window into the workshop. That is NOT this boss; English wiki conflates them.

---

## Plyusch (first encounter, VDNH Drill Mode)
`[std-variant: unknown]` -- appears in multiple encounters (TG9 mini-boss, Ch.7 Pavlov Bridge x3) but all are scripted fights. No confirmed open-world farmable variant in corpus.

**Zone:** `vdnh_drill_mode` (Ch.3)
**Visual ID:** `sprites/plyusch.jpg` | Icon: `sprites/icons/T_Plyush.png`
_source: gameranx Plyusch tactics, daynglsgameguides — 4 sources · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: progression_

- Large organic mutant boss.
- **Resistant to:** gunfire (negligible damage — many players waste ammo), freeze.
- **Vulnerable to:** fire, explosives, telekinesis.
- **Best combo:** Polymer Jet + Fat Boy (if available); fire-cartridge melee as fallback.
- **Community tip:** fire cartridge + Zvezdochka + timed dodges is widely cited as the easiest approach. The Zvezdochka's damage output with fire cartridge makes the fight straightforward once dodge timing is learned.
  _source: r/atomicheart/comments/11tazdc · capture: manual_paste · confidence: medium · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: progression_
- Plyusch also appears as a mini-boss inside Testing Ground 9, and three copies ambush P-3 at the Pavlov Bridge (Ch.5). Same weaknesses apply across all encounters.

> **Cross-system dependency** — see `dependencies.md` DEP-007: Plyusch weakness (fire/explosives/TK; not gunfire/freeze) is independently confirmed in `sections/ch7_bridge.md`. Carry fire-cartridge KS-23 to Ch.7 bridge.

---

## Belyash (Theater Grounds)
`[std-variant: CONFIRMED]` -- after the theater fight, Belyash respawns as a rare standard enemy in the open world, spawned from MTU-7 Bumblebee carriers (see new Fandom claim below). The earlier `[std-variant: suspected]` flag is now resolved.

**Zone:** `lastochkin_theater_grounds` (Ch.4)
**Full designation:** MA-9 Belyash (Fandom canonical name)
**Visual ID:** `sprites/belyash.jpg` | Icon: `sprites/icons/T_Belyash.png` | Backup: `sprites/belyash_2.jpg`
_source: PSNProfiles — 3 sources · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: progression_

- Tank-type boss fought outside the theater.
- **Phase 2:** Fires a flamethrower from its bulbous head — stay at a side angle to avoid the cone.
- **Missable achievement — Chop Chop Chop:** Kill Belyash using only melee weapons on the first encounter. Using any ranged weapon forfeits this achievement permanently. One-shot opportunity.

> **Cross-system dependency** — see `dependencies.md` DEP-014: "Chop Chop Chop" → melee only, first encounter only.

### Belyash standard-enemy spawn + lore (Fandom)

- **Standard-enemy variant confirmed:** After defeating the theater Belyash, Belyash becomes a rare standard enemy that spawns from MTU-7 Bumblebee (Machine class) carriers in the open world. Resolves the prior `[std-variant: suspected]` flag.
- **In-universe role:** MA-9 designed for installation/plumbing/welding; payload capacity ~½ ton; manufacturer guarantees ≥20 years service; argon-arc welding capability.
- **Shell + operating envelope:** Steel-and-titanium alloy shell; operational range -75 °C to +75 °C.
- **Chassis lineage:** Built on a chimpanzee-skeleton frame to climb steep surfaces and construction beams.
- **Tactical note (matches existing corpus):** Vulnerable in the head; landing a melee hit provokes a telegraphed power attack that can be dodged into a follow-up head strike.

_source: https://atomicheart.fandom.com/wiki/MA-9_Belyash · capture: mediawiki_parse · confidence: medium · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: progression · conflicts: none [worked example, captured via Fandom's first-party `api.php?action=parse&page=MA-9_Belyash` endpoint after BreezeWiki rung-2 attempts failed: `breezewiki.com` returned a captcha-gate page, `antifandom.com` returned a JS-only shell that hydrates content via the same Parse API. The Parse API is a distinct ladder rung from BreezeWiki (different host, different operator, different ToS surface) and so warrants its own `capture_method` value. Fandom page marked Stub at capture time 2026-05-20]_

---

## Natasha (Theater Stage / first encounter)
`[std-variant: suspected]` -- "Natasha-class variant" appears as TG12 boss (a second scripted fight, not a standard enemy). Research drop sources list Natasha as a farmable Microelectronics/Superconductor source -- this likely refers to a standard Natasha-type enemy distinct from both boss encounters. Not confirmed in corpus; verify in-game.

**Zone:** `theater_stage` (Ch.4)
**Visual ID:** `sprites/natasha.jpg` | Icon: `sprites/icons/T_Natasha.png` | Backup: `sprites/natasha_2.jpg`
_source: pcgamesn bosses — 3 sources · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: progression_

- Large tank-class boss; slow movement but heavy missile barrages.
- **Weakness:** Jet ports on the back — aim explosives + high rate-of-fire weapons there.
- Shok ability stalls Natasha temporarily.
- A Natasha-class variant also appears as the boss inside Testing Ground 12 (Ch.5). > **Cross-system dependency** — see `dependencies.md` DEP-010: Natasha weakness (jet ports + explosives + Shok stall) applies equally to TG12 variant — confirmed independently in `optional_zones/polygons.md`.

> **Cross-system dependency** — see `dependencies.md` DEP-018: LUC-1 Owls in this encounter respawn infinitely until Natasha is killed — focus Natasha first; Owls clear themselves.

---

## Dewdrop
`[std-variant: unknown]` -- only one encounter documented in corpus (lighthouse_beach, Ch.6). Research lists Dewdrop as a Microelectronics/Superconductor drop source; may refer to a standard variant that appears later. Verify in-game.

**Zone:** `lighthouse_beach` (Ch.6)
**Visual ID:** `sprites/dewdrop.jpg` | No InfoIcon found
_source: pcgamesn, globelivemedia, gamerant — 4 sources · capture: web_fetch · confidence: high · enemy-tier: 2 · puzzle-tier: 0 · category: mainline · spoiler: late-game_

- Agile mining-class boss; uses charge + laser attacks.
- **Phase 2:** Adds tentacle swipes and polymer ball projectiles.
- **Weakness:** Fat Boy launcher + Railgun; Shok stalls movement.
- Use the beached whale carcass on the shore as cover during phase 2.

---

## Twins (Left + Right, final fight)

**Zone:** `sechenov_office_final` (Ch.6)
**Visual ID:** `sprites/twins.jpg` | No InfoIcon found
_source: walkthroughs.games endings, dualshockers, sportskeeda — 5 sources · capture: web_fetch · confidence: high · enemy-tier: 3 · puzzle-tier: 0 · category: mainline · spoiler: story_

- Two distinct bosses fought sequentially: Left twin alone in the lobby, then both Left + Right in the glass plane room.
- **Missable achievement — Scanner:** Scanning Left and Right twins **individually** during the fight is required for the Scanner achievement. This is the final opportunity to scan them — their earlier appearance in the Chelomey prologue does NOT count.

> **Cross-system dependency** — see `dependencies.md` DEP-012: "Scanner" → Ch.10 fight only; prologue appearance does not register.
- Lore context: [spoiler:story — withheld at story tier 3; raise story tier to reveal]

---

## BEA-D Colossus (DLC — Annihilation Instinct)

**Zone:** `mendeleev_complex` (DLC)
_source: EN Fandom BEA-D Colossus page, GamingBolt DLC review, Steam DLC 100% guide 3020368999 · capture: web_fetch · confidence: high · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:Annihilation Instinct_
[Confirmed: 3 sources]

- Giant humanoid composed of ~40 fused BEA-Ds. Appears twice in the DLC.
- **Attacks:** Rapid jump/dash to close distance; wide arm sweeps that knock P-3 down; powerful laser from one arm (arm presses against torso periodically to vent/recharge before the next laser burst).
- **Weaknesses:** Techno-Stasis windows let you reposition out of the laser arc. **Klusha is comparatively weak against Colossus** (community consensus) — bring Secateur with fully-upgraded magazine + energy supercharger, plus Railgun or Fat Boy as secondary. Alenka chocolate buff heavily used on Armageddon difficulty for phases 2 and 3.
- **Phase structure:** _[enemy-tier: 1 — available post-encounter on request]_
- **Achievements (DLC):**
  - "Divide et Impera" — separate combined BEA-Ds with one Secateur shot (earlier room, not this fight)
  - "A Girl's Best Friend" — send all BEA-Ds to NORA's brain (end-of-DLC step)
  - "Maximum Strength" — fully upgrade both Klusha and Secateur (achievable before the 7th bead) — see `dependencies.md` DEP-021: farm ostrich BEA-Ds for Energy Modules before this point.
  - "Return to Utopia" — complete the DLC _[spoiler: dlc:Annihilation Instinct + story]_
- **Drops:** Boss-tier — Energy Modules, Superconductors, scripted DLC unlocks.

---

## Moray (DLC 3 -- Enchantment Under the Sea, final boss)

**Zone:** `enchantment_under_sea` (DLC 3 -- final encounter)
_source: r/atomicheart/comments/1tkw1i0 (score 122, 0.94 ratio; 42 comments; reddit_spoiler_tag: yes) · capture: manual_paste · confidence: medium · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:enchantment_under_sea_

- Serpentine boss ("tapeworm" colloquially). **Community consensus: hardest boss in the game, including all DLCs.**
- **Primary threat:** shockwave orb projectile attacks (multiple orbs per burst). These deal massive damage and are the main source of wipes.
- **Community-recommended loadout:** polymeric whip (fully upgraded) + horizontal shotgun mod. Widely cited as the most effective combination for this fight.
- **Strategy:** sustained high mobility; dodge shockwave orbs as priority; use polymeric whip for DPS windows.
- Community reports this boss as harder than the DLC 4 final boss despite coming first chronologically.

---

## DLC 4 Final Boss ("CHAR-les") -- Blood on Crystal

**Zone:** `blood_on_crystal` (DLC 4 -- final encounter)
_source: r/atomicheart/comments/1tkw1i0 (comments by nate_mcrock91 score 4, Cyberbreaker2004 score 10, TheFurtivePhysician score 4; reddit_spoiler_tag: yes) · capture: manual_paste · confidence: medium · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:blood_on_crystal_

> **[boss identity name withheld at story tier -- deliver name only when player reaches DLC 4]**

- Final boss of Blood on Crystal (DLC 4).
- **Community verdict:** considered significantly easier than Moray despite being the narrative climax boss. Described as "anticlimactic" by multiple commenters.
- **Strategy:** ignore tentacles and blobs -- they are not the priority. Focus all fire on the face. Watch platform edges (falling off is the primary failure mode). Shotgun recommended for face shots.
- **Known bug -- first-attempt softlock:** The first attempt at this boss has a confirmed softlock bug. If the fight freezes or locks up on first try, reload and re-attempt. The second attempt proceeds normally.
  _source: r/atomicheart/comments/1suhzwz (OP report); r/atomicheart/comments/1tkw1i0 · capture: manual_paste · confidence: medium · enemy-tier: 1 · puzzle-tier: 0 · category: mainline · spoiler: dlc:blood_on_crystal_
