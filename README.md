<p align="center">
  <img src="https://img.shields.io/badge/⛏%20Minecraft-1.20.1-2ea44f?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJ3aGl0ZSI+PHJlY3Qgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSIjNWI4NzMxIi8+PC9zdmc+" alt="Minecraft">
  <img src="https://img.shields.io/badge/Modloader-Fabric-dbb78a?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJ3aGl0ZSI+PHJlY3Qgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSIjZGJiNzhhIi8+PC9zdmc+" alt="Fabric">
  <img src="https://img.shields.io/badge/Version-v1.0.3-blue?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/Hosted%20On-AWS%20EC2-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS EC2">
  <img src="https://img.shields.io/badge/Format-.mrpack-8B5CF6?style=for-the-badge" alt="mrpack">
</p>

<h1 align="center">BTD SMP — Modded</h1>

<p align="center">
  <b>A customized modded Minecraft 1.20.1 survival.</b>
  <br/>
  <sub>Enhanced combat · Expanded world generation · 70+ mods · Custom content · Dedicated cloud server</sub>
</p>

---

##  Quick Install

### For Players (Client-Side Modpack)

> **Download the full modpack and import it into your launcher — that's it!**

1. Download **[`FULL MODPACK 1.0.3.mrpack`](./FULL%20MODPACK%201.0.3.mrpack)**
2. Open your preferred launcher (**Modrinth App**, **Prism Launcher**, or **MultiMC**)
3. Import the `.mrpack` file:
   - **Modrinth App** → Drag & drop the file, or go to `＋` → `From file`
   - **Prism Launcher** → `Add Instance` → `Import` → select the `.mrpack` file
   - **MultiMC** → `Add Instance` → `Import from zip` → select the `.mrpack` file
4. Launch the game

### For Server Admins

The server-side files are included in this repository:

```
├── server.jar                      # Minecraft server
├── fabric-server-launch.jar        # Fabric loader
├── server.properties               # Server configuration
├── config/                         # Mod configurations
├── mods/                           # All server-side mods
└── FULL MODPACK 1.0.3.mrpack       # Client modpack for distribution
```

---

## Custom Mods by BTD

> **These mods were developed in-house specifically for BTD SMP and are published on Modrinth.**
> They are open-source, built with Fabric, and available for anyone to use!

### Shop Mod BTD

<p>
  <a href="https://modrinth.com/mod/shop-mod-btd"><img src="https://img.shields.io/badge/Modrinth-Shop%20Mod%20BTD-1bd96a?style=for-the-badge&logo=modrinth&logoColor=white" alt="Modrinth"></a>
  <a href="https://github.com/Ca1tlynRidley/BTD-Shop-Sell"><img src="https://img.shields.io/badge/Source-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="MIT">
</p>

A complete **in-game economy system** with graphical shop and selling interfaces powered by the Impactor economy.

- `/shop` — browse organized categories (Ingredients, Blocks, Combat, Food, Redstone, Functional) and purchase items
-  `/sell` — place items in a double-chest selling GUI, click Sell, and get paid instantly
-  Player balance display using the player's own head
-  Safely returns unsupported/unsold items — no item loss ever
-  Preconfigured buy & sell prices for all vanilla items
-  Optional VinURL compatibility for custom records

### Capture Egg

<p>
  <a href="https://modrinth.com/mod/capture-egg"><img src="https://img.shields.io/badge/Modrinth-Capture%20Egg-1bd96a?style=for-the-badge&logo=modrinth&logoColor=white" alt="Modrinth"></a>
  <a href="https://github.com/Ca1tlynRidley/Capture-Egg"><img src="https://img.shields.io/badge/Source-GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="MIT">
</p>

A lightweight **reusable mob capture item** — right-click any mob to store it, right-click again to release it anywhere.

-  Capture any living mob with a single right-click
-  Fully reusable — capture, release, repeat
-  Preserves villager professions & trades (Shift + Right Click to capture villagers)
-  Filled eggs gain an enchantment glint with mob name in tooltip
-  Configurable `uncapturable` entity tag for bosses
-  Custom capture and release sound effects
-  Works with vanilla and modded mobs

---

##  Features

<table>
<tr>
<td width="50%">

### Combat & Adventure
- Enhanced combat mechanics with **Boss Blades** and **More Swords Legacy**
- Terrifying **Mutant Monsters** and challenging boss encounters
- Unique **Artifacts** — find rare, powerful relics as loot
- **Dungeon Now Loading** — massive procedurally generated dungeons
- **Better Sword Trims** — weapon cosmetics via armor trims

</td>
<td width="50%">

### 🌎 World Generation
- **Terralith** — 100+ new biomes with stunning terrain
- **YUNG's Cave Biomes** — lush, diverse underground
- **Better End** — completely overhauled End dimension
- **TerraBlender** — seamless biome integration
- Custom world generation presets and balancing

</td>
</tr>
<tr>
<td width="50%">

###  Building & Decoration
- **Cluttered** — decorative clutter blocks
- **Banner Flags** & **Banner Bedsheets** — custom banner displays
- **Painters Inc.** — expanded painting mechanics
- **Farmer's Delight** — kitchen, cooking, and farming expansion

</td>
<td width="50%">

###  Quality of Life
- **Veinminer** — mine entire ore veins at once
- **AppleSkin** — food and hunger HUD info
- **Emojiful** — emoji support in chat
- **Capture Egg** — capture and relocate mobs
- **Antique Trading Ship** — find shipwrecks with rare trades

