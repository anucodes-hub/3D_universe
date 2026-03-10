
🌌 Interactive 3D Gesture Particles
A real-time, interactive 3D particle system built with Three.js and MediaPipe Hands. This project allows users to manipulate thousands of particles in 3D space using physical hand gestures captured via webcam.

🚀 Live Demo
https://github.com/anucodes-hub/3D_universe/

🖐️ How to Use
Gesture	Action
Move Hand	Rotates the particle system in 3D space.
Pinch (Thumb + Index)	Dynamically scales and expands the particle volume.
Drop-down Menu	Switch between morphing shapes: Sphere, Heart, Saturn, and Flower.
🛠️ Features
Volumetric Shapes: Particles aren't just outlines; they fill the 3D volume of hearts, flowers (phyllotaxis pattern), and Saturn.

GPU Acceleration: Uses Custom GLSL Vertex Shaders to handle 15,000+ particles smoothly at 60 FPS.

Real-time Vision: Leverages MediaPipe's machine learning models to track 21 hand landmarks instantly.

Additive Blending: Particles glow and blend to create a "neon energy" aesthetic.

💻 Tech Stack
Three.js: 3D Scene rendering and BufferGeometry.

MediaPipe Hands: Computer vision for gesture detection.

GLSL: Custom shaders for particle positioning and morphing.

HTML5/CSS3: UI overlay and camera feed management.

📝 Setup & Installation
Clone the repository:

Bash
git clone https://github.com/yourusername/gesture-particles.git
Open index.html in any modern web browser.

Note: Ensure you grant webcam permissions when prompted!
