# Atomic Heart — Hintforge Companion

![Atomic Heart companion status — coverage, live-game verification, spoiler control, and save reader](assets/readme-status-card.svg)

A spoiler-controlled hint companion for **Atomic Heart**, the first-person action-RPG set in an alternate 1955 USSR. Built in the [Hintforge](https://github.com/hintforge/builder) format: a loyal sidekick that answers only from these guide files — never from guesswork — at the spoiler level you set, and that tracks where you are so you can step away and pick back up.

## Use it

You need a Hintforge reader running in Claude Code, Codex, or OpenClaw. Point it at this repo:

> Load the Atomic Heart guide from github.com/hintforge/atomic-heart

Then just ask — *"how do I beat this fight," "how does this puzzle work," "where was I."* Runtime setup lives in [`hintforge/reader`](https://github.com/hintforge/reader).

## Spoilers & the save reader

**You** control how much this guide volunteers, through two independent dials you set:

- **Enemy warnings (Tier 0–5)** — from "say nothing" up to full boss strategy.
- **Puzzle warnings (Tier 0–3)** — from "silent, ask when you want a hint" up to a step-by-step walkthrough.

Both start **silent** — the guide volunteers nothing pre-emptively until you raise a dial (*"set enemy warning to tier 3"*). The guide only honors what you set.

The one place spoilers are genuinely hard to contain is the **save-state reader**. Atomic Heart's save is encrypted, so the reader sees only the plain header — your current zone and equipped glove skills, nothing deeper. Even that can hint at where the story goes next, so if a spoiler ever slips it will be in save-reader output, not in the guide's answers. One such leak (unprompted next-step volunteering after a save read) was caught and fixed in May 2026; leak reports are always dated to the version they happened on, because the gating is still being tightened.

## What's inside

A structured Markdown corpus — mechanics, zone navigation, enemies/NPCs, items, puzzles, optional zones, and all 82 achievements (base game + DLC) — plus a save-state watcher (`save_watcher.py`) that reports your position spoiler-safely. Interactive planners (skill-tree, weapon-upgrade) are on the roadmap, not yet built. The companion reads and writes only the files you control.
