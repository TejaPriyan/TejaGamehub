<div align="center">

# ⚡ Teja Gaming Hub <sub><sup>v3</sup></sub>

**A neon-cyberpunk arcade of 11 fully playable mini-games — one single-page web app.**
No build step. No dependencies. Just open `index.html` in a browser and play.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

</div>

---

## 📖 About

**Teja Gaming Hub** is a self-contained retro-futuristic gaming arcade wrapped in a neon,
synthwave aesthetic. It's a single `index.html` file — all the layout, styling, and game
logic live in one document, which makes it trivially easy to run, host, or fork.

From a full **chess** engine with a minimax AI to a **rhythm game** played on the `D F J K`
keys, there are 11 games to choose from. Custom cursor trails, a manga-style intro animation,
a per-game character card generator, and a session scoreboard round out the experience.

> ✨ **Tip:** Host it for free on **GitHub Pages** (see the [Deploy](#-deploy-to-github-pages)
> section) or just double-click `index.html` to play right now.

---

## 🕹️ Games

| # | Game | Type / Tag | Description |
|---|------|------------|-------------|
| 1 | **Neon Snake** | Arcade | Guide your neon serpent. Eat, grow, survive. |
| 2 | **Cyber Pong** | Retro | Classic neon pong vs. the AI. First to 7. Challenge a friend — two-player and AI modes. |
| 3 | **Memory Matrix** | Puzzle | Match holographic emoji pairs. |
| 4 | **Tetrix Cyber** | Puzzle | Stack neon blocks, clear lines. |
| 5 | **Flappy Cyber** | Action | Navigate cyber-gates. Tap to flap. |
| 6 | **Reaction Protocol** | Reflex | Click the instant it turns green. |
| 7 | **Space Shooter** | Bullet Hell | Bullet-hell anime space combat. |
| 8 | **Typing Speed Race** | Typing | Race the clock. WPM tracked live. |
| 9 | **2048 Neon Grid** | Puzzle | Merge neon tiles, reach 2048. |
| 10 | **Cyber Chess** | Strategy | Full chess vs. minimax AI with neon glow pieces. |
| 11 | **Guitar Hero Neon** | Rhythm | Hit falling neon notes on beat — `D F J K` keys. |

> Control hints are shown on-screen inside each game, and the games support **touch
> controls** (a virtual joystick and tap keys) for mobile play.

---

## ✨ Features

- 🎮 **11 working mini-games** — all playable immediately, no install or build tooling.
- 🌌 **Neon / cyberpunk theme** — glowing borders, glass panels, and animated background canvas.
- 🖱️ **Custom cursor & trail** — a glowing dot that follows your pointer everywhere.
- 📖 **Manga-style intro** — a splash animation you can skip with one click.
- 🃏 **Character card generator** — spin up a random avatar, name, level, XP, and badges.
- 🏆 **Session scoreboard** — see the top players across the games.
- 🎵 **In-browser sound effects** — Web Audio API, no audio files required.
- 📱 **Responsive + touch-friendly** — virtual joystick and tap controls on mobile.

---

## 🚀 Getting Started

### Clone

```bash
git clone https://github.com/TejaPriyan/TejaGamehub.git
cd TejaGamehub
```

### Run

There is **no build step**. Either:

1. Double-click `index.html`, or
2. Serve it locally with any static file server:

```bash
# Python
python3 -m http.server 8080
# then open http://localhost:8080

# Node.js
npx serve .
```

---

## ☁️ Deploy to GitHub Pages

Since this is a dependency-free static page, deploying to **GitHub Pages** takes just a couple
of clicks:

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Choose the `main` branch and the `/ (root)` folder.
5. Save. Your site goes live at `https://<username>.github.io/TejaGamehub/`.

Alternatively, host it anywhere a static file can be served — Netlify, Vercel, Cloudflare
Pages, or a simple static server.

---

## 🗂️ Project Structure

```
TejaGamehub/
├── index.html               # The entire app (markup + styles + game logic)
├── README.md                # You are here
├── LICENSE                  # MIT License
├── .gitignore
├── SECURITY.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── .github/
    ├── ISSUE_TEMPLATE/      # Bug report & feature request templates
    └── PULL_REQUEST_TEMPLATE.md
```

---

## 🧰 Tech Stack

- **HTML5** & **CSS3** — layout, neon styling, animations, responsiveness
- **Vanilla JavaScript** — all game engines (Canvas 2D + DOM), Web Audio API sounds
- **Google Fonts** — [Orbitron](https://fonts.google.com/specimen/Orbitron),
  [Rajdhani](https://fonts.google.com/specimen/Rajdhani), and
  [Bangers](https://fonts.google.com/specimen/Bangers)
- **Zero dependencies** — no framework, no bundler, no package manager required

---

## 🤝 Contributing

Contributions are welcome! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) and
[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) before getting started. If you find a bug or have an
idea, open an [issue](https://github.com/TejaPriyan/TejaGamehub/issues).

---

## 🔒 Security

Please report any security vulnerabilities privately. See
[SECURITY.md](SECURITY.md) for details. **Do not** open a public issue for a security problem.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

Made with 💜 by **[Teja Priyan](https://github.com/TejaPriyan)** ·
[Report a bug](https://github.com/TejaPriyan/TejaGamehub/issues/new) ·
⭐ Star the repo if you enjoy it!

</div>
