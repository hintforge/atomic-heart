# Atomic Heart — Limitations & Blocked Sources

Sources I found that look useful but couldn't fully fetch — paywalls, Cloudflare, age gates, video-only content, etc. URLs preserved so P-3 (or another contributor) can open them in a real browser.

## How to read this file
- Each entry: topic, URL, block type, what I could glean, best alternative I did get to.
- Each per-topic file (in `puzzles/`, `testing_grounds/`, `items/`, `npcs/`) also lists its own blocked sources at the bottom -- P-3 rarely needs to come hunting here.
- This file is the catch-all for sources that didn't fit a specific topic.

## Block types
- **paywall** — content gated behind a subscription or article limit
- **cloudflare** — Cloudflare bot challenge / 403 / 503 from WebFetch
- **video-only** — YouTube or other video where the answer is shown visually; no readable text equivalent
- **age-gate** — content blocked behind age verification
- **cookie-wall** — popup or consent flow that broke the fetch
- **search-snippet-only** — search engine returned a snippet but the page itself wasn't reachable
- **dead-link** — URL was in another source but no longer resolves

## Source licenses

- **Atomic Heart Fandom Wiki** (atomicheart.fandom.com) -- licensed **CC BY-NC-SA**. Content is usable for non-commercial purposes with attribution and share-alike. Applies to any claim sourced from Fandom wiki pages. Do not use Fandom wiki content in any commercial or redistributed context without checking this license.

## Entries

### Fandom Wiki Interactive Maps -- open world locations
- Source: https://atomicheart.fandom.com/wiki/Special:AllMaps
- Block type: **dead-link** (page exists but no maps have been created -- "Create an interactive map" placeholder only)
- Why I thought it had the answer: Fandom's interactive map feature sometimes has community-created overlays for popular games
- What I could glean: nothing -- no maps exist for Atomic Heart on this wiki as of 2026-05-19
- Best alternative: in-game map satellite dish icons for HAWK relay locations; scan-line method to trace Dandelion cameras back to terminals

### Interactive map tools (MapGenie / GamerMaps / community overlays) -- open world
- Source: searched MapGenie, GamerMaps, community map sites
- Block type: **dead-link** (no Atomic Heart interactive map found on any major community map platform)
- Why I thought it had the answer: most open-world games get MapGenie coverage
- What I could glean: Atomic Heart did not attract this level of community map tooling -- game is smaller-community than typical MapGenie titles
- Best alternative: in-game map + scan method; numbered HAWK sector boundaries visible on map

## Persona operating rule (added 2026-05-21)

For specific room-level navigation questions where the corpus is thin and the answer requires visual context (ledge positions, platform geometry, exact Shok targets), link the relevant YouTube walkthrough **before** attempting a text answer. Text guessing on visual puzzles is worse than useless. Search pattern: `"Atomic Heart [Zone Name] walkthrough" site:youtube.com`.

### Blood on Crystal DLC -- achievement list
- **RESOLVED 2026-05-22.** All 13 Blood on Crystal achievements populated in `achievements.md` via targeted deep-research. Sources: Imagine's Steam Community 100% guide, Treyex Gaming, GAMES.GG, iXBT.games, TrueAchievements DLC page, Steam Hunters. Total count confirmed at 82. Block entry retained for audit trail; gap is closed.

## Always-blocked categories

- **Visual-only puzzle solutions**: some Atomic Heart puzzles (particularly the Tetris-block relays) are demonstrated in video walkthroughs without text transcription. If no text guide exists, note the video timestamp rather than leaving the puzzle empty.
- **Russian-language forums**: VK groups and DTF.ru may require login or have Cloudflare protection. Flag and preserve the URL; the research brief asks for translated excerpts.
