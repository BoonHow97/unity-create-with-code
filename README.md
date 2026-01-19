# Unity 6 Development Portfolio: Create with Code Series

This repository contains five interactive game prototypes developed as part of a self-directed study of the **Unity 6 Engine** and **C# scripting**. Each unit focuses on core game development pillars, including physics-based movement, object-oriented programming (OOP), and UI systems.

---

## 🛠 Technical Overview
* **Engine:** Unity 6 (6000.3.0f1)
* **Language:** C#
* **Version Control:** Git / GitHub (Managed via a mono-repo structure with recursive `.gitignore` optimization)

---

## 🎮 Prototypes & Key Learning Outcomes

| Prototype | Core Mechanics | Challenges Overcome & Features Added |
| :--- | :--- | :--- |
| **01: Driving Sim** | Vehicle physics & camera follow | **Bug Fix:** Resolved camera-to-player lag using `LateUpdate`. **Feature:** Added a local multiplayer split-screen mode. |
| **02: Animal Feed** | Object Pooling & Spawning | **Logic Fix:** Debugged boundary detection scripts. **Feature:** Implemented an "Animal Stampede" wave-based spawning system. |
| **03: Jump Force** | Animation States & Audio | **Animation Fix:** Resolved transition triggers for jump/death states. **Feature:** Added dynamic particle effects for running dust. |
| **04: Sumo Battle** | Physics-based Combat | **Vector Math:** Implemented custom knockback force based on player-enemy distance. **Feature:** Created three unique power-up types. |
| **05: Whack-A-Food** | Game State & UI Management | **State Fix:** Managed persistent high scores and game-over logic. **Feature:** Integrated a difficulty selection screen (Easy/Med/Hard). |

---

## 🧠 Technical Highlights

### 1. Debugging & Problem Solving
Beyond the basic tutorials, I completed the **Lab Challenges** for each unit, which involved:
* Identifying and fixing syntax and logic errors in provided "broken" scripts.
* Refactoring code to improve readability and maintainability.
* Optimizing performance by managing object instantiation and destruction.

### 2. Version Control Architecture
Resolved repository size constraints and Git "Large File" push errors by:
* Implementing a **recursive `.gitignore`** to exclude 1GB+ of unnecessary Unity metadata (`Library/`, `Temp/`, `Obj/`).
* Organizing five independent projects into a single, cohesive "mono-repo" structure for easier portfolio navigation.

---

## 🚀 How to Run
1. Clone the repository: `git clone https://github.com/BoonHow97/unity-create-with-code.git`
2. Open **Unity Hub** and select "Add" -> "Add project from disk."
3. Navigate to a specific Prototype folder (e.g., `Prototype 1`).
4. Open the `SampleScene` in the `Assets/Scenes` folder and press **Play**.

---

*Developed by a Computer Science & Physics student at the National University of Singapore (NUS).*