<div align="center">
  <img src="./Minato/art/hero.jpg" alt="Minato Namikaze Logo" width="100%">

  # ⚡ Minato Namikaze — The Yellow Flash (黄色い閃光)

  *An interactive, high-performance web experience dedicated to the Fourth Hokage of Konohagakure.*
  
</div>

---

## 📜 Overview

This project is a visually rich, WebGL-powered interactive web experience that brings the legendary **Minato Namikaze** to life. Through modern web technologies, it recreates his iconic abilities—from the blistering speed of the Flying Thunder God Technique (Hiraishin) to the concentrated chakra of the Rasengan.

### ✨ Key Features
- **Interactive Particle System**: "Reduced to particles" — cursor interaction scatters and reassembles Minato seamlessly.
- **Rasengan Tracking**: Interactive 3D chakra sphere mapping to user movement.
- **Hiraishin (Flying Thunder God)**: Dynamic lightning strikes and high-speed motion simulations.
- **Cinematic Scrubbing**: Frame-by-frame scroll animations tracking his awakening and movements.
- **Ghost Cursor & Ambient Layers**: Immersive visual effects like vignette, film grain, and atmospheric thunder.

## 🛠️ Technology Stack

Built with a focus on performance, modern aesthetics, and fluid animations:
- **Core**: HTML5, Vanilla JavaScript (ES6 Modules)
- **Styling**: Vanilla CSS with modern flexbox/grid and custom properties.
- **Graphics & 3D**: [Three.js](https://threejs.org/) for WebGL particle objects and physics.
- **Typography**: Shippori Mincho, Zen Kaku Gothic New, Anton, Space Grotesk, JetBrains Mono (via Google Fonts).

## 🚀 Getting Started

To run this project locally, simply serve the directory using any local web server.

### Prerequisites
- A modern web browser with WebGL support.
- A basic local server (e.g., VS Code Live Server, Node's `http-server`, or Python's `http.server`).

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Meghamittal0920/Minato.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Minato
   ```
3. Start a local server. For example, using npx:
   ```bash
   npx serve .
   ```
4. Open your browser and navigate to `http://localhost:3000`.

## 📂 Project Structure

```
Minato/
├── art/                  # Static images, assets, and the hero logo
├── frames/               # Image sequence frames for scroll animations
├── index.html            # Main markup and structure
├── minato.css            # Stylesheets and animations
├── minato.js             # Core logic, module imports, and orchestrator
├── particle-object.js    # Three.js WebGL particle system logic
└── ghost-cursor.js       # Custom interactive cursor logic
```

## ⚡ The Legacy of the Fourth Hokage

> *"I want everyone in the village to acknowledge me and become a great Hokage!"*

This repository stands as a tribute to one of the greatest ninja in the history of Konoha. Explore the code, fork the repo, and may the Yellow Flash guide your development!

---

<div align="center">
  Made with ⚡ and Chakra. 
</div>
