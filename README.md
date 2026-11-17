# 🌱 Little Explorers • Play & Learn (Ages 3–5)

A calm, Montessori-inspired Progressive Web App (PWA) designed using **Tony Fadell's *Build*** and **Steve Jobs' *Apple*** design principles.

Like `colour-quest`, this repository is designed to be hosted directly on **GitHub Pages**, launching into instant, full-screen, responsive play with zero load time and 100% offline support.

---

## 🎮 Included Mini-Games

1. **🐻 Milo’s Color Garden:**
   * *Focus:* Color matching & sensory cause-and-effect.
   * *Mechanic:* Drag water droplets to sleeping flower buds; flowers bloom with rising pentatonic chords.
2. **🐦 Pip’s Cozy Treehouse:**
   * *Focus:* Shapes, spatial reasoning, and peek-a-boo animal habitats.
   * *Mechanic:* Chunky wooden shape-fitting with acoustic wood thuds and surprise animal reveals (Bunny, Fox, Owl).
3. **🐷 Penny’s Muddy Puddle Splash:**
   * *Focus:* Routine, dress-up, and motor laughter (inspired by *Peppa Pig*).
   * *Mechanic:* Slip on rainboots and tap to jump in the mud puddle with dynamic splatter physics and playful pig snorts.

---

## 🚀 How to Host on GitHub Pages in 60 Seconds

1. **Create a new repository on GitHub:**
   * Go to [github.com/new](https://github.com/new).
   * Name it `little-explorers` (or any name you prefer).
   * Keep it **Public**.

2. **Push this code to your repository:**
   ```bash
   cd /Users/shabaz/.gemini/antigravity/scratch/toddler-games-hub
   git remote add origin https://github.com/<YOUR-USERNAME>/little-explorers.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   * In your GitHub repository, click on **Settings** $\rightarrow$ **Pages** (in the left sidebar).
   * Under **Branch**, select `main` and folder `/ (root)`.
   * Click **Save**.

4. **Play Immediately:**
   * In ~30 seconds, GitHub gives you a live URL:  
     `https://<YOUR-USERNAME>.github.io/little-explorers/`
   * When you tap the link, the game opens directly in full screen!
   * On iPad / iPhone: Tap **Share** $\rightarrow$ **Add to Home Screen** to run it as a native standalone app with no browser URL bar!

---

## 🛠️ Design Architecture

* **Zero External Dependencies:** Built with pure vanilla HTML5, CSS3, SVG, and the Web Audio API. No node_modules, no webpack, no build steps required.
* **Offline-First PWA:** Features `manifest.webmanifest` and `service-worker.js` so children can play in cars or on airplanes without Wi-Fi.
* **Zero-Fail UX:** No penalty buzzers, no countdown timers, no "Game Over" states.
