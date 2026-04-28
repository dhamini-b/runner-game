# 🎮 Endless Runner 3D (Temple Runner)

A 3D endless runner game inspired by Temple Run, built using **Three.js** and modern frontend technologies.  
The game features smooth animations, lane-based movement, obstacle avoidance, and mobile support.

---

## 🚀 Live Demo

- 🌐 AWS (S3): https://your-aws-link  
- 🌍 GitHub Pages: https://dhamini-b.github.io/runner-game/

---

## 🎮 Features

- 3D gameplay using Three.js
- Endless runner mechanics (3-lane system)
- Smooth lane switching with interpolation (LERP)
- Jump physics with gravity simulation
- Dynamic obstacle spawning
- Collision detection system
- Score tracking system
- Start screen & Game Over UI
- Mobile swipe controls 📱
- Lighting, shadows, and fog effects for depth

---

## 🎮 Controls

### 💻 Desktop
- ⬅️ Arrow Left → Move Left  
- ➡️ Arrow Right → Move Right  
- ⬆️ Arrow Up / Space → Jump  

### 📱 Mobile
- Swipe Left → Move Left  
- Swipe Right → Move Right  

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3 (Glassmorphism UI)**
- **JavaScript (ES6 Modules)**
- **Three.js (3D Rendering Engine)**

---

## 🧠 Architecture

The project is structured like a mini game engine:

- `Game` → Main game loop & state management  
- `SceneManager` → Camera, lighting, rendering  
- `Player` → Movement & animation  
- `Physics` → Gravity & jump logic  
- `ObstacleManager` → Spawning & collision  
- `InputManager` → Keyboard & touch input  
- `UIManager` → HUD updates  

---

## 📂 Project Structure
runner-game/
│── index.html
│── README.md

---

## 📌 How to Run Locally

1. Download or clone the repository
2. Open `index.html` in your browser
3. Click **Play** and start the game 🎮

---

## 💡 Future Improvements

- Add sound effects 🔊  
- Add character models (GLTF) 🧍  
- Add power-ups & coins 💰  
- Improve collision system (bounding boxes)  
- Add levels & environment variations 🌍  
- Add camera shake & visual effects ✨  

---

## 👩‍💻 Author

**Dhamini**  
- GitHub: https://github.com/dhamini-b  

---

## 📜 License

This project is for learning and personal use.
