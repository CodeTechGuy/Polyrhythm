<div align="center">

# ✦ P O L Y R H Y T H M ✦

**A mesmerizing audiovisual simulation of mathematical harmony.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Canvas](https://img.shields.io/badge/Canvas-API-blue?style=for-the-badge)
  <img src="https://img.shields.io/badge/Web%20Audio%20API-Synthesis-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Type-Polyrhythm%20Visualizer-purple?style=for-the-badge">

<br>

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDl5Z3V4Z3V4Z3V4/placeholder.gif" alt="Preview" width="600">
  <br>
<img width="3136" height="1550" alt="Image" src="https://github.com/user-attachments/assets/aca46760-6f2f-407c-b9fe-aa7036e448ea" />
<img width="3122" height="1534" alt="Image" src="https://github.com/user-attachments/assets/48c5b48f-b304-4e77-84b3-95164c032f86" />
</p>

</div>

---

## 📑 Introduction

This project implements a **browser-based polyrhythm visualizer** that integrates real-time animation with synthesized audio. Designed with a clean, modular architecture, it uses the **HTML5 Canvas API** for rendering, and the **Web Audio API** for procedural sound generation.  

Each rhythmic unit (“ball”) operates with its own frequency, velocity, and harmonic signature. As these independent cycles interact, they produce visually coherent yet rhythmically divergent patterns — resulting in a clear, intuitive visualization of **polyrhythmic structures**.

The codebase is intentionally minimal and framework-independent, making it easy to understand, extend, and integrate into larger systems.

---

### 📂 Project Structure

A modular breakdown of the codebase.

| File | Description |
| :--- | :--- |
| `index.html` | **The Core.** Sets up the canvas, defines simulation constants, and runs the main animation loop. |
| `track.js` | **The Path.** Calculates the semi-circular geometry and draws the curved lines for the tracks. |
| `ball.js` | **The Actor.** Handles physics movement, dynamic color changes, and triggers audio on bounce. |
| `sound.js` | **The Audio.** Manages the Web Audio API to generate oscillator tones with linear fade-out. |

---


<img width="3136" height="1550" alt="Image" src="https://github.com/user-attachments/assets/aca46760-6f2f-407c-b9fe-aa7036e448ea" />
<img width="3122" height="1534" alt="Image" src="https://github.com/user-attachments/assets/48c5b48f-b304-4e77-84b3-95164c032f86" />
### 🎛️ Configuration

You can tweak the simulation in `index.html` to change the aesthetics and physics:

* `N` — Controls the total number of tracks and balls (default: 20).
* `trackStep` — Adjusts the spacing distance between each track.
* `ballSpeed` — Changes the base velocity of the balls.
* `soundFrequencies` — The array defining the specific musical notes played on impact.

---

### 🚀 How to Run

1.  **Download** the source code files.
2.  **Open** `index.html` in any modern web browser.
3.  **Click** on Initialize Harmony.
4.  **Observe** the real-time visual and auditory polyrhythmic interaction.

---