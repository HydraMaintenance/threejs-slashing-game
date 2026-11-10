# ThreeJS Slashing Game

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:00C9FF,100:92FE9D&height=220&section=header&text=Threejs%20Slashing%20Game&fontSize=60&fontColor=ffffff&animation=twinkling&fontAlignY=35&desc=Master%20The%20Art%20Of%20The%20Sword%20In%20Your%20Browser&descAlignY=55&descSize=20)

<div align="center">

![Version](https://img.shields.io/badge/version-3.1.0-92FE9D?style=for-the-badge&logo=git&logoColor=black)
![Downloads](https://img.shields.io/badge/downloads-95.2K-00C9FF?style=for-the-badge&logo=download&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-FFD700?style=for-the-badge&logo=opensourceinitiative&logoColor=black)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20webgl-FF5252?style=for-the-badge&logo=threedotjs&logoColor=white)

</div>

<img width="1672" height="941" alt="59f41bf5-7a02-451e-9349-a48e1bde9e2d" src="https://github.com/user-attachments/assets/a44a7a22-d335-4346-ae4c-446cfd2f46bd" />


---

## ⚔️ The Blade Is Real

Browser games used to be simple 2D flash animations. Today, thanks to the power of WebGL and Three.js, you can play console-quality games directly in your browser. **ThreeJS Slashing Game** is a testament to that power.

This is a fully playable, 3D hack-and-slash action game. You control a samurai warrior in a stylized, low-poly arena. Waves of enemies spawn, and your job is simple: slash them all. But this is not a button-masher. The game features a sophisticated combo system, parry mechanics, and a dynamic camera that follows the action.

This repository contains the complete, open-source source code for the game. It is designed to be an educational resource for developers who want to learn how to build 3D games for the web. It includes detailed comments explaining how to handle 3D models, animations, collision detection, and the game loop. It is the perfect starting point for your own browser-based game studio.

---

## ⚙️ Inside The Game Engine

We have broken down the game into three core systems.

### 1. The Player Controller
The player is not just a static model. The controller handles movement, rotation, and the complex state machine for attacks. When you click, the player performs a light attack. When you hold the mouse button, the player charges a heavy attack. If you press the spacebar at the exact moment an enemy attacks, you perform a perfect parry, stunning the enemy and opening them up for a critical hit.

### 2. The Enemy AI
The enemies are not dumb zombies. They use a finite state machine. They patrol the arena, detect the player, and approach. When they are close, they choose between a fast swipe or a slow, powerful overhead strike. They also react to the player's parries, backing off and re-evaluating their strategy.

### 3. The Combat System
The game uses **Sphere Collision Detection** for hitboxes. Every sword swing creates a sphere in front of the player. If an enemy's body sphere intersects with the sword sphere, a hit is registered. The system calculates the damage based on the angle of the attack and the enemy's armor.

---

<div align="center">

### 🔗 Ready to start slashing?

[![Play Game](https://img.shields.io/badge/⚔️_PLAY_GAME-00C9FF?style=for-the-badge&logoColor=white)](https://share.google/krlIHo91nilOfgRAa)

</div>

---

## ⚡ Core Features & Capabilities

| Feature | Description |
| :--- | :--- |
| **Smooth 3D Graphics** | Powered by Three.js and WebGL for 60 FPS gameplay |
| **Combo System** | Chain light and heavy attacks for devastating combos |
| **Parry Mechanic** | Perfect timing rewards you with a critical opening |
| **Dynamic Camera** | The camera shakes and zooms during heavy hits |
| **Wave Survival** | Enemies get progressively harder with every wave |
| **Mobile Support** | Touch controls optimized for phones and tablets |
| **Open Source** | Fully commented codebase to learn from and modify |

---

## 🧠 Under The Hood: The Game Loop

Every game, from Pong to Elden Ring, is built on the **Game Loop**. This is an infinite `while` loop that runs 60 times per second.

In our game, the loop does three things:
1. **Update:** It reads the user input (mouse clicks, keyboard presses), updates the player's position, updates the enemy AI, and checks for collisions.
2. **Render:** It draws the new frame to the screen using Three.js.
3. **Sync:** It uses `requestAnimationFrame` to ensure the loop syncs with the monitor's refresh rate, preventing screen tearing.

The result is a fluid, responsive experience. Because it is running in the browser, the game is instantly available to anyone with an internet connection. No downloads, no installations.

---

<div align="center">

### ⚙️ Need a detailed configuration guide?

[![Setup Guide](https://img.shields.io/badge/📖_VIEW_SETUP_GUIDE-92FE9D?style=for-the-badge&logoColor=black)](https://share.google/krlIHo91nilOfgRAa)

</div>

---

## 🛠️ Tech Stack

<div align="center">

![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=flat-square&logo=blender&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 🤝 Community & Contributing

We believe that browser gaming should be open and accessible to everyone. If you have created a new weapon, improved the AI, or found a bug in the collision detection, we welcome your contributions!

1. **Fork** the repository.
2. **Create** your feature branch (`git checkout -b feature/new-weapon`).
3. **Commit** your changes (`git commit -m 'Add new weapon'`).
4. **Push** to the branch (`git push origin feature/new-weapon`).
5. **Open** a Pull Request.

Please read our `CONTRIBUTING.md` for detailed coding standards and testing requirements. We also have an active Discord server where you can share your gameplay clips, ask for help with Three.js, and discuss the latest trends in web game development.

---

## 📬 Contact & Support

- 💬 **Discussions:** Join the conversation in the GitHub Discussions tab.
- 🐛 **Issues:** Found a bug? Let us know via the Issues tracker.
- 📧 **Email:** Reach out directly at support@threejs-game.dev.

---

<div align="center">

### ⭐ If this game inspires you, give it a star! ⭐

[![Star](https://img.shields.io/badge/⭐_STAR_THIS_REPO-FFD700?style=for-the-badge&logo=github&logoColor=black)](https://github.com/your-username/threejs-slashing-game)

---

### 🚀 Start playing today

[![Get Started](https://img.shields.io/badge/🚀_GET_STARTED_GUIDE-FF5252?style=for-the-badge&logoColor=white)](https://share.google/krlIHo91nilOfgRAa)

<sub>Crafted with precision and ❤️ by the ThreeJS Slashing Game community</sub>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:92FE9D,100:00C9FF&height=120&section=footer)

</div>
