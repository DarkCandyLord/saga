<img src="docs/screenshots/hero.png" width="100%" alt="Saga" />

<div align="center">

# Saga

**Campaign tracker for tabletop RPGs**

[Live Demo](https://saga-app-nine.vercel.app)

</div>

---

Every campaign I've run eventually turns into a mess of browser tabs, notebooks, and half-remembered NPC names. Saga is the one place where all of it lives — characters, sessions, timelines, dice rolls, initiative order — so I stop losing things between session three and session four.

I built this to learn full-stack development by making something I'd actually use. Nineteen API endpoints later, it's the most complete project in my portfolio and the one I learned the most from.

---

## What It Does

- **8-tab interface** — Characters, sessions, milestones, badges, NPCs, timeline, combat, and export. Everything lives in one place
- **Dice roller** — Floating button accessible from any tab. Roll without leaving what you're doing
- **Initiative tracker** — Add combatants, roll, step through turns. Built for running combat, not prepping for it
- **NPC directory** — Searchable, filterable. When a player asks "who was the merchant in Thornwall?" you have the answer
- **Badge system** — Four rarity tiers for rewarding memorable moments
- **Onboarding wizard** — Four steps, under a minute, you're running
- **PWA** — Installable on your phone for use at the gaming table

Works for D&D, Pathfinder, or whatever system you're running.

---

## Screenshots

<img src="docs/screenshots/feature-1.png" width="100%" alt="Campaign dashboard" />

*Campaign dashboard — roster, timeline, and the stuff you actually need mid-session*

<img src="docs/screenshots/feature-2.png" width="100%" alt="Feature overview" />

<img src="docs/screenshots/mobile.png" width="50%" alt="Saga on mobile" />

*Mobile layout — built for the table, not just a desktop*

---

<details>
<summary>Technical Details</summary>

<br>

**Stack:** Next.js 15, TypeScript, React 19, Tailwind CSS, Prisma 6, PostgreSQL, Framer Motion

- Decomposed components — no file over 250 lines, every tab dynamically imported
- 19 API routes across campaigns, characters, badges, sessions, milestones, dice, encounters, NPCs
- PostgreSQL via Prisma with Neon serverless
- PWA manifest for mobile installation

</details>

---

Part of a [set of tools](https://github.com/CandyFlex) I built for people who run tabletop games. This is the most complete one.
