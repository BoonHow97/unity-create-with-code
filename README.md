# Unity 6 Engineering Prototypes

A collection of five functional prototypes developed to explore the **Unity 6** engine architecture and **C#** systems. This repository demonstrates core game development principles, including physics-based simulation, state-driven animation, and efficient resource management.

---

## Technical Stack
* **Engine:** Unity 6 (6000.3.0f1)
* **Language:** C# (.NET)
* **Version Control:** Git (Mono-repo architecture)

---

## Project Breakdown

### 01: Driving Simulator
**Focus:** Kinematics and Camera Systems
* Resolved transformation jitter by utilizing `LateUpdate()` for camera interpolation.
* Implemented local multiplayer through a split-screen input handler.

### 02: Food Flight
**Focus:** Lifecycle Management and Spawning
* Debugged spatial boundary logic to manage object destruction.
* Engineered a wave-based spawning system for dynamic entity management.

### 03: Jump Force
**Focus:** State Machines and Particle Systems
* Architected a state-driven animation controller to synchronize physics events with visual feedback.
* Integrated dynamic particle effects and audio triggers for enhanced feedback loops.

### 04: Sumo Battle
**Focus:** Physics Interaction and Vector Math
* Developed custom impulse-force mechanics based on directional vector calculations and distance scaling.
* Implemented a modular power-up system using trigger-based collision detection.

### 05: Clicky Mouse
**Focus:** UI Systems and State Persistence
* Built an event-driven UI system with dynamic difficulty scaling.
* Implemented persistent data management for high-score tracking across game sessions.

---

## Engineering & Troubleshooting
* **Debugging:** Successfully resolved 10+ logic challenges in provided "broken" scripts, focusing on refactoring for maintainability.
* **Optimization:** Configured recursive `.gitignore` patterns to exclude ~1.2GB of unnecessary Unity metadata, ensuring a clean and portable repository.
* **Architecture:** Organized five independent projects into a single, cohesive mono-repo structure.

---

## Local Setup
1. **Clone:** `git clone https://github.com/BoonHow97/unity-create-with-code.git`
2. **Open:** In Unity Hub, select **Add** -> **Add project from disk**.
3. **Navigate:** Choose a specific prototype folder (e.g., `Prototype 1`).
4. **Run:** Open `SampleScene` and enter Play mode.

---