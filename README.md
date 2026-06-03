# VELOCITY — Futuristic Car Racing Game

> A fast-paced browser racing game built with **HTML5 Canvas, CSS, and Vanilla JavaScript** featuring neon cyberpunk visuals, dynamic audio, combo scoring, boost mechanics, and progressive difficulty.

live at -  https://tanish-sareen.github.io/VELOCITY-Futuristic-Car-Racing-Game/

---

## 🎮 Overview

**VELOCITY** is an arcade-style racing game where players dodge traffic, build score multipliers through close overtakes, and push their limits using a boost system. The game features a futuristic UI, animated speedometer, sound effects generated with the Web Audio API, and persistent player statistics saved locally.

---

## ✨ Features

### 🚗 Gameplay

* Smooth lane-based racing mechanics
* Dynamic traffic generation
* Progressive difficulty and leveling system
* Life system with collision damage
* Speed boost mechanic
* Combo multiplier for consecutive overtakes
* Distance tracking
* High-score system

### 🎨 Visual Effects

* Cyberpunk-inspired neon UI
* Real-time speedometer
* Animated particle effects
* Screen shake on crashes
* Detailed custom vehicle rendering
* Minimap navigation display
* HUD with live statistics

### 🔊 Audio

* Real-time engine sound synthesis
* Crash sound effects
* Boost activation effects
* Combo and level-up sounds
* Mute / unmute functionality

### 💾 Persistence

Uses **Local Storage** to save:

* Best score
* Highest speed reached
* Total races played

---

## 🎯 Controls

| Key   | Action             |
| ----- | ------------------ |
| ← →   | Steer Left / Right |
| ↑     | Accelerate         |
| ↓     | Brake              |
| Space | Boost              |
| P     | Pause Game         |
| 🔊    | Toggle Sound       |

### Mobile Support

* Touch controls for steering
* Responsive gameplay experience

---

## 🕹️ How to Play

1. Start the game by clicking **RACE NOW**.
2. Use arrow keys to control your vehicle.
3. Avoid crashing into traffic.
4. Overtake cars to earn points and increase combo multipliers.
5. Use boost strategically to maximize score.
6. Reach higher levels as distance increases.
7. Try to beat your personal high score.

---

## 📈 Scoring System

### Points Earned From:

* Maintaining speed
* Overtaking vehicles
* Combo multipliers
* Surviving longer distances

### Combo System

* Each successful overtake increases combo multiplier.
* Higher combo = more points.
* Collisions reset the combo.

---

## 🏆 Progression

The game becomes harder over time:

* Faster traffic vehicles
* Increased spawn rates
* Higher maximum speeds
* More challenging gameplay

Level increases every **500 meters** traveled.

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* HTML5 Canvas API
* Web Audio API
* Local Storage API

---

## 📂 Project Structure

```text
velocity/
│
├── car-racing-game.html
│
└── README.md
│
├──MIT LICENSE

```

Everything is contained within a single HTML file:

* UI
* Styling
* Game Logic
* Audio System
* Canvas Rendering

---

## 🚀 Running the Game

### Option 1: Open Directly

Simply open: 
 https://tanish-sareen.github.io/VELOCITY-Futuristic-Car-Racing-Game/
```bash
car-racing-game.html
```

in any modern browser.

### Option 2: Local Server

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

---

## 🌐 Browser Compatibility

* Google Chrome ✅
* Microsoft Edge ✅
* Firefox ✅
* Brave ✅
* Opera ✅

Recommended: Latest Chromium-based browser.

---

## 🎨 Highlights

* Futuristic racing aesthetics
* Dynamic speedometer dashboard
* Real-time audio synthesis
* Particle and lighting effects
* Persistent player statistics
* Lightweight and dependency-free

---

## 👨‍💻 Developer

**Tanish Sareen**

### ⭐ If you like this project, consider giving it a star on GitHub! 🚀
