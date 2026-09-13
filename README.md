# 👑 Royal Rescue 

> **An AI-Driven Game Environment Developed in Unity**

[![Watch Gameplay Video](https://img.shields.io/badge/Watch_Gameplay_Video-Google_Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1Hg4Bhmfjw2EwFRcGi0yZAXMJWDoW-bQb/view?usp=drive_link)

*(Click the link above to watch the gameplay and AI demonstration)*

<img width="500" height="250" alt="image" src="https://github.com/user-attachments/assets/8154f5a3-c7f8-4d36-b638-4270290a7294" />

<a href="https://www.youtube.com/watch?v=X_KaJ_kD89c">
  <img src="https://img.youtube.com/vi/X_KaJ_kD89c/maxresdefault.jpg" width="600" alt="Watch Royal Rescue Gameplay">
</a>

*(A quick taste of the game! Click the image above to watch the gameplay demonstration on YouTube)*

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
* **Enemy AI & Projectile Combat:** A dynamic monster AI that detects the player and calculates trajectories to throw rock projectiles, utilizing state machines to seamlessly switch between idle, chase, and attack behaviors.
* **Dynamic Minimap System:** A real-time navigational minimap UI built with a secondary orthographic camera, tracking the player's position and orientation to aid exploration across complex environments.
* **Weapon Mechanics & Combat Stats:** An integrated combat system featuring distinct weapons with unique damage values and attack speeds, requiring players to adapt their combat timing and strategy during enemy encounters.


## Gameplay Progression

* **1. Exploration & Narrative (The Village):** 
  The adventure begins in a peaceful village. Players interact with local NPCs (like Miriam the Bartender) through a cinematic dialogue system to uncover the lore and receive the primary quest: rescuing the Princess.
* **2. Combat & Resource Gathering (The Cave):** 
  Players navigate a hostile cavern filled with environmental hazards and hanging weapons. 
  * **Combat:** Engage in dynamic, stats-based combat against a rock-throwing boss monster. Success requires tactical movement, blocking, and timing.
  * **Collection:** Players must explore the cavern to collect essential resources and scattered crystals required for the next phase.
* **3. Puzzle Solving & Escort (The Island):** 
  Upon reaching the island, players utilize their collected resources to construct a bridge, unlocking the path to the captive Princess. Once freed, the Companion AI activates, and the player must safely escort her back to the village.
  

## Game Worlds (Scenes)

| Scene Name | Description | Key Mechanics |
| :--- | :--- | :--- |
| **The Village** | A peaceful starting area featuring the local bar. | Cinematic sequence triggers, advanced audio syncing, and spatial teleportation (Miriam the Bartender). |
| **The Cave** | A treacherous cavern environment with hanging weapons and glowing crystals. | Terrain texture blending (TerrainLit), Proximity IK animations, and dynamic UI triggers (Peasant Man). |
| **The Island** | The final rescue destination. | End-game state management and Companion AI initialization. |

<img width="522" height="254" alt="image" src="https://github.com/user-attachments/assets/d1230159-153a-42d1-90db-5bfbbd4b19a4" />
<img width="521" height="252" alt="image" src="https://github.com/user-attachments/assets/41092ad5-1b65-4438-a541-50584348e344" />
<img width="521" height="250" alt="image" src="https://github.com/user-attachments/assets/78667ab2-8b2b-4bcd-8b9d-f3e682f6e821" />
<img width="522" height="254" alt="image" src="https://github.com/user-attachments/assets/e3a30d0f-6417-45e7-8ac1-5fdbf90530c3" />
<img width="521" height="251" alt="image" src="https://github.com/user-attachments/assets/72928a3c-590b-42a0-96e8-ad3f4307b356" />
<img width="524" height="246" alt="image" src="https://github.com/user-attachments/assets/1003ca9a-d789-458c-a357-5614bacab1ee" />

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
