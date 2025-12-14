#  JS Fireworks Simulation

A fun, interactive particle physics simulation built with vanilla JavaScript and HTML5 Canvas. This project creates a colorful fireworks display that runs automatically and reacts to user input.

##  Features

* **Physics Engine:** Custom implementation of gravity and friction to simulate realistic particle movement.
* **Dynamic Visuals:**
    * **Rainbow Mode:** Particles cycle through HSL colors as they fly.
    * **Burnout Effect:** Particles gradually shrink and fade out like real embers.
* **Custom Shapes:** Uses parametric equations to create explosions in specific shapes:
    *  Circle (Standard)
    *  Heart
    *  Star
* **Audio Sync:** Explosion sound effects trigger on both clicks and automatic launches.
* **Automation:** A self-running mode that launches fireworks at set intervals.
* **Randomizer:** Each explosion randomly selects a shape for a dynamic show.

##  How It's Made

This project uses **Object-Oriented Programming (OOP)** to manage the complexity of thousands of particles.

* **Tech Stack:** HTML5 Canvas, JavaScript (ES6).
* **Key Concepts:**
    * `requestAnimationFrame` for high-performance animation loops.
    * `setInterval` for automated event triggering.
    * Trigonometry (`Math.sin`, `Math.cos`) for calculating particle trajectories and shapes.
    * The HTML `Audio` object for sound management.

##  How to Run

1.  Clone the repository or download the files.
2.  Open `fireworks.html` in any modern web browser.
3.  **Click anywhere** to launch a firework manually, or sit back and watch the auto-show!

##  Future Improvements

* [ ] Add 3D perspective or trails.
* [ ] Implement mouse interaction (repel/attract particles).
* [ ] Add a UI panel to adjust gravity and friction in real-time.
