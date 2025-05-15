# 🚄 3D Endless Runner – Sliding, Trains & Modals

A high-speed, interactive **3D Endless Runner Game** made with **Three.js**, featuring:
- Multi-lane dodging
- Dynamic obstacles like train bogies and barriers
- Double jump with spin
- Sliding under barriers
- Real-time coin collection and scoring
- Countdown start and modals for pause and game over

---

## 🎮 Gameplay Highlights

| Feature               | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| 🛤️ Lanes             | Switch between 3 lanes to dodge obstacles                                   |
| ⛹️ Double Jump + Spin | Jump once to hop, double jump to spin mid-air                              |
| 🧎‍♂️ Slide           | Slide under low barriers (only from ground)                                 |
| 🟡 Coins              | Collect coins along paths or mid-air to boost score                         |
| 🚆 Trains             | Randomly placed trains (1-4 bogies) create dynamic challenge                |
| 🎨 Graffiti Walls     | Procedurally generated graffiti textures along side walls                   |
| ⏳ Countdown + Pause  | Game starts after a countdown. Supports pause/resume                       |
| 🎯 Scoreboard         | Tracks time, coins, and local best score (stored in `localStorage`)        |
| 📱 Mobile Responsive  | Keyboard-based gameplay, optimized for desktop interaction                 |

---

## 📸 Screenshots 

![image](https://github.com/user-attachments/assets/49ec8e98-72ea-4a51-a3bf-9160b3c3a830)
![image](https://github.com/user-attachments/assets/778e575e-9f63-4811-957c-b7ac2950db24)
![image](https://github.com/user-attachments/assets/467291ed-b2ac-44df-b538-022059e2d1b8)
![image](https://github.com/user-attachments/assets/b32aa3e1-de52-45c9-b650-36c7d14532e2)

---

## 🔧 Controls

| Key          | Action                      |
|--------------|-----------------------------|
| ⬅️ / ➡️       | Switch left/right lane      |
| ⬆️           | Jump (double press to spin) |
| ⬇️           | Slide (only when grounded)  |
| ⏸ Blur/tab out | Auto pause modal          |

---

## 🧩 Technical Overview

| Tech             | Use                                   |
|------------------|----------------------------------------|
| **Three.js**     | 3D scene, models, textures, fog        |
| **Vanilla JS**   | Core logic, collision detection, UI    |
| **localStorage** | Save high score                        |
| **CanvasTexture**| Dynamic graffiti walls                 |
| **Box3**         | Collision boxes for player & obstacles |

---

## 🗂 Structure

- `makeRunnerPlayer()` – Builds player model with body, head, legs, and arms
- `generateSegment()` – Creates ground, sleepers, rails, walls
- `spawnObstacle()` – Randomly places bogies, barriers, or coins
- `animate()` – Core game loop: physics, movement, rendering, scoring

---

## 📥 How to Use

1. Clone or download the repository.
2. Open `index.html` in a browser.
3. Press `↑`, `↓`, `←`, `→` to play.
4. Try to survive as long as you can. Coins and time increase your score!

---

## ✨ To-Do Ideas

- Sound effects and background music
- Power-ups (e.g., magnet, shield, 2x score)
- Mobile touch controls
- Skins or themes for the player

---

## 🧑‍💻 Author

Built by **Ishita Rai**  
🎮 JavaScript + Three.js + Creativity

---

## 🪪 License

Free for personal or educational use.  
MIT-style open use allowed with attribution.

---