</td>
</tr>
<tr>
<td width="50%">

### 🚂 Transport & Logistics
- **Create: Steam 'n' Rails** — advanced railways and trains
- Expanded minecart and transport systems

</td>
<td width="50%">

###  Performance
- **C2ME** — concurrent chunk management engine
- **ModernFix** — memory and load time optimization
- **ImmediatelyFast** — instant rendering optimizations
- **Smooth Boot** — faster game startup
- **Clumps** — XP orb optimization
- **Chunky** — world pre-generation

</td>
</tr>
</table>

---

##  Full Mod List

> **70+ mods** carefully selected and configured for the ultimate SMP experience.

<details>
<summary><b>⚔️ Gameplay & Content</b> — click to expand</summary>

| Mod | Description |
|-----|-------------|
| Artifacts | Unique equippable items found as rare loot |
| Better Sword Trims | Sword cosmetics using armor trim system |
| BOMD | Boss encounters and mob overhauls |
| Boss Blades | Unique boss-dropped weapons |
| Capture Egg | Capture and relocate mobs with eggs |
| Farmer's Delight | Cooking, farming, and kitchen expansion |
| More Swords Legacy | Expanded sword types and materials |
| Mutant Monsters | Terrifying mutant mob variants |

</details>

<details>
<summary><b> World Generation</b> — click to expand</summary>

| Mod | Description |
|-----|-------------|
| Better End | Complete End dimension overhaul |
| Better Ruby | Ruby ore and items |
| Terralith | 100+ new biomes with custom terrain |
| TerraBlender | Biome blending API |
| YUNG's Cave Biomes | Diverse underground cave biomes |
| YUNG's API | Core library for YUNG's mods |
| Dungeon Now Loading | Massive procedural dungeons |

</details>

<details>
<summary><b> Building & Decoration</b> — click to expand</summary>

| Mod | Description |
|-----|-------------|
| Banner Bedsheets | Custom banner designs on beds |
| Banner Flags | Display banners as hanging flags |
| Cluttered | Decorative clutter and props |
| Painters Inc. | Expanded painting system |
| Antique Trading Ship | Discoverable trade ships |

</details>

<details>
<summary><b> Server Administration</b> — click to expand</summary>

| Mod | Description |
|-----|-------------|
| Carpet | Server-side tweaks and optimizations |
| Carpet AMS Addition | Extended carpet mod features |
| Carpet TCTC Addition | Additional carpet technical features |
| LuckPerms | Advanced permissions management |
| TAB | Custom tab list and scoreboard |
| Impactor | Server economy and management |
| Impactor Placeholders | Dynamic text placeholders |
| MagicLib | Carpet mod support library |

</details>

<details>
<summary><b> Performance & Optimization</b> — click to expand</summary>

| Mod | Description |
|-----|-------------|
| C2ME | Concurrent chunk management engine |
| Chunky | World pre-generation |
| Clumps | XP orb merging and optimization |
| ImmediatelyFast | Instant rendering improvements |
| ModernFix | Memory and load time fixes |
| Smooth Boot | Faster game startup |
| AttributeFix | Fixes attribute value limits |

</details>

<details>
<summary><b> Libraries & APIs</b> — click to expand</summary>

| Mod | Description |
|-----|-------------|
| Architectury | Cross-platform mod API |
| BCLib | BetterX mods core library |
| Bookshelf | Shared code library |
| Cardinal Components API | Component-based data API |
| Carpet Extra | Extended carpet features |
| Forge Config API Port | Forge config on Fabric |
| Iceberg | Modding library |
| Patchouli | In-game documentation books |
| PuzzlesLib | Shared mod utilities |

</details>

<details>
<summary><b> Quality of Life & Misc</b> — click to expand</summary>

| Mod | Description |
|-----|-------------|
| AppleSkin | Food and saturation HUD overlay |
| Create: Steam 'n' Rails | Advanced train and railway systems |
| Emojiful | Emoji support in chat |
| Veinminer | Mine connected ore blocks at once |

</details>

---

## ☁️ Server Infrastructure

```
[Oracle]
```



---

## Changelog

###  v1.0.3 — Current Release

> **Status:** `Stable` · **Type:** Major Content Update

** Added**
- New gameplay improvements and content expansions
- Updated mod configuration balancing
- Server stability improvements
- Custom server enhancements

** Gameplay Changes**
- Improved progression balance
- Adjusted difficulty scaling
- Enhanced exploration experience
- Updated combat mechanics

** Server Improvements**
- Improved AWS EC2 server management
- Optimized Linux server workflow
- Updated server configurations
- Better backup organization

** Bug Fixes**
- Fixed configuration issues
- General stability improvements

---

##  Requirements

| Requirement | Minimum | Recommended |
|-------------|---------|-------------|
| **Minecraft** | 1.20.1 | 1.20.1 |
| **RAM** | 6–8 GB allocated |
| **Java** | Java 17 | Java 17+ |
| **Launcher** | Modrinth / Prism / PolyMC |

---

##  Contributing

BTD SMP is a community-driven server. If you'd like to suggest mods, report bugs, or request features, open an [Issue](https://github.com/Ca1tlynRidley/BTD-SMP-MODDED/issues) on this repository.

---

## License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

Individual mods are owned by and licensed by their respective authors.

---

<p align="center">
  <sub>Made by the BTD SMP team</sub>
  <br/>
  <sub> Star this repo if you're part of the SMP</sub>
</p>
