# Gezenguz ED Monitor v1.1

Elite Dangerous companion app — multi-commander journal tracking, exploration, nav route, leaderboards, and more.

[![Version](https://img.shields.io/badge/version-1.1-orange.svg)](https://github.com/gezenguz/gezenguz-ed-monitor)
[![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red.svg)]()

---

## Features

- **Real-time journal monitoring** — automatic detection and processing of Elite Dangerous journal files
- **Multi-commander support** — track multiple commanders with individual data isolation
- **Exploration tracking** — high-value body detection, exobiology, FSS/DSS data
- **Nav route** — next systems in route with scoopable star indicators
- **Mining tracker** — prospector feed, session totals, hotspot data
- **Engineering** — material tracking, blueprint planner
- **Materials "Where to find"** — click any material for its sources, plus crystalline shard / brain tree systems
- **Leaderboards** — 38+ categories across all commanders
- **Powerplay** — rank/merit tracking with tier-based perk calculator
- **Community Goals** — progress tracking per commander
- **HGE sightings** — high-grade emission logging by material
- **Market prices** — commodity tracking across stations
- **Overlay** — in-game HUD overlay with live data
- **Friends** — find other commanders by name, send/accept friend requests
- **Colonisation** — track your construction projects (system, station, progress, remaining commodities); share projects with friends and see theirs in a focus panel
- **Colonisation helper / reservations** — reserve a quantity of a commodity for a friend's build so they get notified that you're bringing it ("X is helping with N units"); reservations are pure coordination and never alter the official remaining amount
- **CAPI** — Frontier API integration (token management in Settings)

---

## Requirements

- **Node.js 18+** — [Download](https://nodejs.org)
- **Elite Dangerous** (PC, journal files enabled)

---

## Installation

1. Download and extract the latest release
2. Run `install.bat`
3. Run `start_client_normal.bat` — launches the client; the console window closes after startup

> Use `start_client_debug.bat` instead if something goes wrong: it keeps the console open, shows errors, and pauses if the client crashes.

**First run:**
1. Enter your Commander name
2. Select your journal folder (auto-detected on most systems)
3. Click Register — API key is generated automatically

---

## License

© 2026 GEZENGUZ. All rights reserved.

---

*o7 Commanders*
