<p align="center"><img src="logo.svg" width="96" alt="Fortnite Dynamic Map logo"></p>

# Fortnite Dynamic Map

Interactive map for **Fortnite Chapter 7 Season 4 "Override"** in the style of fortnite.gg — single HTML file, vanilla JS, no dependencies.

**Live:** https://oliainsmith-cmyk.github.io/Dynamic-Fortnite-Map/ (enable GitHub Pages → main / root)

## What it does
- **Official map + exact locations** – the Battle Royale map image and in-game coordinates for every named location, landmark, island and Override Console come from the public [fortnite-api.com](https://fortnite-api.com) `/v1/map` endpoint, cached for offline use. When the season changes, hit Refresh and everything moves.
- **fortnite.gg-style filters** – Locations / AI & Bosses / Spawns sections with master toggles, per-category switches and counts.
- **Real Fortnite icons** for every category (Epic art via the Fortnite Wiki), outlined like the in-game map.
- **25 spawn categories** – Pumpkin Chests, Chests, Rare Chests, Ammo, Vending, Mending, Cheat Codes, Vaults, Launch Pads, Cars, Reboot Vans and more. Tap **+** and mark spawns on the real map; markers cluster by zoom. Export/import to share with your squad.
- **Draw routes** – yellow arrowed routes that snap to locations and your spawns, 2-opt optimise, 6 save slots, share links (`#r=…`).
- **Oracle route AI** – scans every destination (including your spawns) and solves the highest-value loot path within a time budget, weighted by loot, mythics/bosses and safety, optionally finishing inside the zone.
- **Drop calculator** – bus path → exact jump second, jump window, glide distance, expected opponents, live countdown with audio/haptics, best drops for that bus.
- Contest heatmap, loot glow, grid, ruler with real metres, safe-zone planner, Fortnitemares filter, intel for every location (chest counts, players/game, uncontested %, air time, bosses, vaults), home dashboard, 5 themes, settings, backup, update log. Works on phone and desktop.

## Data
Map image & coordinates: fortnite-api.com. Chest/ammo/vending/Reboot counts: Fortnite Wiki where published (others marked *est*). Landing stats: Elite Esports C7S4. Spawn markers are user-charted — no third-party spawn database is bundled.

Fan-made, not affiliated with Epic Games or fortnite.gg.
