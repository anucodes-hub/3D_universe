

# 🌌 Interactive 3D Gesture Particles

A **real-time interactive 3D particle system** built using **Three.js** and **MediaPipe Hands**.
This project lets users manipulate **thousands of particles in 3D space using hand gestures captured through a webcam**.

By combining **computer vision** with **GPU-accelerated rendering**, the system creates immersive volumetric particle shapes that react dynamically to user gestures.

---

# 🚀 Live Demo

🔗https://github.com/anucodes-hub/3D_universe/

---

# 🖐️ How to Use

| Gesture                          | Action                                             |
| -------------------------------- | -------------------------------------------------- |
| **Move Hand**                    | Rotates the particle system in 3D space            |
| **Pinch (Thumb + Index Finger)** | Dynamically scales and expands the particle volume |
| **Drop-down Menu**               | Switch between different morphing particle shapes  |

Available particle morphs include:

* Sphere
* Heart
* Saturn
* Flower

---

# ✨ Features

### 🌟 Volumetric Particle Shapes

Particles fill the **entire 3D volume** rather than just outlines.
Shapes include:

* Heart
* Flower (generated using a **phyllotaxis pattern**)
* Saturn with ring structure
* Sphere

### ⚡ GPU Acceleration

Uses **custom shaders written in GLSL** to render **15,000+ particles smoothly at ~60 FPS**.

### 🧠 Real-Time Hand Tracking

Powered by **MediaPipe Hands**, which detects **21 hand landmarks** in real time for accurate gesture control.

### 🌈 Additive Particle Effects

Particles use **additive blending**, creating a glowing **neon energy aesthetic** when they overlap.

---

# 💻 Tech Stack

* **Three.js** – 3D scene rendering and particle geometry
* **MediaPipe Hands** – Computer vision for gesture detection
* **GLSL** – Custom vertex shaders for particle animation and morphing
* **JavaScript** – Core logic and interactions
* **HTML5 / CSS3** – UI overlay and webcam integration

---

# 🛠️ Setup & Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/gesture-particles.git
```

### 2️⃣ Open the project

Navigate to the folder and open **index.html** in any modern web browser.

### 3️⃣ Allow webcam permissions

When prompted by the browser, **grant webcam access** so gesture tracking can work.

---

# 📌 Notes

* Works best in **modern browsers like Chrome or Edge**
* Requires a **webcam** for gesture recognition
* Ensure hardware acceleration is enabled for smooth particle rendering
