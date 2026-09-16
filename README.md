# tds

⚔ **Tower Defense: Frontline** — a complete single-file, canvas-based tower defense game. No build step, no dependencies.

## Play

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000/

## Features

- **Campaign**: 8 stages (Greenfield Plains → Cyber Ruins) with bosses, plus **Endless Mode** on any of the 8 maps
- **12 tower types**: Archer, Cannon, Freezer, Sniper, Farm (gold generation), Defender (5-tier flagship), Barracks (blocking infantry), Necromancer (skeletons + Death Nova), Laser, Tesla (chain lightning), Missile, DJ Station (buff aura)
- **Loadout system**: pick up to 6 towers per run; upgrade and sell in the field
- **5 difficulties**: Easy → Insane, plus Sandbox
- **Cheat console**: 🛠 button (or `Home` key) — infinite gold/lives, kill all, force-end wave, max towers, unlock stages
- Enemy tooltips, boss health bar, speed control (1x/1.5x/2.5x), pause, touch + mouse support
