# Orb Collector 3000

## Original Request
"just a simple 3D game" — a straightforward fun 3D browser game

## Current State
Fully playable third-person orb collection game with:
- Cute robot character (procedural Three.js model)
- WASD movement + mouse camera orbit
- Orb collection with particles, score, screen shake
- Chasing enemies (colored blobs with spikes)
- Wave system — new wave spawns more/faster enemies, heals 1 HP
- Dash on click with cooldown
- Title screen, HUD, game over screen
- Web Audio procedural sound effects
- Post-processing: bloom, vignette, color grading

## Iteration History
- 2026-07-26: Initial build — Orb Collector 3000, Three.js third-person game

## Entity Roster
- Player: Blue robot character with antenna, glowing eyes, legs
- Orbs: 5 colors, floating + rotating, respawn on collect
- Enemies: Colored spiky blobs, 2 + wave count, get faster each wave
- Decoration: 15 floating geometric shapes (octahedra + tetrahedra)

## Systems Active
- [x] WASD movement (camera-relative)
- [x] Mouse drag orbit camera + scroll zoom
- [x] Click dash with cooldown
- [x] Orb collection + respawn
- [x] Enemy AI (chase player)
- [x] Wave system (timer + spawn)
- [x] Health + invincibility frames
- [x] Particle effects (collect, damage)
- [x] Damage numbers (floating 3D)
- [x] Screen shake
- [x] Screen flash (collect, damage)
- [x] Kill feed
- [x] Web Audio sound effects
- [x] Title screen + game over + restart
- [x] HUD (score, health bar, wave)
- [x] Wave banner

## Controls
- WASD: Move
- Mouse drag: Orbit camera
- Scroll: Zoom in/out
- Left click: Dash (1.5s cooldown)

## Known Issues
- None

## Suggested Next Steps
- Add power-ups (shield, speed boost, freeze enemies)
- Add boss enemy every 5 waves
- Add combo multiplier for collecting orbs quickly
- Add sound for enemy death when wave advances
