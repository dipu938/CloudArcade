# CloudArcade 🕹️⚡

An ultra-modern, zero-download web gaming platform designed specifically for instantaneous **GitHub Pages** hosting.

![CloudArcade Logo](./assets/images/logo.png)

---

## 🚀 How to Deploy to GitHub Pages

You can host this website completely free on GitHub Pages in under 2 minutes:

### Option A: Using GitHub Web Interface
1. Create a new repository on [GitHub](https://github.com/new) (e.g., `cloud-arcade` or `<your-username>.github.io`).
2. Upload all the files in this directory (`index.html`, `assets/`, `README.md`).
3. In your GitHub repository, go to **Settings** → **Pages** (in the left sidebar).
4. Under **Branch**, select `main` (or `master`) and `/ (root)` folder, then click **Save**.
5. Within 30–60 seconds, your site will be live at:
   ```
   https://<your-username>.github.io/<repository-name>/
   ```

### Option B: Using Git Command Line
```bash
git init
git add .
git commit -m "Initial commit of CloudArcade platform"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
Then enable GitHub Pages under **Settings** → **Pages**.

---

## 🎮 Key Features

1. **Instant Play In-Browser Mini-Games**:
   - **CyberRacer: Neo Tokyo**: High-speed vertical pseudo-3D neon dodge racer with nitro boost.
   - **ViperGrid.io**: Classic neon slither arena eating energy cores.
   - **Galactic Overdrive 84**: Retro arcade bullet hell shoot-'em-up with alien waves.
   - **Prismatics Zero**: Laser optics puzzle rotating mirrors to power reactor crystals.
   - **NeoPuck Striker**: Fast cyber air hockey against responsive AI.

2. **Virtual D-Pad & Touch Controls**:
   - Dynamically activates on touch-capable screens and mobile viewports.
   - Includes directional D-Pad plus Action buttons [A / Shoot / Boost] and [B / Nitro].
   - Can also be manually toggled on desktop with the screen controls icon.

3. **Multi-View Catalog**:
   - **Discover**: Featured Hero Spotlight, live scrolling ticker, Continue Playing saves, and Weekend Showdown tournament countdown.
   - **Browse All**: Interactive Genre Filters (Action, Puzzle, Racing, etc.), Hardware Chips (Gamepad, WebGL, Touch), Grid/List view switcher, and pagination.
   - **Top Rated**: Hall of Fame global titles.
   - **Multiplayer**: Live simulated 100-player lobbies and latency telemetry.
   - **Tournaments**: Live tournament brackets and entry confirmation.

4. **Universal Search (`Ctrl+K`)**:
   - Search across 1,200+ simulated titles by name, genre, or developer.

5. **Built-in Web Audio Synthesizer**:
   - Authentic retro 8-bit sound effects (laser, coin, explosion, points chime) with mute/unmute toggle.
