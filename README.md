# 👑 Royal Rescue 

> **An AI-Driven Game Environment Developed in Unity**

[![Watch Video](https://img.shields.io/badge/Watch_Gameplay_Video-Google_Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)]([YOUR_DRIVE_LINK_HERE](https://drive.google.com/file/d/1Hg4Bhmfjw2EwFRcGi0yZAXMJWDoW-bQb/view?usp=sharing))

*(Click the link above to watch the gameplay and AI demonstration)*

<img width="600" height="400" alt="Gemini_Generated_Image_6y0c3k6y0c3k6y0c" src="https://github.com/user-attachments/assets/196fb571-e76f-4d05-b19b-e085327a714e" />


## Tech Stack & Tools
![Unity](https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-8A2BE2?style=for-the-badge&logo=c-sharp&logoColor=white)
![Artificial Intelligence](https://img.shields.io/badge/AI_Algorithms-FF1493?style=for-the-badge)
![Game Development](https://img.shields.io/badge/Game_Dev-0000FF?style=for-the-badge)
![FSM](https://img.shields.io/badge/State_Machines-228B22?style=for-the-badge)

**Royal Rescue** is a 3D RPG developed in Unity, focusing on cinematic storytelling, dynamic NPC interactions, and atmospheric environments. The game transitions players through distinct worlds, from a lively village tavern to a mysterious weapon-filled cave, culminating in a daring island rescue mission.

## Key Features

* **Cinematic Dialogue System:** A custom-built UI and Coroutine sequence manager that handles audio synchronization, smooth fade-to-black transitions, and character teleportation during cutscenes.
* **Companion AI:** An advanced `NavMeshAgent` integration that allows rescued characters (like the Princess) to seamlessly follow the player, maintaining a polite distance and automatically updating animation states.
* **Proximity-Based NPC Behavior:** NPCs react organically to the player's presence. Using custom C# scripts and Unity's Animator, characters transition between ambient idle animations and interactive poses (e.g., kneeling and pointing) based on distance calculation.
* **Custom Editor Automation:** A robust suite of Unity Editor scripts (`[MenuItem]`) designed to eliminate manual Inspector drag-and-drop. These tools programmatically configure Animator parameters, assign AudioClips, inject missing components, and reset bone transforms with a single click.

## Game Worlds (Scenes)

| Scene Name | Description | Key Mechanics |
| :--- | :--- | :--- |
| **The Village** | A peaceful starting area featuring the local bar. | Cinematic sequence triggers, advanced audio syncing, and spatial teleportation (Miriam the Bartender). |
| **The Cave** | A treacherous cavern environment with hanging weapons and glowing crystals. | Terrain texture blending (TerrainLit), Proximity IK animations, and dynamic UI triggers (Peasant Man). |
| **The Island** | The final rescue destination. | End-game state management and Companion AI initialization. |

## Tech Stack & Tools

* **Game Engine:** Unity (2022+)
* **Render Pipeline:** Universal Render Pipeline (URP)
* **Language:** C#
* **Assets:** TextMeshPro (with custom 3D volume/rock materials), NavMesh AI, Standard Terrain Editor.

## Getting Started

1. Clone the repository to your local machine.
2. Open the project via **Unity Hub**.
3. Navigate to `Assets/Scenes` and open the **MainMenu** or **Village** scene.
4. If setting up NPCs from scratch, use the custom toolbar at the top: `Tools > Setup Peasant Man Proximity` or `Tools > Automate NPCs` to auto-configure components.

## Author

**Raz Natanzon**
Software Engineer | Unity & AI Developer
