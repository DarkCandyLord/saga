<img src="docs/screenshots/hero.png" width="100%" alt="Saga" />

<div align="center">

# Saga

**Campaign tracker for tabletop RPGs**

</div>

---

Every campaign I've run eventually turns into a mess of browser tabs, notebooks, and half-remembered NPC names. Saga is the one place where all of it lives — characters, sessions, timelines, dice rolls, initiative order — so I stop losing things between session three and session four.

Works for D&D, Pathfinder, or whatever system you're running. It doesn't care about your edition.

---

## What You Get

- **One interface for everything** — Characters, sessions, milestones, badges, NPCs, and a full timeline instead of six different documents
- **Dice roller that's always there** — Floating button accessible from any tab. Roll without leaving what you're doing
- **Initiative tracker** — Add combatants, roll, step through turns. Built for running combat at the table, not prepping for it
- **NPC directory** — Searchable, filterable. When a player says "who was the merchant in Thornwall?" you have the answer
- **Badge system** — Four rarity tiers for rewarding memorable player moments. Surprisingly motivating
- **Onboarding wizard** — New to this? Four steps, under a minute, you're running
- **Install it on your phone** — PWA-ready. Runs like a native app at the gaming table

---

## Screenshots

<img src="docs/screenshots/feature-1.png" width="100%" alt="Campaign dashboard with character roster, session timeline, and quick stats" />

*Campaign dashboard — roster, timeline, and the stuff you actually need mid-session*

<img src="docs/screenshots/feature-2.png" width="100%" alt="Landing page with feature highlights" />

*Landing page with feature breakdown*

<img src="docs/screenshots/mobile.png" width="50%" alt="Saga on mobile" />

*Mobile layout — built for use at the table, not just on a desktop*

---

<details>
<summary>Under the Hood</summary>

<br>

**Stack:** Next.js 15, TypeScript, React 19, Tailwind CSS, Prisma 6, SQLite, Framer Motion

- Decomposed components — no file over 250 lines, every tab dynamically imported
- 19 API routes across campaigns, characters, badges, sessions, milestones, dice, encounters, NPCs
- SQLite via Prisma — no database server, no config, just works
- PWA manifest for mobile installation

</details>

---

## Part of the Toolkit

Saga is one of seven tools I built for people who run imaginary worlds. See the full set on [my profile](https://github.com/DarkCandyLord).

*Your campaign is worth more than a Google Doc.*
