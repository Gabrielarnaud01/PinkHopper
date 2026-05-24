# 🐸 PinkHopper
	Course: Game Engines (Motores de Jogos)
	Semester: 2025.2
	Institution: Federal University of Rio Grande do Norte (UFRN)

# Project Members
	Gabriel Arnaud Paiva Torres (20210093332)

---

# 🎮 Description
**PinkHopper** is an indie 2D platformer game built using the **Unity Engine** and **C#**. Developed as an academic project for the Game Engines course, the game focuses on delivering precise physics, tight platforming mechanics, and robust state management.

The project highlights core game development practices, including handling user input, managing character physics (such as gravity curves and momentum), and structuring clean, modular script components in Unity.

---

# 🚀 Key Features & Mechanics
*   **Physics-Based Movement**: Custom 2D character controller with tailored jump arcs, falling gravity multipliers, and momentum tracking.
*   **State Management**: Structured C# architecture to handle different player states (Idle, Running, Jumping, Falling).
*   **Smooth Platforming Experience**: Implementation of classic platformer mechanics designed for precise and responsive gameplay controls.
*   **Level Design Integration**: Use of Unity's Tilemap and physics layers to create an optimized and collision-accurate environment.

---

# 🛠️ Tech Stack & Tools
*   **Game Engine:** Unity (C#)
*   **Architecture & Practices:** Component-Based Design, ScriptableObjects for data management, and Event-Driven architecture where applicable.
*   **Version Control:** Git

---

# 💻 How to Run the Project

### Prerequisites
*   **Unity Editor** (Version used during development, e.g., *2022.3 LTS* — *adjust to your actual version if needed*)

### Steps
1.  **Clone the repository:**
```bash
    git clone [https://github.com/Gabrielarnaud01/PinkHopper.git](https://github.com/Gabrielarnaud01/PinkHopper.git)
    ```
2.  **Open in Unity:**
    *   Open the **Unity Hub**.
    *   Click **Add** -> **Add project from disk**.
    *   Select the cloned repository folder.
3.  **Play the Game:**
    *   Once the project loads, navigate to the `Assets/Scenes/` folder.
    *   Open the main scene (e.g., `SampleScene` or `Level1`).
    *   Press the **Play** button at the top of the Unity Editor.

---

# 📂 Project Structure Overview
The repository is structured to separate engine metadata from source code and assets:
*   `/Assets`: Contains all custom C# scripts, animations, sprites, and scene configurations.
*   `/ProjectSettings`: Unity engine configuration files.
