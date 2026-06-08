# Atomic Heart — Settings

**status:** research-integrated
**last_updated:** 2026-05-08
**research_run:** P1 deep research 2026-05-08

**Patch reference:** Latest base-game feature patch is **1.14.4.0** (June 11, 2024) — added ray tracing beta, full accessibility suite, FSR-disable crash fix, and multi-action key-bind removal. Subsequent patches (through 1.16.3.0 as of April 2026) are DLC-focused with minor base-game fixes.

---

## Quick start recommendations (apply before Ch.0)

1. **Motion blur:** OFF
2. **Chromatic aberration:** OFF
3. **Depth of field:** OFF
4. **FOV:** Slider maximum (~95–100 effective)
5. **Mouse acceleration:** OFF (toggle in Settings > Controls, or Input.ini hack)
6. **VO language:** Russian (with English subtitles) — widely recommended as superior audio (see Audio section)
7. **Auto-QTE:** ON (Settings > Accessibility) — eliminates the 4-button Plyusch grapple instant-kill risk
8. **KB&M players:** install r3visited mod (Nexus #46) before Ch.1 — see `controls.md`

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 5 sources — PCGamingWiki, GGRecon, GamesRadar, Hard-Drive.net, Escapist]

---

## Graphics

### Motion Blur

**Toggle:** ON/OFF (added Patch 1.3.4). **Recommendation: OFF.** Driving the Moskvitch car with default blur is the most-reported motion-sickness source. Also reduces readability of boss AoE circles.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: Overclockers UK forum thread, PCGamingWiki, Steam guide]

### FOV Slider

**Menu location: Settings > Gameplay** (confirmed live 2026-05-13). **Range:** added in Patch 1.3.4; slider goes to ~+25 effective. Flawless Widescreen mod can push to ~+40%. **Community recommended: max in-slider (~95–100 effective).** Tighter FOV causes disorientation in Vavilov's corridors and during fast combat.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: GGRecon, GamesRadar, Hard-Drive.net]

### Chromatic Aberration

ON by default. **Recommendation: OFF** for clarity in dark environments and text readability.

### Depth of Field

**Recommendation: OFF** for combat. DoF obscures boss AoE circles (Hedgie's red ring in particular is hard to see with DoF on).

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: PCGamingWiki, Steam guide]

### Ray Tracing (Patch 1.14.4.0+)

Three presets: **Performance / Quality / Balanced.** Requires DXR-capable GPU + ≥12GB VRAM. Notes:
- Player character does not reflect in mirror surfaces (known cosmetic issue).
- Disables FSR automatically when active.
- CPU-bottlenecked; community sentiment: "novelty, not transformative."
- Recommended only if you have RTX 3080+ or RX 6800 XT+.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: PCGamesN, Wccftech, DSOGaming, Destructoid]

### DLSS / FSR

- **DLSS 3.1.1** included.
- **FSR:** advertised as FSR 2 but shipped as FSR 1 (spatial upscaling only, with FSR 1 artifacts). Community confirms mismatch. [Confirmed: PCGamingWiki]
- If image quality is poor with FSR, try DLSS if you have an NVIDIA GPU, or disable upscaling entirely.

### HDR

Not officially exposed in the settings menu. Community Engine.ini hack:
```
r.AllowHDR=1
r.HDR.EnableHDROutput=1
r.HDR.Display.OutputDevice=5
r.HDR.Display.ColorGamut=2
```
Results vary widely by monitor; color shifts reported. [Confirmed: GamePretty] [Single source — test carefully]

### Performance tiers (PC)

| Target | CPU | GPU | RAM |
|---|---|---|---|
| 1080p / 30fps / Low | i5-2500 or Ryzen 3 | GTX 960 / RX 470 | 8GB |
| 1080p / 60fps / Ultra | i7-7700 or Ryzen 5 1500X | GTX 1060 6GB / RX 580 | 16GB |
| Ray Tracing beta | — | RTX 3080+ / RX 6800 XT+ with 12GB+ VRAM | 16GB+ |
| Steam Deck | — | officially compatible since 1.3.4; runs ~30fps Medium; shader-comp stutter on first run | — |

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: PCGamingWiki, TheLoadout, ClutchPoints]

