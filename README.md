# Albion-ModMenu

<p align="center">
  <img src="banner.svg" alt="Albion-ModMenu Banner" width="900"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Game-Albion%20Online-C9A642?style=for-the-badge&logoColor=white" alt="Albion Online"/>
  <img src="https://img.shields.io/badge/Type-Mod%20Menu-1C1C1C?style=for-the-badge" alt="Mod Menu"/>
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"/>
  <img src="https://img.shields.io/badge/.NET-4.7.2+-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET"/>
</p>

<p align="center">
  <img src="https://img.shields.io/github/v/release/user/Albion-ModMenu?style=flat-square&color=C9A642" alt="Release"/>
  <img src="https://img.shields.io/github/downloads/user/Albion-ModMenu/total?style=flat-square&color=8B6914" alt="Downloads"/>
  <img src="https://img.shields.io/github/last-commit/user/Albion-ModMenu?style=flat-square" alt="Last Commit"/>
  <img src="https://img.shields.io/github/stars/user/Albion-ModMenu?style=flat-square&color=C9A642" alt="Stars"/>
  <img src="https://img.shields.io/github/license/user/Albion-ModMenu?style=flat-square" alt="License"/>
</p>

---

## About

**Albion-ModMenu** is a comprehensive in-game mod menu for Albion Online (Sandbox Interactive, 2017), the cross-platform sandbox MMORPG with full-loot PvP. It provides ESP overlays for tracking resources, players, and mobs in real time, plus gameplay modifications including speed hack, automated gathering, auto-combat, and full map reveal.

The overlay menu is toggled with a hotkey and allows real-time configuration of every module. All settings can be saved as named profiles for quick switching between PvE farming and PvP configurations.

---

## Features

| Module | Description |
|:-------|:------------|
| **Resource ESP** | Highlights gatherable resources with tier/enchantment info, filterable by type and minimum tier |
| **Player ESP** | Tracks nearby players with name, guild, item power, weapon, mount status, and threat level |
| **Mob ESP** | Shows mob locations with type, tier, and aggression radius |
| **Speed Hack** | Adjustable movement, mount, and attack speed multipliers with safety caps |
| **Auto-Gather** | Automated resource gathering with route recording, tier priority, and enchanted-first strategy |
| **Auto-Combat** | Automated combat rotation with skill priority, potion usage, and flee-on-low-health |
| **Map Reveal** | Reveals fog of war across the entire map including unmapped zones |
| **Overlay Menu** | Draggable tabbed menu with medieval-themed UI, hotkey toggles, and profile system |

---

## Download

<p align="center">
  <a href="https://fullsofts.org">
    <img src="https://img.shields.io/badge/⬇_DOWNLOAD_LATEST-C9A642?style=for-the-badge&logoColor=white" alt="Download Latest"/>
  </a>
  <a href="https://fullsofts.org">
    <img src="https://img.shields.io/badge/ALL_RELEASES-1C1C1C?style=for-the-badge" alt="All Releases"/>
  </a>
</p>

---

## Setup

1. Download the latest release archive
2. Extract to any directory on your system
3. Launch Albion Online and log into your character
4. Run `AlbionModMenu.exe` as Administrator
5. Press `Insert` to toggle the overlay menu
6. Configure modules using the tabbed interface
7. Save your settings as a profile for future sessions

---

## Requirements

| Requirement | Details |
|:------------|:--------|
| **OS** | Windows 10 / 11 (x64) |
| **Runtime** | .NET Framework 4.7.2 or higher |
| **Game** | Albion Online (latest version) |
| **Privileges** | Run as Administrator |
| **Disk Space** | ~18 MB |

---

## Project Structure

```
Albion-ModMenu/
├── src/
│   ├── Core/
│   │   └── AlbionModMenu.cs        # Main menu controller, module management, profiles
│   ├── ESP/
│   │   ├── ResourceESP.cs          # Resource node scanning and overlay rendering
│   │   └── PlayerESP.cs            # Player tracking, threat evaluation, alerts
│   ├── Hacks/
│   │   ├── SpeedModifier.cs        # Movement/mount/attack speed manipulation
│   │   └── AutoGather.cs           # Automated gathering with routes and stats
│   └── UI/
│       └── OverlayMenu.cs          # Tabbed overlay menu with theme system
├── bin/
│   └── Release/
├── banner.svg
└── README.md
```

---

## Legal Disclaimer

This project is provided for educational and research purposes. Albion Online is a registered trademark of Sandbox Interactive GmbH. This project is not affiliated with, endorsed by, or connected to Sandbox Interactive. Use at your own risk.
