# 🌌 The Fractured World of Cybartera
*Et solo-udviklet 3D MMO RPG bygget i Godot 4.5*  
*(En blanding af World of Warcraft, Habbo Hotel og Cyberpunk)*

[🇬🇧 Read in English](./README.md)

![Godot Engine](https://img.shields.io/badge/Godot-4.5-blue?logo=godot-engine&style=flat-square)
![Platforms](https://img.shields.io/badge/platforme-Linux%20%7C%20Windows%20%7C%20Android-blue?style=flat-square)
![Status](https://img.shields.io/badge/status-Pre--Alpha-orange?style=flat-square)

---

## 👤 Om Udvikleren
Udviklet af **[Dit Navn]**, en **solo indie-udvikler** med fokus på:  
- **Backend-arkitektur & distribuerede systemer**  
- **Skalerbar multiplayer-netværk**  
- **Cross-platform udvikling** i **Custom compiled Godot 4.5 (4.6 vil komme)**  

Projektet demonstrerer både **kreativt spildesign** og **teknisk dybde**, hvor gameplay og robust serverinfrastruktur mødes.

---

## 🚀 Projektoversigt
**The Fractured World of Cybartera** er et **3D MMO RPG** udviklet i **Godot 4.5** med en persistent backend.  
Det startede som et lille portfolio-projekt til jobsøgning — men voksede til et fuldskala MMO-eksperiment.

**Arkitektur:**
- **Backend:** Hjemmelavet **Golang-cluster-klynge**
- **Real-time-servere:** **Golang-cluster-klynge**
- **Gameplay-servere:** **C#-cluster-klynge** (AI, NPC’er, mobs, kamp og verdenssimulering)
- **Hosting:** Egen **VPS** (den eneste udgift indtil videre)

Spillet understøtter **multiplayer-synkronisering, persistent verden** og **skalérbare servere** fordelt over regioner.

---

## ✅ Implementerede Funktioner

### ⚔️ Kamp & Gameplay
- Mobs, angreb, evner og HP-systemer  
- Skade-tal og mål-indikatorer *(effekter mangler endnu)*  

### 🧙 Spillersystemer
- Inventar, udstyr, handel  
- Statistik: Styrke, Smidighed, Intelligens, Modstand  
- Død og genoplivning  
- Erfaring og niveauer *(talenttræ under udvikling)*  

### 🌍 Verden
- Størrelse: **65,5 km × 65,5 km**  
- Superregioner: **2048 m × 2048 m**  
- Underregioner: **128 m × 128 m**  

### 🌐 Netværk & Sociale Funktioner
- Login/registrering  
- Global, gruppe- og privat chat  
- Venne- og bloklister  
- Falsk OS i Godot (Telefon, Desktop, Laptop UI)  

### 🧭 Missioner
- Hovedhistorie og sidequests  

### 💰 Økonomi
- Guld/credits *(auktioner under udvikling)*  

### 🧠 Fjende-AI
- Pathfinding, patruljer, aggro og kamp-taktik  

### 🚀 Rejse
- Hurtigrejse og køretøjer  

### 🛡️ Guilds & Klans
- Styring, chat og delte ressourcer  

### 🪓 Ressourcer & Loot
- Ressource-knuder, sjældenhed, vedholdenhed  

### 🎨 Brugergrænseflade
- Menuer med lyd, grafik og tasteindstillinger  
- **28 sprog** understøttet  

### 🏠 Boliger & Instancer
- Spillerlejligheder med fri eller grid-placering  
- Opgraderinger og dekorationer gemmes permanent  

### 🏰 Dungeons & Raids
- Rammeværk færdigt (indhold mangler)  
- Matchmaking til nye instanser  

### 🔒 Server & Sikkerhed
- Load balancing og auto-skalering  
- Backup-system  
- Anti-cheat og datavalidering  

### 📱 Platforme
- **Understøttet:** Linux, Windows, Android  
- **Under udvikling:** macOS, iOS  

### 🔄 Opdateringer
- Google Play / App Store (pre-alpha)
- GitHub fallback  
- Klientversion-check og in-game opdatering  

---

## 🚧 Manglende Funktioner
- Kamp-effekter  
- PvP (arenaer, battlegrounds, åben verden)  

## ✨ Ønskede Funktioner
- Spilleranalyse & serverstatistik  
- Udseende & kosmetik  
- Dungeon scripting & loot-systemer  
- Raid-mekanik & cross-server sync  
- Gruppe- og buffsamarbejde  
- Håndværk & ressourcer  
- Status-effekter (gift, stuns, regeneration)  
- Vejr, biomer, dag/nat-cyklus  
- Tutorial til nye spillere  
- Inventarværktøjer og lootsortering  
- Serverstress-tests  
- DDOS-beskyttelse og logning  
- Lyd og musikudvidelser  

---

## 🛠️ Teknologi
- **Engine:** Godot 4.5 (custom klient)  
- **Servere:** Golang cluster + C# cluster + CockroachDB  
- **Hosting:** Egen VPS  
- **Netværk:** Skalerbar og modulær arkitektur  

---

## 📷 Billeder & Medier
_Screenshots, concept art eller GIFs vil komme her_

---

## 🌐 Links
- [Udgivelser](https://github.com/USERNAME/REPO/releases)
- [Issues](https://github.com/USERNAME/REPO/issues)
- [Diskussioner](https://github.com/USERNAME/REPO/discussions)
- [Godot Engine](https://godotengine.org)
