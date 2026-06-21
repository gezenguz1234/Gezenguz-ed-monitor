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

There are **two download packages** on the Releases page — pick one:

| Package | Size | Use when |
|---|---|---|
| **`gezenguz-ed-monitor-client.zip`** (Standard) | small | The normal case. Runs `install.bat`, which downloads the Electron engine. |
| **`gezenguz-ed-monitor-client-full.zip`** (Full / antivirus-friendly) | ~110 MB | Your antivirus (e.g. Avast) blocks the Electron download. Everything is bundled — **no download, no `install.bat`**. |

### Standard package

1. Download and extract the latest release
2. Run `install.bat`
3. Run `start_client_normal.bat` — launches the client; the console window closes after startup

> Use `start_client_debug.bat` instead if something goes wrong: it keeps the console open, shows errors, and pauses if the client crashes.

### Full / antivirus-friendly package

Use this if your antivirus blocks `electron.exe`. Nothing is downloaded, so there is no download for the antivirus to block.

1. Create a new empty folder for the app
2. **Add that folder to your antivirus exclusions** *(Avast: Menu → Settings → General → Exceptions → Add)*
3. **Extract** `gezenguz-ed-monitor-client-full.zip` into the folder — the Electron engine lands directly in the already-excluded folder, so it stays safe
4. Run `start_client_normal.bat` — no `install.bat` needed

### Antivirus (Avast and others) — Standard package only

If you use the **Standard** package and your antivirus blocks the download (`install.bat` reports `node_modules\electron\dist\electron.exe` is missing):

1. **Add a folder exclusion** for the app folder *(Avast: Menu → Settings → General → Exceptions → Add)*
2. **Temporarily turn off the antivirus shields for 10 minutes** *(Avast: right-click the tray icon → Avast shields control → Disable for 10 minutes)*
3. **Run `install.bat` again** — the download goes through this time
4. When it finishes, the shields turn back on by themselves; the file is now in the excluded folder, so it stays safe

> A folder exclusion **alone is not enough** — the file is blocked during download, so you also need step 2. If it still fails, additionally exclude the cache folder `%LOCALAPPDATA%\electron\Cache`. **Or just use the Full package above** and skip all of this.

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
