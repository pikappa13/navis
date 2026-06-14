<div align="center">

# 🚀 Navis — Arcade Survivor

🌍 **English** · [Italiano](README.md)

[![▶ Play now](https://img.shields.io/badge/▶%20PLAY%20NOW-online-00f0ff.svg?style=for-the-badge)](https://pikappa13.github.io/navis/)
[![License: MIT](https://img.shields.io/badge/License-MIT-00f0ff.svg)](LICENSE)
![No dependencies](https://img.shields.io/badge/dependencies-zero-ff2d95.svg)
![Single file](https://img.shields.io/badge/build-single%20HTML%20file-ffd166.svg)
![Vanilla JS](https://img.shields.io/badge/JavaScript-vanilla-b14dff.svg)

**A neon/synthwave 2D twin-stick arcade game in a single HTML file — no dependencies, no build.**

### ▶ [**Play now in your browser →**](https://pikappa13.github.io/navis/)

![Navis — Arcade Survivor](og-image.png)

</div>

---

*Navis* (Latin for "ship") is a **wave-based twin-stick shooter**: pilot your ship, dodge enemy swarms,
shoot non-stop, collect power-ups, pick an upgrade after every wave and survive as long as you can while
facing tougher bosses. It runs **entirely in the browser** — no download, no install, no plugins.

## ✨ Features
- 🎮 **Wave-based twin-stick** with auto-fire and continuous aiming
- 👾 **4 enemy types** with distinct behaviours (chasers, zig-zaggers, darters, tanks)
- 💀 **A boss every 5 waves** with 3 attack patterns and an *enrage* phase below 40% HP
- 🃏 **Roguelite progression**: choose **1 of 3 upgrade cards** after each wave
- 💊 **Pick-ups**: coins, heal, rapid fire, multi-shot
- ⚡ **Dash/dodge** with invincibility frames and cooldown
- 🔥 **Combo system** with a score multiplier
- 🎆 Lots of juice: particles, screen-shake, neon glow, slow-motion
- 🎵 **Synthwave music and SFX generated at runtime** via the Web Audio API (no audio files)
- 🏆 **High score saved** locally (`localStorage`)
- 📱 Full **touch controls** for mobile
- 🪶 **Single file, zero dependencies**: ~800 lines of vanilla HTML/CSS/JS

## 🕹 How to play
Survive the waves, power up and defeat the bosses. The bigger your combo, the more points you earn.

### Desktop
| Control | Action |
|---|---|
| `W` `A` `S` `D` / arrows | Move the ship |
| Mouse | Aim (fire is **automatic**) |
| `Space` / `Shift` | Dash / dodge |
| `P` / `Esc` | Pause |

### Mobile
| Control | Action |
|---|---|
| Drag | Move the ship (auto-aim at the nearest enemy) |
| Double tap | Dash / dodge |

## ⚙️ Gameplay

### Enemies
| Type | Behaviour |
|---|---|
| **Chaser** | Comes straight at you |
| **Zig-zag** | Weaves toward you, hard to hit |
| **Darter** | Fast and fragile |
| **Tank** | Slow and tough, with a health bar |

### Bosses
A boss appears **every 5 waves**, with increasing health. They alternate three patterns — **radial**
burst, **aimed** shots and **spiral** — and become more aggressive (*enrage*) below 40% HP. Defeating one
grants a big score bonus and a shower of power-ups.

### Upgrades (after each wave)
Pick **one of three cards**:

| Upgrade | Effect |
|---|---|
| 🔱 Twin cannons | +1 projectile per shot |
| ⚡ Rapid fire | +18% fire rate |
| 💥 Piercing rounds | +1 damage per shot |
| 🛡️ Reinforced hull | +1 max HP (and heal) |
| ❤️ Repair | +2 HP |
| 🚀 Thrusters | +12% speed |
| 💨 Dash reactor | −20% dash cooldown |
| 🧲 Magnet | +50% pickup range |

## 💻 Run locally
No build, nothing to install.

```bash
git clone https://github.com/pikappa13/navis.git
cd navis
# open index.html directly, or serve it:
python -m http.server 8000   # then open http://localhost:8000
```

## 🛠 Built with
- **HTML5 Canvas 2D** for rendering
- **Web Audio API** for runtime-generated music and SFX (no audio assets)
- **localStorage** for high-score persistence
- **Vanilla JavaScript** — no framework, no dependencies, no build step
- **GitHub Pages** + GitHub Actions for automatic deployment

## 🤝 Contributing
Ideas, bug reports and pull requests are welcome! Since it's a single file, just edit `index.html` and
reload the browser to see your changes.

## 📄 License
Released under the **[MIT](LICENSE)** license.

## 👤 Author
**Developed by Patrick Battistini** — GitHub: [@pikappa13](https://github.com/pikappa13)

If you like Navis, leave a ⭐ on the repo — it helps the project get discovered!
