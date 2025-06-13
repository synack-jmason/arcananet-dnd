# 📁 ArcanaNet One-Shot – Project Structure Overview

This file outlines the recommended folder structure and content purpose for organizing the ArcanaNet one-shot campaign in a GitHub repository.

---

## 📂 Root Directory: `/ArcanaNet`

Top-level folder for the project. Include:

* `README.md` – High-level overview of the project, campaign tone, setup instructions, and player expectations.
* `LICENSE` – If distributing publicly, define usage rights.

---

## 📁 `/characters`

Contains all 15 player character files in Markdown format.

* Each file: `[name].md` (e.g., `marcus.md`, `zoe.md`)
* Naming Convention: lowercase, no spaces, use hyphens or underscores if needed.

---

## 📁 `/encounters`

Used for encounter write-ups, enemy groups, boss fights, and narrative combat blocks.

* `arcananet_antagonists.md` – Overview of major factions and bosses (Lazarus, Fancy Bear, etc.)
* `[encounter_name].md` – e.g., `bloodminers_lair.md`, `staticpaw_temple.md`

---

## 📁 `/story`

Supports plot structure, timeline, and scene design.

* `plot_outline.md` – Three-act structure or session progression overview
* `scene_beats.md` – Boxed text and GM prompts
* `timeline.md` – Key in-world events leading to the one-shot

---

## 📁 `/npcs`

Detailed profiles for recurring or major NPCs.

* `emmy_clickbaiter.md`
* `bront_the_rewriter.md`
* `nyah_staticpaw.md`
* `lazarus_voice_interface.md`

These can be cross-referenced from encounters or story files.

---

## 📁 `/assets`

Maps, visual aids, printable props, character art.

* `maps/` – Node 7 diagram, firewall core map, backdoor temple
* `tokens/` – Character and enemy tokens
* `badges/` – ArcanaNet symbol or player handouts

---

## 📁 `/guides`

Helper files for the GM or new players.

* `gm_quickstart.md` – How to run the session
* `player_briefing.md` – What the players know going in
* `rules_summary.md` – Homebrew rules, potions as bonus actions, etc.

---

## 📁 `/tools` *(optional)*

Scripts, generators, or printable sheets to randomize names, surge effects, etc.

* `wild_magic_generator.md`
* `loot_table_generator.md`

---
