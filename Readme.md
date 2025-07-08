## 🐰 My 3D Web Game - Powered by Three.js + PWA

> An interactive, mobile-ready 3D web game made with ❤️ using [Three.js](https://threejs.org/) — works offline, supports mobile install, and comes with a retro-fantasy visual flair!

![cover](https://your-domain.com/screenshot.jpg) <!-- Replace with a real screenshot -->

<br>

### 🚀 Features

* ⚙️ Built with **Three.js**
* 🎮 Playable on **mobile & desktop**
* 📦 Fully installable as a **PWA**
* 📡 Works **offline** after first load
* 🌟 Custom shaders, models, and animations
* 💾 **No download needed** — plays right in the browser

<br>

### 📱 Install the Game

> Want the full-screen, app-like experience on your phone? Tap below 👇

**👉 [Install Game](https://hamim-ally.github.io/skating-bunny/src/install.html)**
*(Works on Android Chrome & iOS Safari)*

<br>

### 💻 How to Run Locally

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
npx live-server
```

Or use [VSCode Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

> ⚠️ This project needs to run on `localhost` or `https` to work properly with service workers.

<br>

### 🛠 Tech Stack

| Tech                                                                     | Usage                       |
| ------------------------------------------------------------------------ | --------------------------- |
| [Three.js](https://threejs.org/)                                         | 3D rendering engine         |
| [GSAP](https://gsap.com/)                                                | Smooth animations           |
| [PWA](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps) | Installable web app         |
| Custom GLSL shaders                                                      | Floor effects & outlines    |
| GLTF                                                                     | 3D models (Rabbit + Carrot) |

<br>

### 🧾 Project Structure

```
📁 public/
├── index.html          # Game entry
├── install.html        # Custom install screen
├── service-worker.js   # Cache & offline logic
├── manifest.json       # PWA settings
├── models/
│   └── rabbit.glb
└── shaders/
    ├── outline.vert
    ├── outline.frag
    └── ...
```

<br>

### 🎨 Screenshots

| Gameplay                    | Install Prompt              | Floor Effects               |
| --------------------------- | --------------------------- | --------------------------- |
| ![ss1](./screenshots/1.png) | ![ss2](./screenshots/2.png) | ![ss3](./screenshots/3.png) |

<br>

### 🤝 Contribute?

PRs are welcome! If you're into shaders, animations, or mobile web performance — let’s collab 💪

<br>

### 📜 License

MIT © [Hamim Ally](https://github.com/yourusername)

<br>

Want me to add a version with Bengali headings, emojis, or custom art style? Just say the word 🔥
