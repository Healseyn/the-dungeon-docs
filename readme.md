# The Dungeon

> **Version:** Pre‑Alpha 0.1 • *Last updated: 13 Jun 2025*

Welcome to **The Dungeon** — a cooperative, real‑time, browser‑based MMO where **every player in the world attacks the same monster together**. Built with **Next.js**, **Tailwind CSS** and **Socket.IO** on the frontend and powered by the **Solana blockchain** for ownership and rewards, The Dungeon delivers a lightweight “click to slay” experience that scales from casual mobile play to coordinated PC raids.

---

## Quick pitch

* **Team clicker combat** – Your taps add to the global damage pool; unleash spells for massive bursts.
* **On‑chain rewards** – Earn the \$ESSENCE token as you fight. Claim, trade, or spend it on upgrades.
* **No installs, no barriers** – Everything runs in a single web page. Connect any Solana wallet and jump in.
* **Community‑driven** – Open‑source client & server, transparent economy, rapid iteration with player feedback.

---

## Gameplay loop

1. **Join the current encounter** – A single boss monster spawns for all connected players.
2. **Attack** – Click or tap to deal damage. Your base damage scales with your token balance and level.
3. **Cast spells** – Spend tokens on powerful abilities (e.g., *Fireball*, *Void Sigil*) to push the team closer to victory.
4. **Claim rewards** – When the boss falls, loot drops proportionally to your contribution.
5. **Prepare for the next wave** – Tougher monsters spawn, new spells unlock, leaderboard resets.

---

## Tech stack

| Layer          | Choices                                                 |
| -------------- | ------------------------------------------------------- |
| **Frontend**   | Next.js 14 · React 18 · Tailwind CSS · Socket.IO client |
| **Backend**    | Node.js · Express · Socket.IO server                    |
| **Blockchain** | Solana SPL tokens · Wallet Adapter                      |
| **CI/CD**      | GitHub Actions · GitHub Pages (Docs)                    |

For a deep dive into the codebase see the [thedungeon‑frontend](https://github.com/Healseyn/thedungeon-frontend) repository.

---

## Getting started locally

```bash
# 1. Clone the frontend
$ git clone https://github.com/Healseyn/thedungeon-frontend.git

# 2. Install dependencies
$ cd thedungeon-frontend && npm install

# 3. Provide environment variables
$ cp .env.example .env.local
# -> set NEXT_PUBLIC_SOCKET_URL and other keys

# 4. Run dev server
$ npm run dev    # http://localhost:3000
```

A detailed setup guide (including backend & database) lives in **Tech ▶ Build & Deploy**.

---

## Roadmap snapshot

| Phase   | Milestone                      | ETA      |
| ------- | ------------------------------ | -------- |
| **0.2** | Mobile UI polish               | Jul 2025 |
| **0.3** | Multiple monsters & HP scaling | Aug 2025 |
| **0.5** | PvP damage events              | Sep 2025 |
| **0.9** | Token launch on Pump.fun       | Oct 2025 |
| **1.0** | Public beta & main‑net rewards | Dec 2025 |

*(Full interactive roadmap will be added soon.)*

---

## Community & links

* **Discord:** `https://discord.gg/thedungeon`
* **Twitter / X:** `@TheDungeonGame`
* **GitHub (code):** `Healseyn/thedungeon-frontend`

Have suggestions or found a bug? Open an issue or pull request — we welcome contributions!
