# Gezenguz ED Monitor v1.4

Elite Dangerous companion app — multi-commander journal tracking, exploration, nav route, leaderboards, and more.

[![Version](https://img.shields.io/badge/version-1.4-orange.svg)](https://github.com/gezenguz/gezenguz-ed-monitor)
[![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red.svg)]()

---

## Features

- **Real-time journal monitoring** — automatic detection and processing of Elite Dangerous journal files
- **Multi-commander support** — track multiple commanders with individual data isolation
- **Exploration tracking** — high-value body detection, exobiology, FSS/DSS data
- **Nav route** — next systems in route with scoopable star indicators
- **Mining tracker** — prospector feed, session totals, hotspot data
- **Engineering** — material tracking, blueprint planner
- **Loadout** — Odyssey suit & weapon planner with per-grade stats and modification effects
- **Materials "Where to find"** — click any material for its sources, plus crystalline shard / brain tree systems
- **Leaderboards** — 38+ categories across all commanders
- **Powerplay** — rank/merit tracking with tier-based perk calculator
- **Community Goals** — progress tracking per commander
- **HGE sightings** — high-grade emission logging by material
- **Market prices & trade routes** — commodity tracking across stations, best profit routes, and high-demand goods
- **Overlay** — in-game HUD overlay with live data, including an on-foot exobiology sampling assistant (live clonal-colony distance meter while collecting samples)
- **Friends** — find other commanders by name, send/accept friend requests
- **Colonisation** — track your construction projects (system, station, progress, remaining commodities); share projects with friends and see theirs in a focus panel
- **Colonisation helper / reservations** — reserve a quantity of a commodity for a friend's build so they get notified that you're bringing it ("X is helping with N units"); reservations are pure coordination and never alter the official remaining amount
- **CAPI** — Frontier API integration; signing in is required to use the app (token management in Settings)

---

## Requirements

- **Windows** (PC)
- **Elite Dangerous** with journal files enabled

---

## Installation

Download **`gezenguz-ed-monitor-client-full.zip`** from the [Releases](https://github.com/gezenguz1234/Gezenguz-ed-monitor/releases) page. Everything — including the Electron engine — is bundled, so there is no separate download and no `install.bat`.

1. Create a new empty folder for the app
2. **Add that folder to your antivirus exclusions** *(Avast: Menu → Settings → General → Exceptions → Add)* — some antivirus tools flag the bundled `electron.exe`
3. **Extract** the zip into the folder
4. Run `start_client_normal.bat`

> Use `start_client_debug.bat` instead if something goes wrong: it keeps the console open and shows errors.

**First run:**
1. Enter your Commander name
2. Select your journal folder (auto-detected on most systems)
3. Click Register — API key is generated automatically

---

## Community & Feedback

Questions, ideas, or bug reports? Join the Discord — that's the best place to reach me:

**[discord.gg/JhhfkQgPS](https://discord.gg/JhhfkQgPS)**

---

## License

© 2026 GEZENGUZ. All rights reserved.

---

*o7 Commanders*
