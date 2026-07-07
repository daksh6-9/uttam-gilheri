# 💾 UTTAM GILHERI // Neon Grapple Protocol

A fast-paced, high-octane neon cyberpunk spiritual successor to *Mecha Chameleon*. Instead of a mechanical lizard swinging with its tongue, players control **Uttam Gilheri**—a cybernetic neon squirrel navigating a high-tech vertical metropolis using a plasma-powered vector grapple line.

---

## 🕹️ Live Demo

🚀 **[Click Here to Play the Game Instantly in Your Browser](https://www.google.com/search?q=%23)** *(Replace this with your actual GitHub Pages deployment link)*

---

## 🚀 Key Features

* **Advanced Pendulum Physics Loop:** Built entirely from scratch using pure JavaScript linear-to-angular velocity physics equations for real, satisfying momentum-based swinging mechanics.
* **Immersive Cyberpunk Aesthetics:** Features a striking, high-saturation color palette consisting of Cyberpunk Pink (`#ff007f`), Neon Cyan (`#00f3ff`), and Acid Green (`#39ff14`).
* **Procedural Infinite City Generation:** Structural neon platforms and anchor matrices spawn indefinitely ahead of the player as they scale the metropolis.
* **Overdrive Turbo Boost Mechanic:** Collect hidden glowing purple quantum chips to trigger a 5-second supersonic kinetic boost.
* **Sleek Glassmorphic HUD:** Transparent overlays utilizing CSS background blurs and intense box-shadow glows provide real-time altitude metrics and score indexes.

---

## 🎮 How to Play

### 💻 Controls

* **Press & HOLD Left Click (or Tap on Mobile):** Deploys the plasma grapple line to the nearest ceiling anchor point directly ahead of you.
* **RELEASE Hold:** Disconnects the grapple line, instantly converting your angular momentum into an intense linear slingshot trajectory.

### 🎯 Objective

Navigate as far right through the network grid as possible. Keep your momentum high to swing over security towers, avoid falling into the digital grid sludge below, and attempt to overwrite the network high scores!

---

## 🛠️ Tech Stack & Architecture

This architecture is packaged entirely into a lightweight **single-file distribution layer (`index.html`)** to eliminate cross-origin request policies, ensuring effortless portability.

```
├── UI Layout Layer     --> Tailwind CSS v4 Engine & Google Fonts Integration
├── HUD Overlay State   --> Vanilla JavaScript DOM Matrix Drivers
└── Physics Core Engine --> HTML5 Canvas 2D Rendering Context

```

* **Display Engine:** HTML5 Canvas API (Custom 60 FPS requestAnimationFrame loop)
* **Styling Engine:** Tailwind CSS Engine via CDN
* **Typography:** Google Fonts (`Orbitron` & `Share Tech Mono`)

---

## 📦 Local Installation & Setup

Because the architecture utilizes a modular single-file pattern, running it locally is incredibly straightforward:

1. **Clone the repository:**
```bash
git clone https://github.com/YOUR_USERNAME/uttam-gilheri.git

```


2. **Navigate into the project directory:**
```bash
cd uttam-gilheri

```


3. **Launch the game:**
Simply double-click the `index.html` file to launch it inside any modern web browser (Chrome, Firefox, Safari, Edge), or run a lightweight local server extension like Live Server in VS Code.

---

## 📜 Modification & Tweaks

Want to hack the core framework parameters? Open `index.html` and tweak these data parameters inside the configuration block:

```javascript
const squirrel = {
    gravity: 0.15,     // Lower this value (e.g., 0.08) for floaty moon gravity
    drag: 0.992,       // Adjust air friction metrics
    vx: 5,             // Change initial horizontal launch speed
};

```

---


1. Create a file named `README.md` in your game's root directory.
2. Paste the text above inside it.
3. Don't forget to update your **username** and your **Live Demo** link at the top once you have enabled **GitHub Pages** under your repository settings!
