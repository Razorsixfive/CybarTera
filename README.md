# CybarTera
# 🌌 The Fractured World of Cybartera
*A solo-developed 3D MMO RPG built in Godot 4.5*  
*(A mix of World of Warcraft, Habbo Hotel, and Cyberpunk)*

[🇩🇰 Læs på dansk](./README.da.md)

![Godot Engine](https://img.shields.io/badge/Godot-4.5-blue?logo=godot-engine&style=flat-square)
![Platforms](https://img.shields.io/badge/platforms-Linux%20%7C%20Windows%20%7C%20Android-blue?style=flat-square)
![License](https://img.shields.io/badge/license-Proprietary-red?style=flat-square)](./LICENSE)
![Status](https://img.shields.io/badge/status-Pre--Alpha-orange?style=flat-square)

---

## 👤 About the Developer
Developed by **[Razorsixfive]**, a **solo indie developer** with a focus on:  
- **Backend architecture & distributed systems**  
- **Scalable multiplayer networking**  
- **Cross-platform development** in **Custom compiled Godot 4.5 (4.6 will come)**  

This project demonstrates both **game design creativity** and **technical engineering depth**, blending gameplay systems with robust backend infrastructure.

---

## 🚀 Project Overview
**The Fractured World of Cybartera** is a **3D massively multiplayer RPG** built in **Godot 4.5** with a persistent backend.  
Originally intended as a small portfolio piece, it evolved into a full-scale MMO architecture experiment.

**Architecture highlights:**
- **Backend**: DIY **Golang cluster**
- **Real-time servers**: **Golang cluster**
- **Gameplay servers**: **C# cluster** (AI, mobs, NPCs, combat, world simulation)
- **Hosting**: Self-hosted **VPS** (only running cost so far)

**Core systems include:**  
Full multiplayer synchronization, persistent world data, modular region scaling, and multi-cluster networking.

---

## ✅ Implemented Features

### ⚔️ Combat & Gameplay
- Mobs, attacks, abilities, and HP systems  
- Combat feedback: damage numbers, targeting indicators *(hit effects in progress)*  

### 🧙 Player Systems
- Inventory, equipment, trading  
- Stats: Strength, Agility, Intelligence, Resistances  
- Death and respawn cycle  
- Progression and leveling *(skill trees in progress)*  

### 🌍 World Structure
- Total size: **65.5 km × 65.5 km**  
- Superregions: **2048m × 2048m**  
- Subregions: **128m × 128m**  

### 🌐 Networking & Social
- Login & registration  
- Global, group, and private chat  
- Friends & block lists  
- Fake OS inside Godot (Phone, Desktop, Laptop UI)  

### 🧭 Quests
- Main story & side quests  

### 💰 Economy
- Gold/credits *(auction system in progress)*  

### 🧠 AI
- Pathfinding, patrols, aggro system, and combat tactics  

### 🚀 Traversal
- Fast travel & vehicles  

### 🛡️ Guilds & Clans
- Guild management, chat, shared storage  

### 🪓 Resources & Loot
- Resource nodes, rarity, persistence  

### 🎨 Interface
- Menus with audio, 3D graphics, and key mapping settings  
- Localization: **28 languages supported**  

### 🏠 Housing & Instances
- Player apartments with free or grid placement  
- Persistent housing upgrades and decor  

### 🏰 Dungeons & Raids
- Framework functional (currently empty)  
- Matchmaking to fresh instance worlds  

### 🔒 Server & Security
- Load balancing, sharding, auto-scaling  
- Persistent backups  
- Anti-cheat & data validation systems  

### 📱 Multiplatform
- **Supported:** Linux, Windows, Android  
- **In Progress:** macOS, iOS  

### 🔄 Dynamic Updates
- Google Play / App Store (pre-alpha)  
- GitHub release fallback  
- In-game client version checks and restart updates  

---

## 🚧 Missing Features
- Hit effects & advanced combat feedback  
- Player vs Player (arenas, open-world PvP)  

## ✨ Nice-to-Have Features
*(Planned or experimental)*
- Player analytics & server metrics  
- Character cosmetics  
- Dungeon scripting, puzzles, traps  
- Raid mechanics & cross-server sync  
- Group AI coordination  
- Crafting, gathering, and recipes  
- Status effects (poison, stun, regen)  
- Weather, biomes, and day/night cycles  
- Tutorial & onboarding flow  
- Loot & inventory tools  
- Combat balancing utilities  
- Stress testing & admin spawners  
- DDOS mitigation & exploit logging  
- Soundtrack & 3D audio expansion  

---

## 🛠️ Tech Stack
- **Engine:** Godot 4.5 (custom compiled client)  
- **Servers:** Golang clsuter + C# cluster + CockroachDB  
- **Hosting:** DIY VPS  
- **Networking:** Load-balanced, modular, scalable  

---

## 📷 Screenshots & Media
_Gameplay images, concept art, or GIFs will come here_

---

## 🌐 Links
- [Releases](https://github.com/USERNAME/REPO/releases)
- [Issues](https://github.com/USERNAME/REPO/issues)
- [Discussions](https://github.com/USERNAME/REPO/discussions)
- [Godot Engine](https://godotengine.org)
