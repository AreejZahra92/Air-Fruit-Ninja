# 🍉 Air Fruit Ninja

A browser-based hand-gesture game where you slice flying fruit in mid-air using just your index finger and a webcam — no mouse, no keyboard, no controller needed. Built entirely with vanilla JavaScript and Google's MediaPipe Hands for real-time hand tracking.

🔗 [Play it Live](https://areejzahra92.github.io/Air-Fruit-Ninja/)

---

## ✋ How to Play

- ☝️ Point your index finger at the camera to start slicing
- Fruit flies up from the bottom of the screen in arcs — swipe your finger through them to slice
- 💣 Avoid bombs — hitting one ends the game instantly
- Miss 3 fruits and it's game over
- ✊ Make a fist to pause the game, point your finger again to resume

---

## ✨ Features

### 🎮 Three Difficulty Modes
Choose Easy, Normal, or Hard from the start screen — each changes how fast fruit spawns and how many bombs appear.

### 🏆 High Score Tracking
Your best score is saved automatically and displayed alongside your current score. A trophy animation appears when you beat your personal best.

### 🔊 Sound Effects
Every slice, swipe, and bomb explosion has its own sound effect built with the Web Audio API — no external sound files needed.

### 💥 Screen Shake on Bomb Hit
The screen shakes dramatically when a bomb explodes, adding extra impact to the moment.

### ⏸️ Pause with a Fist Gesture
Make a closed fist in front of the camera to pause mid-game. Raise your index finger again to resume exactly where you left off.

### 🎯 Combo System
Slice multiple fruits in one fast swipe to chain combos and earn bonus points. The bigger the combo, the more points per fruit.

### 🌊 Smooth Hand Tracking
Uses exponential smoothing on fingertip coordinates for a fluid, lag-free slicing experience.

---

## 🛠️ Tech Stack

- HTML5 Canvas — game rendering, fruit physics, juice particle effects
- MediaPipe Hands — real-time 21-point hand landmark detection, fully client-side
- Web Audio API — procedurally generated sound effects (whoosh, splat, boom)
- Vanilla JavaScript — no frameworks, no build step, no dependencies to install

---

## 🚀 Running Locally

1. Clone this repo:
   git clone https://github.com/AreejZahra92/Air-Fruit-Ninja.git

2. Open air_fruit_ninja.html in Chrome (recommended for best webcam and audio support)

3. Allow camera access when prompted

4. Click Start Slicing and go!

---

## 🍓 Fruit Types

- 🍉 Watermelon — large, easy to hit
- 🍊 Orange — medium size
- 🍋 Lemon — medium size
- 🫐 Plum — medium size
- 🥝 Kiwi — smallest, hardest to slice

---

## 📋 Controls Summary

| Gesture | Action |
|---|---|
| ☝️ Index finger extended | Slice mode — move fast to cut fruit |
| ✊ Closed fist | Pause the game |
| ☝️ Finger again | Resume from pause |

---

## 📄 License

Feel free to use, modify, and build on this project.
