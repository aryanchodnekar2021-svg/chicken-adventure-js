# chicken-adventure-js
"A retro-style, multi-level platformer game built entirely with vanilla JavaScript and HTML5 Canvas. Guide the chicken, collect seeds, and avoid foxes!"
# 🐔 Chicken Adventure

**Chicken Adventure** is a classic 2D platformer game built from scratch using **HTML5 Canvas** and **Vanilla JavaScript**. 

Control a brave chicken as it navigates through 5 increasingly difficult levels, collecting seeds, dodging foxes, and trying to reach the safety of the nest!

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Tech](https://img.shields.io/badge/tech-HTML5%20%7C%20JS%20%7C%20CSS-orange.svg)

## 🎮 Game Features

* **5 Unique Levels:** Progression from "Easy" to "Master" difficulty.
* **Pure JavaScript Engine:** No external game libraries used; physics, collision detection, and rendering are custom-built.
* **Dynamic Physics:** Includes gravity, momentum, and platform collision logic.
* **Enemy AI:** Foxes patrol platforms and change direction upon hitting edges.
* **Visual Effects:** Particle systems for collecting items and defeating enemies.
* **Responsive UI:** Start menu, level selector, HUD, and Game Over/Win screens.

## 🕹️ How to Play

1.  **Clone the repository** or download the source code.
2.  Open the `index.html` file in any modern web browser.
3.  Use the **Start Menu** to select a level (Levels 1-5).

### Controls

| Action | Key(s) |
| :--- | :--- |
| **Move Left** | `Left Arrow` or `A` |
| **Move Right** | `Right Arrow` or `D` |
| **Jump** | `Spacebar` or `Up Arrow` |
| **Restart** | Button on screen |

### Objectives
* **Collect Seeds (🌾):** Increases your score.
* **Defeat Foxes (🦊):** Jump on top of them to remove them (Mario-style).
* **Reach the Nest (🪹):** Located at the end of the level to win.
* **Watch your Hearts (❤️):** You start with 3 lives!

## 🛠️ Technical Implementation

This project demonstrates core game development concepts without the overhead of an engine:

* **Game Loop:** Uses `requestAnimationFrame` for smooth rendering.
* **Canvas API:** All graphics are drawn programmatically using the HTML5 Canvas context.
* **State Management:** Handles game states (Menu, Playing, Game Over, Win).
* **Collision Detection:** AABB (Axis-Aligned Bounding Box) collision for platforms and entities.

## 📂 Project Structure

```text
chicken-adventure/
├── index.html      # Contains the game structure and logic
└── README.md       # Project documentation