---

## Audio

### Voice language recommendation

**Russian VO + English subtitles** is the overwhelming community recommendation (~95% of guides agree). The English VO for the protagonist and Char-les is divisive; the Russian original is widely considered superior quality.

To set: Main Menu → Settings → Audio → Voice Language → Russian. Subtitles stay in English.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: Steam Community guide, multiple Reddit threads; translated from: ru via Steam DE-RU community thread]

### Standard audio sliders

Master / SFX / VO / Music — all present. No unusual settings.

### Char-les chatter mod (optional)

**199 Char-les voice lines were cut in Patch 1.6.0.0** due to player complaints about excessive chatter. A Nexus Mods mod restores them. If you want the full intended chatter experience, install before Ch.1.

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: PCGamingWiki — sourced from Mundfish patch note]

### Subtitle background

Added in Patch 1.3.4. **Recommendation: ON** — Char-les's banter overlaps with environmental dialogue; background improves readability during layered audio.

---

## Accessibility (added Patch 1.14.4.0)

| Setting | Notes |
|---|---|
| **Colorblind modes** | Deuteranopia, Protanopia, Tritanopia | Enable at Forester's Village (Ch.2) to see laser-tripwire colors clearly |
| **Special-contrast mode** | High-contrast alternative | |
| **Black-and-white mode** | | |
| **Element highlight** | Highlights interactive objects | |
| **Auto-QTE** | Auto-wins all Plyusch grapple QTEs | **Strongly recommended** — missing a 4-input QTE is an instant kill regardless of HP |
| **Auto-heal** | Automatically uses Neuromed when HP drops low | Optional; manual gives more Neuromed economy |
| **Subtitle size + background** | Added Patch 1.3.4 | Increase for readability in Academy of Consequences (dense monologue subtitles) |
| **HUD scaling** | Added Patch 1.3.4 | |
| **Controller deadzone** | **Not exposed in-game** — requires Engine.ini override; see PCGamingWiki | [Single source — verify before relying on it] |

_source: P1 deep research 2026-05-08 · capture: web_fetch · confidence: high · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_
[Confirmed: 4 sources — Mundfish X/Twitter, ClutchPoints, PCGamesN, Destructoid]

---

---

## Known Platform Bugs

### Steam Achievement Reset Bug (PC)

Steam achievements can silently reset to 0% progress when starting a new game. Save files are not affected -- only the Steam achievement tracking layer resets. Reported by multiple community members; particularly noted after starting NG+.

**Workaround:** SAM (Steam Achievement Manager) tool to restore lost achievement progress. Community consensus: using SAM for this specific case (restoring already-earned achievements that were erased by a bug) is in a grey zone but widely accepted. See `achievements.md` Known Bugs section for full details.

_source: r/atomicheart community threads · capture: manual_paste · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: none_

### Blood on Crystal Windows Launch Bug (PC -- RESOLVED)

BoC had a Windows-specific crash-on-launch bug at release (April 2026). Patched and fully resolved in the first post-launch update. No workaround needed. If guides reference this, the fix is already live -- update the game.

_source: r/atomicheart/comments/1suhzwz · capture: manual_paste · confidence: medium · enemy-tier: 0 · puzzle-tier: 0 · category: mainline · spoiler: dlc:blood_on_crystal_

---

## Sources

- [PCGamingWiki — Atomic Heart](https://www.pcgamingwiki.com/wiki/Atomic_Heart) — input, API, settings reference
- [GGRecon — FOV and settings guide](https://www.ggRecon.com/)
- GamesRadar; Hard-Drive.net; PCGamesN; Wccftech; DSOGaming
