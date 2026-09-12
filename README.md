<div align="center">

# 🎣 EA Fishing

### Custom FiveM Fishing & Progression Ecosystem

Developed by **W7zzard**  
Built for **East Atlanta Stories**

![FiveM](https://img.shields.io/badge/FiveM-Cfx.re-black?style=for-the-badge)
![Lua](https://img.shields.io/badge/Lua-Development-black?style=for-the-badge&logo=lua)
![JavaScript](https://img.shields.io/badge/JavaScript-Development-black?style=for-the-badge&logo=javascript)
![SQL](https://img.shields.io/badge/SQL-Database-black?style=for-the-badge&logo=mysql)

</div>

---

## Overview

**EA Fishing** is a custom fishing ecosystem designed for East Atlanta Stories.

The goal is to move beyond the typical FiveM fishing script and create a system that feels like an actual activity players can progress through, compete in, earn from, and continue returning to.

The system is designed around:

- Interactive fishing gameplay
- Player progression
- Equipment progression
- Fish variety
- Economy integration
- Location-based fishing
- Competitive events
- Tournament-ready architecture

EA Fishing is part of the larger custom `ea-*` development ecosystem powering East Atlanta Stories.

---

## Project Goals

The fishing system is being designed around three priorities:

### Gameplay

Fishing should feel like an activity instead of a simple progress bar.

Players should have decisions to make involving:

- Location
- Equipment
- Bait
- Fish type
- Catch difficulty
- Risk vs. reward

### Progression

Players should have reasons to continue fishing over time through:

- Better equipment
- Higher-value catches
- Unlockable areas
- Skill progression
- Competitive rankings
- Special events

### Economy

Fishing is being designed as a real part of the server economy rather than an isolated money-printing activity.

The system can support:

- Fish values
- Catch rarity
- Market balancing
- Equipment costs
- Sell locations
- Progression-based earnings

---

# Core System Architecture

EA Fishing is being structured as a modular FiveM resource.

```text
ea-fishing/
│
├── client/
│   └── gameplay logic
│
├── server/
│   └── validation & economy logic
│
├── shared/
│   └── configuration
│
├── ui/
│   └── interface systems
│
└── database/
    └── persistent progression
