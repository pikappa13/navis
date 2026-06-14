# Navis — Arcade Survivor

[![Gioca ora](https://img.shields.io/badge/▶%20GIOCA%20ORA-online-00f0ff.svg?style=for-the-badge)](https://pikappa13.github.io/navis/)
[![License: MIT](https://img.shields.io/badge/License-MIT-00f0ff.svg)](LICENSE)
![No dependencies](https://img.shields.io/badge/dependencies-none-ff2d95.svg)
![Single file](https://img.shields.io/badge/build-single--file%20HTML-ffd166.svg)

Un gioco arcade 2D twin-stick in stile neon/synthwave, in un **singolo file HTML**, zero dipendenze.

### ▶ [Gioca ora nel browser →](https://pikappa13.github.io/navis/)

Oppure apri `index.html` in locale: nessun download, nessuna installazione.

![Navis](og-image.png)

## 🎮 Come si gioca
- **WASD / frecce** — muovi la nave
- **Mouse** — mira (il fuoco è automatico)
- **SPAZIO** — scatto/schivata (con i-frame e cooldown)
- **P / Esc** — pausa
- 📱 **Mobile**: trascina per muovere, doppio tocco per scattare

Raccogli i potenziamenti, sopravvivi alle ondate e batti i **BOSS** che arrivano ogni 5 onde.

## ✨ Caratteristiche
- 4 tipi di nemici con comportamenti diversi (chaser, zigzag, darter, tank)
- Boss ogni 5 onde con 3 pattern di fuoco + fase *enrage*
- Power-up: gettoni, cura, rapid fire, multi-shot
- Sistema combo, particelle, screen-shake, glow al neon
- Musica synthwave ed effetti generati in tempo reale via WebAudio (niente file)
- Record salvato in `localStorage`

## 🚀 Avvio
Nessuna build. Doppio click su `index.html`, oppure servilo con un server statico:

```bash
python -m http.server 8000
# poi apri http://localhost:8000
```

Realizzato con HTML5 Canvas vanilla.

## 📄 Licenza

Questo progetto è **open source** sotto licenza [MIT](LICENSE).
Sei libero di usarlo, modificarlo e ridistribuirlo, anche per scopi commerciali,
mantenendo la nota di copyright. Fork e contributi sono benvenuti!
