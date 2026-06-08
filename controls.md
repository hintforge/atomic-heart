# Atomic Heart — Controls

**status:** research-integrated
**last_updated:** 2026-05-08
**research_run:** P1 deep research 2026-05-08

---

## KB&M Sprint-Lock Issue (read first — PC players)

**Cause:** the game's input system pipes keyboard movement at 100% magnitude. A controller's analog stick varies 0.0–1.0, allowing walk/jog/sprint differentiation. On keyboard, there is no way to express less-than-full magnitude — so **PC players are permanently sprinting** at all times.

**Consequences:**
- The "Morning Exercise" character upgrade (movement speed bonus) is wasted — sprinting is already the only speed.
- Stealth is compromised (sprint = louder footsteps).
- Any mechanic that distinguishes jog from sprint doesn't fire correctly.

**Fix — r3visited controls mod (Nexus Mods #46):**
The `r3visited controls for Keyboard and Mouse` mod sets the default movement to jog (50% or 65% baseline variants) and adds Shift-to-sprint. It also remaps lockpicking to A/D (vs. default Q/E) and fixes diagonal-double-speed in newer versions.

- Nexus Mods page: [https://www.nexusmods.com/atomicheart/mods/46](https://www.nexusmods.com/atomicheart/mods/46)
- **Install before Chapter 1** (the problem is apparent from the first hallway of Vavilov).
- Verify mod is current for your game patch before installing.

**Alternative:** Manual `Input.ini` edit to lower base movement magnitude (less reliable; community reports mixed results).

**Controller:** No sprint-lock issue. Analog stick gives full walk/jog/sprint range naturally. If the sprint-lock bothers you, play with Xbox/DualSense.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: Nexus Mods r3visited #46 mod page; Reddit threads; TechRaptor]

---

## PC (KB&M) Default Bindings

| Action | Default key | Notes |
|---|---|---|
| Move (WASD) | W / A / S / D | Locked to sprint speed by default — see sprint-lock issue above |
| Jump | Space | |
| Crouch (toggle) | C or Ctrl | |
| Dodge | Shift | **Conflicts with sprint if installing r3visited — reassign** |
| Fire | Left Click | |
| Aim (ADS) | Right Click | |
| Reload | R | **Also** used as Scanner hold — there is a timing window; hold R for scanner, tap R for reload |
| Scanner | Hold R (or Tab) | |
| Use Polymer ability | Q (toggle polymer mode) + Left Click | |
| Switch ability slot | F (or D-Pad equivalent) | |
| Weapon wheel | Hold Tab | |
| Cartridge swap | Middle-click | **Undocumented** in-game; fastest cartridge switching method |
| Use Neuromed (heal) | X | |
| Interact / Enter or exit vehicle | F | Same key for both; confirmed live 2026-05-12 |
| Lockpick rotate | Q / E (default) → A / D (r3visited mod) | r3visited changes this; less cramped with A/D |
| QTE inputs | Q / E (default) → Left Click / Right Click (r3visited) | Plyusch grapple QTE is 4-button; missing = instant kill unless Auto-QTE enabled |

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: GameNGuides, MagicGameWorld, MP1st, Nexus r3visited #46]

### Remapping notes (PC)

Full remap available in Settings > Controls. **Known limit since Patch 1.14.4.0:** multi-action key binding removed (e.g., E cannot be assigned to both "interact" and "vehicle accelerate" simultaneously). [Confirmed: PCGamingWiki]

**Accessibility note:** Xbox/PS console versions have no in-game remap option — use system-level controller remap (DualSense Edge / Xbox Accessories app).

---

## Controller Bindings (Xbox / DualSense — identical mapping, different glyphs)

| Action | Xbox | PS |
|---|---|---|
| Move | Left stick | Left stick |
| Look | Right stick | Right stick |
| Sprint | L3 (click) | L3 |
| Jump | A | × |
| Dodge | B | ○ |
| Crouch | L3 click (toggle) | L3 (toggle) |
| Fire | RT | R2 |
| Aim (ADS) | LT | L2 |
| Use ability | LB | L1 |
| Swap ability slot | D-Pad ↑ | D-Pad ↑ |
| Switch weapon (next) | D-Pad → | D-Pad → |
| Reload | X | □ |
| Weapon wheel | Hold X or RB | □ or R1 |
| Scanner | Hold RB | Hold R1 |
| Use Neuromed | LB-hold or quick-item | L1-hold |
| Interact | Y | △ |

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: MP1st controller config guide, PrimaGames]

---

## Remap Recommendations (community consensus)

| Recommendation | Why |
|---|---|
| Bind **cartridge swap** to a mouse side button (thumb button) | Default middle-click on wheel is slow in a fight; side button is instant |
| Install **r3visited mod (Nexus #46)** before Ch.1 | Eliminates the sprint-lock issue; also remaps QTE to LMB/RMB and lockpick to A/D |
| **Auto-QTE on** (Settings > Accessibility, Patch 1.14.4.0+) | Plyusch grapple is a 4-input QTE; missing any input = instant kill; Auto-QTE eliminates this |
| Disable mouse smoothing | Set `bEnableMouseSmoothing=False` in `%LOCALAPPDATA%\AtomicHeart\Saved\Config\WindowsNoEditor\Input.ini` if not exposed in your patch |

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: PCGamingWiki, Reddit threads, Nexus r3visited #46, GGRecon]

---

## Mouse Sensitivity

- Mouse sensitivity slider in Settings > Controls.
- Mouse-sensitivity tool has an Atomic Heart profile: https://www.mouse-sensitivity.com/updates/updates/atomic-heart-r1151/ (verify current)
- Deadzone tuning (controller): **Engine.ini deadzone override is likely non-functional as of patch 1.16.3.0.** PCGamingWiki no longer documents a working deadzone INI fix. Use **Steam Input → Controller Configuration → Calibration deadzone** instead. [Confirmed: Steam community discussions; P3 gap-fill 2026-05-09]

---

## DLC — Techno-Stasis binding (Annihilation Instinct)

**Techno-Stasis** is activated with **Q** (PC default) — the same key as the base-game "Use Polymer ability" toggle. The DLC context-switches automatically since Shok/Frostbite/Mass TK are absent. No rebind required.

_source: Compass P3 deep research 2026-05-09 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:annihilation_instinct_
[Confirmed: walkthroughs.games hidden-features guide (EN/RU, 2023), notesread (EN, 2023)]

---

## Sources

- [r3visited controls mod — Nexus Mods #46](https://www.nexusmods.com/atomicheart/mods/46)
- [PCGamingWiki — Atomic Heart](https://www.pcgamingwiki.com/wiki/Atomic_Heart)
- [GameNGuides, MagicGameWorld, MP1st — full bindings reference]
- [All Atomic Heart Controls (PC/PS/Xbox) — GameSkinny](https://www.gameskinny.com/tips/all-atomic-heart-controls-list-for-pc-playstation-and-xbox/)
