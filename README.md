# 🏎️ Turbo Rush — HD Car Racing

**Turbo Rush** is a fast-paced, single-file, fully offline HD endless highway racing game built entirely with HTML5 Canvas, CSS, and vanilla JavaScript — no frameworks, no build tools, no internet connection required.

Dodge traffic and oil barrels, collect coins for bonus points, and race as far as you can as the speed and difficulty ramp up the further you go.

![Made with HTML5](https://img.shields.io/badge/HTML5-Canvas-orange)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)
![Offline](https://img.shields.io/badge/Offline-Ready-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## 🎮 Live Demo

Play it directly in your browser: **[Turbo Rush — Play Now](#)**
*(Update this link with your GitHub Pages URL, e.g. `https://aniruddhasutradhar40.github.io/turbo-rush/`)*

---

## ✨ Features

- **Endless Highway Racing** — procedurally spawning traffic, obstacles, and coins with increasing difficulty
- **Dynamic Level & Speed Scaling** — game speed and spawn rate automatically increase with distance traveled
- **Coin Bonus System** — collect coins mid-race for extra score
- **Dark / Light Theme Toggle** — neon dark mode by default, with a clean light mode option, preference saved automatically
- **Best Score Tracking** — high score persists locally between sessions
- **Cross-Platform Controls** — full keyboard support on desktop and touch/swipe controls on mobile
- **Fully Responsive HUD** — score, best score, level, and speed indicator adapt to any screen size
- **Bilingual In-Game Instructions** — how-to-play guide shown in Bengali and English
- **100% Offline** — a single HTML file, no external dependencies or server required

---

## 🕹️ Controls

### Desktop
| Action | Keys |
|---|---|
| Change lane | `←` `→` or `A` `D` |
| Accelerate | `↑` or `W` or `Space` |
| Brake | `↓` or `S` |

### Mobile / Touch
- Use the on-screen **◀ ▶ ▲ ▼** buttons
- Or swipe/tap the left and right side of the screen to steer

---

## 🚦 How to Play

1. Tap **START RACE** to begin.
2. Steer between lanes to avoid oncoming traffic and oil barrels.
3. Collect coins along the way for bonus score.
4. Survive as long as possible — the further you travel, the higher the level and the faster the traffic gets.
5. Crashing ends the run and shows your final score, best score, and total distance covered.

---

## 🛠️ Tech Stack

- **HTML5 Canvas** — real-time game rendering
- **Vanilla JavaScript** — game loop, physics, collision detection, and state management
- **CSS3** — HUD styling, theming (CSS variables), responsive layout, and animations
- **localStorage** — theme preference and best score persistence

No external libraries, frameworks, or build steps are used — the entire game lives in a single `index.html` file.

---

## 📦 Installation & Local Setup

Since Turbo Rush is a single self-contained HTML file, there's nothing to install or build.

```bash
# Clone the repository
git clone https://github.com/aniruddhasutradhar40/turbo-rush.git

# Move into the project folder
cd turbo-rush

# Open the game directly in your browser
open index.html      # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

You can also just double-click `index.html`, or drag it into any modern browser tab.

---

## 🌐 Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — your game will be live at:
   `https://<your-username>.github.io/<repo-name>/`

---

## 📁 Project Structure

```
turbo-rush/
└── index.html   # Complete game — markup, styles, and logic in one file
```

---

## 🎨 Customization

Key gameplay and visual parameters are defined near the top of the `<script>` and `<style>` sections in `index.html`, including:

- Neon color palette and theme variables (`--neon-cyan`, `--neon-pink`, `--neon-yellow`, etc.)
- Base speed, level progression, and spawn interval scaling
- Coin/obstacle spawn logic and scoring values

Feel free to tweak these values to change the game's difficulty curve or visual style.

---

## 🗺️ Roadmap Ideas

- [ ] Additional car skins / color selection
- [ ] Power-ups (shield, slow-motion, magnet)
- [ ] Global leaderboard integration
- [ ] Sound effects and background music toggle
- [ ] Multiple road environments (city, desert, night mode variants)

---

## 🤝 Contributing

Contributions, bug reports, and feature suggestions are welcome. Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

## 👤 Author

**Aniruddha Sutradhar**
GitHub: [@aniruddhasutradhar40](https://github.com/aniruddhasutradhar40)

---

<p align="center">Built with ❤️ and a lot of coffee — race responsibly! 🏁</p>
