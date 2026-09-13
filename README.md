# 🚩 Ganesha Divine Dash (3D Endless Runner)

A 3D Subway Surfers style endless runner web game created for college game development competitions celebrating **Ganesh Chaturthi**.

---

## 🌟 Game Highlights & Competition Features
- **Zero Asset Dependency**: Built using procedural 3D Three.js geometry and browser Web Audio API music synthesis. Guaranteed instantaneous loading with 0 broken asset risks.
- **3D Festive Aesthetics**:
  - Lord Ganesha low-poly 3D character model with crown (Mukut), fan ears, dhoti, and radiant halo aura.
  - Temple boulevard with carved pillars, glowing oil diyas, colorful Rangoli pavement, marigold garlands, and golden sunset sky.
  - Particle visual juice (marigold rose petals, golden dust trails, celebration fireworks).
- **Controls & Gameplay**:
  - 3 continuous running lanes with smooth physics interpolations.
  - **Jump** over wooden carts & kalash.
  - **Slide/Duck** under temple archways & banners.
  - Keyboard Arrow keys / WASD / Spacebar & Mobile Touch Swipe Controls.
- **Power-Ups**:
  - 🧲 **Modak Magnet**: Pulls all nearby gold modaks toward Ganesha.
  - 🔱 **Trishul Shield**: Grants invincibility to smash through wooden cart barriers.
  - 🐭 **Celestial Mushak Flight**: Rides Ganesha's mouse high above obstacles into a golden sky lane.
- **Modak Shop & Meta**:
  - Spend collected Modaks to upgrade Magnet duration, Shield duration, Mushak flight speed, and Cosmic Aura color.
  - Progress persists in browser `localStorage`.
- **College Leaderboard**:
  - Local High Score tracking + optional Express.js campus leaderboard server.

---

## 🎮 Game Controls

| Action | Desktop Keyboard | Mobile Touch |
| :--- | :--- | :--- |
| **Move Left** | `←` or `A` | Swipe Left / Touch Button |
| **Move Right** | `→` or `D` | Swipe Right / Touch Button |
| **Jump** | `↑` / `W` / `Space` | Swipe Up / Touch Button |
| **Slide / Duck** | `↓` or `S` | Swipe Down / Touch Button |
| **Pause** | `Esc` or `P` | Touch Pause Icon |

---

## 🚀 How to Run the Game

### Method 1: Instant Local Browser Play (No Server Needed)
Simply open `E:\ganesha-runner\index.html` directly in Google Chrome, Microsoft Edge, or Mozilla Firefox!

Or start a quick local HTTP server:
```bash
npx serve E:\ganesha-runner
```
Open `http://localhost:3000` in your browser.

### Method 2: Launch with Competition Live Leaderboard Server
If you want players and judges to submit their name and view a shared campus leaderboard:

1. Open terminal in `E:\ganesha-runner\server`:
```bash
cd E:\ganesha-runner\server
npm install
npm start
```
2. Open `index.html` in your browser. Any high scores submitted on the Game Over screen will automatically sync to the campus leaderboard!

---

## 🛠 Tech Stack
- **Engine**: Three.js (WebGL 3D)
- **UI & Styling**: HTML5, Vanilla CSS3 (Glassmorphism design system)
- **Audio Engine**: Web Audio API (Synthesized Dhol-Tasha drums & chimes)
- **Backend (Optional)**: Node.js, Express.js, LocalStorage API
